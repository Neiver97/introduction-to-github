test(Given I had items in the cart
 
When I finish the purchase
 
Then I will see the message 'THANK YOU FOR YOUR ORDER',
 
async ({page}) => {
 
await page.click('[data-test="checkout"]');

await page.fill('[data-test="firstName"]', "Fake");

await page.fill('[data-test="lastName"]', "User");

await page.fill('[data-test="postalCode"]', "00000");

await page.click('[data-test="continue"]');

expect(await page.innerText(".summary_subtotal_label")).toContain("55.97");

await page.click('[data-test="finish"]');

expect(await page.innerText(".complete-header")).toBe("THANK YOU FOR YOUR ORDER");

});
