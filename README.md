# Secrets-AuthenticationDemo

## Description
It is a basic project that is created to learn various ways of authenticating websites. I used mongoDb to store new users and their credentials. Also learnt to use Passport npm package to make sign-in using Google and Facebook accounts.
Only authenticated users can access the secrets page of website. Also used express-session npm package to store sessions data.

## How to run 
1. Clone the repo.
2. Create a .env file.
3. Get Client Id and Client secret keys after creating profiles on Facebook developers and Google developers and registering new application there.
4. Once got it, store it in .env as
      CLIENT_ID=
      CLIENT_SECRET=
      FACEBOOK_CLIENT_ID=
      FACEBOOK_CLIENT_SECRET=
5. Now run the project using node app.js
6. The project can be seen at 
### http://localhost:3000/
