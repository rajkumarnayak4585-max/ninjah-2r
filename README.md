```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Ninja H2R | Raj Kumar Nayak</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background: #080b09;
    color: white;
}

header {
    background: #101510;
    padding: 22px;
    text-align: center;
    border-bottom: 3px solid #8cff00;
}

header h1 {
    color: #8cff00;
    font-size: 32px;
}

header p {
    margin-top: 8px;
}

nav {
    text-align: center;
    padding: 16px;
    background: #191f19;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 12px;
    font-weight: bold;
}

nav a:hover {
    color: #8cff00;
}

.hero {
    text-align: center;
    padding: 65px 20px;
    background: linear-gradient(135deg, #111811, #263526);
}

.hero h2 {
    font-size: 42px;
    color: #8cff00;
    margin-bottom: 18px;
}

.hero p {
    margin: 12px 0;
    line-height: 1.7;
}

.bike-image {
    display: block;
    width: 100%;
    max-width: 750px;
    height: auto;
    margin: 25px auto;
    border-radius: 14px;
    border: 2px solid #8cff00;
}

button {
    background: #8cff00;
    color: #080b09;
    padding: 13px 22px;
    border: none;
    border-radius: 5px;
    font-weight: bold;
    cursor: pointer;
    margin-top: 15px;
}

button:hover {
    background: white;
}

section {
    padding: 40px 20px;
}

section h2 {
    text-align: center;
    color: #8cff00;
    margin-bottom: 25px;
}

.specs {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
    gap: 18px;
    max-width: 950px;
    margin: auto;
}

.card {
    background: #171d17;
    padding: 25px;
    border: 1px solid #405040;
    border-radius: 10px;
    text-align: center;
}

.card h3 {
    color: #8cff00;
    margin-bottom: 12px;
}

.about {
    max-width: 800px;
    margin: auto;
    text-align: center;
    line-height: 1.9;
}

footer {
    background: #111811;
    border-top: 2px solid #8cff00;
    text-align: center;
    padding: 25px;
    line-height: 1.8;
}

@media (max-width: 500px) {
    .hero h2 {
        font-size: 30px;
    }

    header h1 {
        font-size: 25px;
    }

    nav a {
        display: inline-block;
        margin: 8px;
    }
}
</style>
</head>

<body>

<header>
    <h1>🏍️ NINJA H2R</h1>
    <p>Created by Raj Kumar Nayak | Class 9th</p>
    <p>Sandipani School</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#specifications">Specifications</a>
