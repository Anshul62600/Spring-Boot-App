

## Student Information
- **Name**: Anshul Sahu








## Project Structure

```
src/main/java/com/example/webhookapp/
├── WebhookAppApplication.java          # Main Spring Boot application
├── config/StartupRunner.java           # Triggers workflow on startup
├── service/
│   ├── WebhookService.java            # BFHL API integration
│   └── SqlSolverService.java          # Question 2 SQL solution
├── model/WebhookResponse.java         # API response model
└── controller/HealthController.java   # Health endpoints
```

## How to Run

### Using Pre-built JAR (Recommended)
```bash
# Navigate to the project directory
cd E:\Bajaj\spring-webhook-app

# Run the application using the pre-built JAR
java -jar target/webhook-app.jar
```

### Using Maven (if dependencies are available)
```bash
# Build the project
mvn clean package

# Run the application
mvn spring-boot:run
```



### Health Check
```
GET http://localhost:8080/api/health
```

### Application Info
```
GET http://localhost:8080/api/info
```



## Author

**Anshul Sahu** - Roll Number: 0126IT221023

---

*This application demonstrates advanced Spring Boot concepts, webhook processing, and SQL analytics for the Bajaj technical assignment.*
