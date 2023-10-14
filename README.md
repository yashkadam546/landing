<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Webinar Registration</title>
    <link rel="pagesheet" href="page.css"
</head>
<body>
    <header>
        <img src="your_logo.png" alt="Company Logo">
    </header>
    <main>
        <section class="hero">
            <h1>Unlock the Power of Webinar Topic</h1>
            <h2>Join Our Exclusive Webinar on Date and Time</h2>
            <img src="webinar_image.jpg" alt="Webinar Image">
        </section>
        <section class="registration-form">
            <h2>Register Now</h2>
            <form action="process_registration.php" method="post">
                <div class="input-group">
                    <input type="text" name="first_name" placeholder="First Name" required>
                    <input type="text" name="last_name" placeholder="Last Name" required>
                </div>
                <div class="input-group">
                    <input type="email" name="email" placeholder="Email" required>
                    <input type="text" name="company" placeholder="Company" required>
                </div>
                <input type="text" name="job_title" placeholder="Job Title" required>
                <input type="tel" name="phone" placeholder="Phone (Optional)">
                <button type="submit">Register Now</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2023 Your Company Name. All Rights Reserved.</p>
    </footer>
</body>
</html>
