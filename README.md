[style.css](https://github.com/user-attachments/files/24741154/style.css)# PRODIGY_WD_04
[index.html](https://github.com/user-attachments/files/24741139/index.html)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Developer Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <section id="home" class="hero">
        <div class="hero-content">
            <img src="IMG_9693" alt="Professional Photo" class="profile-img">
            <h1>Creative Web Developer</h1>
            <p class="headline">Building innovative digital solutions with modern technology.</p>
            <div class="skill-tags">
                <span>HTML5</span> | <span>CSS3</span> | <span>JavaScript</span>
            </div>
        </div>
    </section>

    <section id="about" class="about-section">
        <h2>About Me</h2>
        <div class="content-grid">
            <div class="bio">
                <h3>Background</h3>
                <p>Hello! I am a passionate developer with a strong foundation in building responsive and user-friendly web applications.</p>
            </div>[Uploadi:root {
    --bg-dark: #0f172a;
    --text-light: #f1f5f9;
    --accent-blue: #38bdf8;
    --card-bg: #1e293b;
}

body {
    background-color: var(--bg-dark);
    color: var(--text-light);
    font-family: 'Inter', sans-serif;
    line-height: 1.6;
    margin: 0;
}

/* Hero Section */
.hero {
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    background: linear-gradient(rgba(15, 23, 42, 0.8), rgba(15, 23, 42, 0.8)), url('hero-bg.jpg');
    background-size: cover;
}

.profile-img {
    width: 180px;
    height: 180px;
    border-radius: 50%;
    border: 4px solid var(--accent-blue);
    margin-bottom: 20px;
}

h1 { font-size: 3.5rem; color: var(--accent-blue); }

/* About Section */
.about-section {
    padding: 80px 10%;
    background-color: var(--bg-dark);
}

.content-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 30px;
    margin-top: 40px;
}

h3 { color: var(--accent-blue); border-bottom: 1px solid #334155; padding-bottom: 10px; }ng style.css…]()

            <div class="education">
                <h3>Education</h3>
                <p>Bachelor of Science in Computer Science - University Name</p>
            </div>
            <div class="experience">
                <h3>Professional Experience</h3>
                <ul>
                    <li>Frontend Intern - Tech Solutions (2025)</li>
                    <li>Freelance Web Designer (2024-Present)</li>
                </ul>
            </div>
        </div>
    </section>
</body>
</html>
