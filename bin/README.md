# aseef_spring_security


## 5 Core Concepts in Spring Security
- Authentication
- Authorization
- Principal
- Granted Authority
- Roles

# Authentication vs Authorization

## Authentication

let assume you are entering a building and watchman stopped and asks question "Who are you", you said while showing your id card "It is my Id Card" this is Authentication

Like in web app, you provide username and password to logging in website

### Knowledge Based Authentication:
    - Password
    - Pincode
    - Answer to secret questions

### Possesion Based Authentication
    - Phone/Text Messages
    - Key Card and badges
    - Access Token Devices

### Multi Factor Authentication
    - combination of above two

## Authorization

"Can the user do this?" Yes/No

### How does Authorization Happens
    - By some permissions which is Granted Authority in spring security


## Principal
Currently Logged in User

## Granted Authority
    - What users can do(i.e., Permission)
    
    - Authorities are fine grained

## Role
    - Group of Authorities
    - Roles are coarse-grained