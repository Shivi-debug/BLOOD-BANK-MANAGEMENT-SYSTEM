____BLOOD BANK MANAGEMENT SYSTEM________
____OVERVIEW_____
The Blood Bank Management System is a C++ application designed to manage the records of blood donors, patients, and the blood inventory of a blood bank. It allows users to add new donors, add patients requesting blood, check blood inventory, and more. The system is primarily designed for use by an administrator who can manage these records securely.
______Features_____
1)Admin Login: Admins can log in using a password stored in adminpwd.txt.
2)Donor Management:Add new donors with their name, blood group, age, contact details, and the number of blood bags donated.
3)Display a list of all registered donors.
4)Patient Management:Add patients with their required blood group, name, age, and contact details.
5)Allocate blood to patients based on available inventory.
6)Blood Inventory:Track the available blood bags for each blood type (e.g., O-, O+, A-, A+, etc.).
Blood inventory is updated whenever blood is provided to a patient.
7)Health Check for Donors:Ensure that donors meet certain health criteria before donation (BMI, allergies, tattoos).
____File Handling_____
Donor and patient information is saved to text files (donor2.txt and patient_list.txt).
____Menu System____
The system is menu-driven, with separate menus for donor and patient operations.
_____Prerequisites_____
A C++ compiler that supports C++11 or later.
The application uses basic file handling for storing donor and patient data.
adminpwd.txt file should exist in the working directory containing the admin password.
______File Structure_____
main.cpp: The main program file containing all the logic for the blood bank management system.
adminpwd.txt: A text file containing the admin password for secure login.
donor2.txt: A text file where donor details are stored.
patient_list.txt: A text file where patient details are stored.
