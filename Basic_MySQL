# MySQL-Databases

1️⃣ Creating a Sample Table
Before running the queries, create a sample users table:


CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(50),
    email VARCHAR(100),
    age INT
);


2️⃣ INSERT – Add Data

INSERT INTO users (name, email, age) 
VALUES 
('Alice', 'alice@example.com', 25),
('Bob', 'bob@example.com', 30),
('Charlie', 'charlie@example.com', 28);



3️⃣ SELECT – Retrieve Data

-- Select all users
SELECT * FROM users;

-- Select specific columns
SELECT name, email FROM users;

-- Select users older than 26
SELECT * FROM users WHERE age > 26;

-- Order users by age (descending)
SELECT * FROM users ORDER BY age DESC;


4️⃣ UPDATE – Modify Existing Data
-- Update Bob's age
UPDATE users 
SET age = 35 
WHERE name = 'Bob';

-- Update email for Charlie
UPDATE users 
SET email = 'charlie_new@example.com' 
WHERE name = 'Charlie';


5️⃣ DELETE – Remove Data
-- Delete Alice's record
DELETE FROM users WHERE name = 'Alice';

-- Delete all users above 30 years old
DELETE FROM users WHERE age > 30;


