HTML  book chapter 1 
So today we are going to talk about  html 
 How people  access the  web ? 
1.	Browerse: people access websites using  web browers like chrome and firefox .
2.	Web server :  when we ask the brower to show us a page the brower show us a page the request is  send to a spiceal computer called server  
When you visit a website, the web server
hosting that site could be anywhere in the
world. In order for you to find the location of
the web server, your browser will first connect
to a Domain Name System (DNS) server. 
How the web works >
  1- when we connect with the web we do it using ISP (internet serviver provider) and then we type the domian name or the web adress 
   2- then  our computer will contact with the DNS and will give it the ip address for this domian name  and the ip address consstes of 12 digits and every  device  have a unieq ip address
    then the ip address allows us to contact with this website 
    The web server then sends the
page you requested back to your
web browser.
  so tages in html is like a container and  inside the tag we put the contant   weh ave <h1>  to <h6> and <p> and   <html > and <body> and a lots if tages that we are going to talk aboyut it later 
   and we have to close our tages by using  backslash   like this <p> </p> 
   and we are going to talk about attribute that we use it to give more info abouyt the content and we have put the value of the attribute in doble qution  like this 
   <p lang= "en-us">
    inside the body we put everything we wants we put things that we want it to be display on the web browers  
    and inside the head we put the metadeta (the deta that doesnt show to the user but it`s for our selfs  and for responsive attacts)
     the tittle we put it inside the head and the tittle display the  tittle if  our page inside the tab 
      ## extra markup  
      because we have many version of html  we have to  use the tag doctype like this <!DOCTYPE html> this indcaites that we are using html 5 
       when we want to make notes or comment   in html so we use <!-- -->  any thing insdie it it will not be showen to the  user it just memoes for you as a programer 

       ID Attribute:  we use the id attrubute for soem tages that we  want to give it a unieq id and we will use the id  with styling  . <h1 id="heading"> 
       we can use the class atturbuite  and we can  have  more than one emlemnt in the same class so if we have some  elents and we want to give it the same style we can  put in in a class with the same name and then style  by the class name   <p class= "ggg">
         

         block element:
         Some elements will alwaysappear to start on a new line inthe browser window. These are known as block level elements. like  h1 ,p, ul ,li 
         inline ements :the elemetns thats apper to  contuiune on the same line like <em> <img>
           the div allows us to  set a diffrent type of elents inside a block  it called div  
           escape  charactors :
           so if we want to use some charactors that  we use it with html we have to use the escape charactor to print it 
           Less-than sign like :&lt; or &#60;. 
           i nhtml5 we have new elements we call it semantic element that the name repsrest the content of the element like articael header and footer and main also the nav  
            chapter 18 
            process and design
            Who is the Site For? 
            so when we want to make a site we dont make it to our self  or to the owner of it we make it to suites with the costomers or  who are our oudiance and then we ask alots of  question about the  audience to know how to design the page  and then we ask the owner why the visit our website and what elements should we have it   and what servers can we privide it to the coustmer and know what the custmer needs  
            site maps 
             we can build a map and put in it the leements we want it to  be showen to the user  and build the structure of oyur website 
              the wireframe is when we orgnize  the struct  and the desiogn on our page on paper or using some programs 

## Java script 
so  we use java script to make the  page intractive  and intersting and more friendly 
so javascript make the page intractive by allowing the user to modify   the content  at the run time (when we are exctitign the page )  
java script Reacts to event when we chlicked on a bottom  or chick on the link  
so fitst  we need to know what is script and how   to write it ?
 the script is a series on instration (commands ) that we give it to the computer to achive a spicfic task .
 writing a script is like give a   recipe  for some one to  do it step by step to  get a succefual desiceas meal. 

  to write a script we have to  state the goal and then put the steps that will lead us to accomplish it and if we have a big goal we can simpleize it to small goals and then concatinute it togather to have the script that we need it  we can write the steps  then translate to our programing lanuge and here to translate it and write it in java script and then we will have our code so congrats 
  ## events 
  An event is the computer's way of sticking up its
hand to say, "Hey, this just happened!"
 ## methodes 
  it repssnt things we need to do it with an object 
  ## how the browser see a web page 
   fitst  it recvie  a page as html code 
   2- create a model of the page and store it on the meomry 
   and then  use a rendering engine to show the page on the screen 
   so how html and css and java script fits togather ?
    its like making layer like first to defind the stucture of the page by using html and then we use some styling with css and finaly we make our page inractive by using some java scripts 
     if we want to link a script with our html file we write in the  head  
     <link  rel="stylesheet", href=" the refrence of the scipt here "> 
      this is extrenal way and if we want it to make it internal we put  script tag at  the end of the html like this <scipt> </script> and we put it the java script commands we put it at the end of the html file before we close the body bec it`s talk alot of time so i dont want to have an error or delay durring  browsing the page 
    