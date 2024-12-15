# OAuth2.0IntegrationwithSpringBoot

I'm excited to share that I've successfully integrated Google OAuth 2.0 authentication in a Spring Boot application! 🎉

OAuth 2.0 has become a standard for secure authentication and authorization, and with Spring Security, it's easier than ever to protect your web applications. In this project, I leveraged Spring Boot to build a seamless authentication flow using Google Sign-In, allowing users to authenticate via their Google account.

🔑 Key Features of this Integration:

Google OAuth 2.0 Authentication
Easy integration with Spring Security
Secure API access with token validation
Simple and efficient user login flow
This project not only helped me understand OAuth 2.0 better but also gave me hands-on experience with Spring Security and Spring Boot.



Spring Boot OAuth 2.0 Implementation - 
OAuth 2.0, which stands for “Open Authorization”, is a standard designed to allow a website or application to access resources hosted by other web apps on behalf of a user.

Steps for OAuth 2.0-
1. Google Console
2. API & Services
3. Credentials
4. Create OAuth client ID
5. Select as Web Application
6. Give Application Name
7. URI's- http://localhost:8080
8. Redirect URI's- http://localhost:8080/login/oauth2/code/google
9. Click on Create
10. Copy the Client ID and Secrete then add those in Spring Boot Application YAML File
11. Run & Test your Spring  Boot Application

---------------------------------------------------------------------------------------------------


please user below content in application.properties file -

spring.application.name=SpringoauthApp

spring.security.oauth2.client.registration.google.client-id=64609091
spring.security.oauth2.client.registration.google.client-secret=GOCSPX-dvkDSLfblRoftZ_

