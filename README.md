# CODERS_OF_PUNE

This project is a mini data analysis application built using pure Python on a self-generated dataset inspired by a coding social media platform for Pune Coders. The dataset is stored in JSON format and contains information about users, their friends, and the pages they like.

The goal of this project is to analyze social connections and build recommendation systems similar to those used by real-world social media platforms.

Data Cleaning

The dataset was cleaned using pure Python without any external libraries. The following operations were performed:
Removal of users with missing values
Removal of duplicate user records
Validation of friends and liked page references
This ensures the dataset is accurate and suitable for analysis.

Recommendation Systems

Two recommendation engines were built:
🔹 People You May Know

Suggests new friends to a user based on:
Mutual friends
Network connections

🔹 Pages You May Like

Suggests pages to users based on:
Pages liked by their friends
Common interests

These recommendations were implemented using:

Loops
Sets
Dictionaries

Conditional logic
