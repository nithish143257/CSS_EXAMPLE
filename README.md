home.html

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ROOP TECH</title>
    <style>
        * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    color: white;
    background-color: black;
    height: 100vh;
}

header {
    background-color: black;
    padding: 20px;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 20px; 
}

.logo {
    font-size: 24px;
    font-weight: bold;
    color: #00ffff;
    margin-right: 20px; 
}

.nav-links {
    list-style: none;
    display: flex;
    gap: 20px;
}

.nav-links a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

.search-bar {
    display: flex;
    align-items: center;
    margin-left: 20px; 
}

.search-bar input {
    padding: 5px;
    border: none;
    border-radius: 5px;
}

.search-bar button {
    margin-left: 10px;
    padding: 6px 12px;
    background-color: #00ffff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.hero {
    text-align: center;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: calc(100vh - 80px); 
    padding: 20px; 
    
}

.hero h1 {
    font-size: 48px; 
    margin-bottom: 30px; 
    line-height: 1.5; 
}

.buttons {
    display: flex;
    justify-content: center;
    gap: 20px;
}

button {
    padding: 10px 20px;
    font-size: 16px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.login {
    background-color: red;
    color: white;
}

.signup {
    background-color: green;
    color: white;
}

footer {
    background-color: red;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}

    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">ROOPTECH</div>
            <ul class="nav-links">
                <li><a href="home.html">HOME</a></li>
                <li><a href="productS.html">PRODUCTS</a></li>
                <li><a href="people.html">PEOPLE</a></li>
                <li><a href="contact.html">CONTACT</a></li>
            </ul>
            <div class="search-bar">
                <input type="text" placeholder="Enter to Search">
                <button>Search</button>
            </div>
        </nav>
    </header>

    <main>
        <div class="hero">
            <h1>"Driving progress through <br> precision engineering <br>and boundless creativity."</h1>
            <div class="buttons">
                <button class="login">Log In</button>
                <button class="signup">Sign Up</button>
            </div>
        </div>
    </main>

    <footer>
        <p>DESIGNED AND DEVELOPED BY NITHISH KUMAR P (212221040115) </p>
    </footer>
</body>
</html>

```

products.html

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ROOP TECH</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            color: white;
            background-color: black;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
        }

        header {
            background-color: black;
            padding: 20px;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 20px; 
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
            color: #ff0000;
            margin-right: 20px; 
        }

        .nav-links {
            list-style: none;
            display: flex;
            gap: 20px;
        }

        .nav-links a {
            color: white;
            text-decoration: none;
            font-size: 18px;
        }

        .nav-links a.active {
            color: #ff0000;
        }

        .search-bar {
            display: flex;
            align-items: center;
            margin-left: 20px; 
        }

        .search-bar input {
            padding: 5px;
            border: none;
            border-radius: 5px;
        }

        .search-bar button {
            margin-left: 10px;
            padding: 6px 12px;
            background-color: #ff0000;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        main {
            flex: 1;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 20px;
        }

        .products {
            width: 100%;
            text-align: center;
        }

        .products h1 {
            font-size: 48px;
            margin-bottom: 30px;
            color: #ff0000;
        }

        .product-grid {
            display: grid;
            grid-template-columns: repeat(5, 1fr);
            gap: 20px;
            width: 100%;
        }

        .product-card {
            background-color: #1a1a1a;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 275px;
            width:275px;
            border: 1px solid white;
        }

        .product-card:hover {
            transform: translateY(-10px);
        }

        .product-card h2 {
            font-size: 18px;
            margin-bottom: 10px;
            color: #ff0000;
        }

        .product-card p {
            font-size: 14px;
            color: white;
            text-align: center;
        }

        footer {
            background-color: red;
            text-align: center;
            padding: 10px 0;
            width: 100%;
            position: static;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">ROOPTECH</div>
            <ul class="nav-links">
                <li><a href="home.html">HOME</a></li>
                <li><a href="products.html" class="active">PRODUCTS</a></li>
                <li><a href="people.html">PEOPLE</a></li>
                <li><a href="contact.html">CONTACT</a></li>
            </ul>
            <div class="search-bar">
                <input type="text" placeholder="Enter to Search">
                <button>Search</button>
            </div>
        </nav>
    </header>

    <main>
        <section class="products">
            <h1>Our Products</h1>
            <div class="product-grid">
                <div class="product-card">
                    <h2>C++</h2>
                    <p>Efficiency Redefined: Harnessing the Power of C++ for Next-Level Development</p>
                </div>
                <div class="product-card">
                    <h2>C</h2>
                    <p>Crafting Performance: Where Precision Meets C Programming</p>
                </div>
                <div class="product-card">
                    <h2>JavaScript</h2>
                    <p>Scripting Success: Unleashing the Power of JavaScript</p>
                </div>
                <div class="product-card">
                    <h2>PHP</h2>
                    <p>PHP is a server side scripting language that is embedded in HTML.</p>
                </div>
                <div class="product-card">
                    <h2>Python</h2>
                    <p>Unlocking Innovation: Python Paving the Way to Progress.</p>
                </div>
                <div class="product-card">
                    <h2>SQL</h2>
                    <p>SQL is a standard language for accessing and manipulating databases.</p>
                </div>
                <div class="product-card">
                    <h2>Shell</h2>
                    <p>Shell can be accessed by users using a command line interface.</p>
                </div>
                <div class="product-card">
                    <h2>Ruby</h2>
                    <p>Ruby: Where Simplicity Meets Power in Programming</p>
                </div>
                <div class="product-card">
                    <h2>TypeScript</h2>
                    <p>Empower Your Code: Embrace the Future with TypeScript</p>
                </div>
                <div class="product-card">
                    <h2>F#</h2>
                    <p>F# is an Open-source programming language with a lot of features.</p>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <p>DESIGNED AND DEVELOPED BY NITHISH KUMAR P (212221040115) </p>
    </footer>
</body>
</html>

```

people.html

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>People</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            color: white;
            background-color: black;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
        }

        header {
            background-color: black;
            padding: 20px;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 20px; 
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
            color: #ff0000;
            margin-right: 20px; 
        }

        .nav-links {
            list-style: none;
            display: flex;
            gap: 20px;
        }

        .nav-links a {
            color: white;
            text-decoration: none;
            font-size: 18px;
        }

        .nav-links a.active {
            color: #ff0000;
        }

        .search-bar {
            display: flex;
            align-items: center;
            margin-left: 20px; 
        }

        .search-bar input {
            padding: 5px;
            border: none;
            border-radius: 5px;
        }

        .search-bar button {
            margin-left: 10px;
            padding: 6px 12px;
            background-color: #ff0000;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        main {
            flex: 1;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 20px;
        }

        .team {
            width: 100%;
            text-align: center;
        }

        .team h1 {
            font-size: 48px;
            margin-bottom: 30px;
            color: #ff0000;
        }

        .member-grid {
            display: grid;
            grid-template-columns: repeat(6, 1fr);
            gap: 20px;
            width: 100%;
        }

        .member-card {
            background-color: transparent;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }

        .member-card img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin-bottom: 10px;
            border: 5px solid white; /* Added white border */
        }

        .member-card h2 {
            font-size: 18px;
            margin-bottom: 10px;
            color: #ff0000;
        }

        .member-card p {
            font-size: 14px;
            color: white;
            text-align: center;
        }

        footer {
            background-color: red;
            text-align: center;
            padding: 10px 0;
            width: 100%;
            position: static;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">ROOPTECH</div>
            <ul class="nav-links">
                <li><a href="home.html">HOME</a></li>
                <li><a href="products.html">PRODUCTS</a></li>
                <li><a href="people.html" class="active">PEOPLE</a></li>
                <li><a href="contact.html">CONTACT</a></li>
            </ul>
            <div class="search-bar">
                <input type="text" placeholder="Enter to Search">
                <button>Search</button>
            </div>
        </nav>
    </header>

    <main>
        <section class="team">
            <h1>Our Team</h1>
            <div class="member-grid">
                <div class="member-card">
                    <img src="roop.jpeg" alt="Roop Sagar">
                    <h2>ROOP SAGAR</h2>
                    <p>CEO</p>
                </div>
                <div class="member-card">
                    <img src="tata.jpeg" alt="Ratan Tata">
                    <h2>RATAN TATA</h2>
                    <p>CEO, Co-Founder</p>
                </div>
                <div class="member-card">
                    <img src="steve.jpeg" alt="Steve Jobs">
                    <h2>STEVE JOBS</h2>
                    <p>CTO, Co-Founder</p>
                </div>
                <div class="member-card">
                    <img src="sundar.jpeg" alt="Sundar">
                    <h2>SUNDAR</h2>
                    <p>DIRECTOR</p>
                </div>
                <div class="member-card">
                    <img src="walt.jpeg" alt="Walt Disney">
                    <h2>WALT DISNEY</h2>
                    <p>Asst. Director</p>
                </div>
                <div class="member-card">
                    <img src="elon.jpeg" alt="Elon Musk">
                    <h2>ELON MUSK</h2>
                    <p>Dy. Director</p>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <p>DESIGNED AND DEVELOPED BY NITHISH KUMAR P (212221040115)</p>
    </footer>
</body>
</html>

```

contact.html

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            color: white;
            background-color: black;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
        }

        header {
            background-color: black;
            padding: 20px;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 20px; 
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
            color: #ff0000;
            margin-right: 20px; 
        }

        .nav-links {
            list-style: none;
            display: flex;
            gap: 20px;
        }

        .nav-links a {
            color: white;
            text-decoration: none;
            font-size: 18px;
        }

        .nav-links a.active {
            color: #ff0000;
        }

        .search-bar {
            display: flex;
            align-items: center;
            margin-left: 20px; 
        }

        .search-bar input {
            padding: 5px;
            border: none;
            border-radius: 5px;
        }

        .search-bar button {
            margin-left: 10px;
            padding: 6px 12px;
            background-color: #ff0000;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        main {
            flex: 1;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 20px;
        }

        .contact {
            width: 100%;
            text-align: center;
        }

        .contact h1 {
            font-size: 48px;
            margin-bottom: 30px;
            color: #ff0000;
        }

        .contact-container {
            display: flex;
            justify-content: center;
            gap: 40px;
            width: 100%;
        }

        .contact-form,
        .contact-info {
            background-color: #1a1a1a;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            flex: 1;
            max-width: 400px;
            border: 1px solid white;
        }

        .contact-form h2,
        .contact-info h2 {
            font-size: 24px;
            margin-bottom: 20px;
            color: #ff0000;
        }

        .contact-form input {
            width: 100%;
            padding: 10px;
            margin-bottom: 20px;
            border: none;
            border-radius: 5px;
            background-color: #333;
            color: white;
        }

        .contact-form button {
            width: 100%;
            padding: 10px;
            background-color: #ff0000;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 18px;
        }

        .contact-info p {
            font-size: 18px;
            margin-bottom: 10px;
        }

        .contact-info .highlight {
            color: #ff0000;
        }

        footer {
            background-color: red;
            text-align: center;
            padding: 10px 0;
            width: 100%;
            position: static;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">ROOPTECH</div>
            <ul class="nav-links">
                <li><a href="home.html">HOME</a></li>
                <li><a href="products.html">PRODUCTS</a></li>
                <li><a href="people.html">PEOPLE</a></li>
                <li><a href="contact.html" class="active">CONTACT</a></li>
            </ul>
            <div class="search-bar">
                <input type="text" placeholder="Enter to Search">
                <button>Search</button>
            </div>
        </nav>
    </header>

    <main>
        <section class="contact">
            <h1>Contact Us</h1>
            <div class="contact-container">
                <div class="contact-form">
                    <h2>Contact Us</h2>
                    <input type="text" placeholder="Your Name">
                    <input type="email" placeholder="Your Email">
                    <button>Submit</button>
                </div>
                <div class="contact-info">
                    <h2>Contact Information</h2>
                    <p><span class="highlight">Address :</span> 3RD Floor, Tower 12, FCA Building No.18, ROOP DEVELOP CITY Phase-I SECUNDERABAD HR IN 1888546</p>
                    <p><span class="highlight">Email :</span> nithish.official@gmail.com</p>
                    <p><span class="highlight">Phone :</span> 1234567890</p>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <p>DESIGNED AND DEVELOPED BY NITHISH KUMAR P (212221040115))</p>
    </footer>
</body>
</html>

```


OUTPUT

![alt text](<Screenshot (185).png>)
![alt text](<Screenshot (187).png>)
![alt text](<Screenshot (188).png>)
![alt text](<Screenshot (186).png>)



