

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exercise Tips</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #35424a;
            color: #ffffff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            margin: 20px 0;
        }
        nav a {
            margin: 0 15px;
            color: #ffffff;
            text-decoration: none;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        section {
            background: #ffffff;
            padding: 20px;
            margin: 20px 0;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #35424a;
        }
        footer {
            text-align: center;
            padding: 10px 0;
            background: #35424a;
            color: #ffffff;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .tip {
            margin: 10px 0;
            padding: 10px;
            background: #e2e2e2;
            border-left: 5px solid #35424a;
        }
        .accordion {
            background-color: #f1f1f1;
            color: #444;
            cursor: pointer;
            padding: 10px;
            width: 100%;
            border: none;
            text-align: left;
            outline: none;
            font-size: 15px;
            transition: 0.4s;
            margin: 5px 0;
        }
        .active, .accordion:hover {
            background-color: #ccc;
        }
        .panel {
            padding: 0 18px;
            display: none;
            overflow: hidden;
            background-color: white;
        }
    </style>
</head>
<body>

<header>
    <h1>Exercise Tips for a Healthier You</h1>
    <nav>
        <a href="https://example.com/tips" target="_blank">Tips</a>
        <a href="https://example.com/workouts" target="_blank">Workouts</a>
        <a href="https://example.com/nutrition" target="_blank">Nutrition</a>
        <a href="https://example.com/contact" target="_blank">Contact</a>
    </nav>
</header>

<div class="container">
    <section id="tips">
        <h2>General Exercise Tips</h2>
        <div class="tip">1. Start Slow: If you're new to exercise, start with shorter sessions and gradually increase the duration and intensity.</div>
        <div class="tip">2. Stay Hydrated: Drink plenty of water before, during, and after your workout.</div>
        <div class="tip">3. Mix It Up: Incorporate a variety of exercises to work different muscle groups and keep things interesting.</div>
        <div class="tip">4. Set Realistic Goals: Set achievable fitness goals to stay motivated and track your progress.</div>
        <div class="tip">5. Listen to Your Body: Pay attention to how your body feels during exercise and rest when needed.</div>
    </section>

    <section id="workouts">
        <h2>Workout Routines</h2>
        <button class="accordion">Cardio Workouts</button>
        <div class="panel">
            <p>Cardio workouts are great for improving heart health and burning calories. Here are some examples:</p>
            <ul>
                <li>Running or jogging</li>
                <li>Cycling</li>
                <li>Swimming</li>
                <li>Jump rope</li>
                <li>High-Intensity Interval Training (HIIT)</li>
            </ul>
        </div>

        <button class="accordion">Strength Training</button>
       
