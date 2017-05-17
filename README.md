This project is a simple Spring Boot application that demonstrates using multiple `CompleteFutures` to create an asynchronous REST controller that handles any number of blocking operations. To use:

1. Clone the repo: `git clone https://github.com/carlmartensen/spring_mvc_controller_completablefutures.git`
2. In the root directory run: `mvn spring-boot:run`
3. Test it with `curl http://localhost:8080/async?input=lorem,ipsum,dolor,sit,amet` or by visiting that URL in a browser.