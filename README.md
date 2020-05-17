This is a simple loan interest calculator made with React.

## Features :-
- A user interface that allows a user to enter a loan amount and a
  loan duration in months which then displays the interest rate and the monthly payment.
- The user is able to enter the monetary amount and loan duration by using a slider.
- The calculated values is automatically updated as the slider is used - without requiring any
  further interaction by the user.
- The loan amount should be between 500 and 5000 \$ and the loan duration between 6
  and 24 months.
- The following API is used - `https://ftl-frontend-test.herokuapp.com/interest?amount=<amount>&numMonths=<numMonths>`<br/>
This returns a JSON object with information about the monthly payment and the interest
rates.

# Prerequisites
-Node.Js and npm must be installed
```
To Run:
>npm start
Go to `http://localhost:3000` to view the app.

Built With:
- [React.JS](https://reactjs.org/) -Frontend library used in the project.
- [Bootstrap](https://getbootstrap.com/) - Used for basic styling.
