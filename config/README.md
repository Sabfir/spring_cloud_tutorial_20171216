#### Done by tutorial: http://www.baeldung.com/spring-cloud-bootstrapping

##### NOTES:
1. used spring-boot version 1.5.9
2. to run the servers/services run: `mvn spring-boot:run`

#### The servers and service run order:
1. config
2. discovery
3. gateway
4. book-service
5. rating-service

#### REST API:
1. to get books: `GET` on `http://localhost:8080/book-service/books`
2. to get ratings: `GET` on `http://localhost:8080/rating-service/ratings/all`
