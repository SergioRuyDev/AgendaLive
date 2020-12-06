# ScheduleLive
Api Rest


## Description of Project

RESTful API for schedule live from Youtube. 

## Functionalities

:bell: Schedule Youtube links

## Steps and Requirements to build and run the Project

**1. Clone the application**
```bash
https://github.com/SergioRuyDev/ScheduleLive.git
```

**2. Create MongoDB database and execute**

**3. Change mongoDB host and port as per your installation**

+ open `src/main/resources/application.properties`
+ change `spring.data.mongodb.host=` and `spring.data.mongodb.port` as per your mongoDB installation

**4. Run the app using maven**

```bash
mvn spring-boot:run or src/main/java/com.spring.ScheduleLive/ScheduleLive:run
```
The app will start running at <http://localhost:8080>
