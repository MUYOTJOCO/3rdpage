
<html>
<head>
    <title>Home Workout Hub</title>

    <style>
        body {
            font-family: Arial;
        }

        nav button {
            margin: 5px;
            padding: 8px 12px;
            cursor: pointer;
        }

        section {
            display: none;
        }

        section.active {
            display: block;
        }
    </style>

    <script>
        function showSection(id) {
            var sections = document.querySelectorAll("section");
            sections.forEach(function(s) {
                s.classList.remove("active");
            });
            document.getElementById(id).classList.add("active");
        }

        window.onload = function() {
            showSection("home");
        }
    </script>
</head>

<body>

<header>
    <h2>Home Workout Hub</h2>

    <nav>
        <button onclick="showSection('home')">Home</button>
        <button onclick="showSection('workouts')">Workouts</button>
        <button onclick="showSection('tips')">Tips & Guides</button>
    </nav>

    <hr>
</header>

<section id="home">

    <h1>Welcome to Home Workout Hub</h1>
    <p>Your journey to a stronger and healthier body starts at home!</p>

    <h2>READ ME</h2>

    <img src="https://images.unsplash.com/photo-1554284126-aa88f22d8b74?auto=format&fit=crop&w=600&q=60" width="300">
    <p><strong>"one day or day one?"</strong></p>

    <br>

    <img src="https://images.unsplash.com/photo-1583454110551-21f2fa2afe61?auto=format&fit=crop&w=600&q=60" width="300">
    <p><strong>"If you don't sacrifice for what you want, what you want becomes the sacrifice."</strong></p>

    <br>

    <img src="https://images.unsplash.com/photo-1517960413843-0aee8e2b3285?auto=format&fit=crop&w=600&q=60" width="300">
    <p><strong>"Not every lion that chased the deer caught it. But every lion that caught a deer chased it."</strong></p>

    <br>

    <h2>Why Choose Home Workout?</h2>
    <ul>
        <li>No equipment needed</li>
        <li>Save money</li>
        <li>Save time</li>
        <li>Workout anytime</li>
    </ul>

</section>

<section id="workouts">

    <h1>Workout Programs</h1>
    <p>Select a difficulty level and start training!</p>

    <hr>

    <h2>🟢 Easy Level</h2>

    <h3>Jumping Jacks</h3>
    <p><strong>Duration:</strong> 3 sets of 20 reps</p>
    <p><strong>Benefit:</strong> Improves cardiovascular endurance and warms up the body.</p>
    <p><a href="https://www.youtube.com/watch?v=c4DAnQ6DtF8" target="_blank">Watch Here</a></p>

    <h3>Wall Sit</h3>
    <p><strong>Duration:</strong> 3 sets of 30 seconds</p>
    <p><strong>Benefit:</strong> Strengthens legs and improves lower body endurance.</p>
    <p><a href="https://www.youtube.com/watch?v=y-wV4Venusw" target="_blank">Watch Here</a></p>

    <hr>

    <h2>🟡 Intermediate Level</h2>

    <h3>Push-ups</h3>
    <p><strong>Duration:</strong> 3 sets of 10 reps</p>
    <p><strong>Benefit:</strong> Builds chest, shoulders, and arm strength.</p>
    <p><a href="https://www.youtube.com/watch?v=IODxDxX7oi4" target="_blank">Watch Here</a></p>

    <h3>Bodyweight Squats</h3>
    <p><strong>Duration:</strong> 3 sets of 15 reps</p>
    <p><strong>Benefit:</strong> Strengthens legs, glutes, and improves mobility.</p>
    <p><a href="https://www.youtube.com/watch?v=aclHkVaku9U" target="_blank">Watch Here</a></p>

    <hr>

    <h2>🔴 Hard Level</h2>

    <h3>Burpees</h3>
    <p><strong>Duration:</strong> 3 sets of 12 reps</p>
    <p><strong>Benefit:</strong> Full-body workout that increases strength and endurance.</p>
    <p><a href="https://www.youtube.com/watch?v=TU8QYVW0gDU" target="_blank">Watch Here</a></p>

    <h3>Plank</h3>
    <p><strong>Duration:</strong> 3 sets of 45 seconds</p>
    <p><strong>Benefit:</strong> Strengthens core muscles and improves stability.</p>
    <p><a href="https://www.youtube.com/watch?v=pSHjTRCQxIw" target="_blank">Watch Here</a></p>

</section>

<section id="tips">

    <h1>Tips & Guides</h1>

    <h2>Basic Fitness Tips</h2>
    <ul>
        <li>Stay consistent with your workouts</li>
        <li>Focus on proper form instead of speed</li>
        <li>Stay hydrated before, during, and after exercise</li>
        <li>Get enough rest and recovery</li>
    </ul>

    <h2>Safety Guidelines for Workouts</h2>
    <ul>
        <li>Start with exercises suitable for your level</li>
        <li>Listen to your body and avoid overtraining</li>
        <li>Use proper posture to prevent injuries</li>
        <li>Stop immediately if you feel pain or dizziness</li>
    </ul>

    <h2>Warm-up Exercises</h2>
    <ul>
        <li>Do light cardio like jumping jacks</li>
        <li>Arm circles and leg swings</li>
        <li>Light jogging in place</li>
    </ul>
    <p>
        <a href="https://www.youtube.com/watch?v=R0mMyV5OtcM" target="_blank">Watch Here</a>
    </p>

    <h2>Cool-down Exercises</h2>
    <ul>
        <li>Stretch major muscle groups</li>
        <li>Slow walking or light movement</li>
        <li>Deep breathing exercises</li>
    </ul>
    <p>
        <a href="https://www.youtube.com/watch?v=v7AYKMP6rOE" target="_blank">Watch Here</a>
    </p>

</section>

<hr>

<footer>
    <p>© 2026 Home Workout Hub</p>
</footer>

</body>
</html>
