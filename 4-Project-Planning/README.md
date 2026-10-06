* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
}

body {
    background: #f2f7f5;
    color: #222;
}

header {
    background: #176b5b;
    color: white;
    text-align: center;
    padding: 30px;
}

header h1 {
    font-size: 32px;
}

header p {
    margin-top: 8px;
}

nav {
    background: #0e5145;
    text-align: center;
    padding: 15px;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
    font-weight: bold;
}

.hero {
    text-align: center;
    padding: 70px 20px;
}

.hero h2 {
    font-size: 32px;
    color: #176b5b;
    margin-bottom: 15px;
}

.hero p {
    max-width: 600px;
    margin: auto;
    line-height: 1.6;
}

.button,
button {
    display: inline-block;
    margin-top: 25px;
    padding: 13px 25px;
    background: #176b5b;
    color: white;
    border: none;
    border-radius: 8px;
    text-decoration: none;
    cursor: pointer;
}

.cards {
    display: flex;
    justify-content: center;
    gap: 20px;
    padding: 30px;
    flex-wrap: wrap;
}

.card {
    background: white;
    width: 280px;
    padding: 25px;
    text-align: center;
    border-radius: 15px;
    box-shadow: 0 3px 12px rgba(0,0,0,0.1);
}

.card h3 {
    color: #176b5b;
    margin-bottom: 10px;
}

.container {
    max-width: 600px;
    margin: 40px auto;
    padding: 20px;
}

.calculator {
    background: white;
    padding: 30px;
    border-radius: 15px;
    box-shadow: 0 3px 15px rgba(0,0,0,0.1);
}

.calculator h2 {
    color: #176b5b;
    margin-bottom: 20px;
}

label {
    display: block;
    margin-top: 15px;
    font-weight: bold;
}

input {
    width: 100%;
    padding: 12px;
    margin-top: 7px;
    border: 1px solid #ccc;
    border-radius: 7px;
}

button {
    width: 100%;
    font-size: 16px;
}

.result {
    margin-top: 25px;
    padding: 20px;
    background: #e8f5f1;
    border-radius: 10px;
}

.result p {
    margin: 12px 0;
}

.recommendation {
    margin-top: 25px;
    padding: 20px;
    background: #fff4d2;
    border-radius: 10px;
    line-height: 1.6;
}

footer {
    text-align: center;
    background: #176b5b;
    color: white;
    padding: 20px;
    margin-top: 30px;
}

@media (max-width: 600px) {
    .hero h2 {
        font-size: 25px;
    }

    nav a {
        margin: 0 6px;
    }
}
