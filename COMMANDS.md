# Commands

Collection of terminal commands that are encountered as part of the course

1. `docker run --rm --name sso -p 9000:9000 ghcr.io/vmware-tanzu-learning/course-secure-rest-api-oauth2-code/sso:latest` - Commands used to run the authentication server locally. Part of lab exercise "Connecting to an Authorization Server".

2. `http -a cashcard-client:secret --form :9000/oauth2/token grant_type=client_credentials scope=cashcard:read` - httpie command to fetch a token to authentication server. **Note: Must have the authentication server 👆 in order to get token response**.

