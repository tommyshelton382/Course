<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Start & Scale Your Tree Service Business</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <style>
        /* General Styles */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f1f1f1; /* Light background */
            color: #333;
        }
        header {
            background-color: #000; /* Black banner */
            color: white;
            text-align: center;
            padding: 100px 20px;
        }
        header h1 {
            font-size: 3rem;
            margin: 0;
            letter-spacing: 1px;
        }
        header p {
            font-size: 1.2rem;
            margin: 10px 0;
        }
        nav {
            background-color: #333;
            text-align: center;
            padding: 10px 0;
        }
        nav a {
            color: white;
            margin: 0 15px;
            font-size: 1rem;
            text-decoration: none;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        h2, h3 {
            color: #2a7d2a;
        }
        .features ul {
            list-style-type: none;
            padding: 0;
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }
        .features li {
            background: url('https://via.placeholder.com/15/2a7d2a/2a7d2a') no-repeat left center;
            background-size: 15px 15px;
            padding-left: 25px;
            margin-bottom: 15px;
            font-size: 1.1rem;
            width: 45%;
        }
        .image-feature {
            display: flex;
            align-items: center;
            margin-bottom: 30px;
            flex-wrap: wrap;
        }
        .image-feature img {
            width: 100%;
            max-width: 600px;
            border-radius: 8px;
            margin-bottom: 15px;
        }
        .image-feature div {
            width: 100%;
        }
        .pricing {
            background-color: #e7f7e7;
            padding: 30px;
            text-align: center;
            margin-bottom: 30px;
            border-radius: 8px;
        }
        .pricing p {
            font-size: 1.2rem;
        }
        .pricing .price {
            font-size: 2rem;
            font-weight: bold;
            color: #2a7d2a;
        }
        .pricing .payment-button {
            padding: 10px 20px;
            color: white;
            background-color: #2a7d2a;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1rem;
            transition: background-color 0.3s ease;
        }
        .pricing .payment-button:hover {
            background-color: #236423;
        }
        footer {
            background-color: #2a7d2a;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 30px;
        }
        footer a {
            color: white;
            text-decoration: none;
        }
        footer a:hover {
            text-decoration: underline;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 4px;
            border: 1px solid #ddd;
        }
        .contact-form button {
            padding: 10px 20px;
            background-color: #2a7d2a;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        .contact-form button:hover {
            background-color: #236423;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            header {
                padding: 80px 10px;
            }
            header h1 {
                font-size: 2.2rem;
            }
            header p {
                font-size: 1rem;
            }
            nav a {
                margin: 0 10px;
                font-size: 0.9rem;
            }
            .features li {
                width: 100%; /* Full width on smaller screens */
                margin-bottom: 20px;
            }
            .image-feature {
                flex-direction: column;
            }
            .pricing .price {
                font-size: 1.8rem;
            }
        }
    </style>
</head>
<body>

<!-- Navigation Bar -->
<nav>
    <a href="index.html">Home</a>
    <a href="about.html">About Us</a>
    <a href="contact.html">Contact Us</a>
</nav>

<!-- Header Section -->
<header>
    <h1>Start & Scale Your Tree Service Business</h1>
    <p>Learn everything you need to know to launch and grow a profitable tree service business!</p>
</header>

<!-- Main Content Section -->
<div class="container">
    <h2>What You'll Learn</h2>
    <p>Turn your tree work skills into a thriving business with our step-by-step course. Here's what you'll gain:</p>
    <div class="features">
        <ul>
            <li>How to write a business plan and set up your legal structure</li>
            <li>Pricing your services for maximum profit</li>
            <li>Safety protocols and essential equipment</li>
            <li>Marketing strategies to grow your business</li>
            <li>Scaling your services to build a team</li>
        </ul>
    </div>

    <div class="image-feature">
        <img src="https://via.placeholder.com/600x400" alt="Tree Climbing">
        <div>
            <h3>Climbing Trees & Safety</h3>
            <p>Master the techniques for climbing trees safely and effectively, essential for starting your tree service business.</p>
        </div>
    </div>

    <div class="pricing">
        <h3>Course Pricing</h3>
        <p>Get lifetime access to all materials, templates, and updates:</p>
        <div class="price">$997 or 3 payments of $349</div>
        <button class="payment-button" onclick="window.location.href='https://www.paypal.com/paypalme/YourPayPalLinkHere'">
            Pay with PayPal
        </button>
        <button class="payment-button" onclick="window.location.href='https://buy.stripe.com/test_XXXXXXX'">
            Pay with Stripe
        </button>
    </div>
</div>

<footer>
    <p>&copy; 2024 Tree Service Masterclass. All rights reserved. <a href="#">Privacy Policy</a></p>
</footer>

</body>
</html>
