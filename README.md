# Filght-finder-navigeting-your-air-travel-option1<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Flight Finder</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f6f8;
        }
        .container {
            width: 400px;
            margin: 50px auto;
            padding: 20px;
            background: #ffffff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        h2 {
            text-align: center;
        }
        .section {
            margin-bottom: 15px;
        }
        button {
            width: 100%;
            padding: 10px;
            background-color: #007bff;
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 16px;
            cursor: pointer;
        }
        button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>

<div class="container">
    <h2>Flight Finder</h2>

    <form action="#" method="post">

        <div class="section">
            <strong>Trip Type</strong><br>
            <input type="radio" name="tripType" value="oneway" required> One Way<br>
            <input type="radio" name="tripType" value="roundtrip"> Round Trip
        </div>

        <div class="section">
            <strong>Class</strong><br>
            <input type="radio" name="travelClass" value="economy" required> Economy<br>
            <input type="radio" name="travelClass" value="business"> Business<br>
            <input type="radio" name="travelClass" value="first"> First Class
        </div>

        <button type="submit">Search Flights</button>

    </form>
</div>

</body>
</html>
