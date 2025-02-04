<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Page</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://unpkg.com/boxicons@2.1.4/dist/boxicons.js"></script>
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
</head>

<body>
    <div class="glass-container">
        <div class="login-box">
            <h2>Login</h2>
            <form action="#" method="POST">
                <div>
                <input type="text" id="username" name="username" required placeholder="Username">
                <i class='bx bx-user-circle'></i>
                </div>
                <div>
                <input type="password" id="password" name="password" required placeholder="Password">
                <i class='bx bx-lock-alt' ></i>
                </div>
                <div class="options">
                    <input type="checkbox" id="remember" name="remember">
                    <label for="remember">Remember me</label>
                    <a href="#" id="Forgot">Forgot Password?</a>
                </div>
                
                <button type="submit">Login</button>

                <p>Don't have an account? <a href="#" id="register">Create account?</a></p>
            </form>
        </div>
    </div>
</body>
</html>
