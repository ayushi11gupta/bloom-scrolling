<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bloom Scrolling - Learn as You Scroll</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">
                <img src="https://picsum.photos/50/50" alt="Bloom Scrolling Logo" width="50" height="50">
                Bloom Scrolling
            </div>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#features">Features</a></li>
                <li><a href="#gamification">Gamification</a></li>
                <li><a href="#quizzes">Quizzes</a></li>
                <li><a href="#learning">Learning</a></li>
            </ul>
            <div class="burger">
                <div class="line1"></div>
                <div class="line2"></div>
                <div class="line3"></div>
            </div>
        </nav>
    </header>

    <main>
        <section id="home" class="hero">
            <div class="hero-content">
                <h1>Learn as You Scroll</h1>
                <p>Master email marketing, content creation, and public speaking through interactive, bite-sized lessons.</p>
                <a href="#features" class="cta-button">Start Learning</a>
            </div>
            <div class="hero-image">
                <img src="https://picsum.photos/600/400" alt="Students learning online" width="600" height="400">
            </div>
        </section>

        <section id="features" class="features">
            <h2>Why Choose Bloom Scrolling</h2>
            <div class="feature-grid">
                <div class="feature">
                    <img src="https://picsum.photos/100/100?random=1" alt="Interactive Learning" width="100" height="100">
                    <h3>Interactive Learning</h3>
                    <p>Engage with dynamic content that adapts to your learning style and pace.</p>
                </div>
                <div class="feature">
                    <img src="https://picsum.photos/100/100?random=2" alt="Bite-sized Lessons" width="100" height="100">
                    <h3>Bite-sized Lessons</h3>
                    <p>Learn complex topics through easy-to-digest, short lessons as you scroll.</p>
                </div>
                <div class="feature">
                    <img src="https://picsum.photos/100/100?random=3" alt="Community Engagement" width="100" height="100">
                    <h3>Community Engagement</h3>
                    <p>Connect with fellow learners, share insights, and grow together.</p>
                </div>
                <div class="feature">
                    <img src="https://picsum.photos/100/100?random=4" alt="Progress Tracking" width="100" height="100">
                    <h3>Progress Tracking</h3>
                    <p>Monitor your learning journey with detailed analytics and insights.</p>
                </div>
            </div>
        </section>

        <section id="video" class="video-section">
            <h2>See Bloom Scrolling in Action</h2>
            <div class="video-container">
                <video controls width="1280" height="720" poster="https://picsum.photos/1280/720">
                    <source src="https://samplelib.com/lib/preview/mp4/sample-5s.mp4" type="video/mp4">
                    Your browser does not support the video tag.
                </video>
            </div>
        </section>

        <section id="gamification" class="gamification">
            <h2>Learn While You Scroll</h2>
            <div class="gamification-grid">
                <div class="gamification-item">
                    <img src="https://picsum.photos/150/150?random=5" alt="Achievements" width="150" height="150">
                    <h3>Achievements</h3>
                    <p>Unlock badges as you progress through your learning journey.</p>
                </div>
                <div class="gamification-item">
                    <img src="https://picsum.photos/150/150?random=6" alt="Points System" width="150" height="150">
                    <h3>Points System</h3>
                    <p>Earn points for completing lessons, quizzes, and daily streaks.</p>
                </div>
                <div class="gamification-item">
                    <img src="https://picsum.photos/150/150?random=7" alt="Leaderboards" width="150" height="150">
                    <h3>Leaderboards</h3>
                    <p>Compete with others and climb the ranks in various categories.</p>
                </div>
            </div>
        </section>

        <section id="quizzes" class="quizzes">
            <h2>Test Your Knowledge</h2>
            <div class="quiz-container">
                <h3 id="question"></h3>
                <div id="options" class="options"></div>
                <p id="result" class="result"></p>
                <button id="next-question" class="cta-button">Next Question</button>
            </div>
        </section>

        <section id="learning" class="learning">
            <h2>Expand Your Skills</h2>
            <div class="learning-container">
                <div class="topics">
                    <button class="topic-button active" data-topic="email">Email Marketing</button>
                    <button class="topic-button" data-topic="content">Content Creation</button>
                    <button class="topic-button" data-topic="speaking">Public Speaking</button>
                </div>
                <div class="topic-content">
                    <div id="email-content" class="content active">
                        <img src="https://picsum.photos/400/300?random=8" alt="Email Marketing" width="400" height="300">
                        <h3>Email Marketing</h3>
                        <p>Learn the art of crafting compelling email campaigns that engage your audience and drive conversions. Discover best practices for subject lines, content creation, and list segmentation.</p>
                        <button class="cta-button">Start Learning</button>
                    </div>
                    <div id="content-content" class="content">
                        <img src="https://picsum.photos/400/300?random=9" alt="Content Creation" width="400" height="300">
                        <h3>Content Creation</h3>
                        <p>Master the skills of creating valuable, engaging content that resonates with your target audience. Explore different content formats, SEO optimization, and storytelling techniques.</p>
                        <button class="cta-button">Start Learning</button>
                    </div>
                    <div id="speaking-content" class="content">
                        <img src="https://picsum.photos/400/300?random=10" alt="Public Speaking" width="400" height="300">
                        <h3>Public Speaking</h3>
                        <p>Develop confidence and charisma in public speaking. Learn strategies for effective communication, audience engagement, and overcoming stage fright.</p>
                        <button class="cta-button">Start Learning</button>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2023 Bloom Scrolling. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>

