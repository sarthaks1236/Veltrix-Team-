# Veltrix-Team-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Team Veltrix</title>
    <meta name="description" content="Veltrix - Quality products and services with years of experience.">
    <meta property="og:title" content="Welcome to Team Veltrix">
    <meta property="og:description" content="Quality products and services with years of experience.">
    <meta property="og:image" content="path-to-image.jpg">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
            scroll-behavior: smooth;
        }
        body {
            background: #1a1a2e;
            color: #eaeaea;
            font-size: 18px;
            line-height: 1.6;
            transition: background 0.3s, color 0.3s;
        }
        body.dark-mode {
            background: #121212;
            color: #d4d4d4;
        }
        header {
            background: linear-gradient(45deg, #0072ff, #00c6ff);
            color: white;
            text-align: center;
            padding: 25px;
            font-size: 32px;
            font-weight: bold;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
        }
        .toggle-btn {
            position: fixed;
            top: 15px;
            right: 15px;
            background: #333;
            color: white;
            padding: 12px 20px;
            border: none;
            cursor: pointer;
            border-radius: 8px;
            transition: 0.3s;
            font-weight: bold;
        }
        .toggle-btn:hover {
            background: #0072ff;
        }
        .container {
            max-width: 1000px;
            margin: 50px auto;
            background: rgba(30, 30, 47, 0.95);
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0px 10px 30px rgba(0, 0, 0, 0.5);
            transition: background 0.3s;
        }
        body.dark-mode .container {
            background: rgba(18, 18, 18, 0.95);
            box-shadow: 0px 10px 30px rgba(255, 255, 255, 0.1);
        }
        .section {
            margin: 30px 0;
            padding: 20px;
            background: rgba(40, 40, 60, 0.9);
            border-radius: 12px;
            transition: 0.3s;
            text-align: center;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
        }
        body.dark-mode .section {
            background: rgba(25, 25, 25, 0.9);
        }
        .btn {
            display: inline-block;
            padding: 15px 30px;
            background: linear-gradient(45deg, #0072ff, #00c6ff);
            color: white;
            font-size: 18px;
            text-decoration: none;
            border-radius: 30px;
            transition: 0.3s;
            margin-top: 15px;
            font-weight: bold;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
        }
        .btn:hover {
            transform: scale(1.1);
            background: linear-gradient(45deg, #00c6ff, #0072ff);
        }
        form {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 20px;
            padding: 25px;
        }
        input, textarea {
            width: 95%;
            padding: 15px;
            border-radius: 12px;
            border: 1px solid #444;
            background: #2a2a3f;
            color: #eaeaea;
            font-size: 16px;
            transition: 0.3s;
        }
        input:focus, textarea:focus {
            border-color: #0072ff;
            box-shadow: 0 0 10px rgba(0, 114, 255, 0.5);
        }
        button {
            background: linear-gradient(45deg, #0072ff, #00c6ff);
            color: white;
            padding: 15px 30px;
            border: none;
            cursor: pointer;
            border-radius: 30px;
            font-weight: bold;
            font-size: 18px;
            transition: 0.3s;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
        }
        button:hover {
            transform: scale(1.1);
            background: linear-gradient(45deg, #00c6ff, #0072ff);
        }
        footer {
            margin-top: 40px;
            padding: 20px;
            background: linear-gradient(45deg, #0072ff, #00c6ff);
            color: white;
            text-align: center;
            font-size: 18px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
        }
        .review-box {
            background: rgba(40, 40, 60, 0.9);
            padding: 25px;
            margin: 20px 0;
            border-radius: 12px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
            transition: 0.3s;
            text-align: center;
            position: relative;
        }
        body.dark-mode .review-box {
            background: rgba(25, 25, 25, 0.9);
        }
        .review-box p {
            font-size: 18px;
            color: #eaeaea;
            margin-bottom: 15px;
            line-height: 1.8;
        }
        .review-box h4 {
            font-size: 16px;
            color: #0072ff;
            font-weight: bold;
            margin-top: 15px;
        }
        .review-box .rating {
            margin-top: 15px;
            font-size: 20px;
            color: #ffd700; /* Gold color for stars */
        }
        .review-box:hover {
            transform: scale(1.03);
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.5);
        }
    </style>
</head>
<body>

<header>Welcome to Team Veltrix</header>
<button class="toggle-btn" onclick="toggleDarkMode()" aria-label="Toggle Dark Mode">Dark Mode</button>

<div class="container">
    <h2>Who We Are</h2>
    <p>Veltrix has been providing top-quality products and professional services to thousands of happy customers.</p>
    <p>Our mission is simple: <b>quality, affordability, and convenience.</b> Whether you're looking for reliable products or premium services, we've got you covered. We believe in building long-term relationships with our customers by consistently exceeding their expectations.</p>

    <div class="section">
        <h2>Why Choose Us?</h2>
        <p>✅ <b>Extensive industry experience:</b> Our experience ensures that we understand your needs and deliver the best solutions.</p>
        <p>✅ <b>100% customer satisfaction guarantee:</b> We are committed to providing exceptional service and products that leave our customers delighted.</p>
        <p>✅ <b>High-quality products & reliable services:</b> We source only the best materials and employ skilled professionals to ensure top-notch quality.</p>
        <p>✅ <b>Affordable pricing & doorstep convenience:</b> Enjoy premium services and products at competitive prices, delivered right to your doorstep.</p>
    </div>

    <div class="section">
        <h2>🛍️ Veltrix Sells – Quality Products</h2>
        <p>We offer a wide range of <b>premium products</b> designed to meet your needs. From everyday essentials to luxury items, our catalog is curated to provide the best value for your money. Our products are rigorously tested for quality and durability, ensuring you get nothing but the best.</p>
        <p>Whether you're shopping for your home, office, or personal use, Veltrix Sells is your one-stop destination for reliable and affordable products.</p>
        <a href="#" class="btn">Shop Now</a>
    </div>

    <div class="section">
        <h2>🚗 Veltrix Cleans – Portable Car Cleaning</h2>
        <p>No time to visit a car wash? No problem! <b>Veltrix Cleans</b> brings professional car cleaning right to your doorstep. Our eco-friendly cleaning solutions and expert team ensure your car looks brand new without harming the environment.</p>
        <p>We specialize in interior and exterior cleaning, polishing, and detailing services. Experience hassle-free, high-quality car cleaning that saves you time and effort.</p>
        <a href="#" class="btn">Book a Service</a>
    </div>

    <div class="section">
        <h2>📢 Veltrix Promotes – Boost Your Brand</h2>
        <p>Looking to grow your business and reach a wider audience? <b>Veltrix Promotes</b> is here to help! We specialize in digital marketing, social media campaigns, and brand promotions tailored to your needs.</p>
        <p>Our team of experts will work with you to create impactful strategies that drive results and help your brand stand out in a competitive market.</p>
        <p style="font-size: 20px; font-weight: bold; color: #0072ff; margin-top: 20px;">Coming Soon</p>
    </div>

    <div class="section">
        <h2>⭐ What Our Customers Say</h2>
        <div class="review-box">
            <p>"Veltrix Sells always delivers quality products at great prices! Their customer service is exceptional, and I always receive my orders on time. Highly recommended!"</p>
            <h4>– Ayesha K.</h4>
            <div class="rating">⭐⭐⭐⭐⭐</div>
        </div>
        <div class="review-box">
            <p>"Veltrix Cleans is a game-changer! My car looks brand new every time. The team is professional, and the doorstep service is so convenient. I can't imagine going back to a regular car wash."</p>
            <h4>– Rahul M.</h4>
            <div class="rating">⭐⭐⭐⭐⭐</div>
        </div>
        <div class="review-box">
            <p>"Amazing service and top-notch products. Veltrix never disappoints! Their attention to detail and commitment to quality are unmatched. I’ve been a loyal customer for years."</p>
            <h4>– Priya S.</h4>
            <div class="rating">⭐⭐⭐⭐</div>
        </div>
    </div>

    <h2>📞 Contact Us</h2>
    <form action="https://formspree.io/f/your-form-id" method="POST">
        <input type="text" name="name" placeholder="Your Name" required aria-label="Your Name">
        <input type="email" name="email" placeholder="Your Email" required aria-label="Your Email">
        <textarea name="message" rows="4" placeholder="Your Message" required aria-label="Your Message"></textarea>
        <button type="submit">Send Message</button>
    </form>
</div>

<footer>Thank you for being a part of Team Veltrix!</footer>

<script>
    function toggleDarkMode() {
        const body = document.body;
        const button = document.querySelector('.toggle-btn');
        body.classList.toggle("dark-mode");
        const isDarkMode = body.classList.contains("dark-mode");
        localStorage.setItem("darkMode", isDarkMode ? "enabled" : "disabled");
        button.textContent = isDarkMode ? "Light Mode" : "Dark Mode";
    }
    window.onload = function () {
        if (localStorage.getItem("darkMode") === "enabled") {
            document.body.classList.add("dark-mode");
            document.querySelector('.toggle-btn').textContent = "Light Mode";
        }
    };
</script>

</body>
</html>
