 <style>
        /* Basic CSS for styling */
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f0f0f0;
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 800px;
            margin: auto;
            background-color: #fff;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            border-radius: 8px;
        }
        h1, h2, p {
            margin-bottom: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Ayla Herman</h1>
            <p>Welcome to my GitHub profile!</p>
        </header>
        <section>
            <h2>About Me</h2>
            <p>I'm passionate about programming and design. I enjoy creating web applications and enhancing user experiences through thoughtful design and smooth animations.</p>
        </section>
        <section>
            <h2>Skills</h2>
            <ul>
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>
                <li>Web Design</li>
                <li>GitHub</li>
            </ul>
        </section>
    </div>

    <script>
        // Example of JavaScript animation (you can add more complex animations here)
        const header = document.querySelector('header h1');
        header.addEventListener('mouseover', function() {
            header.style.color = 'blue';
        });
        header.addEventListener('mouseout', function() {
            header.style.color = 'black';
        });
    </script>
</body>
