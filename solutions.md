HTML
<!-- index.html — Home -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coders Club - Home</title>
    <meta name="description" content="Welcome to the Coders Club at Invertis University. Learn programming, web development, and participate in exciting tech events.">
    <link rel="icon" type="image/x-icon" href="images/favicon.ico">
</head>
<body>
    <header>
        <h1>Coders Club</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="registration.html">Register</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="hero">
            <h2>Welcome to Coders Club</h2>
            <p>Empowering students through code, collaborative projects, and hands-on workshops in software development.</p>
            <img src="images/club-banner.jpg" alt="Coders club members collaborating on programming projects in the computer lab" width="600" height="300">
        </section>

        <section id="activities">
            <h2>Our Core Activities</h2>
            <ul>
                <li>Weekly coding workshops covering Java, JavaScript, and web development.</li>
                <li>Hackathons and competitive programming practice sessions.</li>
                <li>Peer mentoring and collaborative open-source projects.</li>
            </ul>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 Coders Club, Invertis University. All rights reserved.</p>
    </footer>
</body>
</html>
HTML
<!-- about.html — Club Introduction -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coders Club - About</title>
    <meta name="description" content="Learn about the Coders Club mission, core members, and upcoming event schedules at Invertis University.">
    <link rel="icon" type="image/x-icon" href="images/favicon.ico">
</head>
<body>
    <header>
        <h1>Coders Club</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="registration.html">Register</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="about-intro">
            <h2>About the Club</h2>
            <p>Founded by passionate Computer Science Engineering students at Invertis University, Coders Club bridges the gap between theoretical classroom knowledge and practical software engineering.</p>
        </section>

        <section id="members">
            <h2>Core Committee Members</h2>
            <ul>
                <li><strong>Atim Akhtar</strong> — President & Lead Web Developer</li>
                <li><strong>Falak Siddiqui</strong> — Vice President & Event Coordinator</li>
                <li><strong>Utkarsh Tiwari</strong> — Technical Lead</li>
            </ul>
        </section>

        <section id="events">
            <h2>Upcoming Events Schedule</h2>
            <table>
                <caption>Coders Club Fall Semester Schedule</caption>
                <thead>
                    <tr>
                        <th>Event Name</th>
                        <th>Date</th>
                        <th>Time</th>
                        <th>Location</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>HTML & CSS Workshop</td>
                        <td>November 12, 2026</td>
                        <td>3:00 PM - 5:00 PM</td>
                        <td>Computer Lab 1</td>
                    </tr>
                    <tr>
                        <td>JavaScript Hackathon</td>
                        <td>November 25, 2026</td>
                        <td>10:00 AM - 4:00 PM</td>
                        <td>Main Auditorium</td>
                    </tr>
                    <tr>
                        <td>Git & GitHub Session</td>
                        <td>December 5, 2026</td>
                        <td>2:00 PM - 4:00 PM</td>
                        <td>Computer Lab 2</td>
                    </tr>
                </tbody>
            </table>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 Coders Club, Invertis University. All rights reserved.</p>
    </footer>
</body>
</html>
HTML
<!-- registration.html — Club Registration Form -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coders Club - Registration</title>
    <meta name="description" content="Register to join the Coders Club at Invertis University and participate in tech events.">
    <link rel="icon" type="image/x-icon" href="images/favicon.ico">
</head>
<body>
    <header>
        <h1>Coders Club</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="registration.html">Register</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <h1>Club Membership Registration</h1>
        <form action="#" method="POST">
            <div>
                <label for="fullname">Full Name:</label>
                <input type="text" id="fullname" name="fullname" required>
            </div>

            <div>
                <label for="email">University Email:</label>
                <input type="email" id="email" name="email" required>
            </div>

            <div>
                <label for="rollno">Roll Number:</label>
                <input type="text" id="rollno" name="rollno" required>
            </div>

            <div>
                <label for="department">Department:</label>
                <select id="department" name="department" required>
                    <option value="">-- Select Department --</option>
                    <option value="cse">Computer Science Engineering</option>
                    <option value="it">Information Technology</option>
                    <option value="ece">Electronics & Communication</option>
                </select>
            </div>

            <fieldset>
                <legend>Programming Experience:</legend>
                <input type="checkbox" id="exp-html" name="experience" value="html">
                <label for="exp-html">HTML/CSS</label>
                <input type="checkbox" id="exp-js" name="experience" value="javascript">
                <label for="exp-js">JavaScript</label>
                <input type="checkbox" id="exp-java" name="experience" value="java">
                <label for="exp-java">Java</label>
            </fieldset>

            <div>
                <button type="submit">Submit Registration</button>
            </div>
        </form>
    </main>

    <footer>
        <p>&copy; 2026 Coders Club, Invertis University. All rights reserved.</p>
    </footer>
</body>
</html>
HTML
<!-- contact.html — Contact Details -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coders Club - Contact</title>
    <meta name="description" content="Get in touch with the Coders Club team at Invertis University, Bareilly.">
    <link rel="icon" type="image/x-icon" href="images/favicon.ico">
</head>
<body>
    <header>
        <h1>Coders Club</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="registration.html">Register</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="contact-info">
            <h2>Contact Details</h2>
            <p>Have questions about events, workshops, or club memberships? Reach out to us using the details below:</p>
            <ul>
                <li><strong>Email:</strong> codersclub@invertisuniversity.ac.in</li>
                <li><strong>Phone:</strong> +91 98765 43210</li>
                <li><strong>Location:</strong> Department of Computer Science Engineering, Invertis University, Bareilly, Uttar Pradesh, India</li>
            </ul>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 Coders Club, Invertis University. All rights reserved.</p>
    </footer>
</body>
</html>