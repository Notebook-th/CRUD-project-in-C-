
 **CRUD Project in CSharp**

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
   git clone https://github.com/yourusername/CRUD-project-in-CSharp-
   ```

2. Open the Project in Visual Studio:
   - Navigate to the project folder and open the `.sln` file in Visual Studio.

3. Run the Project:
   - Build and run the project. You’ll see a form interface where you can input student information and perform CRUD operations.

 **Usage Instructions**
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

**Database script:** 


USE [master]
GO

/****** Object:  Database [assignmentform]    Script Date: 9/17/2024 4:51:00 PM ******/
CREATE DATABASE [assignmentform]
 CONTAINMENT = NONE
 ON  PRIMARY 
( NAME = N'assignmentform', FILENAME = N'E:\softweres\sql\MSSQL16.SQLEXPRESS\MSSQL\DATA\assignmentform.mdf' , SIZE = 8192KB , MAXSIZE = UNLIMITED, FILEGROWTH = 65536KB )
 LOG ON 
( NAME = N'assignmentform_log', FILENAME = N'E:\softweres\sql\MSSQL16.SQLEXPRESS\MSSQL\DATA\assignmentform_log.ldf' , SIZE = 8192KB , MAXSIZE = 2048GB , FILEGROWTH = 65536KB )
 WITH CATALOG_COLLATION = DATABASE_DEFAULT, LEDGER = OFF
GO

IF (1 = FULLTEXTSERVICEPROPERTY('IsFullTextInstalled'))
begin
EXEC [assignmentform].[dbo].[sp_fulltext_database] @action = 'enable'
end
GO

ALTER DATABASE [assignmentform] SET ANSI_NULL_DEFAULT OFF 
GO

ALTER DATABASE [assignmentform] SET ANSI_NULLS OFF 
GO

ALTER DATABASE [assignmentform] SET ANSI_PADDING OFF 
GO

ALTER DATABASE [assignmentform] SET ANSI_WARNINGS OFF 
GO

ALTER DATABASE [assignmentform] SET ARITHABORT OFF 
GO

ALTER DATABASE [assignmentform] SET AUTO_CLOSE OFF 
GO

ALTER DATABASE [assignmentform] SET AUTO_SHRINK OFF 
GO

ALTER DATABASE [assignmentform] SET AUTO_UPDATE_STATISTICS ON 
GO

ALTER DATABASE [assignmentform] SET CURSOR_CLOSE_ON_COMMIT OFF 
GO

ALTER DATABASE [assignmentform] SET CURSOR_DEFAULT  GLOBAL 
GO

ALTER DATABASE [assignmentform] SET CONCAT_NULL_YIELDS_NULL OFF 
GO

ALTER DATABASE [assignmentform] SET NUMERIC_ROUNDABORT OFF 
GO

ALTER DATABASE [assignmentform] SET QUOTED_IDENTIFIER OFF 
GO

ALTER DATABASE [assignmentform] SET RECURSIVE_TRIGGERS OFF 
GO

ALTER DATABASE [assignmentform] SET  DISABLE_BROKER 
GO

ALTER DATABASE [assignmentform] SET AUTO_UPDATE_STATISTICS_ASYNC OFF 
GO

ALTER DATABASE [assignmentform] SET DATE_CORRELATION_OPTIMIZATION OFF 
GO

ALTER DATABASE [assignmentform] SET TRUSTWORTHY OFF 
GO

ALTER DATABASE [assignmentform] SET ALLOW_SNAPSHOT_ISOLATION OFF 
GO

ALTER DATABASE [assignmentform] SET PARAMETERIZATION SIMPLE 
GO

ALTER DATABASE [assignmentform] SET READ_COMMITTED_SNAPSHOT OFF 
GO

ALTER DATABASE [assignmentform] SET HONOR_BROKER_PRIORITY OFF 
GO

ALTER DATABASE [assignmentform] SET RECOVERY SIMPLE 
GO

ALTER DATABASE [assignmentform] SET  MULTI_USER 
GO

ALTER DATABASE [assignmentform] SET PAGE_VERIFY CHECKSUM  
GO

ALTER DATABASE [assignmentform] SET DB_CHAINING OFF 
GO

ALTER DATABASE [assignmentform] SET FILESTREAM( NON_TRANSACTED_ACCESS = OFF ) 
GO

ALTER DATABASE [assignmentform] SET TARGET_RECOVERY_TIME = 60 SECONDS 
GO

ALTER DATABASE [assignmentform] SET DELAYED_DURABILITY = DISABLED 
GO

ALTER DATABASE [assignmentform] SET ACCELERATED_DATABASE_RECOVERY = OFF  
GO

ALTER DATABASE [assignmentform] SET QUERY_STORE = ON
GO

ALTER DATABASE [assignmentform] SET QUERY_STORE (OPERATION_MODE = READ_WRITE, CLEANUP_POLICY = (STALE_QUERY_THRESHOLD_DAYS = 30), DATA_FLUSH_INTERVAL_SECONDS = 900, INTERVAL_LENGTH_MINUTES = 60, MAX_STORAGE_SIZE_MB = 1000, QUERY_CAPTURE_MODE = AUTO, SIZE_BASED_CLEANUP_MODE = AUTO, MAX_PLANS_PER_QUERY = 200, WAIT_STATS_CAPTURE_MODE = ON)
GO

ALTER DATABASE [assignmentform] SET  READ_WRITE 
GO




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




