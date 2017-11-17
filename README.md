# spring_getting_started
Test projekt for getting started with spring on 2. semester

After creating an empty new spring project in IntelliJ through the _Spring Initializer Template_     
(described here: [#4 Hello Spring](https://github.com/dat17v1/2_03_hello_spring)), you should now create your first website.

## Your First Website
You now have a folder and file structure that looks something like this:    

<img src="https://github.com/clbokea/spring_getting_started/blob/master/img/Screen%20Shot%202017-11-17%20at%2010.58.46.png" width="200px"/>    


If you open your src folder you will see a _main_ and a _test_ folder. Delete the _test_ folder, and delete the _mvnw_ and the _mvnw.cmd_ files. <sup>(you could leave them in the project, but since we are not going to use them we delete them for a better overview)</sup>    

<img src="https://github.com/clbokea/spring_getting_started/blob/master/img/Screen%20Shot%202017-11-17%20at%2011.06.38.png" width="200px"/>     


Now you have a project structure that looks like this:    

<img src="https://github.com/clbokea/spring_getting_started/blob/master/img/Screen%20Shot%202017-11-17%20at%2011.13.55.png" width="400px"/>     

Don´t be confused by all the folders. They are packages (or just folders) and is not specially important right now. You can for now see the _demo_ folder as your root folder.

## Create a normal java class file
In the demo folder create a class and call it HomeController.java.     
* Right click the "demo" folder
* chose: New -> Java Class  
* Name: HomeController
* Kind: Class

<img src="https://github.com/clbokea/spring_getting_started/blob/master/img/Screen%20Shot%202017-11-17%20at%2023.12.13.png" width="600px"/>      

### Create an index method in the class
Create a public method called index with a return type of String, and return the string "index".

<img src="https://github.com/clbokea/spring_getting_started/blob/master/img/Screen%20Shot%202017-11-17%20at%2023.19.40.png" width="400px"/>  



Add _@Controller_ above the class definition and _@GetMapping("/")_ above the method definition.    


<img src="https://github.com/clbokea/spring_getting_started/blob/master/img/Screen%20Shot%202017-11-17%20at%2023.30.50.png" width="400px"/>  



