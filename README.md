#This is your lovely homework
Basically , we planned two versions homework for you.The first one we think is mainly about summarize almost every part we learned in the training , while the second one is most focused on design partterns and refactor based Test Driven Development. It's up to you to pick a perfect homework for yourself. In the meantime , any kind of innovation is welcome, which means whatever new requirements you think is good for the scenario.

Good luck and don't forget to complete this home work before the next class.If you got any questions please ask @Honglai or your corresponding buddy for help .

#1. Book selling website

##Requirements guideline
1. Backend should be Java based , SpringMVC framework is strongly recommended.
2. Home page should show all the books, should allow customer to search by book name.
3. If customer click the book in the home page , should go to see the details about this specific book. Here both front end route (refer to angular route) and backend route(detail page is another separate page) are recommended.
4. Customer should be able to add any book to their shopping cart. Shopping cart should always be visible on the top of the page with some summary infos.
5. Shopping cart summary infos should contains : Book count, total price.
6. Customer should be able to go to the details shopping cart page by click the shopping cart area.
7. In shopping cart detail page , customer should see everything inside the shopping cart , and should be able to remove or add every book's quantity. after the quantity reduced to 0, the book should no longer exist in shopping cart page .
8. In shopping cart page , customer should be able to submit order and then will got a success page (still , both front end route or backend route are welcome).
9. Success page should display a summary of what customer purchased .


The webs page design is 100% up to you , and you are welcome to add whatever useful features you think is good for our customer.

##Hint
1. There is one important concept called "SESSION" in this project. Session means one period of time server is communicating with some specific client , and server side is able to remember some status of the client within one session.

2. If you want to add a login for our website , it's strongly recommended to use the one called Spring Security , which is quite interesting.

3. It's ok we use some hard coded product catalog (which describes all the products' info), but would be better if we make it possible to use some configuration file like XML, JSON or whatever you think is good.
4. This project is 60% similiar with the project you gonna join in TWU , the only difference is we don't use any database at this moment, but if you are curious enough, don't hesitate to import the database layer.





#2. Richest in the world
Richest in the world is one PC game I played when I was a student. It's chinese name is called "富甲天下", it's quite similiar with the game "大富翁". In this game , there are three kings mr.Liu, mr.Cao and mr.Sun which refers to the very famous book "Three Kindoms".Players can pick up one of them as the role to play.
##Requirements guideline
1. This is a command line game
2. Player's first step is to choose a role to play, here players have three options : mr.Liu, mr.Cao and mr.Sun
3. Each king have 5 generals , and each generals have two attributes : attack and intelligence.
4.
