function getRecommendation() {

    let income =
        Number(document.getElementById("recIncome").value);

    let expenses =
        Number(document.getElementById("recExpenses").value);

    let result =
        document.getElementById("recommendation");

    if (income <= 0 || expenses < 0) {

        result.innerText =
            "⚠️ Please enter valid income and expense values.";

        return;
    }

    let percentage =
        (expenses / income) * 100;

    if (expenses > income) {

        result.innerText =
            "⚠️ Your expenses are higher than your income. " +
            "Try reducing unnecessary spending and create a strict budget.";

    }

    else if (percentage > 80) {

        result.innerText =
            "💡 You are using more than 80% of your income. " +
            "Try reducing unnecessary expenses and increase your savings.";

    }

    else if (percentage > 50) {

        result.innerText =
            "📊 Your spending is moderate. " +
            "Try to save at least 20% of your income every month.";

    }

    else {

        result.innerText =
            "🎉 Great job! Your expenses are under control. " +
            "You can increase your savings or work towards your financial goals.";

    }
}
