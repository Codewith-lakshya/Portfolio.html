<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lakshya Mishra - Student Portfolio</title>
    <style>
        /* General Styling */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to right, #f0f4c3, #f0e1e4); /* Light lime and soft pink */
            color: #333;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .container {
            max-width: 800px;
            width: 90%;
            background: white;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
            margin: 20px;
        }

        /* Header Styling */
        .header {
            display: flex;
            align-items: center;
            gap: 15px;
            text-align: center;
            margin-bottom: 20px;
            background-color: #3949ab; /* Navy */
            color: #ffffff;
            padding: 20px;
            border-radius: 10px;
        }

        .header img.logo {
            width: 80px;
            height: auto;
            border-radius: 50%;
        }

        .header img.profile-picture {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            object-fit: cover;
            border: 3px solid #3949ab; /* Navy border */
        }

        /* Section Styling */
        .section {
            padding: 20px;
            margin: 20px 0;
            border-radius: 8px;
            color: #333;
            line-height: 1.6;
        }

        /* Section Headers */
        .section h2 {
            font-size: 24px;
            color: #ffffff;
            padding: 10px;
            border-radius: 5px;
        }

        /* Individual Sections with Unique Backgrounds */
        .personal-info {
            background-color: #ffab91; /* Light coral */
        }

        .achievements {
            background-color: #80cbc4; /* Teal */
        }

        .subjects-grade {
            background-color: #b39ddb; /* Lavender */
        }

        .goals {
            background-color: #ffe082; /* Light peach */
        }

        .profile {
            background-color: #ffcc80; /* Light orange */
        }

        .contact-info {
            background-color: #d7ccc8; /* Light gray-brown */
            text-align: center;
            border-radius: 10px;
            padding: 15px;
        }

        /* Text and Layout */
        p, h2 {
            margin: 0 0 10px;
        }

        ul {
            padding-left: 20px;
            list-style-type: square;
        }

        .contact-info p {
            font-size: 18px;
            color: #424242;
        }

        .signature {
            text-align: center;
            font-size: 14px;
            margin-top: 20px;
            padding: 10px;
            color: #555;
            border-top: 2px solid #3949ab;
        }
    </style>
</head>
<body>

<div class="container">
    <!-- Header with school logo and title -->
    <div class="header">
        <img src="content://com.android.providers.media.documents/document/image%3A1000010075" alt="School Logo" class="logo"> <!-- School logo image -->
        <div>
            <h1>Lakshya's Portfolio</h1>
        </div>
        <img src="content://com.android.providers.media.documents/document/image%3A1000010072" alt="Lakshya Mishra Photo" class="profile-picture"> <!-- Student profile picture -->
    </div>

    <!-- Personal Information section with school name as text -->
    <div class="section personal-info">
        <h2>Personal Information</h2>
        <p><strong>Name:</strong> Lakshya Mishra</p>
        <p><strong>Class:</strong> 7th</p>
        <p><strong>School:</strong> Pride International School</p> <!-- School name as text -->
        <p><strong>Age:</strong> 12</p>
        <p><strong>Favourite Subject:</strong> Science</p>
        <p><strong>Dream:</strong> Software Engineer</p>
        <p><strong>Hobby:</strong> Reading</p>
        <p>Lakshya is a dedicated student with a passion for learning, particularly in subjects like Science, Mathematics, and Social Studies...</p>
    </div>

    <!-- Achievements section -->
    <div class="section achievements">
        <h2>Achievements</h2>
        <ul>
            <li>Recognized for academic excellence in Science and Mathematics.</li>
            <li>Represented the school in  sports tournaments.</li>
            <li>Active participant in cricket.</li>
            <li>Won awards in the school's art competitions.</li>
        </ul>
    </div>

    <!-- Subjects Grade Section -->
    <div class="section subjects-grade">
        <h2>Subjects and Grades</h2>
        <p>Science: A1</p>
        <p>Social Studies: A1</p>
        <p>English: A1</p>
        <p>Computer Science: A1</p>
        <p>Maths: B1</p>
    </div>

    <!-- Goals section -->
    <div class="section goals">
        <h2>Goals</h2>
        <p><strong>Short-term Goals:</strong> To strengthen his understanding of core subjects...</p>
        <p><strong>Long-term Goals:</strong> Lakshya’s dream is to become an Software Engineer...</p>
    </div>

    <!-- Profile section with a longer paragraph -->
    <div class="section profile">
        <h2>Student Profile</h2>
        <p>Lakshya Mishra is a bright and ambitious young student who dreams big...</p>
    </div>

    <!-- Contact Information -->
    <div class="section contact-info">
        <h2>Contact Information</h2>
        <p><strong>Phone:</strong> 9955520523,6299610799</p>
        <p><strong>Email:</strong> lakshyamishra13@gmail.com</p>
    </div>

    <!-- Signature and Date -->
    <div class="signature">
        &copy; 2024 Lakshya Mishra. All rights reserved.
    </div>
</div>

</body>
</html>
