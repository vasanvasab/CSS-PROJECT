### HTML AND CSS PAGE TO RE-CREATE THE IMAGE

### AIM:
To re-create a HTML and CSS page based on the given image.

### HTML CODE
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ROOP TECH</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">ROOPTECH</div>
            <ul>
                <li><a href="#">HOME</a></li>
                <li><a href="#">PRODUCTS</a></li>
                <li><a href="#">PEOPLE</a></li>
                <li><a href="#">CONTACT</a></li>
            </ul>
            <div class="search-bar">
                <input type="text" placeholder="Enter to Search">
                <button>Search</button>
            </div>
        </nav>
    </header>
    <main>
        <section class="hero">
            <h1>"Driving progress through precision engineering and boundless creativity."</h1>
            <div class="buttons">
                <button class="login">Log In</button>
                <button class="signup">Sign Up</button>
            </div>
        </section>
    </main>
    <footer>
        <p>DESIGNED AND DEVELOPED KAVIVARSHINI(212221040078)</p>
    </footer>
</body>
</html>

~~~
### CSS CODE
~~~
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: url('background.jpg') no-repeat center center fixed;
    background-size: cover;
    color: white;
}

header {
    background: rgba(0, 0, 0, 0.8);
    padding: 20px 0;
    position: fixed;
    width: 100%;
    top: 0;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

.logo {
    font-size: 24px;
    font-weight: bold;
}

nav ul {
    list-style: none;
    display: flex;
    margin: 0;
    padding: 0;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    text-decoration: none;
    color: white;
    font-size: 16px;
}

.search-bar {
    display: flex;
}

.search-bar input {
    padding: 5px;
    border: none;
    border-radius: 5px 0 0 5px;
}

.search-bar button {
    padding: 5px 10px;
    border: none;
    border-radius: 0 5px 5px 0;
    background: #00c0ff;
    color: white;
    cursor: pointer;
}

.hero {
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 0 20px;
    background: rgba(0, 0, 0, 0.6);
    position: relative;
    top: 80px;
}

.hero h1 {
    font-size: 36px;
    margin-bottom: 20px;
}

.buttons {
    display: flex;
    gap: 20px;
}

.buttons button {
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    font-size: 16px;
    cursor: pointer;
}

.login {
    background: red;
    color: white;
}

.signup {
    background: green;
    color: white;
}

footer {
    background: rgba(0, 123, 255, 0.71);
    text-align: center;
    padding: 10px;
    position: fixed;
    width: 100%;
    bottom: 0;
}
body{
    background-image: url(back.jpg);
}
~~~
### OUTPUT
![image](https://github.com/vasanvasab/CSS-PROJECT/assets/143481226/f18c00ec-e519-4779-b0b8-7eac49ddf304)

### RESULT:
Thus the program has been completed successfully.
