```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Saswata Bag | Biography</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

body{
    background:#0f172a;
    color:#e2e8f0;
    line-height:1.8;
}

.hero{
    min-height:70vh;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    padding:60px 20px;
    background:linear-gradient(135deg,#0f172a,#1e293b,#0f172a);
}

.hero-content{
    max-width:900px;
}

.hero h1{
    font-size:4rem;
    color:#fff;
    margin-bottom:10px;
}

.hero h2{
    font-size:1.4rem;
    color:#38bdf8;
    font-weight:500;
}

.hero p{
    margin-top:20px;
    color:#cbd5e1;
    font-size:1.1rem;
}

.container{
    width:90%;
    max-width:1200px;
    margin:auto;
    padding:60px 0;
}

.section-title{
    font-size:2rem;
    color:#38bdf8;
    margin-bottom:30px;
    border-left:5px solid #38bdf8;
    padding-left:15px;
}

.card-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:25px;
}

.card{
    background:#1e293b;
    padding:25px;
    border-radius:15px;
    transition:0.3s;
}

.card:hover{
    transform:translateY(-5px);
    box-shadow:0 10px 30px rgba(56,189,248,.2);
}

.card h3{
    color:#38bdf8;
    margin-bottom:10px;
}

.skills{
    display:flex;
    flex-wrap:wrap;
    gap:10px;
}

.skill{
    background:#334155;
    padding:10px 15px;
    border-radius:30px;
    font-size:14px;
}

.timeline{
    border-left:3px solid #38bdf8;
    padding-left:25px;
}

.timeline-item{
    margin-bottom:35px;
}

.timeline-item h3{
    color:#38bdf8;
}

.project{
    background:#1e293b;
    padding:20px;
    border-radius:12px;
    margin-bottom:20px;
}

.project h3{
    color:#38bdf8;
    margin-bottom:10px;
}

.contact{
    text-align:center;
    padding:60px 20px;
    background:#111827;
}

.contact h2{
    color:#38bdf8;
    margin-bottom:20px;
}

.contact a{
    color:#38bdf8;
    text-decoration:none;
}

footer{
    text-align:center;
    padding:25px;
    background:#020617;
    color:#94a3b8;
}
</style>
</head>
<body>

<section class="hero">
    <div class="hero-content">
        <h1>Saswata Bag</h1>
        <h2>Student Researcher • Innovator • Developer</h2>
        <p>
            Specializing in Embedded Systems, IoT, Artificial Intelligence,
            Environmental Monitoring, Industrial Safety Technologies and
            Smart Automation Solutions.
        </p>
    </div>
</section>

<div class="container">

    <h2 class="section-title">About Me</h2>
    <div class="card">
        <p>
            I am a passionate researcher and innovator focused on developing
            practical technologies that solve real-world challenges. My work
            combines Embedded Systems, IoT, Artificial Intelligence, Sensor
            Networks and Data Analytics to create impactful solutions in
            industrial safety, disaster management, healthcare, environmental
            monitoring and automation.
        </p>
    </div>

    <br><br>

    <h2 class="section-title">Family & Inspiration</h2>

    <div class="card-grid">

        <div class="card">
            <h3>Dr. Subhendu Sekhar Bag</h3>
            <p>
                Professor, Department of Chemistry, IIT Guwahati and Head of
                Central Instrument Facility (CIF). My greatest inspiration and
                mentor who introduced me to scientific research and innovation.
            </p>
        </div>

        <div class="card">
            <h3>Aditi Bag</h3>
            <p>
                My mother and strongest supporter whose encouragement and
                guidance continue to shape my journey.
            </p>
        </div>

        <div class="card">
            <h3>Shreyasi Bag</h3>
            <p>
                My sister and constant motivator who inspires me to keep
                learning and pushing boundaries.
            </p>
        </div>

    </div>

    <br><br>

    <h2 class="section-title">Technical Skills</h2>

    <div class="skills">

        <div class="skill">Arduino</div>
        <div class="skill">ESP32</div>
        <div class="skill">Raspberry Pi</div>
        <div class="skill">IoT Systems</div>
        <div class="skill">Embedded Systems</div>
        <div class="skill">Artificial Intelligence</div>
        <div class="skill">Machine Learning</div>
        <div class="skill">C++</div>
        <div class="skill">Python</div>
        <div class="skill">HTML</div>
        <div class="skill">CSS</div>
        <div class="skill">JavaScript</div>
        <div class="skill">Sensor Integration</div>
        <div class="skill">GSM</div>
        <div class="skill">GPS</div>
        <div class="skill">RF Communication</div>
        <div class="skill">Data Logging</div>

    </div>

    <br><br>

    <h2 class="section-title">Awards & Recognition</h2>

    <div class="timeline">

        <div class="timeline-item">
            <h3>🏆 1st Prize</h3>
            <p>Rajya Stariya Bal Vaigyanik Pradarshani</p>
        </div>

        <div class="timeline-item">
            <h3>🏆 1st Prize</h3>
            <p>Research & Industrial Conclave Integration (RIC) 2024</p>
        </div>

        <div class="timeline-item">
            <h3>🏆 1st Prize</h3>
            <p>Environmental Hackathon 2024, IIT Guwahati</p>
        </div>

        <div class="timeline-item">
            <h3>🏆 Best Theme Award</h3>
            <p>India International Science Festival (IISF)</p>
        </div>

    </div>

    <br><br>

    <h2 class="section-title">Major Projects</h2>

    <div class="project">
        <h3>CHETAK</h3>
        <p>Coal Mine Hazard Evaluation and Tracking Assessment Kit for real-time hazardous gas monitoring and worker safety.</p>
    </div>

    <div class="project">
        <h3>CHETAK 2.0</h3>
        <p>Next-generation intelligent coal mine safety monitoring platform under development.</p>
    </div>

    <div class="project">
        <h3>SURAKSHA</h3>
        <p>Smart Security Lock with RFID, biometric authentication, attendance automation and unauthorized access prevention.</p>
    </div>

    <div class="project">
        <h3>EMG Controlled Wheelchair</h3>
        <p>Hands-free wheelchair system controlled through electromyography signals.</p>
    </div>

    <div class="project">
        <h3>Smart Safety Helmet</h3>
        <p>Accident detection and worker health monitoring system with emergency alerts.</p>
    </div>

    <div class="project">
        <h3>Cyclone Detection using AI/ML</h3>
        <p>Satellite data and weather station based cyclone prediction system.</p>
    </div>

    <br><br>

    <h2 class="section-title">Future Vision</h2>

    <div class="card">
        <ul>
            <li>AI-powered hazard prediction systems</li>
            <li>Advanced industrial safety technologies</li>
            <li>Smart environmental monitoring networks</li>
            <li>Disaster management solutions</li>
            <li>Satellite data analytics and forecasting</li>
            <li>Large-scale IoT monitoring systems</li>
        </ul>
    </div>

</div>

<section class="contact">
    <h2>Contact</h2>
    <p>Email: info@bagresearch.co.in</p>
    <p>Phone: 0361-2914255</p>
    <p>Website: <a href="https://www.bagresearch.co.in">www.bagresearch.co.in</a></p>
    <p>Location: India</p>
</section>

<footer>
    © 2026 Saswata Bag | Research • Innovation • Technology
</footer>

</body>
</html>
```

