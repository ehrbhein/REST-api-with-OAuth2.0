# REST-api-with-OAuth2.0

A repository to house and compile learning materials and small projects regarding securing rest api with OAuth 2.0.

https://spring.academy/courses/spring-academy-secure-rest-api-oauth2/

Clone this repository and change directory into `./course-secure-rest-api-oauth2-code`.

## Chapters and context 🔖

The instructions are found on the official spring academy supported by broadcom.

On the broadcom tutorial, the Laboratory exercises are marked by different commit on the repository's `main` branch. On this project, each laboratory exercise are differentiated by their own branch.

| Chapter/lab                            | Branch on submodule                           | Site to lab instructions                                                                                                                                       |
|----------------------------------------|-----------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Spring security defaults               | `lab/spring-security-defaults`                | https://spring.academy/courses/spring-academy-secure-rest-api-oauth2/lessons/spring-security-defaults                                                          |
| Adding OAuth 2.0 Bearer JWT            | `lab/adding-oauth2-bearer-jwt-authentication` | https://spring.academy/courses/spring-academy-secure-rest-api-oauth2/lessons/adding-oauth-2-bearer-jwt-authentication                                          |
| Accessing Authentication in Spring MVC | `lab/accessing-authentication-spring-mvc`     | https://spring.academy/courses/spring-academy-secure-rest-api-oauth2/lessons/accessing-authentication-in-spring-mvc-lab                                        |
| Validating claims                      | ``lab/validate-claims``                       | https://spring.academy/courses/spring-academy-secure-rest-api-oauth2/lessons/spring-academy-secure-rest-api-oauth2-authentication-validate-audience-lab        |
| Processing failure                     | `lab/processing-failure`                      | https://spring.academy/courses/spring-academy-secure-rest-api-oauth2/lessons/spring-academy-secure-rest-api-oauth2-authentication-processing-failures-lab      |
| Adding request authorization           | `lab/add-request-authorization`               | https://spring.academy/courses/spring-academy-secure-rest-api-oauth2/lessons/spring-academy-secure-rest-api-oauth2-authorization-lab-add-request-authorization |
| Adding method authorization            | `lab/add-method-authorization`                | https://spring.academy/courses/spring-academy-secure-rest-api-oauth2/lessons/spring-academy-secure-rest-api-oauth2-authorization-lab-add-method-authorization  |
| Adding data authorization              | `lab/add-data-authorization`                  | https://spring.academy/courses/spring-academy-secure-rest-api-oauth2/lessons/spring-academy-secure-rest-api-oauth2-authorization-add-data-authorization        |
| Connecting to an Authorization Server  | `lab/connecting-to-authorization-server`      | https://spring.academy/courses/spring-academy-secure-rest-api-oauth2/lessons/spring-academy-secure-rest-api-oauth2-authorization-lab-authorization-server      |

## Resources

### Tokens

Tokens are used throughout the different lab exercise of the course. Having a copy of those token might come in handy when you try to simulate them on your local environment.

The tokens are stored on [TOKENS.md file](./TOKENS.md).

### Commands

Throughout the course, different commands are utilized to demonstrate running servers and HTTP requests using `httpie`. Some commands are saved on [this file](./COMMANDS.md).