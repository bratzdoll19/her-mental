<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Her Mental - Women's Mental Health & Confidence</title>
    <link rel="stylesheet" href="styles.css">
    <script src="https://cdn.jsdelivr.net/npm/fullcalendar@5.10.1/main.min.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/fullcalendar@5.10.1/main.min.css">
    <script>
        document.addEventListener('DOMContentLoaded', function() {
            var calendarEl = document.getElementById('calendar-container');
            if (calendarEl) {
                var calendar = new FullCalendar.Calendar(calendarEl, {
                    initialView: 'dayGridMonth'
                });
                calendar.render();
            }
        });
    </script>
    <style>
        body {
            background-image: url('marble-pink.jpg');
            background-size: cover;
            background-position: center;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .content-container {
            background-color: white;
            padding: 20px;
            margin: 20px auto;
            max-width: 800px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        header, footer {
            text-align: center;
            padding: 1rem;
            background: #ff69b4;
            color: white;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #ff1493;
            padding: 0.5rem;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <header>
        <h1 style="font-family: 'Cursive', cursive;">Her Mental</h1>
        <p>Supporting Women's Mental Health & Confidence</p>
    </header>
    
    <nav>
        <a href="index.html">Home</a>
        <a href="share.html">Anonymous Sharing</a>
        <a href="book-club.html">Book Club</a>
        <a href="calendar.html">Calendar</a>
        <a href="forums.html">Forums</a>
        <a href="tracker.html">Package Tracker</a>
        <a href="login.html">Login</a>
        <a href="contact.html">Contact</a>
    </nav>
    
    <div class="content-container">
        <h2>Welcome to Her Mental</h2>
        <p>Your safe space for sharing, growing, and uplifting one another.</p>
    </div>
    
    <footer>
        <p>&copy; 2025 Her Mental. All rights reserved.</p>
    </footer>
</body>
</html>
