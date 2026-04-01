<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Video Editing Portfolio</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #0f172a;
    color: white;
}

header {
    text-align: center;
    padding: 60px 20px;
    background: linear-gradient(135deg, #1e293b, #0f172a);
}

header h1 {
    font-size: 3rem;
}

header p {
    color: #94a3b8;
}

.btn {
    display: inline-block;
    padding: 12px 25px;
    margin-top: 20px;
    background: #3b82f6;
    color: white;
    text-decoration: none;
    border-radius: 8px;
}

section {
    padding: 50px 20px;
    max-width: 1000px;
    margin: auto;
}

h2 {
    text-align: center;
    margin-bottom: 30px;
}

.videos {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
}

iframe {
    width: 100%;
    height: 200px;
    border-radius: 10px;
}

.card {
    background: #1e293b;
    padding: 20px;
    border-radius: 10px;
}

footer {
    text-align: center;
    padding: 20px;
    background: #020617;
    color: #64748b;
}
</style>

</head>

<body>

<header>
    <h1>Diptesh kumar Das</h1>
    <p>Professional Video Editor | Reels • YouTube • Cinematic Edits</p>
    <a href="#contact" class="btn">Hire Me</a>
</header>

<section>
    <h2>About Me</h2>
    <p>
        I am a passionate video editor specializing in cinematic edits,
        YouTube content, reels, and social media videos. I help creators
        and brands bring their vision to life through engaging visuals.
    </p>
</section>

<section>
    <h2>My Work</h2>
    <div class="videos">
        <!-- Replace with your video links -->
        <iframe src="https://www.youtube.com/embed/VIDEO_ID1" allowfullscreen></iframe>
        <iframe src="https://www.youtube.com/embed/VIDEO_ID2" allowfullscreen></iframe>
        <iframe src="https://www.youtube.com/embed/VIDEO_ID3" allowfullscreen></iframe>
    </div>
</section>

<section>
    <h2>Services</h2>
    <div class="videos">
        <div class="card">
            <h3>YouTube Editing</h3>
            <p>Professional long-form content editing.</p>
        </div>
        <div class="card">
            <h3>Reels & Shorts</h3>
            <p>High-engagement short videos for social media.</p>
        </div>
        <div class="card">
            <h3>Cinematic Edits</h3>
            <p>Story-driven cinematic video production.</p>
        </div>
    </div>
</section>

<section id="contact">
    <h2>Contact Me</h2>
    <p>Email: dasdipteshkumar1@gmail.com</p>
    <p>Instagram: @diptesh_ds_07</p>
</section>

<footer>
    <p>© 2026 deep vfx | Video Editor</p>
</footer>

</body>
</html>
