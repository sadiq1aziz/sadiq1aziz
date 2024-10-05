- 👋 Hi, I’m @sadiq1aziz
- 🌱 A Senior Developer with more than 5 years of extensive experience in Java, specializing in frameworks like Liferay and Spring Boot, and proficient in JS frameworks such as React. Passionate about enhancing 
      user experiences and driving innovation. 
- 💞️ I’m looking to collaborate/work on new opensource projects to build upon my knowledge of application development
- 📫 How to reach me - via mail - sadiq1aziz@gmail.com


Usecase scenarios for portfolio projects deployed in this repo :

A. Finance App (FinHub): https://finhub-flax.vercel.app 

Sign-up Flow:
1. On signing up, user is required to use Plaid to authenticate their bank account to connect to the app
2. Since this is a sandbox environment configured for this portfolio from Plaid, using some of the popular american bank brands would be easier such as Chase
3. Platypus will require the user to autheticate creds
4. Creds to authenticate for both username and password -> user_good
5. For any MFA, user can proceed via direct submission
6. User can accept which account to be linked i.e savings or checking from the displayed list
7. Once signed up, user can see the application
 
Transfer Funds Flow:
1. A user can navigate to the my-banks section to see the associated accounts
2. Copy the encrypted address of the account to which you want to share funds or share it with
   another trusted party on the application from whom funds are to be credited to your account
   (receivers plaid ID)
4. Fill up the form details and submit
5. The transaction should appear in processing in the transctions list and will generally complete in 2 working days


B. E-commerce App: https://celebrated-shortbread-c1dd0d.netlify.app

Flow:
1. Choose product to add to cart
2. Choose either on home screen or in shop page
3. view cart
4. make purchase using swift - test card details : 4242....
5. submit
6. Can also register an account via google or through email (Firebase).

<!---
sadiq1aziz/sadiq1aziz is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
