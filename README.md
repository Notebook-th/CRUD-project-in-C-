
 **CRUD Project in C**

 **Project Overview**
This is a simple project demonstrating the use of CRUD (Create, Read, Update, Delete) operations. The application allows users to manage student records, including their names, IDs, and ages. It is built using C and Windows Forms in Visual Studio.

 **Features**
- Add Student: Add a new student record with name, ID, and age.
- Remove Student: Delete a student’s record from the system.
- Search Student: Search for a student using their ID or name.
- Edit Student: Update a student’s information (name, ID, or age).

 **Requirements**
- Visual Studio: The project is developed in Visual Studio, so you need to have it installed on your system.
- CSharp Language: Basic knowledge of C is required to understand the code.

 **How to Use**
1. Clone the Repository:
   ```bash
   git clone https://github.com/yourusername/CRUD-project-in-C-
   ```

2. Open the Project in Visual Studio:
   - Navigate to the project folder and open the `.sln` file in Visual Studio.

3. Run the Project:
   - Build and run the project. You’ll see a form interface where you can input student information and perform CRUD operations.

** Usage Instructions**
- Add a Student: 
  1. Enter the student's name, ID, and age in the respective fields.
  2. Click on the Add button to store the record.

- Search for a Student:
  1. Enter the student’s ID or name in the search field.
  2. Click the Search button to find the record.

- Edit a Student's Details:
  1. Select a student from the list.
  2. Update the fields with new values.
  3. Click the Update button to save the changes.

- Delete a Student:
  1. Select a student record.
  2. Click the Delete button to remove the record from the list.

 **Code Structure**
- MainForm.cs: Contains the logic for adding, removing, editing, and searching student records.
- Student.cs: Represents the student entity, with properties for name, ID, and age.
- StudentManager.cs: Handles data management, including storing, updating, and deleting student records.

 **Screenshots**
initial interface:
![image](https://github.com/user-attachments/assets/e910866c-ad5c-4db1-ad65-c8c6a7d32ecd)

after insertion a record:
![image](https://github.com/user-attachments/assets/072e7d6b-87f4-42da-aaf8-6a1450fdbf45)

after updating the record :
![image](https://github.com/user-attachments/assets/f7fa11dd-57a0-4242-b2d4-7573ae66bda8)

searching will show the result in the box : 
![image](https://github.com/user-attachments/assets/887c575b-89d2-463c-be2a-4dc4501783c3)

after deletation : 
![image](https://github.com/user-attachments/assets/50d8c6be-9d37-4f98-8251-9e80d9fb3ecc)


 **Future Improvements**
- Add validation to ensure no duplicate student IDs.
- Improve UI/UX for a more user-friendly experience.
- Export and import student data from/to a file (e.g., CSV or JSON).

 **Contributing**
If you'd like to contribute to this project:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m "Add feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.




