 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Helping One Person at a Time</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f8f9fa;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #ffcc80;
            padding: 20px;
            text-align: center;
            font-size: 24px;
            font-weight: bold;
        }
        nav {
            text-align: center;
            padding: 10px;
            background-color: #ffb74d;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }
        .container {
            padding: 20px;
            text-align: center;
        }
        footer {
            background-color: #ffcc80;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        form {
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            max-width: 400px;
            margin: 0 auto;
        }
        input, textarea, select {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            background-color: #ffb74d;
            color: #333;
            padding: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #ffa726;
        }
    </style>
</head>
<body>
    <header>Helping One Person at a Time</header>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#resources">Resources</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container" id="home">
        <h2>Welcome to Our Community</h2>
        <p>Providing support, health resources, and community connections.</p>
    </div>
    <div class="container" id="about">
        <h2>About Us</h2>
        <p>We are dedicated to bringing vital health and community resources to those in need.</p>
    </div>
    <div class="container" id="resources">
        <h2>Resources</h2>
        <p>Explore a variety of health and community support services available to you.</p>
        <ul>
            <li>Access to Home Health Services</li>
            <li>Transportation to Medical Appointments</li>
            <li>Recommendations for Primary Care Providers and Pain Management</li>
            <li>Help Receiving Medical Equipment and Devices</li>
        </ul>
        <label for="services">What services are most important to you?</label>
        <select id="services" name="services">
            <option value="home_health">Access to Home Health Services</option>
            <option value="transportation">Transportation to Medical Appointments</option>
            <option value="primary_care">Recommendations for Primary Care Providers and Pain Management</option>
            <option value="medical_equipment">Help Receiving Medical Equipment and Devices</option>
        </select>
    </div>
    <div class="container" id="contact">
        <h2>Contact Us</h2>
        <p><strong>Email:</strong> Advocacyforthepeople@gmail.com</p>
        <p><strong>Phone:</strong> 702-706-2901</p>
        <p>Our intake coordinators are available 24/7 to assist with your needs. Reach out today!</p>
    </div>
    <div class="container" id="personal-info">
        <h2>Enter Your Information</h2>
        <form>
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required>
            
            <label for="phone">Phone Number:</label>
            <input type="text" id="phone" name="phone" required>
            
            <label for="address">Address:</label>
            <input type="text" id="address" name="address" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="4" required></textarea>
            
            <button type="submit">Submit</button>
        </form>
    </div>
    <footer>
        &copy; 2025 Helping One Person at a Time
    </footer>
</body>
</html>
