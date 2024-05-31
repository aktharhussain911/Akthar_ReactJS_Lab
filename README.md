# Akthar_ReactJS_Lab

<h1>This is react-based-application for expense-tracker created from 'create-react-app'.</h1>

There are many components in it ->
<h3>Learning Objectives - ShowList Component --></h3>
<b>The ShowList component manages the display of expense details in an Expense Tracker application. It utilizes React features to fetch, calculate, and present expense data.</b>
<br>
<br>
<b>Key Features:</b>
<ol>
  <li>Data Handling: Uses useEffect to fetch and manage expense data,Tracks total sum and individual expenditures.</li>
  <li>User Interaction: Displays expenses dynamically,Allows users to add new expenses with the ExpenseTracker form.</li>
  <li>Callback Functions: Implements callbacks for successful form submission and closing.</li>
  <li>Layout and Styling: Utilizes CSS for an organized and visually appealing display.</li>
  <li>Error Handling: Shows error message if there's an issue fetching data.</li>
  <li>Financial Insights: Calculates payable amounts based on individual expenditures.</li>
</ol>
<b>Usages --> Integrated into the main application, ShowList provides a user-friendly interface for expense visualization, addition, and financial insights.</b>
<br>
<br>
<h3>Learning Objective - ExpenseTracker Component --></h3>
<b>The ExpenseTracker component enables users to add new expenses in an Expense Tracker application. It employs React state, event handling, and server communication for a streamlined form entry experience.</b>
<br>
<br>
<b>Key Features:</b>
<ol>
  <li>State Management: Uses React state for dynamic handling of user input data (payee name, product, price, date).</li>
  <li>Event Handling: Implements event handlers (setPayee, setProduct, setPrice, loggedDate) for real-time state updates.</li>
  <li>Form Submission: Defines submitHandler for form submission, creating and sending a data object to the server using pushDataToServer.</li>
  <li>Default Date Calculation: Generates a default date during component initialization using setDefaultDate.</li>
  <li>Visual Elements: Presents an organized layout with headers, input fields, and clear form instructions.</li>
</ol>
<b>Usage: Integrated into the main application, ExpenseTracker enhances the user experience by providing a user-friendly form for adding and submitting new expenses.</b>
<br>
<br>
<h3>Learning Objectives - Menu.ts HTTP Requests with Axios</h3>
<b>Learn to perform HTTP requests in a React application using the Axios library for fetching and pushing data to a server.</b>
<br>
<br>
<b>Key Features:</b>
<ol>
  <li>Axios Integration:Import and use the Axios library for making HTTP requests in a React application.</li>
  <li>GET Request: Implement a function (getDataFromServer) to make a GET request to the server's 'items' endpoint, fetching and returning data.</li>
  <li>POST Request:Develop a function (pushDataToServer) to make a POST request, pushing new expense data to the server's 'items' endpoint.</li>
  <li>Data Structure:Utilize the IDataList interface for defining the structure of the data exchanged between the client and server.</li>
  <li>Headers Configuration: Understand how to configure headers, specifically setting "Content-Type" to "application/json" for POST requests.</li>
</ol>
<b>Usage: Apply the learned concepts to fetch existing data from a server and push new expense data to facilitate interaction between a React application and a server.</b>
<br>
