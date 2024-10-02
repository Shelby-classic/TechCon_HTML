<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="TechCon 2024 - The Premier Technology Conference">
    <title>TechCon 2024 - Homepage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #333;
            color: white;
            padding: 15px;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav {
            margin-top: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        main {
            padding: 20px;
            background-color: #fff;
            margin: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        section {
            margin-bottom: 40px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        video {
            max-width: 100%;
            height: auto;
            margin-top: 15px;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>TechCon 2024</h1>
        <nav>
            <a href="about.html">About</a>
            <a href="schedule.html">Schedule</a>
            <a href="register.html">Register</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>

    <!-- Main Content Section -->
    <main>
        <section>
            <h2>Welcome to TechCon 2024</h2>
            <p>
                TechCon 2024 is the premier event for technology enthusiasts, professionals, and innovators. 
                Join us for insightful talks, workshops, and networking with industry leaders to explore 
                the future of technology.
            </p>

            <!-- Embedded Video -->
            <video controls>
                <source src="promo-video.mp4" type="video/mp4">
                <track src="promo-subtitles.vtt" kind="subtitles" srclang="en" label="English">
                Your browser does not support the video tag.
            </video>
        </section>
    </main>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 TechCon. All rights reserved.</p>
    </footer>

</body>
</html>
