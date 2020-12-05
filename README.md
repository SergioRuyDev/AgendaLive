# AgendaLive
Api Rest de agendamento de Lives do YouTube.


## Description of Project

RESTful API for a Employee list web application. 

## Functionalities

:bell: Schedule Youtube links

## Steps and Requirements to build and run the Project

**1. Clone the application**
```bash
https://github.com/SergioRuyDev/AgendaLive.git
```

**2. Create MongoDB database and execute**

**3. Change mongoDB host and port as per your installation**

+ open `src/main/resources/application.properties`
+ change `spring.data.mongodb.host=` and `spring.data.mongodb.port` as per your mongoDB installation

**4. Run the app using maven**

```bash
mvn spring-boot:run or src/main/java/com.spring.AgendaLive/AgendaLive:run
```
The app will start running at <http://localhost:8080>
