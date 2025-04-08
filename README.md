<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Multimedia-Rich Webpage</title>
</head>
<body>

    <!-- Embedded Image -->
    <h2>Embedded Image</h2>
    <img src="image.jpg" alt="Sample Image" width="300">

    <!-- Audio Element -->
    <h2>Audio Element</h2>
    <audio controls>
        <source src="audio.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>

    <!-- Video Element -->
    <h2>Video Element</h2>
    <video width="400" controls>
        <source src="video.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>

    <!-- Registration Form with Validation -->
    <h2>Registration Form</h2>
    <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required><br><br>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required><br><br>

        <label for="password">Password:</label>
        <input type="password" id="password" name="password" required><br><br>

        <label for="age">Age:</label>
        <input type="number" id="age" name="age" min="18" required><br><br>

        <button type="submit">Register</button>
    </form>

    <!-- Embedded Table -->
    <h2>Sample Table</h2>
    <table border="1">
        <tr>
            <th>Name</th>
            <th>Age</th>
            <th>Country</th>
        </tr>
        <tr>
            <td>Alice</td>
            <td>25</td>
            <td>USA</td>
        </tr>
        <tr>
            <td>Bob</td>
            <td>30</td>
            <td>UK</td>
        </tr>
    </table>

    <!-- List -->
    <h2>Grocery List</h2>
    <ul>
        <li>Milk</li>
        <li>Eggs</li>
        <li>Bread</li>
        <li>Butter</li>
    </ul>

</body>
</html>
