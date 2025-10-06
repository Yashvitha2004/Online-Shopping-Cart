Online Shopping Cart (E-Commerce Website)
This is an E-Commerce Website build for selling of any electronics products online.

About
In this projects a user can visit the websites, registers and login to the website. They can check all the products available for shopping, filter and search item based on different categories, and then add to cart. They can add multiple item to the cart and also plus or minus the quantity in the cart. Once the cart is updated, the user can proceed to checkout and click the credit card payment details to proceed. Once the payment is success the orders will be placed and users will be able to see the orders details in the orders section along with the shipping status of the product.

The admin also plays an important role for this project as the admin is the one responsible for adding any product to the store, updating the items, removing the item from the store as well as managing the inventory. The admin can see all the product orders placed and also can mark them as shipped or delivered based on the conditions.

One of the best functionality that the projects include is mailing the customers, so once a user registers to the website, they will recieve a mail for the successful registration to the website, and along with that whenever a user orders any product or the product got shipped from the store, then the user will also receive the email for its confirmation. Sometimes, if the user tried to add any item which is out of stock, them they will get an email one the item is available again the stock.

Note: The payment page is created only for demo purpose and its not fully integrated with any payment gateway. So for now any credit card details will be accepted and the demo orders will be placed.

Highlights :--
The users will get a mail to their registered mail Id during:-
New User Registration
Order Successfully Placed
The Item was out of stock while exploring but now it got available in the store
Successful shipment and delivery of the Item
Technologies used:-
Front-End Development:
HTML
CSS
Javascript
BootStrap
Back-End Development:
Java [JDK 8+]
JDBC
Servlet
JSP
Database:
MySql
================ Software And Tools Required ================
: Git [https://www.youtube.com/watch?v=gv7VPQ4LZ7g]
: Java JDK 8+ [https://www.youtube.com/watch?v=O9PWH9SeTTE]
: Eclipse EE (Enterprise Edition) [https://www.youtube.com/watch?v=8aDsEV7txXE]
: Apache Maven [https://www.youtube.com/watch?v=jd2zx3dLjuw]
: Tomcat v8.0+ [https://youtu.be/mLFPodZO8Iw?t=903]
: MySQL Server [https://www.youtube.com/watch?v=Ydh5jYA6Frs]
: MySQL Workbench [https://www.youtube.com/watch?v=t79oCeTXHwg]
================= Dummy Database Initialization =================
STEP 1: Open MySQL Command Prompt or MySQL Workbench

STEP 2: Login to the administrator user of MySql: mysql -u <username> -p (Enter Password if asked)

STEP 3: Copy paste and execute the MySQL Query from the following file:-

Run the Sql Query From this file: databases/mysql_query.sql
======GENERATING GMAIL APP PASSWORD [For Mailing Functionalities]========
Step 1: Create a gmail account or login to existing account in any browser

Step 2 : Go to https://myaccount.google.com/security and check if 2 step verifications is enabled or not, enable it if not enabled

Step 3: Go to https://myaccount.google.com/apppasswords and enter password if asked

Step 4: In Select an App Section: select Other (custom name) => enter "Ellison Electronics" => Generate

Step 5: After that it will generate 16 digits app password which you need to copy and save for future configurations.

Step 6: Done : Now continue to importing the project. [Don't share the above password generated to anyone]

========== Importing and Running The Project Through Eclipse EE ==========
Step 1: Open Eclipse Enterprise Edition. [Install, if not already installed.]

Step 2: Click On File > Import > Git > Projects From Git > Clone Uri > Paste The Repository Url as: https://github.com/shashirajraja/shopping-cart.git> Select master Branch > Next > Next > Finish.

Step 3: Go inside Java Resources > src > application.properties and update the values as below:

a) Update value for db.username and db.password according to your installed mysql credentials.
b) Update value for mailer.email and mailer.password, with the same email and app password that you generated earlier in above section [ NOTE:Actual gmail password will not work]
Step 4: Right Click on Project > Run as > Maven Build > In the goals field enter "clean install" > apply > run

Step 5: Right Click On Project > Build Path > Configure Build Path > Libraries > Remove and Update Any Libraries if Red Mark Exists > Finish.

Step 6: Right Click on Project > maven > update project > select force update > apply > close

Step 7: Tomcat Configurations:

If Tomcat Server is not configured in Eclipse :

Right Click On Project > Run As > Run On Server > Manually Define a new server > Select server type > select Tomcat v8.0+ > (Select Tomcat V8.0+ Installation Location If Asked) > Next > Add the current project > Finish.
Else If Tomcat Server is already configured in Eclipse:

Right Click On Project > Run As > Run On Server > Select Tomcat Version > Next > Add the project > Finish.
or

You can directly goto server tab, select the tomcat server and use the debug or run button to start the previously ran project
Step 8: Check Running The Site At http://localhost:8080/shopping-cart/

Step 9: [To Change the Port, if getting error like 'port already in use'] Open The Server Tab > Double Click On Tomcat Server > Ports > Change The Port Number For Http/1.1 To 8083 > Close And Save. Now Start and you can access the project on http://localhost:8083/shopping-cart/

Step 10: Default Username And Password For Admin Is "admin@gmail.com" And "admin"

Step 11: The default Username And Password For User Is "guest@gmail.com" And "guest"

FAQ
Question:1 Unable to Connect to Database?

Answer: Please check you have installed the mysql correctly and have updated the correct db details in application.properties file. Also you can try doing maven clean install and force update the project and restart.

Note:- This is a Sample Project for learning purpose, we have not much considered of web security.

Some Screenshots for the project:

<img width="993" height="517" alt="Img1" src="https://github.com/user-attachments/assets/d16e00ca-4ee5-4613-a6bd-88df37bc50c3" />
<img width="993" height="521" alt="Img2" src="https://github.com/user-attachments/assets/b5870e33-4648-44cf-b446-af02cfa57141" />
<img width="996" height="522" alt="Img3" src="https://github.com/user-attachments/assets/ff06a0ee-f592-48b1-bbb9-fd34829245b8" />
<img width="993" height="520" alt="Img4" src="https://github.com/user-attachments/assets/66b2f065-7fa9-4a4b-9e02-5922c21156d5" />
<img width="996" height="520" alt="Img5" src="https://github.com/user-attachments/assets/81c68f1f-3ebb-4022-9449-95dc46d03067" />
<img width="992" height="512" alt="Img6" src="https://github.com/user-attachments/assets/9e458afb-39e9-4837-bf4c-a81037fd8f1d" />
<img width="997" height="517" alt="Img7" src="https://github.com/user-attachments/assets/c2eddda3-9321-474e-b4e9-fad06cabfa1e" />
<img width="992" height="522" alt="Img8" src="https://github.com/user-attachments/assets/b33079c0-6d97-481a-9b07-fbc13d9c2aa4" />
<img width="997" height="522" alt="Img9" src="https://github.com/user-attachments/assets/3ea99678-1984-424e-b3e8-138c19a5ab0e" />
<img width="987" height="512" alt="Img10" src="https://github.com/user-attachments/assets/7078b4f3-6ebf-471e-8dc6-d2388cec525b" />
<img width="996" height="516" alt="Img11" src="https://github.com/user-attachments/assets/57ee2c57-9a58-4846-ab76-15bad06fd121" />
<img width="993" height="516" alt="Img12" src="https://github.com/user-attachments/assets/2c9ec933-82d4-4c46-9b38-7f4efb6c81ab" />
<img width="997" height="515" alt="Img13" src="https://github.com/user-attachments/assets/0e7540e1-d5fb-4bdc-9e25-84e6dbb7a3d8" />
<img width="1000" height="516" alt="Img14" src="https://github.com/user-attachments/assets/40ec0bd4-bdad-4ab0-968c-33addcc1a9d8" />
<img width="993" height="518" alt="Img15" src="https://github.com/user-attachments/assets/ddf08d36-32d7-434d-94a7-9fea2e02ff6f" />
<img width="732" height="448" alt="Img16" src="https://github.com/user-attachments/assets/0b9382c0-a271-4030-b491-5fbca608f18d" />

"Suggestions and project improvement ideas are welcomed!"
Thanks a lot,
Project Leader
Yashvitha Reddy
