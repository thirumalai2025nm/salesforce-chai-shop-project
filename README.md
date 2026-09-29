<!DOCTYPE html>
<html>
<head>
    <title>Chai Shop CRM</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <header>
        <h1>THE CHAI SHOP & CO</h1>
        <p>Customer Relationship Management System</p>
    </header>

    <nav>
        <a href="#">Dashboard</a>
        <a href="#">Customers</a>
        <a href="#">Orders</a>
        <a href="#">Reports</a>
    </nav>

    <div class="container">

        <h2>Customer Management</h2>

        <div class="form-box">
            <input type="text" id="name" placeholder="Customer Name">
            <input type="text" id="phone" placeholder="Phone Number">
            <input type="email" id="email" placeholder="Email">
            <input type="text" id="favorite" placeholder="Favorite Chai">
            <button onclick="addCustomer()">Add Customer</button>
        </div>

        <input
            type="text"
            id="search"
            placeholder="Search Customer..."
            onkeyup="searchCustomer()"
        >

        <table>
            <thead>
                <tr>
                    <th>ID</th>
                    <th>Name</th>
                    <th>Phone</th>
                    <th>Email</th>
                    <th>Favorite Chai</th>
                </tr>
            </thead>

            <tbody id="customerTable">
                <tr>
                    <td>1</td>
                    <td>Thirumalai</td>
                    <td>9876543210</td>
                    <td>thiru@gmail.com</td>
                    <td>Masala Chai</td>
                </tr>
            </tbody>
        </table>

    </div>

    <footer>
        <p>© 2026 The Chai Shop & Co</p>
    </footer>

    <script src="script.js"></script>

</body>
</html>
