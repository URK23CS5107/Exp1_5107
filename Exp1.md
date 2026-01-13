<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Online event Registration</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #532e23;
        }
        .container {
            width: 700px;
            margin: auto;
            background-color: rgb(255, 255, 255);
            padding: 20px;
            border-radius: 8px;
        }
        h1 {
            text-align: center;
            color: #030303;
        }
        label {
            font-weight: bold;
        }
        input, select, textarea {
            width: 100%;
            padding: 8px;
            margin: 6px 0 15px 0;
        }
        input[type="radio"],
        input[type="checkbox"] {
            width: auto;
        }
        button {
            background-color: #437945;
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
            width: 100%;
            font-size: 16px;
        }
        button:hover {
            background-color: #2c4e2e;
        }
        .media {
            margin-top: 20px;
        }
    </style>
</head>

<body>

<div class="container">
    <h1>Art Exhibition</h1>

    <!-- Media Elements -->
    <div class="media">
        <h1>Artistic Magics</h1>

    <!-- Image -->
        <img src="C:\Users\urk23cs5107\Downloads\28663.jpg" alt="Event Banner" width="100%">


    <!-- Video -->
        <p>Event Promo Video:</p>
        <video width="100%" controls>
            <source src="C:\Users\urk23cs5107\Downloads\IAG Cargo  The National Gallery teaser - IAG Cargo (1080p, h264).mp4" type="video/mp4">
        </video>

    <!-- Audio -->
        <p>Event Promo Audio:</p>
        <audio controls>
            <source src="C:\Users\urk23cs5107\Downloads\event_regaudio.mp3" type="audio/mpeg">
        </audio>

        </div>

    <form>
        <!-- Text Input -->
        <label>Full Name:</label>
        <input type="text" name="name" required>

        <!-- Email -->
        <label>Email:</label>
        <input type="email" name="email" required>

        <!-- Phone Number -->
        <label>Phone Number:</label>
        <input type="number" name="phone" required>

        <!-- Date -->
        <label>Event Date:</label>
        <input type="date" name="date" required>

        <!-- Radio Buttons -->
        <label>Gender:</label><br>
        <input type="radio" name="gender" value="Male" required> Male
        <input type="radio" name="gender" value="Female"> Female
        <br><br>

        <!-- Dropdown -->
        <label>Event Type:</label>
        <select name="event" required>
            <option value="">--Select Event--</option>
            <option>exhibition</option>
        </select>

        <!-- Textarea -->
        <label>Comments:</label>
        <textarea rows="4" placeholder="Enter your comments"></textarea>

        <!-- Checkbox -->
        <input type="checkbox" required>
        I agree to the Terms and Conditions
        <br><br>

        <!-- Submit Button -->
        <button type="submit">Register</button>
    </form>
 
</div>

</body>
</html>
