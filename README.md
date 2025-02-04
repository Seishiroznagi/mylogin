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







~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


* {
    margin: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}

body {
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-image: url('image/husk.jpg');
    background-size: cover;
}

.glass-container {
    width: 300px;
    height: 400px;
    position: relative;
    z-index: 1;
    background: rgba(255, 255, 255, 0.1);
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    border-radius: 10px;
    border: 1px solid #000000;
}

.glass-container::before {
    content: '';
    position: absolute;
    width: 100%;
    height: 100%;
    border-radius: 10px;
    backdrop-filter: blur(5px);
    -webkit-backdrop-filter: blur(5px);
    z-index: -1;
}

.login-box {
    max-width: 250px;
    margin: 0 auto;
    text-align: center;
}

h2 {
    color: #000000;
    margin-top: 30px;
    margin-bottom: -20px;
}

form {
    display: flex;
    flex-direction: column;
    margin-top: 20px;
}

input {
    padding: 10px;
    margin-top: 25px;
    border: none;
    border-radius: 10px;
    background: transparent;
    border: 1px solid #000000;
    color: #000000;
    font-size: 15px;
}

input::placeholder {
    color: #000000;
}

input:focus {
    outline: none;
}

.options {
    display: flex;
    align-items: center;
    margin-top: 15px;
    font-size: 12px;
    color: #000000;
}

.options input {
    margin-right: 5px;
    margin-top: 0px;
}

.options a {
    text-decoration: none;
    color: black;
    margin-left: auto;
}

button {
    background: lightskyblue;
    color: black;
    padding: 10px;
    border: none;
    border-radius: 10px;
    cursor: pointer;
    margin-top: 15px;
}

button:hover {
    background: transparent;
    color: white;
    outline: 1px solid #000000;
}

p {
    font-size: 12px;
    color: #000000;
    margin-top: 15px;
}

#register {
    text-decoration: none;
    color: #000000;
    font-weight: bold;
}


