
  font-weight: bold;
}

.logo i {
  font-size: 1.8rem;
}

.nav-links {
  display: flex;
  gap: 2rem;
}

.nav-links a {
  color: #8892b0;
  text-decoration: none;
  transition: color 0.3s;
  position: relative;
}

.nav-links a:hover,
.nav-links a.active {
  color: #64ffda;
}

.nav-links a::after {
  content: '';
  position: absolute;
  bottom: -5px;
  left: 0;
  width: 0;
  height: 2px;
  background: #64ffda;
  transition: width 0.3s;
}

.nav-links a:hover::after,
.nav-links a.active::after {
  width: 100%;
}

.theme-toggle {
  color: #8892b0;
  cursor: pointer;
  transition: color 0.3s;
}

.theme-toggle:hover {
  color: #64ffda;
}

/* Features Section */
.features {
  margin-top: 4rem;
  padding: 2rem 0;
}

.features h2 {
  text-align: center;
  color: #64ffda;
  margin-bottom: 2rem;
  font-size: 2rem;
}

.feature-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
  padding: 1rem;
}

.feature-card {
  background: rgba(10, 25, 47, 0.8);
  padding: 2rem;
  border-radius: 15px;
  text-align: center;
  border: 1px solid rgba(100, 255, 218, 0.1);
  transition: transform 0.3s, box-shadow 0.3s;
}

.feature-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
}

.feature-card i {
  font-size: 2.5rem;
  color: #64ffda;
  margin-bottom: 1rem;
}

.feature-card h3 {
  color: #e6f1ff;
  margin-bottom: 1rem;
}

.feature-card p {
  color: #8892b0;
}

/* Footer Styles */
footer {
  background: rgba(10, 25, 47, 0.9);
  color: #8892b0;
  padding: 3rem 0 1rem;
  margin-top: 4rem;
}

.footer-content {
  max-width: 1200px;
  margin: 0 auto;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
  padding: 0 2rem;
}

.footer-section h3 {
  color: #64ffda;
  margin-bottom: 1rem;
}

.footer-section ul {
  list-style: none;
}

.footer-section ul li {
  margin-bottom: 0.5rem;
}

.footer-section a {
  color: #8892b0;
  text-decoration: none;
  transition: color 0.3s;
}

.footer-section a:hover {
  color: #64ffda;
}

.social-links {
  display: flex;
  gap: 1rem;
  margin-top: 1rem;
}

.social-links a {
  color: #8892b0;
  font-size: 1.5rem;
  transition: color 0.3s;
}

.social-links a:hover {
  color: #64ffda;
}

.footer-bottom {
  text-align: center;
  margin-top: 2rem;
  padding-top: 2rem;
  border-top: 1px solid rgba(100, 255, 218, 0.1);
}

/* Light Theme Styles */
body.light-theme {
  background: linear-gradient(135deg, #f0f7ff 0%, #e6f1ff 100%);
  color: #1a1a1a;
}

body.light-theme .chat-container {
  background: rgba(255, 255, 255, 0.9);
  border: 1px solid rgba(0, 0, 0, 0.1);
}

body.light-theme .message.coach {
  background: rgba(100, 255, 218, 0.1);
  border: 1px solid rgba(0, 0, 0, 0.1);
}

body.light-theme .message.user {
  background: rgba(0, 0, 0, 0.05);
  border: 1px solid rgba(0, 0, 0, 0.1);
}

body.light-theme #user-input {
  background: rgba(255, 255, 255, 0.8);
  border: 1px solid rgba(0, 0, 0, 0.2);
  color: #1a1a1a;
}

body.light-theme #user-input::placeholder {
  color: #666;
}

body.light-theme .navbar {
  background: rgba(255, 255, 255, 0.9);
  border-bottom: 1px solid rgba(0, 0, 0, 0.1);
}

body.light-theme .nav-links a {
  color: #666;
}

body.light-theme .nav-links a:hover,
body.light-theme .nav-links a.active {
  color: #1a1a1a;
}

body.light-theme .theme-toggle {
  color: #666;
}

body.light-theme .theme-toggle:hover {
  color: #1a1a1a;
}

body.light-theme .feature-card {
  background: rgba(255, 255, 255, 0.9);
  border: 1px solid rgba(0, 0, 0, 0.1);
}

body.light-theme .feature-card h3 {
  color: #1a1a1a;
}

body.light-theme .feature-card p {
  color: #666;
}

body.light-theme footer {
  background: rgba(255, 255, 255, 0.9);
  border-top: 1px solid rgba(0, 0, 0, 0.1);
}

body.light-theme .footer-section h3 {
  color: #1a1a1a;
}

body.light-theme .footer-section a {
  color: #666;
}

body.light-theme .footer-section a:hover {
  color: #1a1a1a;
}

body.light-theme .social-links a {
  color: #666;
}

body.light-theme .social-links a:hover {
  color: #1a1a1a;
}

body.light-theme .footer-bottom {
  border-top: 1px solid rgba(0, 0, 0, 0.1);
}

/* Animation Classes */
.animate-fade-in {
  opacity: 0;
  animation: fadeIn 1s ease forwards;
}

.animate-fade-in-delay {
  opacity: 0;
  animation: fadeIn 1s ease forwards 0.5s;
}

.animate-slide-up {
  opacity: 0;
  transform: translateY(50px);
  animation: slideUp 1s ease forwards;
}

.animate-slide-left {
  opacity: 0;
  transform: translateX(-50px);
  animation: slideLeft 1s ease forwards;
}

.animate-slide-right {
  opacity: 0;
  transform: translateX(50px);
  animation: slideRight 1s ease forwards;
}

.animate-count-up {
  opacity: 0;
  animation: countUp 2s ease forwards;
}

@keyframes fadeIn {
  to {
    opacity: 1;
  }
}

@keyframes slideUp {
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

@keyframes slideLeft {
  to {
    opacity: 1;
    transform: translateX(0);
  }
}

@keyframes slideRight {
  to {
    opacity: 1;
    transform: translateX(0);
  }
}

@keyframes countUp {
  to {
    opacity: 1;
  }
}

/* About Page Styles */
.about-hero {
  text-align: center;
  padding: 4rem 0;
}

.about-hero h1 {
  font-size: 3rem;
  margin-bottom: 1rem;
}

.about-content {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  margin: 4rem 0;
}

.about-card {
  background: rgba(10, 25, 47, 0.8);
  padding: 2rem;
  border-radius: 15px;
  text-align: center;
  border: 1px solid rgba(100, 255, 218, 0.1);
  transition: transform 0.3s, box-shadow 0.3s;
}

.about-card:hover {
  transform: translateY(-10px);
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
}

.about-icon {
  font-size: 3rem;
  color: #64ffda;
  margin-bottom: 1rem;
}

.timeline {
  margin: 4rem 0;
}

.timeline h2 {
  text-align: center;
  margin-bottom: 3rem;
}

.timeline-container {
  position: relative;
  max-width: 800px;
  margin: 0 auto;
}

.timeline-container::before {
  content: '';
  position: absolute;
  width: 2px;
  background: #64ffda;
  top: 0;
  bottom: 0;
  left: 50%;
  transform: translateX(-50%);
}

.timeline-item {
  padding: 2rem;
  position: relative;
  width: 50%;
  margin-bottom: 2rem;
}

.timeline-item:nth-child(odd) {
  left: 0;
}

.timeline-item:nth-child(even) {
  left: 50%;
}

.timeline-date {
  position: absolute;
  top: 0;
  font-size: 1.2rem;
  font-weight: bold;
  color: #64ffda;
}

.timeline-content {
  background: rgba(10, 25, 47, 0.8);
  padding: 1.5rem;
  border-radius: 10px;
  border: 1px solid rgba(100, 255, 218, 0.1);
}

.stats {
  margin: 4rem 0;
}

.stats h2 {
  text-align: center;
  margin-bottom: 3rem;
}

.stats-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 2rem;
}

.stat-card {
  text-align: center;
  padding: 2rem;
  background: rgba(10, 25, 47, 0.8);
  border-radius: 15px;
  border: 1px solid rgba(100, 255, 218, 0.1);
}

.stat-card i {
  font-size: 2.5rem;
  color: #64ffda;
  margin-bottom: 1rem;
}

.stat-card h3 {
  font-size: 2rem;
  margin-bottom: 0.5rem;
}

/* Contact Page Styles */
.contact-hero {
  text-align: center;
  padding: 4rem 0;
}

.contact-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 4rem;
  margin: 4rem 0;
}

.contact-info {
  display: flex;
  flex-direction: column;
  gap: 2rem;
}

.info-card {
  background: rgba(10, 25, 47, 0.8);
  padding: 2rem;
  border-radius: 15px;
  text-align: center;
  border: 1px solid rgba(100, 255, 218, 0.1);
  transition: transform 0.3s;
}

.info-card:hover {
  transform: translateY(-5px);
}

.info-card i {
  font-size: 2.5rem;
  color: #64ffda;
  margin-bottom: 1rem;
}

.contact-form {
  background: rgba(10, 25, 47, 0.8);
  padding: 2rem;
  border-radius: 15px;
  border: 1px solid rgba(100, 255, 218, 0.1);
}

.form-group {
  margin-bottom: 1.5rem;
}

.form-group label {
  display: block;
  margin-bottom: 0.5rem;
  color: #64ffda;
}

.form-group input,
.form-group textarea {
  width: 100%;
  padding: 0.8rem;
  background: rgba(10, 25, 47, 0.5);
  border: 1px solid rgba(100, 255, 218, 0.2);
  border-radius: 5px;
  color: #e6f1ff;
  transition: border-color 0.3s;
}

.form-group input:focus,
.form-group textarea:focus {
  outline: none;
  border-color: #64ffda;
}

.submit-btn {
  background: linear-gradient(135deg, #64ffda 0%, #1e90ff 100%);
  color: #0a192f;
  border: none;
  padding: 1rem 2rem;
  border-radius: 5px;
  cursor: pointer;
  display: flex;
  align-items: center;
  gap: 0.5rem;
  font-weight: bold;
  transition: transform 0.3s, box-shadow 0.3s;
}

.submit-btn:hover {
  transform: translateY(-2px);
  box-shadow: 0 5px 15px rgba(100, 255, 218, 0.3);
}

.submit-btn:active {
  transform: translateY(0);
}

.faq-section {
  margin: 4rem 0;
}

.faq-section h2 {
  text-align: center;
  margin-bottom: 3rem;
}

.faq-container {
  max-width: 800px;
  margin: 0 auto;
}

.faq-item {
  background: rgba(10, 25, 47, 0.8);
  border-radius: 10px;
  margin-bottom: 1rem;
  border: 1px solid rgba(100, 255, 218, 0.1);
  overflow: hidden;
}

.faq-question {
  padding: 1.5rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
  cursor: pointer;
}

.faq-question h3 {
  margin: 0;
}

.faq-question i {
  transition: transform 0.3s;
}

.faq-item.active .faq-question i {
  transform: rotate(180deg);
}

.faq-answer {
  padding: 0 1.5rem;
  max-height: 0;
  overflow: hidden;
  transition: max-height 0.3s ease-out;
}

.faq-item.active .faq-answer {
  padding: 1.5rem;
  max-height: 500px;
}

/* Responsive Design */
@media (max-width: 768px) {
  .timeline-container::before {
    left: 30px;
  }

  .timeline-item {
    width: 100%;
    padding-left: 70px;
    padding-right: 25px;
  }

  .timeline-item:nth-child(even) {
    left: 0;
  }

  .timeline-date {
    left: 0;
  }
}

/* Comic Script Formatting */
.panel-header {
  font-weight: bold;
  color: #64ffda;
  margin: 1rem 0 0.5rem;
  padding: 0.5rem;
  background: rgba(100, 255, 218, 0.1);
  border-left: 3px solid #64ffda;
}

.character-line {
  font-weight: bold;
  color: #1e90ff;
  margin: 0.5rem 0;
  padding-left: 1rem;
}

.dialogue-line {
  margin: 0.5rem 0;
  padding-left: 2rem;
  font-style: italic;
}

.sfx-line {
  font-weight: bold;
  color: #ff6b6b;
  margin: 0.5rem 0;
  padding-left: 1rem;
  text-transform: uppercase;
}

.description-line {
  color: #8892b0;
  margin: 0.5rem 0;
  padding-left: 1rem;
  font-size: 0.9em;
}

/* Light Theme Comic Script Formatting */
body.light-theme .panel-header {
  background: rgba(100, 255, 218, 0.1);
  color: #1a1a1a;
  border-left: 3px solid #1a1a1a;
}

body.light-theme .character-line {
  color: #1a1a1a;
}

body.light-theme .sfx-line {
  color: #d32f2f;
}

body.light-theme .description-line {
  color: #666;
}

/* Travel Packing List Formatting */
.category-header {
  font-weight: bold;
  color: #64ffda;
  margin: 1.5rem 0 0.5rem;
  padding: 0.5rem;
  background: rgba(100, 255, 218, 0.1);
  border-left: 3px solid #64ffda;
  border-radius: 0 5px 5px 0;
}

.item-line {
  margin: 0.5rem 0;
  padding: 0.5rem 1rem;
  display: flex;
  align-items: center;
  background: rgba(100, 255, 218, 0.05);
  border-radius: 5px;
}

.item-line::before {
  content: "✓";
  color: #64ffda;
  margin-right: 0.5rem;
  font-weight: bold;
}

.tip-line {
  color: #1e90ff;
  margin: 0.5rem 0;
  padding: 0.5rem 1rem;
  font-style: italic;
  background: rgba(30, 144, 255, 0.05);
  border-radius: 5px;
}

.weather-line {
  color: #ff6b6b;
  margin: 0.5rem 0;
  padding: 0.5rem 1rem;
  font-weight: bold;
  background: rgba(255, 107, 107, 0.05);
  border-radius: 5px;
}

/* Light Theme Packing List Styles */
body.light-theme .category-header {
  background: rgba(100, 255, 218, 0.1);
  color: #1a1a1a;
  border-left: 3px solid #1a1a1a;
}

body.light-theme .item-line {
  background: rgba(0, 0, 0, 0.05);
}

body.light-theme .item-line::before {
  color: #1a1a1a;
}

body.light-theme .tip-line {
  color: #1a1a1a;
  background: rgba(0, 0, 0, 0.05);
}

body.light-theme .weather-line {
  color: #d32f2f;
  background: rgba(211, 47, 47, 0.05);
}

/* Download Section Styles */
.download-section {
  text-align: center;
  margin: 2rem 0;
  padding: 1rem;
}

.download-btn {
  background: linear-gradient(135deg, #64ffda 0%, #1e90ff 100%);
  color: #0a192f;
  border: none;
  padding: 1rem 2rem;
  border-radius: 5px;
  cursor: pointer;
  font-size: 1.1rem;
  font-weight: bold;
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  transition: transform 0.3s, box-shadow 0.3s;
  margin: 2rem 0;
}

.download-btn:hover {
  transform: translateY(-2px);
  box-shadow: 0 5px 15px rgba(100, 255, 218, 0.3);
}

.download-btn:active {
  transform: translateY(0);
}

.download-btn i {
  font-size: 1.2rem;
}

/* Light Theme Download Button */
body.light-theme .download-btn {
  background: linear-gradient(135deg, #1e90ff 0%, #64ffda 100%);
  color: #ffffff;
}
