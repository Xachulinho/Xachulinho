body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0;
    padding: 0;
    background: #f9f9f9;
    color: #333;
    line-height: 1.6;
}

header {
    background: linear-gradient(to right, #4e54c8, #8f94fb);
    color: #fff;
    padding: 2.5rem 0;
    text-align: center;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

header h1 {
    margin: 0;
    font-size: 3.5rem;
    text-transform: uppercase;
}

header p {
    margin: 0.5rem 0 0;
    font-size: 1.5rem;
    font-style: italic;
}

nav {
    background: #333;
    padding: 0.5rem 0;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: center;
}

nav ul li {
    margin: 0 1.5rem;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 1.2rem;
    font-weight: bold;
    transition: color 0.3s;
}

nav ul li a:hover {
    color: #a8d0e6;
}

.container {
    width: 90%;
    max-width: 1200px;
    margin: 2rem auto;
}

.blog-post {
    border: 1px solid #ddd;
    margin: 2rem 0;
    padding: 2rem;
    border-radius: 10px;
    background: #fff;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.blog-post h2 {
    color: #4e54c8;
    font-size: 2rem;
    margin-bottom: 1rem;
}

.blog-post p {
    font-size: 1.2rem;
    color: #555;
}

.blog-post a {
    display: inline-block;
    margin-top: 1rem;
    color: #4e54c8;
    text-decoration: none;
    font-weight: bold;
    transition: text-decoration 0.3s;
}

.blog-post a:hover {
    text-decoration: underline;
}

.subscribe {
    text-align: center;
    margin: 3rem 0;
    background: #fff;
    padding: 2rem;
    border-radius: 10px;
    box-shadow: 0 3px 6px rgba(0, 0, 0, 0.1);
}

.subscribe h3 {
    margin-bottom: 1.5rem;
    font-size: 1.8rem;
    color: #4e54c8;
}

.subscribe input[type="email"] {
    padding: 0.8rem;
    width: 320px;
    max-width: 100%;
    border: 1px solid #ddd;
    border-radius: 5px;
    margin-right: 0.5rem;
}

.subscribe button {
    padding: 0.8rem 1.8rem;
    background: #4e54c8;
    color: #fff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 1rem;
    transition: background 0.3s;
}

.subscribe button:hover {
    background: #8f94fb;
}

footer {
    background: #222;
    color: #fff;
    text-align: center;
    padding: 2rem 0;
    margin-top: 3rem;
    font-size: 1rem;
}

footer p {
    margin: 0;
}
