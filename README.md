<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <div class="container">
        <h1>Hotel Management Console Application</h1>
        <p>This project is a console-based application designed for managing hotel operations efficiently using Java and JDBC. It provides an interface for both hotel managers and customers to interact with hotel-related functionalities.</p>
        <h2>Features</h2>
        <h3>Manager Features:</h3>
        <ul>
            <li><strong>Post details of available rooms:</strong> Allows managers to add new rooms with information such as room type, capacity, and pricing.</li>
            <li><strong>Update room information:</strong> Enables managers to update existing room details to keep information current, including availability status and pricing.</li>
            <li><strong>Manage booking and reservation statuses:</strong> Provides functionality to view and update booking and reservation statuses, such as marking rooms as booked, reserved, or available.</li>
        </ul>
        <h3>Customer Features:</h3>
        <ul>
            <li><strong>Browse available rooms:</strong> Customers can search and view available rooms based on criteria like dates and room type.</li>
            <li><strong>Book rooms online:</strong> Allows customers to book rooms directly through the application, specifying booking details and personal information.</li>
            <li><strong>View booking confirmations and reservation details:</strong> Customers can view booking confirmations and details of their reservations.</li>
        </ul>
        <h2>Getting Started</h2>
        <h3>Prerequisites</h3>
        <ul>
            <li>Java Development Kit (JDK) installed (version X.X or higher).</li>
            <li>MySQL or another JDBC-compatible database server installed and running.</li>
        </ul>
        <h3>Installation</h3>
        <pre><code>git clone https://github.com/your-username/hotel-management.git
cd hotel-management</code></pre>
        <p><strong>Set up your database:</strong></p>
        <ol>
            <li>Create a MySQL database named <code>hotel_management</code>.</li>
            <li>Import the provided SQL schema (<code>hotel_management.sql</code>) to set up the necessary tables.</li>
        </ol>
        <p><strong>Configure database connection:</strong></p>
        <pre><code>Open src/main/resources/db.properties.
Modify the url, user, and password properties to match your database configuration.</code></pre>
        <h2>Acknowledgments</h2>
        <ul>
            <li>Inspired by the need for efficient hotel management solutions.</li>
            <li>Built using Java and JDBC.</li>
        </ul>
    </div>
</body>
</html>
