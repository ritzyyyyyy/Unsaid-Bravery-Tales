# Unsaid-Bravery-Tales
This project aims to create a platform that is a website where untold stories of military bravery can be shared and celebrated. 
<br>
Author- Ritu Mandiya


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 50px;
            background-color: #2b2b2b;
            color: #fff;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        h1 {
            color: hsl(0, 14%, 95%);
        }




form {
    max-width: 300px;
    margin: 0 auto;
    background-color: #1c1c1c;
    padding: 20px;
    border-radius: 8px;
    margin-top: 20px;
}

label {
    display: block;
    margin-bottom: 8px;
    color: hsl(0, 10%, 92%);
}

input {
    width: 100%;
    padding: 8px;
    margin-bottom: 16px;
    box-sizing: border-box;
}

button {
    background-color: #4CAF50;
    color: white;
    padding: 10px 15px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

select {
            width: 100%;
            padding: 8px;
            margin-bottom: 16px;
            box-sizing: border-box;
        }
    </style>
</head>
<body>

    <form action="one.php" method="post">
        <h1>Registration Form</h1>
    
        <label for="username">Name:</label>
        <input type="text" id="username" required>
    
        <label for="email">Email:</label>
        <input type="email" id="email" required>
    
        <label for="mobileNumber">Phone Number:</label>
        <input type="tel" id="mobileNumber" required>
    
        <label for="militaryBranch">Military Branch:</label>
        <select id="militaryBranch" required>
            <option value="Indian Army">Indian Army</option>
            <option value="Indian Navy">Indian Navy</option>
            <option value="Indian Air Force">Indian Air Force</option>
            <option value="Paramilitary and special forces">Paramilitary and special forces</option>
         
        </select>
    
     
        <label for="yearsofservice">Years of Service:</label>
        <input type="number" id="yearsofservice" required>
    
        <label for="militaryId">Military ID:</label>
        <input type="file" id="militaryId" accept="image/*" required>
    
        <button type="button" onclick="registerUser()">Register</button>
    </form>
    

    </body>
    </html>
