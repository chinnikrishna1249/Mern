<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Management System</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<header>
    <h1>Student Management System</h1>
    <nav>
        <a href="#">Home</a>
        <a href="#">Students</a>
        <a href="#">Attendance</a>
        <a href="#">Results</a>
        <a href="#">Contact</a>
    </nav>
</header>

<section class="hero">
    <h2>Student Details</h2>
    <p>View and manage student information.</p>

    <input type="text" id="search" placeholder="Search Student...">
</section>

<section class="table-section">

<table id="studentTable">

<thead>
<tr>
<th>ID</th>
<th>Name</th>
<th>Department</th>
<th>Year</th>
<th>Attendance</th>
<th>Status</th>
</tr>
</thead>

<tbody>

<tr>
<td>1001</td>
<td>Rahul Kumar</td>
<td>BCA</td>
<td>3rd Year</td>
<td>92%</td>
<td>Active</td>
</tr>

<tr>
<td>1002</td>
<td>Priya Sharma</td>
<td>B.Com</td>
<td>2nd Year</td>
<td>89%</td>
<td>Active</td>
</tr>

<tr>
<td>1003</td>
<td>Arjun Reddy</td>
<td>B.Sc</td>
<td>1st Year</td>
<td>95%</td>
<td>Active</td>
</tr>

<tr>
<td>1004</td>
<td>Anjali Singh</td>
<td>BBA</td>
<td>3rd Year</td>
<td>90%</td>
<td>Active</td>
</tr>

</tbody>

</table>

</section>

<footer>
<p>©️ 2026 Student Management System</p>
</footer>

<script src="script.js"></script>

</body>
</html>
