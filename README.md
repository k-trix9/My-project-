<!DOCTYPE html>
<html lang="en">
<head>
    <form>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Form</title>
    <style>
        /* Basic Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: content-box;
        }

        /* Body and background styling */
        body {
            font-family: Arial, sans-serif;
            height: 100vh;
            background-image: url("couple.webp"); /* Change this to your image path */
            background-size: cover;
            background-position: center;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        /* Styling for the login container */
        .blessing {
            display: flex;
            justify-content: center;
            align-items: center;
            width: 90%;
            height: 90%;
        }

        /* Styling for the login form */
        .login-form {
            background: rgba(0, 5, 0, 0.5); /* Semi-transparent background */
            padding: 70px;
            border-radius: 10px;
            color: red;
            width: 100
            max-width: 300px;
        }

        .login-form h2 {
            text-align: center;
            margin-bottom: 10px;
        }

        /* Input and button styling */
        .input-group {
            margin-bottom: 50px;
        }

        .input-group label {
            display: block;
            margin-bottom: 5px;
        }

        .input-group input {
            background-color: pink;
            width: 100%;
            padding: 5px;
            font-size: 16px;
            border: none;
            border-radius: 5px;
        }

        .button-group button {
            width: 100%;
            padding: 10px;
            font-size: 16px;
            border: none;
            border-radius: 5px;
            background-color: #6A0DAD;
            color:red;
            cursor: pointer;
        }

        .button-group button:hover {
            background-color: blue;
        }
    </style>
</head>
<body>
    <div class="blessing">
        <div class="login-form">
            <h2>Login</h2>
            <form action="#">
                <div class="input-group">
                    <label for="username">Username</label>
                    <input type="text" id="username" name="username" required>
                </div>
                <div class="input-group">
                    <label for="password">Password</label>
                    <input type="password"  name="password" required>
                </div>
                <div class="button-group">
                    <button type="submit">Login</button>
                    if you don't have an account<a href="p2.html">create new account</a>
                </div>
            </form>
        </div>
    </div>
</body>
</html>
