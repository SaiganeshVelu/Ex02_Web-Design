# Ex.02 Implementation of Lists
## AIM:
  To create list of Departments in an Institution.

## ALGORITHM:
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Create an ordered list using ```<ol>``` tag.

### STEP-3
  List the Departments using ```<li>``` tag.

### STEP-4
  Create an unordered list using ```<ul>``` tag for nesting lists.

### STEP-5
  Open the file in a browser and verify the output.
  
## CODE:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Implementation of Lists</title>
</head>
<style>
    body{
        background-color: black;
        color:whitesmoke;
    }
</style>
<body>
    <h1>Saveetha Engineering College</h1>
    <hr>
    <ol type="A">
        <li>Agricultural Engineering</li>
        <li>Computer Science And Engineering</li>
        <li>Information Technology</li>
        <li>Data Science</li>
        <ul>
            <li>Artificial Intelligence - Data Science</li>
            <li>Artificial Intelligence - Machine Learning</li>
            <li>Internet of Things</li>
        </ul>
        <li>Electonics & Communication Engineering</li>
        <li>Electonics & Electronics Engineering</li>
        <li>Mechanical Engineeringd</li>
    </ol>
</body>
</html>
~~~
## OUTPUT:
![Screenshot 2023-05-22 233326](https://github.com/SaiganeshVelu/Ex02_Web-Design/assets/127816325/c0c208f3-37c0-429a-8c46-3d4a9e91cac5)

## RESULT:
  List of Departments in an Institution is created successfully.
