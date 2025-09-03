<h1>📸 Focus.Frame — Single-Page Photography Website</h1>

<p><em>Discover the magic of photography in our school!</em></p>

<p>
  <strong>Focus.Frame</strong> is a single-page, fully responsive photography school website
  developed as part of the GoIT Full Stack Developer course.
  The page includes sections for courses, mentors, reviews, contact information,
  and a professional footer.
</p>

<hr />

<h2>🌐 Live Demo</h2>
<p>
  👉 <a href="https://<YOUR_GH_USERNAME>.github.io/goit-focusframe-project/" target="_blank" rel="noopener">GitHub Pages (add link)</a>
</p>

<hr />

<h2>📋 Table of Contents</h2>
<ol>
  <li><a href="#about-the-project">About the Project</a></li>
  <li><a href="#core-features-and-requirements">Core Features &amp; Requirements</a></li>
  <li><a href="#technical-specifications">Technical Specifications</a></li>
  <li><a href="#project-structure-sections">Project Structure (Sections)</a></li>
  <li><a href="#features">Features</a></li>
  <li><a href="#technologies-used">Technologies Used</a></li>
  <li><a href="#team-members">Team Members</a></li>
  <li><a href="#challenges">Challenges</a></li>
  <li><a href="#screenshots">Screenshots</a></li>
  <li><a href="#license">License</a></li>
</ol>

<hr />

<h2 id="about-the-project">📖 About the Project</h2>
<p>
  Focus.Frame simulates a real landing page experience:
</p>
<ul>
  <li>A <strong>Hero</strong> section introducing the school</li>
  <li><strong>Course</strong> cards (Basics, Landscape, Portrait)</li>
  <li><strong>Mentor</strong> profiles</li>
  <li>Student <strong>Reviews</strong></li>
  <li>A <strong>Sign Up</strong> form</li>
  <li>A <strong>Footer</strong> with social links and contact information</li>
</ul>

<hr />

<h2 id="core-features-and-requirements">✨ Core Features and Requirements</h2>

<h3>Layout and Responsiveness 📱💻🖥️</h3>
<ul>
  <li><strong>Mobile:</strong> Responsive from 375px</li>
  <li><strong>Tablet:</strong> Responsive from 768px</li>
  <li><strong>Desktop:</strong> Responsive from 1280px (optional optimization for 1440px)</li>
</ul>

<hr />

<h2 id="technical-specifications">⚙️ Technical Specifications</h2>
<ul>
  <li><strong>Validation:</strong> Must pass HTML/CSS validation:
    <ul>
      <li><a href="https://validator.w3.org/" target="_blank" rel="noopener">validator.w3.org</a></li>
      <li><a href="https://jigsaw.w3.org/css-validator/" target="_blank" rel="noopener">jigsaw.w3.org/css-validator</a></li>
      <li><a href="https://pagespeed.web.dev/" target="_blank" rel="noopener">pagespeed.web.dev</a></li>
    </ul>
  </li>
  <li><strong>Semantics:</strong> Must comply with HTML5 semantic standards</li>
  <li><strong>Fonts:</strong> Must be linked externally</li>
  <li><strong>Image Optimization:</strong>
    <ul>
      <li>Optimized dimensions for vector and raster images</li>
      <li>Support for Retina displays</li>
      <li>Optimized image loading</li>
    </ul>
  </li>
  <li><strong>SVG Icons:</strong> All icons must be linked via a <code>sprite</code></li>
  <li><strong>Favicon:</strong> A favicon image must be added</li>
</ul>

<hr />

<h2 id="project-structure-sections">🏗️ Project Structure (Sections)</h2>

<ul>
  <li><strong>Header:</strong> Includes logo, navigation, and a “Sign Up” link (camera icon on mobile). On mobile, the navigation menu is a fixed <em>dropdown sidebar</em> that fills the viewport height. Header and Hero share a dotted grid PNG background applied to a wrapper.</li>
  <li><strong>Hero:</strong> Heading: “Discover the magic of photography in our school.” Contains descriptive text, student info, and references. The “Our happy students” link redirects to the Reviews section.</li>
  <li><strong>Advertisement:</strong> Single-line heading: “Master your photography skills with us!”</li>
  <li><strong>About Us:</strong> Heading: “About us.” Images must be content images.</li>
  <li><strong>Our Courses:</strong> Heading: “Our courses.” List implemented with <code>&lt;ol&gt;</code>. Each card includes: number + title + description + ⇗ link (redirects to Sign Up).</li>
  <li><strong>Our Mentors:</strong> Heading: “Our Mentors.” List implemented with <code>&lt;ul&gt;</code>. Each card includes: photo (content image) + name + experience.</li>
  <li><strong>Sign Up:</strong> Heading: “Sign up.” The form includes <code>&lt;input pattern&gt;</code>, a <code>&lt;textarea&gt;</code>, and a <code>type="submit"</code> “Send” button.</li>
  <li><strong>Reviews:</strong> Heading: “Reviews.” List implemented with <code>&lt;ul&gt;</code>. Each review card includes: photo + name + status + feedback + rating.</li>
  <li><strong>Footer:</strong> Includes logo, contact info, social links, site links, a required <code>input</code> with <code>pattern</code>, and a “Go” button.
    <ul>
      <li>Phone number implemented with link protocols (<code>tel:</code>)</li>
      <li>Social links implemented with <code>&lt;ul&gt;</code> and open in a new tab:
        <ul>
          <li><a href="https://www.instagram.com/goit.turkiye/" target="_blank" rel="noopener">Instagram</a></li>
          <li><a href="https://m.youtube.com/@GoITTurkey" target="_blank" rel="noopener">YouTube</a></li>
          <li><a href="https://www.facebook.com/people/GOIT-T%C3%BCrkiye/61558036560161/" target="_blank" rel="noopener">Facebook</a></li>
        </ul>
      </li>
      <li>Dotted grid background applied as a PNG image</li>
    </ul>
  </li>
</ul>

<hr />

<h2 id="features">💡 Features</h2>
<ul>
  <li>Fully <strong>responsive</strong> (mobile–tablet–desktop)</li>
  <li><strong>Flexbox</strong> &amp; <strong>CSS Grid</strong> layout</li>
  <li>Semantic HTML structure</li>
  <li>Modern typography and UI styled according to Figma design</li>
  <li>Footer with company info, quick links, and subscription form</li>
</ul>

<hr />

<h2 id="technologies-used">🛠️ Technologies Used</h2>
<ul>
  <li><strong>HTML5</strong> — Semantic structure</li>
  <li><strong>CSS3</strong> — Styling &amp; responsive layout</li>
  <li><strong>Flexbox &amp; CSS Grid</strong> — Page layout</li>
  <li><strong>Git &amp; GitHub</strong> — Version control &amp; collaboration</li>
  <li><strong>Figma</strong> — Design reference</li>
</ul>

<hr />

<h2 id="team-members">👥 Team Members</h2>
<p>This project was developed collaboratively as part of the GoIT group project.</p>

<ul>
  <li><strong>Team Leader:</strong> Emiralp Saka</li>
  <li><strong>Scrum Master:</strong> Esra Aras</li>
</ul>

<p><strong>Section Responsibilities:</strong></p>
<ul>
  <li><strong>Header:</strong> Ayşegül Gök</li>
  <li><strong>Hero:</strong> Esra Aras</li>
  <li><strong>About Us:</strong> Emiralp Saka</li>
  <li><strong>Our Courses:</strong> Ali Kemal Demir</li>
  <li><strong>Our Mentors:</strong> Rıdvan Kesken</li>
  <li><strong>Sign Up:</strong> Nur Seda Ağgünlü</li>
  <li><strong>Reviews:</strong> Gülnihan Yazıcı</li>
  <li><strong>Footer:</strong> Kutluhan Gül</li>
</ul>

<p>
  We collaborated using GitHub branches, Pull Requests, and Trello for task management.  
</p>

<hr />

<h2 id="challenges">🚧 Challenges</h2>
<ul>
  <li>Maintaining <strong>pixel-perfect</strong> alignment with Figma mockups</li>
  <li>Ensuring <strong>responsive</strong> design at all breakpoints</li>
  <li>Keeping fonts, spacing, and icons consistent</li>
  <li>Team coordination and resolving merge conflicts</li>
</ul>

<hr />

<h2 id="screenshots">📸 Screenshots</h2>
<p>
  <img src="./src/images/FocusFrame-1440.png" alt="Focus.Frame - 1440px Desktop Preview" width="100%" />
</p>

<hr />

<h2 id="license">📜 License</h2>
<p>
  This project is created for <strong>educational purposes</strong> under the GoIT Full Stack Developer course.
  <br />© 2024 Focus.Frame — All rights reserved
</p>

