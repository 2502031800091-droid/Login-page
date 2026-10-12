<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Page</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: linear-gradient(135deg, #667eea, #764ba2);
        }

        .login-box {
            width: 350px;
            padding: 35px;
            background: white;
            border-radius: 15px;
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.2);
        }

        h2 {
            text-align: center;
            margin-bottom: 25px;
            color: #333;
        }

        .input-box {
            margin-bottom: 18px;
        }

        .input-box label {
            display: block;
            margin-bottom: 7px;
            color: #444;
        }

        .input-box input {
            width: 100%;
            padding: 12px;
            border: 1px solid #ccc;
            border-radius: 7px;
            outline: none;
        }

        .input-box input:focus {
            border-color: #667eea;
        }

        .remember {
            display: flex;
            align-items: center;
            gap: 8px;
            font-size: 14px;
            margin-bottom: 20px;
        }

        button {
            width: 100%;
            padding: 12px;
            background: #667eea;
            color: white;
            border: none;
            border-radius: 7px;
            font-size: 16px;
            cursor: pointer;
        }

        button:hover {
            background: #5266cc;
        }

        .register {
            text-align: center;
            margin-top: 20px;
            font-size: 14px;
        }

        .register a {
            color: #667eea;
            text-decoration: none;
        }
    </style>
</head>

<body>

    <div class="login-box">
        <h2>Login</h2>

        <form action="#" method="post">

            <div class="input-box">
                <label for="email">Email Address</label>
                <input type="email" id="email"
                       name="email"
                       placeholder="Enter your email"
                       required>
            </div>

            <div class="input-box">
                <label for="password">Password</label>
                <input type="password" id="password"
                       name="password"
                       placeholder="Enter your password"
                       required>
            </div>

            <div class="remember">
                <input type="checkbox" id="remember">
                <label for="remember">Remember me</label>
            </div>

            <button type="submit">Login</button>

            <div class="register">
                Don't have an account?
                <a href="register.html">Register</a>
            </div>

        </form>
    </div>

</body>
</html>
