<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>BBI Academy Registration</title>

<style>
body{
    font-family: Arial, sans-serif;
    background:#f4f4f4;
    margin:0;
    padding:0;
}

nav{
    background:#007BFF;
    padding:15px;
    text-align:center;
}

nav a{
    color:white;
    text-decoration:none;
    margin:0 15px;
    font-weight:bold;
}

.container{
    width:90%;
    max-width:500px;
    margin:40px auto;
    background:white;
    padding:25px;
    border-radius:10px;
    box-shadow:0 0 15px rgba(0,0,0,0.1);
}

.logo{
    display:block;
    margin:0 auto 15px;
    width:100px;
}

h1,h2,h3{
    text-align:center;
    color:#333;
}

input, select{
    width:100%;
    padding:12px;
    margin-top:5px;
    margin-bottom:15px;
    border:1px solid #ccc;
    border-radius:5px;
    box-sizing:border-box;
}

button{
    width:100%;
    padding:12px;
    background:#007BFF;
    color:white;
    border:none;
    border-radius:5px;
    font-size:16px;
    cursor:pointer;
}

button:hover{
    background:#0056b3;
}

.website-link{
    display:block;
    text-align:center;
    margin-top:20px;
    text-decoration:none;
    color:#007BFF;
    font-weight:bold;
}

footer{
    text-align:center;
    padding:15px;
    background:#333;
    color:white;
    margin-top:20px;
}
</style>
</head>

<body>

<nav>
    <a href="#">Home</a>
    <a href="#">Courses</a>
    <a href="#">About</a>
    <a href="#">Contact</a>
</nav>

<div class="container">

<img src="logo.png" alt="BBI Academy Logo" class="logo">

<h1>Welcome to BBI Academy</h1>
<h2>Registration Form</h2>
<h3>Computer Training for Students</h3>

<form action="#" method="post">

<label>Full Name</label>
<input type="text" name="fullname" placeholder="Enter your full name" required>

<label>Phone Number</label>
<input type="tel" name="phone" placeholder="Enter phone number" required>

<label>Email Address</label>
<input type="email" name="email" placeholder="Enter your email" required>

<label>Age</label>
<input type="number" name="age" placeholder="Enter your age" required>

<label>Select Course</label>
<select name="course" required>
    <option value="">Choose a Course</option>
    <option>Web Design</option>
    <option>Graphic Design</option>
    <option>Computer Appreciation</option>
    <option>Computer Programming</option>
</select>

<label>Password</label>
<input type="password" name="password" placeholder="Create a password" required>

<button type="submit">Register Now</button>

</form>

<a class="website-link" href="https://engineerbikola.com" target="_blank">
Visit Engineer Bikola Website
</a>

</div>

<footer>
    <p>&copy; 2025 BBI Academy. All Rights Reserved.</p>
</footer>

</body>
</html># index.html