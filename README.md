<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title style ="color:aqua" blue; font-size:40px">Telemedicine Application</title>
    <style>
        body

        <p class="text-center">
  <span>Part 1</span>
  <span>Part 2</span>
  <span>Part 3</span>
</p>
.text-center {
  text-align: center;
  margin: 10;
  display: flex;
  justify-content: center;
  align-items: center;
}

.text-center span {
  margin: 0 1em;
  font-size: 1.2em;
  font-weight: bold;
}
        {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            overflow-x: hidden; /* Prevent horizontal scrolling */
        }
        
        header {
            background-color: #173a18;
            color: white;
            padding: 20px 30px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            position: relative;
        }
        
        <img src="Leonardo_Phoenix_A_modern_futuristic_and_calming_logo_design_f_2" alt="Image description">
        .logo {
            
            height: 50px;
        }

        .marquee {
            position: absolute;
            top: 60px; /* Position below header */
            left: 0;
            white-space: nowrap;
            font-size: 24px;
            animation: marquee 10s linear infinite;
        }

        @keyframes marquee {
            0% { transform: translateX(100%); }
            100% { transform: translateX(-100%); }
        }

        nav {
            display: flex;
        }

        .nav-links {
            list-style: none;
            display: flex;
            margin: 0;
            padding: 0;
        }

        .nav-links li {
            margin: 0 15px;
        }

        .nav-links a {
            color: white;
            text-decoration: none;
        }

        .hamburger {
            display: none;
            cursor: pointer;
        }

        .container {
            display: flex;
            margin: 20px;
        }

        main {
            flex: 3;
            margin-right: 20px;
        }

        aside {
            flex: 1;
            background: #f4f4f4;
            padding: 15px;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
        }

        .social-media a {
            margin: 0 10px;
            color: white;
            text-decoration: none;
        }

        @media (max-width: 768px) {
            .container {
                flex-direction: column;
            }
            main {
                margin-right: 0;
            }
            .hamburger {
                display: block;
            }
            .nav-links {
                display: none;
                flex-direction: column;
                position: absolute;
                top: 60px;
                left: 0;
                background: #4CAF50;
                width: 100%;
            }
            .nav-links.active {
                display: flex;
            }
        }
    </style>
</head>
<body>

    <header>
        
        <h1>Telemedicine Application</h1>
        <nav>
            <div class="hamburger" onclick="toggleMenu()">
                <div class="line"></div>
                <div class="line"></div>
                <div class="line"></div>
            </div>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
        <div class="marquee">Welcome to Telemedicine</div>
    </header>

    <div class="container">
        <main>
            <h2>Welcome to Our Telemedicine Service</h2>
            <p>We provide accessible healthcare from the comfort of your home. Our platform connects you with licensed healthcare professionals through video consultations.</p>
            <h3>Why Choose Telemedicine?</h3>
            <p>Telemedicine: A Revolutionary Tool for Healthcare

                Telemedicine, the practice of providing healthcare remotely through telecommunications technology, has revolutionized the medical landscape. Its numerous benefits have transformed patient care, making it more accessible, convenient, and efficient.
                
                Enhanced Accessibility:
                
                Telemedicine bridges geographical barriers to healthcare, enabling patients in remote or underserved areas to connect with medical professionals. It eliminates the need for time-consuming and expensive travel, particularly for patients with limited mobility or chronic conditions.
                
                Convenience and Flexibility:
                
                Telemedicine offers unparalleled convenience. Patients can access care from the comfort of their homes or any location with an internet connection. They can schedule appointments at times that fit their busy schedules, reducing waiting room time and disruption to their daily routines.
                
                Improved Patient Outcomes:
                
                Telemedicine facilitates early detection and timely intervention. Remote monitoring devices and virtual consultations allow healthcare providers to track patient health parameters regularly, identify potential issues, and provide prompt treatment. This proactive approach improves patient outcomes and reduces the risk of complications.
                
                Expanded Healthcare Services:
                
                Telemedicine expands access to specialized healthcare services that may not be available locally. Patients can connect with experts in a wide range of fields, including cardiology, dermatology, and mental health. This enhanced access to specialized care improves patient care and reduces the need for costly referrals.
                
                Reduced Costs:
                
                Telemedicine has the potential to reduce healthcare costs significantly. By eliminating the need for in-person visits, travel expenses, and office overhead, telemedicine lowers administrative costs. It also saves patients money on transportation and parking fees.
                
                Improved Communication and Patient Engagement:
                
                Telemedicine improves communication between patients and healthcare providers. Virtual platforms facilitate secure messaging, file sharing, and video conferencing. This enhanced communication fosters patient engagement and empowers patients to take a more active role in their health management.
                
                Benefits for Healthcare Providers:
                
                Telemedicine also offers numerous benefits to healthcare providers. It allows them to reach a larger patient population, increase their efficiency, and improve their work-life balance. Remote monitoring and virtual consultations enable providers to provide continuous care without the constraints of traditional office hours.
                
                Conclusion:
                
                Telemedicine has emerged as a game-changer in healthcare, offering a myriad of benefits for patients and providers alike. Its accessibility, convenience, improved patient outcomes, expanded healthcare services, cost-effectiveness, and enhanced communication make it an essential tool for transforming healthcare delivery in the 21st century. By embracing telemedicine, we can create a more equitable, efficient, and patient-centered healthcare system for the future.</p>
            <ul>
                <li>Convenience: Access healthcare services anytime, anywhere.</li>
                <li>Cost-effective: Save on travel and consultation costs.</li>
                <li>Privacy: Consult with doctors in the comfort of your own space.</li>
            </ul>
        </main>
       
        <aside>
            <h3>Additional Resources</h3>
            <form>
                <input type="text" placeholder="Search...">
                <button type="submit">Search</button>
            </form>
            <h4>Quick Links</h4>
            <ul>
                <li><a href="#faq">FAQs</a></li>
                <li><a href="#testimonials">Testimonials</a></li>
                <li><a href="#blog">Blog</a></li>
            </ul>
        </aside>
    </div>

    <footer>
        <p>&copy; 2024 Telemedicine Application. All Rights Reserved.</p>
        <div class="social-media">
            <a href="#">Facebook</a>
            <a href="#">X</a>
            <a href="#">LinkedIn</a>
            <a href="https://github.com/Hardennes7">Github </a>
            <a href="whatsapp://send?phone=+254799485028&text=Hello%20there!">Click to Chat</a>
        </div>
        <p>Contact us: info@telemedicineapp.com</p>
        <p>Contact us: on whatapp</p>
    </footer>

    <script>
        function toggleMenu() {
            const navLinks = document.querySelector('.nav-links');
            navLinks.classList.toggle('active');
        }
    </script>



</body>
</html>
- 👋 Hi, I’m @Hardennes7
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Hardennes7/Hardennes7 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
