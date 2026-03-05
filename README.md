<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="The official website of author Sara Iddir">
    <title>Sara Iddir</title>
    <style>
        /* Base Styles */
        body {
            font-family: "Georgia", serif;
            margin: 0;
            /* 🌟 HERO IMAGE / BACKGROUND IMAGE ADDED HERE 🌟 */
            background: url('https://miro.medium.com/v2/da%3Atrue/resize%3Afit%3A1200/0%2AcqPWt_uqeZgPWRby') no-repeat center center fixed;
            background-size: cover;
            color: #e6efe9;
            line-height: 1.7;
        }

        /* Navigation */
        nav {
            background-color: rgba(20, 58, 45, 0.85);
            padding: 15px;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        nav a {
            color: #cddfd5;
            margin: 0 20px;
            text-decoration: none;
            font-size: 18px;
            font-weight: 500;
        }

        nav a:hover {
            color: #ffffff;
        }

        /* Header */
        header {
            text-align: center;
            padding: 120px 20px 80px 20px;
            background: rgba(28, 75, 58, 0.8);
        }

        header h1 {
            font-size: 56px;
            margin-bottom: 15px;
            letter-spacing: 2px;
        }

        header p {
            font-style: italic;
            color: #c8d8cf;
            font-size: 22px;
        }

        /* Sections */
        section {
            max-width: 900px;
            margin: auto;
            padding: 60px 20px;
            background: rgba(15, 42, 32, 0.85);
            border-radius: 12px;
            margin-bottom: 60px;
        }

        h2 {
            border-bottom: 1px solid #6f9a87;
            padding-bottom: 12px;
            margin-bottom: 30px;
            font-size: 28px;
        }

        /* Works Grid */
        .works-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
            gap: 25px;
            justify-items: center;
        }

        .work {
            text-align: center;
            background: rgba(28, 58, 45, 0.9);
            padding: 20px;
            border-radius: 10px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .work:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.4);
        }

        .work img {
            max-width: 100%;
            border-radius: 8px;
            margin-bottom: 15px;
        }

        .work strong {
            display: block;
            margin-bottom: 8px;
            font-size: 18px;
        }

        /* Events */
        .event {
            margin-bottom: 20px;
        }

        /* Contact */
        .contact-box {
            background: rgba(23, 62, 49, 0.95);
            padding: 30px;
            border-radius: 10px;
        }

        /* Newsletter Section */
        #newsletter {
            max-width: 900px;
            margin: 0 auto 60px auto; /* 🌿 centered horizontally */
            padding: 40px 20px;
            background: rgba(28, 58, 45, 0.9);
            border-radius: 12px;
            text-align: center;
        }

        #newsletter h2 {
            border-bottom: 1px solid #6f9a87;
            padding-bottom: 12px;
            margin-bottom: 25px;
            font-size: 28px;
        }

        .newsletter-box p {
            margin-bottom: 20px;
            font-style: italic;
            color: #d1e0d6;
        }

        #newsletter form {
            display: flex;
            flex-direction: row; /* input + button side by side */
            justify-content: center; /* center horizontally */
            flex-wrap: wrap; /* wrap on small screens */
            gap: 15px;
        }

        #newsletter input[type="email"] {
            padding: 12px 15px;
            font-size: 16px;
            border-radius: 8px;
            border: none;
            width: 300px;
            max-width: 90%; /* responsive on small screens */
        }

        #newsletter button {
            padding: 12px 25px;
            font-size: 16px;
            background-color: #6f9a87;
            color: #e6efe9;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            transition: background 0.3s ease;
        }

        #newsletter button:hover {
            background-color: #5a7c6b;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 30px;
            background: rgba(11, 31, 24, 0.9);
            font-size: 14px;
        }

        /* Scroll effect for literary feel */
        .literary {
            font-style: italic;
            font-size: 20px;
            line-height: 1.8;
            margin: 20px 0;
            color: #d1e0d6;
        }
    </style>
</head>

<body>

    <nav>
        <a href="#about">About</a>
        <a href="#works">Selected Works</a>
        <a href="#events">Events</a>
        <a href="#contact">Contact</a>
    </nav>

    <header>
        <h1>Sara Iddir</h1>
        <p>Poems • Essays • Fiction</p>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p class="literary">
            Sara Iddir is a writer whose work explores memory, landscape, and the quiet dramas of everyday life.
            Her essays and stories often dwell in the space between reflection and imagination.
        </p>
        <p class="literary">
            She lives between libraries, notebooks, and long walks, collecting fragments of language and turning them into
            stories about place, time, and human connection.
        </p>
    </section>

    <section id="works">
        <h2>Selected Works</h2>
        <div class="works-grid">
            <div class="work">
                <img src="https://images.unsplash.com/photo-1512820790803-83ca734da794?auto=format&fit=crop&w=300&q=80"
                    alt="The Quiet Orchard">
                <strong>The Quiet Orchard</strong>
                A short story collection exploring solitude and belonging.
            </div>

            <div class="work">
                <img src="https://images.unsplash.com/photo-1519681393784-d120267933ba?auto=format&fit=crop&w=300&q=80"
                    alt="Letters from the River">
                <strong>Letters from the River</strong>
                A reflective essay series on landscape and memory.
            </div>

            <div class="work">
                <img src="https://images.unsplash.com/photo-1524995997946-a1c2e315a42f?auto=format&fit=crop&w=300&q=80"
                    alt="The Green Notebook">
                <strong>The Green Notebook</strong>
                Fragments and observations from everyday life.
            </div>
        </div>
    </section>

    <section id="events">
        <h2>Upcoming Events</h2>
        <div class="event">
            <strong>April 12 — Cambridge Reading</strong><br>
            An evening reading at a local independent bookshop.
        </div>
        <div class="event">
            <strong>May 6 — Literary Festival Panel</strong><br>
            Conversation on writing and place.
        </div>
        <div class="event">
            <strong>June 20 — Workshop</strong><br>
            A small writing workshop on essays and memory.
        </div>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <div class="contact-box">
            <p>For enquiries, collaborations, or speaking invitations:</p>
            <p>Email: <em>your@email.com</em></p>
            <p>Instagram / Twitter: <em>@yourhandle</em></p>
			<p>Linkenin: <em>@yourhandle</em></p>
			<p>Bluesky: <em>@yourhandle</em></p>
        </div>
    </section>

    <!-- 🌿 MAILING LIST SECTION (Centered Fix) 🌿 -->
    <section id="newsletter">
        <h2>Join the Mailing List</h2>
        <div class="newsletter-box">
            <p class="literary">
                Stay up to date with new releases, events, and essays. Enter your email below to receive updates directly.
            </p>
            <form action="#" method="post">
                <input type="email" name="email" placeholder="Your email address" required>
                <button type="submit">Subscribe</button>
            </form>
        </div>
    </section>

    <footer>
        © 2026 Sara Iddir
    </footer>

</body>

</html>
