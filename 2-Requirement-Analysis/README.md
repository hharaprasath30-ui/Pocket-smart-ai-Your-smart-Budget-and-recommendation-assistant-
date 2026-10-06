<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Budget - PocketSmart AI</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<header>
    <h1>💰 PocketSmart AI</h1>
    <p>Budget Calculator</p>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="budget.html">Budget</a>
    <a href="recommendations.html">Recommendations</a>
</nav>

<div class="container">

    <div class="calculator">

        <h2>Monthly Budget</h2>

        <label>Monthly Income ₹</label>
        <input type="number" id="income" placeholder="Enter income">

        <label>Food ₹</label>
        <input type="number" id="food" placeholder="Food expenses">

        <label>Transport ₹</label>
        <input type="number" id="transport" placeholder="Transport expenses">

        <label>Shopping ₹</label>
        <input type="number" id="shopping" placeholder="Shopping expenses">

        <label>Entertainment ₹</label>
        <input type="number" id="entertainment" placeholder="Entertainment expenses">

        <button onclick="calculateBudget()">Calculate Budget</button>

        <div class="result">
            <h3>Budget Summary</h3>

            <p>Total Expenses:
                <strong id="total">₹0</strong>
            </p>

            <p>Remaining Balance:
                <strong id="remaining">₹0</strong>
            </p>

            <p>Suggested Savings:
                <strong id="savings">₹0</strong>
            </p>
        </div>

    </div>

</div>

<script src="script.js"></script>

</body>
</html>
