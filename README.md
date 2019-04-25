# PHP-mega-login
Register, Login, Logout, Reset-password System in PHP

DB NAME : another-login

DATABASE STRUCTURE AS SHOWN BELOW FOR USERS

CREATE TABLE users (
    id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
    username VARCHAR(50) NOT NULL UNIQUE,
    password VARCHAR(255) NOT NULL,
    created_at DATETIME DEFAULT CURRENT_TIMESTAMP
);
