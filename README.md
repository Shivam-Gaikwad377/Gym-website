<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Elite Gym & Fitness</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Header & Navigation -->
    <header>
        <h1> Elite Gym & Fitness </h1>
        <nav>
            <a href="#about">About</a>
            <a href="#programs">Programs</a>
            <a href="#pricing">Pricing</a>
            <a href="#admission">Admission</a>
            <a href="#testimonials">Testimonials</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="hero-text">
            <h2>Transform Your Body, Transform Your Life</h2>
            <p>Join the best fitness programs & achieve your goals</p>
            <a href="#admission" class="btn">Join Now</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="section">
        <h2>About Us</h2>
        <p>Elite Gym & Fitness is the premier fitness center focused on strength, endurance, and holistic well-being. With top-class trainers and cutting-edge facilities, we ensure you achieve your dream physique.</p>
    </section>

    <!-- Programs Section -->
    <section id="programs" class="section">
        <h2>Our Programs</h2>
        <div class="programs">
            <div class="program">
                <h3>Strength Training</h3>
                <p>🏋️ Build muscle & increase strength.</p>
                <p>⏰ Timings: Mon-Fri, 6 AM - 8 AM</p>
                <p>📍 Location: Gym Hall 1</p>
            </div>
            <div class="program">
                <h3>Cardio & Endurance</h3>
                <p>🔥 Boost stamina & burn fat.</p>
                <p>⏰ Timings: Mon-Fri, 9 AM - 11 AM</p>
                <p>📍 Location: Gym Hall 2</p>
            </div>
            <div class="program">
                <h3>Yoga & Meditation</h3>
                <p>🧘‍♂️ Improve flexibility & mental peace.</p>
                <p>⏰ Timings: Mon-Wed, 7 PM - 9 PM</p>
                <p>📍 Location: Yoga Room</p>
            </div>
            <div class="program">
                <h3>Weight Loss Program</h3>
                <p>⚖️ Personalized weight management.</p>
                <p>⏰ Timings: Mon-Fri, 5 PM - 7 PM</p>
                <p>📍 Location: Gym Hall 3</p>
            </div>
        </div>
    </section>

    <!-- Pricing Section -->
    <section id="pricing" class="section">
        <h2>Membership Pricing</h2>
        <div class="pricing">
            <div class="price-plan">
                <h3>Basic Plan</h3>
                <p>💰 ₹2,500/month</p>
                <p>✔ Access to gym & equipment.</p>
            </div>
            <div class="price-plan">
                <h3>Standard Plan</h3>
                <p>💰 ₹4,500/month</p>
                <p>✔ Includes gym + 1 specialized program.</p>
            </div>
            <div class="price-plan">
                <h3>Premium Plan</h3>
                <p>💰 ₹7,500/month</p>
                <p>✔ All programs + personal trainer.</p>
            </div>
        </div>
    </section>

    <!-- Admission Form -->
    <section id="admission" class="section">
        <h2>Join Our Gym</h2>
        <form class="admission-form">
            <label for="name">Full Name:</label>
            <input type="text" id="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" required>

            <label for="phone">Phone Number:</label>
            <input type="tel" id="phone" required>

            <label for="program">Select Program:</label>
            <select id="program">
                <option value="strength">Strength Training</option>
                <option value="cardio">Cardio & Endurance</option>
                <option value="yoga">Yoga & Meditation</option>
                <option value="weightloss">Weight Loss Program</option>
            </select>

            <button type="submit">Register Now</button>
        </form>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <p><b>📍 Address:</b> Fortune plaza,near railway crossing kale padal bypass road, <br>
            Vardhaman Township, Sasane Nagar, Hadapsar, <br>
            Pune, Maharashtra  411028, </p>
        <p><b>📞 Phone:</b> 9022282535</p>
        <p><b>📧 Email:</b> elitegym.321@gmail.com</p>
    </section>

</body>
</html>
