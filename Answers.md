1. What is the purpose of using sessions?

Each client has its own unique session and it’s used to hold and store data and “persist” across requests, so that you don’t have to log in again every time you want to do anything.


2. What does bcrypt do to help us store passwords in a secure manner.

Bcrypt hashes the password information multiple times so it’s more difficult for people to crack your password and get access to any information stored on your site.


3. What does bcrypt do to slow down attackers?

Again, it hashes through the information it’s given (usually the password) multiple times, so it’s harder for a hacker to get access to your information.


4. What are the three parts of the JSON Web Token?

JWTs consist of a header, a payload, and a signature. The header contains the type of token and the algorithm used to create the toke. The payload holds claims information or other data we want stored, like an ID. The signature then combines the first two parts and “signs” it with a secret.