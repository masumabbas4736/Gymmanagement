# Gymmanagement
Gym Management project 
<br>

Author Masum Abbas ,Omer jabbar,Bilal, Syed bilal ali
<br>
FitPakistan Gym 

Overview

FitPakistan Gym Manager is a C++-based application designed to manage gym operations efficiently. Located in the GymManagement folder, it uses the Gym.cpp file to handle member registrations, track memberships, manage trainers, and calculate health metrics like BMI. This project is tailored for a gym setting in Pakistan, incorporating local pricing (in Pakistani Rupees) and a user-friendly interface for gym administrators.

Features





Member Management: Register, update, delete, and search members with details like registration number, name, locker number, weight, height, age, gender, BMI, and membership plans.



Membership Plans: Offers various plans (1 month, 3 months, 6 months, 1 year) with options for treadmill access, priced in PKR with relief discounts.



Trainer Management: Add, update, delete, and search trainers with qualifications, contact details, and fees.



Health Metrics: Calculate BMI based on member data and display sorted lists of members and trainers.



Locker Assignment: Automatically assigns available locker numbers to new members.



Data Display: View all members and trainers in a formatted table with truncation for long names or qualifications.

Prerequisites





A C++ compiler (e.g., g++).



Basic terminal or IDE (e.g., Visual Studio Code, Code::Blocks) to run the program.

Setup Instructions





Clone or Download the Repository:





Navigate to the GymManagement folder containing Gym.cpp.



Compile the Code:





Open a terminal in the GymManagement directory.



Run the following command to compile:

g++ -o FitPakistanGymManager Gym.cpp



Run the Program:





Execute the compiled file:

./FitPakistanGymManager



Follow the on-screen menu to interact with the system.

Usage





Upon running, the program displays a menu with options:





Display and buy a membership plan.



Insert a new member.



Delete a member.



Update member details.



Search for a member.



Sort members by registration number.



Display all members.



Insert a new trainer.



Delete a trainer.



Update trainer details.



Search for a trainer.



Sort trainers by fee.



Display all trainers.



Exit the program.



Enter the corresponding number to perform the desired action.



Input data as prompted (e.g., registration number, name, weight in kg, height in cm).

Example Workflow





Select option 1 to register a new member and buy a membership plan.



Enter a unique registration number, name, physical stats, and choose a plan (e.g., 'a' for 1 month at Rs 2000).



The system assigns a locker and calculates BMI.



Use option 7 to view all members in a tabulated format.

Contributing





Fork the repository.



Create a new branch for your feature or bug fix.



Submit a pull request with a clear description of changes.



Ensure code follows C++ best practices and is well-documented.

License

This project is open-source and available under the MIT License. Feel free to modify and distribute, but please retain the original copyright notice.

Contact

For questions or suggestions, contact the project maintainer at [your-email@example.com].

Acknowledgements





Inspired by gym management needs in Pakistan.



Utilizes standard C++ libraries for efficient data handling.
