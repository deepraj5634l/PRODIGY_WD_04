# PRODIGY_WD_04
[index.html](https://github.com/user-attachments/files/24741191/index.html)
[style.css](https://github.com/user-attachments/files/24741199/style.css)
:root {
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

h3 { color: var(--accent-blue); border-bottom: 1px solid #334155; padding-bottom: 10px; }
