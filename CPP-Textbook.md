សម្រាប់និស្សិតខ្មែរ ការសរសេរ **Lecturer Textbook** និង **Student Workbook** គួរតែប្រើ **ភាសាខ្មែរជាចម្បង** ហើយរក្សាទុក **Technical Terms ជាភាសាអង់គ្លេស** ដើម្បីឱ្យនិស្សិតអាចអានឯកសារបច្ចេកទេស និងស្វែងរកព័ត៌មានបន្ថែមបានងាយ។ ខាងក្រោមជាគំរូស្តង់ដារដែលសាកសមសម្រាប់សាកលវិទ្យាល័យ និងវិទ្យាស្ថាននៅកម្ពុជា។

# 📘 សៀវភៅសម្រាប់គ្រូបង្រៀន (Lecturer Textbook)

## C++ Programming: Beginner to Advanced

### សរសេរដោយ៖ សេង ស៊ង់ (SENG Sourng)

### Course Information

| Item        | Description          |
| ----------- | -------------------- |
| Course Name | C++ Programming      |
| Course Code | CS201                |
| Credits     | 3                    |
| Total Hours | 45 Hours             |
| Session     | 30 Sessions          |
| Duration    | 90 Minutes / Session |
| Theory      | 30%                  |
| Practice    | 70%                  |

---

# Course Description

មុខវិជ្ជា C++ Programming ត្រូវបានរៀបចំឡើងដើម្បីឱ្យនិស្សិតយល់ដឹងអំពីគោលការណ៍សរសេរកម្មវិធី (Programming Concepts) ចាប់ពីកម្រិតមូលដ្ឋាន (Beginner) រហូតដល់កម្រិតខ្ពស់ (Advanced)។ និស្សិតនឹងសិក្សាអំពី Variables, Data Types, Operators, Conditional Statements, Loops, Functions, Arrays, Pointers, Object-Oriented Programming (OOP), File Handling, Standard Template Library (STL) និង Project Development។

---

# Course Learning Outcomes (CLOs)

នៅចុងបញ្ចប់នៃវគ្គសិក្សា និស្សិតអាច៖

### CLO1

ពន្យល់អំពីគោលការណ៍ Programming និង Algorithm បាន។

### CLO2

សរសេរកម្មវិធី C++ ដើម្បីដោះស្រាយបញ្ហាជាក់ស្តែងបាន។

### CLO3

ប្រើ Conditional Statements និង Loops បានត្រឹមត្រូវ។

### CLO4

អនុវត្ត Object-Oriented Programming (OOP) ក្នុងការអភិវឌ្ឍកម្មវិធីបាន។

### CLO5

អភិវឌ្ឍ Mini Project និង Final Project ដោយប្រើ C++ បាន។

---

# Module 1: សេចក្តីផ្តើមអំពី Programming និង C++

## Chapter 1: Introduction to Programming

### Learning Objectives

បន្ទាប់ពីរៀនមេរៀននេះ និស្សិតអាច៖

* យល់ពីអត្ថន័យនៃ Programming
* យល់ពី Algorithm
* អាន Flowchart បាន
* យល់ពី Problem Solving Process

---

## 1.1 តើ Programming ជាអ្វី?

Programming គឺជាដំណើរការសរសេរពាក្យបញ្ជា (Instructions) ដើម្បីឱ្យកុំព្យូទ័រអនុវត្តការងារណាមួយ។

### ឧទាហរណ៍

បញ្ហា៖ គណនាផ្ទៃក្រឡាចតុកោណ

```text
Input Length
Input Width
Area = Length × Width
Display Area
```

---

## 1.2 Algorithm

Algorithm គឺជាលំដាប់ជំហានក្នុងការដោះស្រាយបញ្ហា។

### Example

```text
Start
Input Radius
Calculate Area
Display Result
End
```

---

## Classroom Discussion

សំណួរពិភាក្សា៖

1. តើកម្មវិធី Computer មានសារៈសំខាន់ដូចម្តេច?
2. តើអ្នកប្រើប្រាស់កម្មវិធីអ្វីខ្លះរៀងរាល់ថ្ងៃ?

---

## Instructor Notes

👉 ពន្យល់ដោយប្រើឧទាហរណ៍ជីវិតប្រចាំថ្ងៃ

* Making Coffee
* Cooking Rice
* ATM Withdrawal

---

## Lab Activity

បង្កើត Algorithm សម្រាប់៖

* Login Facebook
* Borrow Book from Library
* Register Course Online

---

## Quiz

1. តើ Algorithm ជាអ្វី?
2. តើ Flowchart ប្រើសម្រាប់អ្វី?

---

# Module 2: C++ Fundamentals

## Chapter 3: Variables and Data Types

### Learning Objectives

និស្សិតអាច៖

* ប្រកាស Variables
* ប្រើ Data Types បាន
* បញ្ចូល និងបង្ហាញទិន្នន័យ

---

## 3.1 Variables

Variable គឺជាទីតាំងផ្ទុកទិន្នន័យក្នុង Memory។

### Syntax

```cpp
int age;
float salary;
char grade;
string name;
```

---

## 3.2 Data Types

| Data Type | Description   | Example  |
| --------- | ------------- | -------- |
| int       | Integer       | 25       |
| float     | Decimal       | 25.5     |
| double    | Large Decimal | 123.456  |
| char      | Character     | 'A'      |
| string    | Text          | "Sourng" |
| bool      | True/False    | true     |

---

## Example Program

```cpp
#include <iostream>
using namespace std;

int main()
{
    string name;
    int age;

    cout<<"Enter Name: ";
    cin>>name;

    cout<<"Enter Age: ";
    cin>>age;

    cout<<"Name = "<<name<<endl;
    cout<<"Age = "<<age;

    return 0;
}
```

---

## Teaching Tips

សួរនិស្សិតឱ្យបង្កើត

### Student Profile

* Student ID
* Name
* Gender
* Age
* Major

---

## Lab Exercise

### Lab 01: Student Information System

បង្កើតកម្មវិធីបញ្ចូលព័ត៌មាននិស្សិត

Output

```text
Student ID : AU001
Name       : Dara
Age        : 20
Major      : Computer Science
```

---

# Module 5: Object-Oriented Programming (OOP)

## Chapter 15: Classes and Objects

### Learning Objectives

និស្សិតអាច៖

* បង្កើត Class
* បង្កើត Object
* ប្រើ Constructor

---

## 15.1 Class

Class គឺជា Blueprint សម្រាប់បង្កើត Object។

### Example

```cpp
class Student
{
public:
    string name;
    int age;

    void display()
    {
        cout<<name<<endl;
        cout<<age;
    }
};
```

---

## 15.2 Object

```cpp
Student s1;
```

---

## Complete Example

```cpp
#include <iostream>
using namespace std;

class Student
{
public:
    string name;
    int age;

    void display()
    {
        cout<<"Name: "<<name<<endl;
        cout<<"Age : "<<age<<endl;
    }
};

int main()
{
    Student s1;

    s1.name="Dara";
    s1.age=20;

    s1.display();

    return 0;
}
```

---

## Lab Activity

### Student Management System

Requirements:

* Add Student
* Display Student
* Search Student

---

# 📗 សៀវភៅសម្រាប់និស្សិត (Student Workbook)

## Chapter Structure

---

### 🎯 Learning Objectives

បន្ទាប់ពីរៀនចប់ និស្សិតអាច៖

* សរសេរកូដបាន
* អនុវត្ត Lab បាន
* ដោះស្រាយបញ្ហាបាន

---

### 📚 Key Concepts

| Term      | Meaning        |
| --------- | -------------- |
| Variable  | អថេរ           |
| Data Type | ប្រភេទទិន្នន័យ |
| Loop      | រង្វិលជុំ      |
| Function  | អនុគមន៍        |
| Class     | ថ្នាក់         |
| Object    | វត្ថុ          |

---

### 📝 Guided Example

```cpp
#include <iostream>
using namespace std;

int main()
{
    cout<<"Welcome to C++";
    return 0;
}
```

---

### ✍ Practice Exercise

#### Exercise 1

បង្កើតកម្មវិធីបង្ហាញ

```text
Welcome to C++ Programming
```

---

#### Exercise 2

ប្រកាស Variable ខាងក្រោម

```cpp
name
age
gender
salary
```

ហើយបង្ហាញលទ្ធផល។

---

### 🚀 Challenge Exercise

បង្កើតកម្មវិធី

### Student Registration System

Input:

```text
Student ID
Name
Gender
Age
Major
```

Output:

```text
===== Student Profile =====

Student ID : AU001
Name       : Sokha
Gender     : Male
Age        : 20
Major      : IT
```

---

### 🔍 Reflection Questions

1. តើអ្នកបានរៀនអ្វីខ្លះពីមេរៀននេះ?
2. តើចំណុចណាដែលពិបាក?
3. តើអ្នកអាចអនុវត្តវានៅទីណា?

---

### 🧪 Lab Checklist

| Task             | Complete |
| ---------------- | -------- |
| Create Project   | ☐        |
| Write Code       | ☐        |
| Compile Program  | ☐        |
| Debug Program    | ☐        |
| Run Successfully | ☐        |

---

### 📖 Chapter Summary

* Variable ប្រើសម្រាប់ផ្ទុកទិន្នន័យ
* Data Type កំណត់ប្រភេទទិន្នន័យ
* Input ប្រើ `cin`
* Output ប្រើ `cout`

---

### 📋 Chapter Quiz

#### Multiple Choice

1. Which keyword is used to display output?

A. cin
B. cout
C. int
D. return

---

#### Coding Question

សរសេរកម្មវិធីគណនា Area of Rectangle។

---

## 🎓 Final Project Portfolio

### Beginner Project

* Calculator System
* Grade Management System

### Intermediate Project

* Employee Management System
* Library Management System

### Advanced Project

* Hotel Management System
* Inventory Management System
* Point of Sale (POS)

គំរូនេះគឺសាកសមបំផុតសម្រាប់ការបង្កើត **Lecturer Textbook (300–500 Pages)** និង **Student Workbook (150–250 Pages)** សម្រាប់និស្សិត Computer Science នៅកម្ពុជា ដោយប្រើភាសាខ្មែរ និងរក្សា Technical Terms ជាភាសាអង់គ្លេស។
