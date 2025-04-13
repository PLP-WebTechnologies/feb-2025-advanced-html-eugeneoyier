<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML5 Example Page</title>
    <link rel="stylesheet" href="styles.css"> <!-- External CSS file link -->
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Welcome to My Example Page</h1>
    </header>

    <!-- Ordered List with Roman Numerals -->
    <section>
        <h2>Important Steps</h2>
        <ol type="I">
            <li>Learn HTML5 Basics</li>
            <li>Explore CSS and Styling</li>
            <li>Start JavaScript for Interactivity</li>
            <li>Build Projects and Practice</li>
        </ol>
    </section>

    <!-- External Image -->
    <section>
        <h2>Beautiful Landscape</h2>
        <img src="https://images.pexels.com/photos/1461744/pexels-photo-1461744.jpeg" alt="Beautiful landscape" width="600">
    </section>

    <!-- Table of Contacts -->
    <section>
        <h2>Contact Information</h2>
        <table border="1">
            <thead>
                <tr>
                    <th>Name</th>
                    <th>Address</th>
                    <th>Mobile</th>
                    <th>Email</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>John Doe</td>
                    <td>123 Main St</td>
                    <td>(555) 123-4567</td>
                    <td>john.doe@example.com</td>
                </tr>
                <tr>
                    <td>Jane Smith</td>
                    <td>456 Oak Ave</td>
                    <td>(555) 234-5678</td>
                    <td>jane.smith@example.com</td>
                </tr>
                <tr>
                    <td>Emily Davis</td>
                    <td>789 Pine Rd</td>
                    <td>(555) 345-6789</td>
                    <td>emily.davis@example.com</td>
                </tr>
                <tr>
                    <td>Michael Brown</td>
                    <td>101 Maple Ln</td>
                    <td>(555) 456-7890</td>
                    <td>michael.brown@example.com</td>
                </tr>
                <tr>
                    <td>Alice Green</td>
                    <td>202 Birch Blvd</td>
                    <td>(555) 567-8901</td>
                    <td>alice.green@example.com</td>
                </tr>
            </tbody>
        </table>
    </section>

    <!-- Registration Form -->
    <section>
        <h2>Registration Form</h2>
        <form action="/submit" method="POST">

            <!-- Name Field -->
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required>
            <br>

            <!-- Email Field -->
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>
            <br>

            <!-- Password Field -->
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter your password" required>
            <br>

            <!-- Date of Birth Field -->
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required>
            <br>

            <!-- Dropdown Field -->
            <label for="country">Country:</label>
            <select id="country" name="country" required>
                <option value="us">United States</option>
                <option value="ca">Canada</option>
                <option value="uk">United Kingdom</option>
                <option value="aus">Australia</option>
            </select>
            <br>

            <!-- Radio Button Field -->
            <label>Gender:</label>
            <input type="radio" id="male" name="gender" value="male">
            <label for="male">Male</label>
            <input type="radio" id="female" name="gender" value="female">
            <label for="female">Female</label>
            <input type="radio" id="other" name="gender" value="other">
            <label for="other">Other</label>
            <br>

            <!-- Checkbox Field -->
            <label for="newsletter">Subscribe to Newsletter:</label>
            <input type="checkbox" id="newsletter" name="newsletter">
            <br>

            <!-- Submit Button -->
            <button type="submit">Register</button>
        </form>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>© 2025 My Startup</p>
    </footer>

</body>
</html>
