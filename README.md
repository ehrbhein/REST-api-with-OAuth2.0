# REST-api-with-OAuth2.0

A repository to house and compile learning materials and small projects regarding securing rest api with OAuth 2.0.

https://spring.academy/courses/spring-academy-secure-rest-api-oauth2/

Clone this repository and change directory into `./course-secure-rest-api-oauth2-code`.

## Chapters and context 🔖

The instructions are found on the official spring academy supported by broadcom.

On the broadcom tutorial, the Laboratory exercises are marked by different commit on the repository's `main` branch. On this project, each laboratory exercise are differentiated by their own branch.

### Spring security defaults

Branch: `lab/spring-security-defaults`

Context and instructions on [this site](https://spring.academy/courses/spring-academy-secure-rest-api-oauth2/lessons/spring-security-defaults).

### Adding OAuth 2.0 Bearer JWT Authentication

Branch: `lab/adding-oauth2-bearer-jwt-authentication`

Context and instructions on [this site](https://spring.academy/courses/spring-academy-secure-rest-api-oauth2/lessons/adding-oauth-2-bearer-jwt-authentication).

### Accessing Authentication in Spring MVC

Branch: `lab/accessing-authentication-spring-mvc`

Context and instructions on [this site](https://spring.academy/courses/spring-academy-secure-rest-api-oauth2/lessons/accessing-authentication-in-spring-mvc-lab).

## Maintenance and contribution 🛠

Follow this format for adding new chapters and create a separate branch for each laboratory/chapter.

```text
### ${laboratory-chapter-name}

Branch: ${branch-name}
Context and instructions on [this site](https://link-to-site.com).
```

## Resources

### Tokens

Tokens are used throughout the different lab exercise of the course. Having a copy of those token might come in handy when you try to simulate them on your local environment.

The tokens are stored on [TOKENS.md file](./TOKENS.md).

### Commands

Throughout the course, different commands are utilized to demonstrate running servers and HTTP requests using `httpie`. Some commands are saved on [this file](./COMMANDS.md).