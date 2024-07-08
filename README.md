# Calculator
This is a simple web-based calculator designed using HTML, CSS, and JavaScript. It allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division. It also allows the user to switch from day mode to night mode.

The calculator application in app.py leverages Flask to provide a responsive and interactive user experience. When accessing the application at http://localhost:5000/, Flask renders index.html, where users can perform calculations using a straightforward interface. When the user inputs an expression and clicks "=", the client side JavaScript sends a POST request to /calculate, passing the expression. In app.py, the server-side logic uses Sympy to evaluate the expression safely and returns the result as JSON. 

<img width="930" alt="Screenshot 2024-07-08 at 19 08 04" src="https://github.com/fatima178/Calculator/assets/124153153/a74a36df-fa80-4884-8db8-fa03e7734467">

<img width="940" alt="Screenshot 2024-07-08 at 19 08 23" src="https://github.com/fatima178/Calculator/assets/124153153/0e84d0aa-d773-4084-a1db-32b18c5018f6">
