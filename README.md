
# A Entry Management Website that Schedules an appointment for Guest to meet his Host At Office

  

* Visit Website  https://summergeek.herokuapp.com/ 

### Important instructions 

```

Since there is Heavy Images , Web Site Loading Takes Time , Please operate after Full Load
This website is only made to be viewed in desktop version , it interface is not suitable for mobile platform .(due to time constraints of submitting the assignment , I am unable to do so )
For SMS alert , between 10 pm to 9 am the government of India restrict the promotional msg on DND numbers , there it may be possible that you will not get get the msg on the given time , but surely you will get that on morning .
```

  

## Steps To Install and Run Locally

1) Clone the Package
2) Type "npm install"
3) Type "node app.js"
4) or Type "npm run start"
5) Type http://localhost:5000/ in WebBrowser or use command : "python -m SimpleHTTPServer 5000"



## Technology Stack Used
* **Programming Language**
   a)Nodejs

* **DataBase** : MongoDB  (mongodb Atlas)
* **Web Framework**
  a)Bootstrap 
  b)Semantic-ui

* **Web Server** -- Express
* J**avaScript Libraries** -- jquery, Passport.js
* **APIs** 
*1) Gmail Api 2)   Way2sms Api

```
```
## Steps To Use 

### If You Are A Guest 
   
 1) **Want to meet someone from Office** 
	* Hover over the Guest option in Navigation bar and select Check-in
   	* Fill The details Name, Email , Phone
   	* In the Field of Host Name , Fill Full Host Name (see Available Host Name For reference)
   	* Click Submit
    * It Will send Your Meeting Request To the Host
    
   2) **Want to Check Out**
       1) Hover over the Guest option in Navigation bar and select Check-out
       2) Find Your Name
       3) Click Checkout Button
       4) This will Send You email and sms , on your Provided Phone number and email about details about todays Visit at summergeek

###  If you are a Host
```
Imp: For Host , You Have To Sign Up On summer Geek
 ```
 1) Click on **Sign Up** On Navigation Bar
 2) Fill Your Details
 3) THis Details Will Show in checkin Page Under Available Host Option
 4) Click **Submit**
 5) Now Wait for Some Guest , once he come , An Email and Sms will Be Send On Your Email id and Phone number so that you can attend the meeting with him
 -- If Already registered click **Login** in on Navigation bar


### Approch Of Project
1) First I have Decided total number of **Routes** needed For Summergeek And their Work including All ***Get Route*** And ***Post Route*** and ***delete route***
2) Then I have Designed its Frontend Part In **Bootstrap and semantic Ui** (Due to Time Constaints , I have Less Focused on FrontEnd part Desigining , more on Backend Designing )
3) Then I set up **Express Node** Web Server at my Local Port
4) All the Route and their Links had been added
5) Now For **Api** Section , I have Selected **Gmail Api**  From Email , And ***WaysT0Sms*** api for Sms . Then I integrated Those in my web server
6) Uses **Passport .js** For ***login Authentication*** For Host Login and Signup
7) Implemented of **Database** on **MongoDb**
8) then After Completion , I had Hosted Full WebSite On **Heroku**
  

   
  

# AUTHOR

```

SAJAL AGRAWAL

NIT PATNA

sajal.agarwal703@gmail.com
```
