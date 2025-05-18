# Loan Payment Tracker

A simple web application to track loans and payments, allowing users to add payments towards loans and see updated balances and summaries in real-time.

## Features

- Display a list of loans with borrower names, original amounts, and outstanding balances.
- Add payments to each loan via a modal form.
- Validate payment amounts to ensure they are positive and do not exceed the outstanding balance.
- Update the loan’s outstanding balance and summary information dynamically after each payment.
- Responsive UI built with Bootstrap for easy use.

## Technologies Used

- HTML5, CSS3
- JavaScript (Vanilla)
- Bootstrap 5

## How to Use

1. Open `index.html` in a modern web browser.
2. View the list of loans and their current outstanding amounts.
3. Click the "Add Payment" button next to a loan to open the payment modal.
4. Enter a payment amount and submit the form.
5. The payment will be validated and, if valid, applied to the loan.
6. The loan list and summary section will update automatically to reflect the new payment.

## Project Structure

- `index.html` — The main HTML page containing the loan table, payment modal, and summary section.
- `styles.css` — Custom styles (if any).
- `script.js` — JavaScript code managing data, modal interactions, validations, and UI updates.

## Future Enhancements

- Persist loan and payment data using local storage or a backend database.
- Add user authentication.
- Enable editing and deleting of payments.
- Support multiple currencies and detailed loan schedules.
- Improve UI with more detailed reporting and charts.

## License

This project is open-source and available under the MIT License.

---

If you have any questions or want to contribute, feel free to open an issue or submit a pull request.

Thank you for using the Loan Payment Tracker!
