# trial.github.io
<!DOCTYPE html>
<HTML lang="en">



<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Password Protected Website</title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <div class="password-container">
        <h1>Welcome to the Protected Website</h1>
        <p>Please enter the password to continue:</p>
        <input type="password" id="password-input">
        <button onclick="checkPassword()">Submit</button>
        <p id="error-message" class="error-message"></p>
    </div>

const correctPassword = "secret"; // Change this to your desired password

    <div class="main-page-container" style="display: none;">
        <h1>Main Page</h1>
        <!-- Add your main page content here -->
    </div>

   
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

.password-container {
    text-align: center;
    padding: 20px;
}

.main-page-container {
    text-align: center;
    padding: 20px;
}

.error-message {
    color: red;
}

function checkPassword() {
    const enteredPassword = document.getElementById("password-input").value;
    const correctPassword = "secret"; // Change this to your desired password

    if (enteredPassword === correctPassword) {
        document.querySelector(".password-container").style.display = "none";
        document.querySelector(".main-page-container").style.display = "Correct password";
    } else {
        document.getElementById("error-message").textContent = "Incorrect password. Please try again.";
    }
}

