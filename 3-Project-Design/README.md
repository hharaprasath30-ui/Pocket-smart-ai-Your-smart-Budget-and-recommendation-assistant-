<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Recommendations - PocketSmart AI</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<header>
    <h1>🤖 PocketSmart AI</h1>
    <p>Smart Financial Recommendations</p>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="budget.html">Budget</a>
    <a href="recommendations.html">Recommendations</a>
</nav>

<div class="container">

    <div class="calculator">

        <h2>Get Your Recommendation</h2>

        <label>Monthly Income ₹</label>
        <input type="number" id="recIncome">

        <label>Monthly Expenses ₹</label>
        <input type="number" id="recExpenses">

        <button onclick="getRecommendation()">
            Get Smart Recommendation
        </button>

        <div id="recommendation" class="recommendation">
            💡 Enter your details to receive a recommendation.
        </div>

    </div>

</div>

<script src="recommendations.js"></script>

</body>
</html>
