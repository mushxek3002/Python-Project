
## SQL

### CREATING STUDENT TABLE 
    CREATE TABLE student (
    Student_ID INT PRIMARY KEY AUTO_INCREMENT,
    Name VARCHAR(255),
    Department VARCHAR(255),
    Course VARCHAR(255),
    Year VARCHAR(50),
    Semester VARCHAR(50),
    Division VARCHAR(50),
    Gender VARCHAR(10),
    DOB DATE,
    Mobile_No VARCHAR(15),
    Address VARCHAR(255),
    Roll_No VARCHAR(20),
    Email VARCHAR(255),
    Teacher_Name VARCHAR(255),
    PhotoSample BLOB
    );

### CREATING REGTEACH TABLE
    CREATE TABLE regteach (
    fname VARCHAR(255),
    lname VARCHAR(255),
    cnum VARCHAR(20),
    email VARCHAR(255),
    ssq VARCHAR(50),
    sa VARCHAR(255),
    pwd VARCHAR(255)
    );

### CREATING STDATTENDANCE TABLE
    CREATE TABLE stdattendance (
    std_id INT,
    std_roll_no VARCHAR(20),
    std_name VARCHAR(255),
    std_time TIME,
    std_date DATE,
    std_attendance VARCHAR(10),
    PRIMARY KEY (std_id)
    );