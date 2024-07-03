# CSS-ASS

## PROGRAM: 
# HOME :
## HTML:
```
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
        <div class="logo">ROOPTECH</div>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="products.html">Products</a></li>
                <li><a href="council.html">People</a></li>
                <li><a href="contact_us.html">Contact</a></li>
            </ul>
        </nav>
        <div class="search-container">
            <input type="text" placeholder="Enter to Search">
            <button>Search</button>
        </div>
    </header>
    <main>
        <h1>"Driving progress through precision engineering and boundless creativity."</h1>
        <div class="button-container">
            <button class="login-btn">Log In</button>
            <button class="signup-btn">Sign Up</button>
        </div>
    </main>
    <footer>
        DESIGNED AND DEVELOPED BY GURU PRASAD B(212221230032)
    </footer>
</body>
</html>
```

## CSS:
```
/* Reset some default browser styles */
body, h1, ul {
  margin: 0;
  padding: 0;
}

body {
  font-family: Arial, sans-serif;
  background-color: black;
  color: white;
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px;
  background-color: black;
}

.logo {
  font-size: 24px;
  font-weight: bold;
  color: #00c6ff;
}

nav ul {
  display: flex;
  list-style: none;
}

nav ul li {
  margin: 0 10px;
}

nav ul li a {
  color: white;
  text-decoration: none;
}

.search-container {
  display: flex;
}

.search-container input {
  padding: 5px;
  border: none;
  border-radius: 5px 0 0 5px;
}

.search-container button {
  padding: 5px 10px;
  border: none;
  background-color: #00c6ff;
  color: black;
  border-radius: 0 5px 5px 0;
  cursor: pointer;
}

main {
  flex: 1;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
  padding: 20px;
  background: url('img/bg.jpeg') no-repeat center center/cover;
}

main h1 {
  font-size: 2em;
  margin-bottom: 20px;
}

.button-container {
  display: flex;
  gap: 20px;
}

button {
  padding: 10px 20px;
  border: none;
  cursor: pointer;
  border-radius: 5px;
  font-size: 1em;
}

.login-btn {
  background-color: red;
  color: white;
}

.signup-btn {
  background-color: green;
  color: white;
}

footer {
  background-color: red;
  color: black;
  text-align: center;
  padding: 10px;
}
```

# PRODUCT:

## HTML:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Page</title>
    <link rel="stylesheet" href="products.css">
</head>
<body>
    <header>
        <div class="logo">ROOPTECH</div>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="products.html">Products</a></li>
                <li><a href="council.html">People</a></li>
                <li><a href="contact_us.html">Contact</a></li>
            </ul>
        </nav>
        <div class="search-container">
            <input type="text" placeholder="Enter to Search">
            <button>Search</button>
        </div>
    </header>
    <main>
        <div class="product-container">
            <div class="product-card">
                <h2>C++</h2>
                <p>Efficiency Redefined: Harnessing the Power of C++ for Next-Level Development</p>
            </div>
            <div class="product-card">
                <h2>C</h2>
                <p>Crafting Performance: Where Precision Meets C Programming.</p>
            </div>
            <div class="product-card">
                <h2>JAVASCRIPT</h2>
                <p>Scripting Success: Unleashing the Power of JavaScript.</p>
            </div>
            <div class="product-card">
                <h2>PHP</h2>
                <p>PHP is a server side scripting language that is embedded in HTML.</p>
            </div>
            <div class="product-card">
                <h2>PYTHON</h2>
                <p>Unlocking Innovation: Python Paving the Way to Progress.</p>
            </div>
            <div class="product-card">
                <h2>SQL</h2>
                <p>SQL is a standard language for accessing and manipulating databases.</p>
            </div>
            <div class="product-card">
                <h2>SHELL</h2>
                <p>Shell can be accessed by users using a command line interface.</p>
            </div>
            <div class="product-card">
                <h2>RUBY</h2>
                <p>Ruby: Where Simplicity Meets Power in Programming</p>
            </div>
            <div class="product-card">
                <h2>TYPESCRIPT</h2>
                <p>Empower Your Code: Embrace the Future with TypeScript</p>
            </div>
            <div class="product-card">
                <h2>F#</h2>
                <p>F# is an Open-source programming language with a lot of features.</p>
            </div>
        </div>
    </main>
    <footer>
        Designed and DEVELOPED BY  GURU PRASAD B(212221230032)
    </footer>
</body>
</html>
```
## CSS:
```
/* Reset some default browser styles */
body, h1, h2, ul, p {
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
    background-color: black;
    color: white;
    display: flex;
    flex-direction: column;
    min-height: 100vh;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background-color: black;
}

.logo {
    font-size: 24px;
    font-weight: bold;
    color: #FF0000;
}

nav ul {
    display: flex;
    list-style: none;
}

nav ul li {
    margin: 0 10px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

nav ul li a.active {
    color: red;
}

.search-container {
    display: flex;
}

.search-container input {
    padding: 5px;
    border: none;
    border-radius: 5px 0 0 5px;
}

.search-container button {
    padding: 5px 10px;
    border: none;
    background-color: red;
    color: white;
    border-radius: 0 5px 5px 0;
    cursor: pointer;
}

main {
    flex: 1;
    padding: 20px;
    background: url('img/bg.jpeg') no-repeat center center/cover;
}

.product-container {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
}

.product-card {
    background-color: rgba(255, 255, 255, 0.1);
    border: 1px solid white;
    border-radius: 10px;
    padding: 20px;
    width: 200px;
    text-align: center;
}

.product-card h2 {
    color: red;
    margin-bottom: 10px;
}

footer {
    background-color: red;
    color: black;
    text-align: center;
    padding: 10px;
}
```
# PEOPLE:

## HTML:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>People Page</title>
    <link rel="stylesheet" href="council.css">
</head>
<body>
    <header>
        <div class="logo">ROOPTECH</div>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="products.html">Products</a></li>
                <li><a href="council.html">People</a></li>
                <li><a href="contact_us.html">Contact</a></li>
            </ul>
        </nav>
        <div class="search-container">
            <input type="text" placeholder="Enter to Search">
            <button>Search</button>
        </div>
    </header>
    <main>
        <div class="people-container">
            <div class="person-card">
                <img src="img/img.me.jpeg" alt="Roop Sagar">
                <h3>GURU PRASAD B</h3>
                <p>CEO</p>
            </div>
            <div class="person-card">
                <img src="img/img ratan.jpeg" alt="Ratan Tata">
                <h3>RATAN TATA</h3>
                <p>CEO, Co-Founder</p>
            </div>
            <div class="person-card">
                <img src="img/img steve.jpeg" alt="Steve Jobs">
                <h3>STEVE JOBS</h3>
                <p>CTO, Co-Founder</p>
            </div>
            <div class="person-card">
                <img src="img/img6.jpeg" alt="Sundar">
                <h3>SUNDAR</h3>
                <p>DIRECTOR</p>
            </div>
            <div class="person-card">
                <img src="img/img walt.jpeg" alt="Walt Disney">
                <h3>WALT DISNEY</h3>
                <p>Asst. Director</p>
            </div>
            <div class="person-card">
                <img src="img/img3.jpeg" alt="Elon Musk">
                <h3>ELON MUSK</h3>
                <p>Dy. Director</p>
            </div>
        </div>
    </main>
    <footer>
        Designed and DEVELOPED BY  GURU PRASAD B(212221230032)
    </footer>
</body>
</html>
```
## CSS:
```
/* Reset some default browser styles */
body, h1, h2, ul, p {
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
    background-color: black;
    color: white;
    display: flex;
    flex-direction: column;
    min-height: 100vh;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background-color: black;
}

.logo {
    font-size: 24px;
    font-weight: bold;
    color: #FF0000;
}

nav ul {
    display: flex;
    list-style: none;
}

nav ul li {
    margin: 0 10px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

nav ul li a.active {
    color: red;
}

.search-container {
    display: flex;
}

search-container input {
    padding: 5px;
    border: none;
    border-radius: 5px 0 0 5px;
}

.search-container button {
    padding: 5px 10px;
    border: none;
    background-color: red;
    color: white;
    border-radius: 0 5px 5px 0;
    cursor: pointer;
}

main {
    flex: 1;
    padding: 20px;
    background: url('img/bg.jpeg') no-repeat center center/cover;
}

.people-container {
    display: flex;
    justify-content: center;
    gap: 20px;
    flex-wrap: wrap;
}

.person-card {
    text-align: center;
}

.person-card img {
    border-radius: 50%;
    border: 2px solid white;
    width: 150px;
    height: 150px;
}

.person-card h3 {
    margin: 10px 0 5px;
}

.person-card p {
    color: red;
    margin-bottom: 10px;
}

footer {
    background-color: red;
    color: black;
    text-align: center;
    padding: 10px;
}
```
# CONTACT US:

## HTML:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us Page</title>
    <link rel="stylesheet" href="contact_us.css">
</head>
<body>
    <header>
        <div class="logo">ROOPTECH</div>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="products.html">Products</a></li>
                <li><a href="council.html">People</a></li>
                <li><a href="contact_us.html">Contact</a></li>
            </ul>
        </nav>
        <div class="search-container">
            <input type="text" placeholder="Enter to Search">
            <button>Search</button>
        </div>
    </header>
    <main>
        <div class="contact-container">
            <div class="contact-form">
                <h2>Contact Us</h2>
                <form action="#">
                    <input type="text" placeholder="Your Name" required>
                    <input type="email" placeholder="Your Email" required>
                    <button type="submit">Submit</button>
                </form>
            </div>
            <div class="contact-info">
                <h2>Contact Information</h2>
                <p><strong>Address :</strong> <span>3RD Floor, Tower 12, FCA Building No.18, ROOP DEVELOP CITY Phase-I, SECUNDERABAD HR IN 1888546</span></p>
                <p><strong>Email :</strong> <span>rooptech.official@gmail.com</span></p>
                <p><strong>Phone :</strong> <span>+1 45465654</span></p>
            </div>
        </div>
    </main>
    <footer>
        Designed and DEVELOPED BY  GURU PRASAD B(212221230032)
    </footer>
</body>
</html>
```
## CSS:
```
/* Reset some default browser styles */
body, h1, h2, ul, p {
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
    background-color: black;
    color: white;
    display: flex;
    flex-direction: column;
    min-height: 100vh;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background-color: black;
}

.logo {
    font-size: 24px;
    font-weight: bold;
    color: #FF0000;
}

nav ul {
    display: flex;
    list-style: none;
}

nav ul li {
    margin: 0 10px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

nav ul li a.active {
    color: red;
}

.search-container {
    display: flex;
}

.search-container input {
    padding: 5px;
    border: none;
    border-radius: 5px 0 0 5px;
}

.search-container button {
    padding: 5px 10px;
    border: none;
    background-color: red;
    color: white;
    border-radius: 0 5px 5px 0;
    cursor: pointer;
}

main {
    flex: 1;
    padding: 20px;
    background: url('img/bg.jpeg') no-repeat center center/cover;
}

.contact-container {
    display: flex;
    justify-content: center;
    gap: 20px;
    flex-wrap: wrap;
}

.contact-form, .contact-info {
    border: 1px solid white;
    padding: 20px;
    border-radius: 10px;
    width: 300px;
    box-sizing: border-box;
}

.contact-form h2, .contact-info h2 {
    text-align: center;
    margin-bottom: 20px;
}

.contact-form input {
    width: 100%;
    padding: 10px;
    margin: 10px 0;
    border: 1px solid white;
    border-radius: 5px;
    background: transparent;
    color: white;
}

.contact-form button {
    width: 100%;
    padding: 10px;
    border: none;
    background-color: red;
    color: white;
    border-radius: 5px;
    cursor: pointer;
}

.contact-info p {
    margin: 10px 0;
}

.contact-info p strong {
    color: red;
}

footer {
    background-color: red;
    color: black;
    text-align: center;
    padding: 10px;
}
```
# OUTPUT:

![op1](https://github.com/Guruprasad21002001/CSS-ASS/assets/95342910/fec69e10-0c0a-40e0-bb1c-2928847212ec)

![op2](https://github.com/Guruprasad21002001/CSS-ASS/assets/95342910/e34f2247-b4c4-4651-844f-1b0b1db4fb50)

![op3](https://github.com/Guruprasad21002001/CSS-ASS/assets/95342910/9bb0cd94-e108-4808-9c87-4d322b52104b)

![op4](https://github.com/Guruprasad21002001/CSS-ASS/assets/95342910/ed10519b-a33b-49dc-bc67-b145e7e4d833)
