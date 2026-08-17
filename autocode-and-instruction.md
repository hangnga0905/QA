There are 4 steps to complete the test:
1. Install playwright: https://playwright.dev/docs/intro
2. Create a file name in Visual code: 1.login.spec.ts
3. Write the following code in the file above

import {test, expect} from '@playwright/test';

test('Test Login Page with Valid user', async({page})=>{
    const pageURL = "https://www.saucedemo.com/";
    await page.goto(pageURL);

    await page.fill('#user-name', 'standard_user');
    await page.fill('#password', 'secret_sauce');
    await page.click('#login-button');

    const loginPage = page.url(); 
    expect(loginPage).toBe('https://www.saucedemo.com/inventory.html');
})


test('Test Login Page with Invalid User', async({page})=>{
    const pageURL = "https://www.saucedemo.com/";
    await page.goto(pageURL);

    await page.fill('#user-name', 'locked_out_user');
    await page.fill('#password', 'secret_sauce');
    await page.click('#login-button');

    const errorMessage = await page.textContent('.error-message-container');
    expect(errorMessage).toBe('Epic sadface: Sorry, this user has been locked out.');
})


4. Run powershell command: npx playwright test "1.login.spec.ts" --project chromium
