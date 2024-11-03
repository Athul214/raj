<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Smart Parking System</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Smart Parking System</h1>
        <div class="form-container" id="login-form">
            <h2>Login</h2>
            <input type="text" id="login-username" placeholder="Username" required>
            <input type="password" id="login-password" placeholder="Password" required>
            <button id="login-button">Login</button>
            <p>Don't have an account? <span id="show-register">Register here</span></p>
        </div>

        <div class="form-container" id="register-form" style="display: none;">
            <h2>Register</h2>
            <input type="text" id="register-username" placeholder="Username" required>
            <input type="password" id="register-password" placeholder="Password" required>
            <button id="register-button">Register</button>
            <p>Already have an account? <span id="show-login">Login here</span></p>
        </div>
    </div>
    
    <script src="script.js"></script>
</body>
</html>
