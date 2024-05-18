# Bookswap-Hub
Welcome to Bookswap-Hub! This tool can be used to swap books between users by requesting and accepting the swap request. Registered user can upload books by his name which will be available to share and other users can request the book.
The request can be accepted by the owner of the book and then the transaction will be successful. 

## Installation
1. Clone the repository:
``` 
    git clone https://github.com/saurabh4073/Bookswap-Hub.git
```

2. Install Dependencies:
``` 
    npm install
```

2. Required Changes: <br>
    1. Add a config.env file in root folder with the following settins after creating a cluster and database on MongoDB Atlas
    ```
    NODE_ENV=development
    PORT=4000
    DATABASE=mongodb+srv://<username>:<password>@cluster0.hi0evjq.mongodb.net/<collection>
    DATABASE_PASSWORD=<password>
    JWT_SECRET=the -quick-brown-fox-jumped-over-the-happy-developer
    JWT_EXPIRES_IN=10m
    JWT_COOKIE_EXPIRES_IN=9000
    ```

## Usage
Run using the following command:
```
    npm start
```

open in browser the following link:
```
    http://localhost:4000
```

## Working with Screenshots
The Home Page where the user can go to Register, Login or see the About page-
![image](https://github.com/saurabh4073/Bookswap-Hub/assets/49804941/b03d6d22-5076-4be5-9ef4-67d1c3406b1f)

The Registration Page where the user will have to fill the registration details-
![image](https://github.com/saurabh4073/Bookswap-Hub/assets/49804941/a011523a-da6b-4f08-aa65-f0621c327f4c)

User Book List Page where we can see the books which the current user has-
![image](https://github.com/saurabh4073/Bookswap-Hub/assets/49804941/ad9a9672-e17e-40f3-9762-5a83508ca00e)

Add New Book Page where we can add the details to make the book available to swap -
![image](https://github.com/saurabh4073/Bookswap-Hub/assets/49804941/ade2c7d7-1bf3-497d-9c1c-f07e1b706663)

All Books List Page where we can see the list of books which are available for swapping by other users-
![image](https://github.com/saurabh4073/Bookswap-Hub/assets/49804941/efd48cd4-fb13-46de-9f73-72e43eb98a7b)

After Requesting the Book page the transaction successful page is visible-
![image](https://github.com/saurabh4073/Bookswap-Hub/assets/49804941/8a26f281-1af7-42e1-914b-6c05c756ca98)

The Book Status Becomes Unavailable to request anymore as its been exchanged with other user.
![image](https://github.com/saurabh4073/Bookswap-Hub/assets/49804941/ea61cf63-1da2-42be-948c-8dbcaf092be9)

## Acknowledgments
This project was done under the guidance of Prof. Dinesh Sthapit of ASU.