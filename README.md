# Spring-boot-Kotlin-Demo

https://mosenyonjo.github.io/spring-boot-kotlin-sample/

<h1>Customer Demo</h1>

<h2>About</h2>
  <p>This is the source code for my project.</p>

<h2>Installation</h2>
  <p>To run the project using gradle:</p>
  <pre><code>./gradlew bootRun
</code></pre>

## Built With

<p> Spring Boot - Framework for building Spring applications
Kotlin - Programming language for the JVM
Spring Data JPA - Framework for working with relational databases
H2 Database - In-memory database for testing and development
Gradle Kotlin DSL - Gradle build tool with Kotlin support</p>

<h2>Usage</h2>
  <p>Here's an example of how to use the project:</p>
  <pre><code>
HTTP/1.1 200 OK
Content-Type: application/json

{
"id": 1,
"firstName": "John",
"lastName": "Doe",
"email": "john.doe@example.com"
}

POST /api/customers HTTP/1.1
Content-Type: application/json

{
"firstName": "John",
"lastName": "Doe",
"email": "john.doe@example.com"
}

</code></pre>

<h2>Contributing</h2>
  <p>Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.</p>

<h2>License</h2>
  <p>This project is licensed under the <a href="#">MIT License</a>.</p>
</body>
</html>
