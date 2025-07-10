'''# 📘 Usage Guide: Loan EMI Calculator

This guide provides step-by-step instructions on how to use, embed, and interact with the Loan EMI Calculator.

---

## 📅 Getting Started

1. Clone or download this repository.
2. Open loan.html in any modern web browser.

You can also host the file on your website or include it in any project via <iframe> or direct <div> embed (see Embed Options below).

---

## 📌 What It Does

This calculator allows you to:

* ✅ Calculate Monthly EMI
* ✅ View Yearly Payment Estimate
* ✅ See Total Interest and Payment Over Time
* ✅ Download an Amortization Schedule as .csv
* ✅ View Pie Chart (Principal vs. Interest)
* ✅ Keep History of Previous Calculations (stored locally)

---

## 🫮 How to Use the Calculator

1. Open the calculator (loan.html in browser).

2. Fill in the form:

   * Loan Amount (₹): Enter the total loan amount.
   * Annual Interest Rate (%): Enter the yearly interest rate.
   * Loan Tenure: Enter a number and choose either Years or Months.

3. Click Calculate.

4. View the results:

   * Monthly EMI
   * Yearly Payment
   * Total Interest
   * Total Payment
   * Pie chart breakdown

5. Click “📂 Download Amortization (.csv)” to save the payment schedule.

6. View past calculations under the History section (up to 5 recent).

7. Click Reset to clear inputs and results.

---

## 🧩 Embed Options

You can embed this calculator into any web page:

### Option 1: iframe Embed

Upload loan.html to your server and use:

html
<iframe
  src="path/to/loan.html"
  style="border: none; width: 100%; max-width: 420px; height: 800px;">
</iframe>


Adjust width and height as needed.

---

### Option 2: Inline Embed (as <div>)

To embed inline inside another HTML file:

* Copy the full content of <div id="emi-calculator-container">...</div> from loan.html.
* Paste into your desired HTML file.
* Make sure to also include Chart.js via CDN inside the <head>:

html
<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>


---

## 📊 Amortization Schedule

The “📂 Download Amortization (.csv)” button generates a schedule that includes:

* Month Number
* Principal Paid
* Interest Paid
* Remaining Balance

This CSV is browser-generated and does not require a server.

---

## 📈 Chart.js Pie Chart

The calculator visualizes the total repayment with a pie chart:

* Green = Principal
* Red = Interest

The chart updates dynamically after each calculation.

---

## 🧠 Local History

The calculator saves your last 5 calculations in the browser using localStorage.

To clear this, clear your browser’s local storage.

---

## 🔧 Troubleshooting

* Ensure JavaScript is enabled in your browser.
* Use a modern browser (Chrome, Firefox, Edge, Safari).
* The calculator is fully client-side and does not require a backend.
'''
