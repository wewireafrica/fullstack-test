### Wewire Fullstack Take-Home Challenge

We are mainly focused on observing your problem-solving approach and code organization. Have a great time!

**The assessment:**
This challenge requires you to build a currency conversion application that converts money between the wallets 
of a user with our supported currencies ( Find them below this file ). You are required to use NestJS ( Typescript ), 
React ( Typescript ), Prisma, and Postgres. 

**Tips**
1. Create a monorepo with your `ui` and `api`. `yarn workspaces` is a simple and easy way to do this.
2. Design a database schema to store currency exchange rates, wallets and their balances for the supported currencies
and transactions to record the movement of money between wallets.
3. Implement CRUD operations and endpoints for managing the models you create.
4. Adding user authentication is an optional addition but not required and does not affect your submission.
5. Making good use of database transactions is a plus.
6. The look of your user interface does not determine your performance
   

**Evaluation Criteria:**
1. **Functionality:** Ensure that the application can successfully convert currencies using rates and handles errors appropriately.
2. **Code Quality:** Assess the readability, maintainability, and organization of the code.
3. **Backend Implementation:** Evaluate the NestJS and Prisma backend for correctness and efficiency in handling currency conversion.
5. **Database Design:** Check if the database schema is well-designed to store and manage localized exchange rates.
6. **Error Handling:** Ensure that the application gracefully handles invalid inputs and potential errors, both on the frontend and backend.

**Supported Currencies**
    - Naira ( NGN )
    - Ghanaian Cedi ( GHS )
    - United States Dollar ( USD )
    - Kenyan Shillings  ( KES )
    - Euro ( EUR )
