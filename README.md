# Springboot User Registration Email System

Functional backend system that allows a user to be created via email verification.
Verification link sent to email expires in 15 minutes.
Postgres backend
Spring Boot Dependencies:

- Spring Web
- Spring Security
- Postgre SQL Driver
- Spring Data JPA
- Java Mail Sender
- Lombok

# Diagram
<img width="685" alt="Screen Shot 2021-05-09 at 9 47 12 PM" src="https://user-images.githubusercontent.com/25212189/117611577-344d3400-b110-11eb-8b01-5dbbc861e3da.png">


# To Run
Application must be running as well as MailDev (Mock development email server)



# Screenshots

## Postman
Send a GET request to initialize a new user <br>
<img width="1012" alt="Screen Shot 2021-05-09 at 9 49 14 PM" src="https://user-images.githubusercontent.com/25212189/117611688-68285980-b110-11eb-9873-fc685f8bf8ba.png">



## MailDev
An email is then sent to user <br>
<img width="1154" alt="Screen Shot 2021-05-09 at 9 51 39 PM" src="https://user-images.githubusercontent.com/25212189/117611886-be959800-b110-11eb-8823-491f9aecca35.png">


## User Verification
After clicking the link, the user is verified within the database and login. <br>
<img width="400" alt="Screen Shot 2021-05-09 at 9 53 28 PM" src="https://user-images.githubusercontent.com/25212189/117612034-fef51600-b110-11eb-8b87-45fdeff9991d.png">

## TODO:
While the backend is completely operational, the frontend needs to be developed still.
<img width="579" alt="Screen Shot 2021-05-09 at 9 54 04 PM" src="https://user-images.githubusercontent.com/25212189/117612073-146a4000-b111-11eb-8802-f1aab5d86739.png">

