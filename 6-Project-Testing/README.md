function calculateBudget() {

    let income = Number(document.getElementById("income").value);

    let food = Number(document.getElementById("food").value);

    let transport =
        Number(document.getElementById("transport").value);

    let shopping =
        Number(document.getElementById("shopping").value);

    let entertainment =
        Number(document.getElementById("entertainment").value);

    if (income <= 0) {
        alert("Please enter your monthly income.");
        return;
    }

    let totalExpenses =
        food + transport + shopping + entertainment;

    let remaining =
        income - totalExpenses;

    let savings =
        income * 0.20;

    document.getElementById("total").innerText =
        "₹" + totalExpenses.toFixed(2);

    document.getElementById("remaining").innerText =
        "₹" + remaining.toFixed(2);

    document.getElementById("savings").innerText =
        "₹" + savings.toFixed(2);
}
