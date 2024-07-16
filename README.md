# DRIBBLE

## PROGRAM

### HTML
```c
index.html

<!DOCTYPE html>
<html>
<head>
<title>Dribbble</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <div class="container">
      <h1><a href="#">Dribbble</a></h1>
      <nav>
        <ul>
          <li><a href="#">Shots</a></li>
          <li><a href="#">Designers</a></li>
          <li><a href="#">Teams</a></li>
          <li><a href="#">Community</a></li>
          <li><a href="#">Jobs</a></li>
        </ul>
      </nav>
      <div class="auth">
        <a href="#">Sign up</a>
        <a href="#">Sign in</a>
        <form>
          <input type="text" placeholder="Search">
        </form>
      </div>
    </div>
  </header>
  <section class="hero">
    <div class="container">
      <h2>What are you working on? Dribbble is show and tell for designers.</h2>
      <a href="#" class="button">Learn more</a>
      <a href="#" class="button">Sign up</a>
    </div>
  </section>
  <section class="shots">
    <div class="container">
      <div class="controls">
        <button class="active">Popular</button>
        <button>Shots</button>
        <button>Now</button>
        <button>
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13V6a2 2 0 0 0-2-2H5a2 2 0 0 0-2 2v7"></path><path d="M13 18l6-6-6-6"></path></svg>
        </button>
      </div>
      <div class="grid">
        <div class="shot">
          <img src="img1.jpeg" alt="">
          <div class="shot-info">
            <a href="#" class="link">
              <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13V6a2 2 0 0 0-2-2H5a2 2 0 0 0-2 2v7"></path><path d="M13 18l6-6-6-6"></path></svg>
            </a>
            <div class="stats">
              <span class="views">4,044</span>
              <span class="likes">14</span>
              <span class="comments">290</span>
            </div>
            <a href="#">
              <img src="img2.jpeg" alt="">
              Famous
            </a>
          </div>
        </div>
        <div class="shot">
          <img src="img3.jpeg" alt="">
          <div class="shot-info">
            <a href="#" class="link">
              <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13V6a2 2 0 0 0-2-2H5a2 2 0 0 0-2 2v7"></path><path d="M13 18l6-6-6-6"></path></svg>
            </a>
            <div class="stats">
              <span class="views">2,404</span>
              <span class="likes">13</span>
              <span class="comments">236</span>
            </div>
            <a href="#">
              <img src="img4.jpeg" alt="">
              Balkan Brothers
            </a>
          </div>
        </div>
        <div class="shot">
          <img src="img5.jpeg" alt="">
          <div class="shot-info">
            <a href="#" class="link">
              <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13V6a2 2 0 0 0-2-2H5a2 2 0 0 0-2 2v7"></path><path d="M13 18l6-6-6-6"></path></svg>
            </a>
            <div class="stats">
              <span class="views">3,985</span>
              <span class="likes">17</span>
              <span class="comments">264</span>
            </div>
            <a href="#">
              <img src="img6.jpeg" alt="">
              Jan Losert
            </a>
          </div>
        </div>
        <div class="shot">
          <img src="img7.jpeg" alt="">
          <div class="shot-info">
            <a href="#" class="link">
              <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13V6a2 2 0 0 0-2-2H5a2 2 0 0 0-2 2v7"></path><path d="M13 18l6-6-6-6"></path></svg>
            </a>
            <div class="stats">
              <span class="views">2,602</span>
              <span class="likes">23</span>
              <span class="comments">186</span>
            </div>
            <a href="#">
              <img src="img8.jpeg" alt="">
              Mattias Johansson
            </a>
          </div>
        </div>
  </section>
  <footer>
    <div class="container">
      <p>&copy; 2023 Dribbble</p>
    </div>
  </footer>
</body>
</html>
```
### css
```c
style.css

body {
    font-family: sans-serif;
    margin: 0;
    background-color: #f2f2f2;
  }
  
  .container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
  }
  
  header {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
  }
  
  header h1 {
    margin: 0;
    float: left;
  }
  
  header h1 a {
    color: #fff;
    text-decoration: none;
  }
  
  header nav {
    float: left;
    margin-left: 50px;
  }
  
  header nav ul {
    margin: 0;
    padding: 0;
    list-style: none;
  }
  
  header nav li {
    display: inline-block;
    margin-right: 20px;
  }
  
  header nav a {
    color: #fff;
    text-decoration: none;
  }
  
  .auth {
    float: right;
  }
  
  .auth a {
    color: #fff;
    text-decoration: none;
    margin-right: 20px;
  }
  
  .auth form {
    display: inline-block;
  }
  
  .auth input {
    background-color: transparent;
    border: 1px solid #fff;
    color: #fff;
    padding: 10px;
    border-radius: 5px;
  }
  
  .hero {
    background-color: #fff;
    padding: 80px 0;
    text-align: center;
  }
  
  .hero h2 {
    margin-bottom: 20px;
  }
  
  .hero .button {
    background-color: #007bff;
    color: #fff;
    border: none;
    padding: 15px 30px;
    border-radius: 5px;
    text-decoration: none;
    display: inline-block;
    margin: 0 10px;
  }
  
  .shots {
    background-color: #fff;
    padding: 40px 0;
  }
  
  .controls {
    text-align: center;
    margin-bottom: 20px;
  }
  
  .controls button {
    background-color: #fff;
    border: 1px solid #ddd;
    color: #333;
    padding: 10px 20px;
    border-radius: 5px;
    margin: 0 10px;
    cursor: pointer;
  }
  
  .controls button.active {
    background-color: #007bff;
    color: #fff;
    border: none;
  }
  
  .grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
  }
  
  .shot {
    border: 1px solid #ddd;
    border-radius: 5px;
    overflow: hidden;
  }
  
  .shot img {
    width: 100%;
    height: 200px;
    object-fit: cover;
  }
  
  .shot-info {
    padding: 15px;
  }
  
  .shot-info a {
    color: #333;
    text-decoration: none;
  }
  
  .shot-info .link {
    float: right;
    margin-bottom: 10px;
  }
  
  .shot-info .stats {
    margin-bottom: 10px;
  }
  
  .shot-info .stats span {
    display: inline-block;
    margin-right: 10px;
  }
  
  footer {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
  }
  
  footer p {
    margin: 0;
  }
  ```

## OUTPUT:
![Screenshot (19)](https://github.com/user-attachments/assets/307fe382-531c-4f80-89ea-d7573bad8bc0)


