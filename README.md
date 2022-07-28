Creating a USSD (Example *300#)
Press the USSB, creating a new user account (enter full name, national ID, and Phone number)
After entering personal details, the user will created a password to complete account creation phase
After creating an account, the user will get a welcome message "congratulations you have successfully created your account you have received a bonus of 1000 Frw on your e-wallet)
Login option, a user will enter full name and password
USSD menu (1. Balance inquiry, 2. send money, 3. receive money)
When an user press 2, transaction fee will be deducted according to the formula:
Ifs ((<=10,000),"0",(10,000-100,000),"200", "1000)
log out or session time out if the user spend 7 minutes without any action
