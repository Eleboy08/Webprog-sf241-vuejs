<template>
  <div class="container">
    <header>
      <h1>Personal Profile Web Page</h1>
    </header>

    <main>
      <section class="main-content">
        <div class="card">
          <h3>1. About Me</h3>
          <p>Hello! I'm [Your Name], a passionate student at Asia Pacific College. I love solving problems through code and design.</p>
        </div>

        <div class="card">
          <h3>2. Education / Achievements</h3>
          <ul>
            <li>High School Graduate - [School Name] (With Honors)</li>
            <li>Dean's Lister - First Semester 2024</li>
          </ul>
        </div>

        <div class="card">
          <h3>3. Course</h3>
          <p>Bachelor of Science in Information Technology (BSIT)</p>
          <p>Specialization: Mobile and Web Application Development</p>
        </div>

        <div class="card">
          <h3>4. IT Experience</h3>
          <ul>
            <li>Languages: HTML, CSS, JavaScript, Vue.js</li>
            <li>Projects: Portfolio Website, Basic Inventory System</li>
          </ul>
        </div>

        <div class="card">
          <h3>5. Hobbies & Interests</h3>
          <div class="tags">
            <span>Coding</span> <span>Gaming</span> <span>Photography</span> <span>Travel</span>
          </div>
        </div>

        <div class="card">
          <h3>6. Goals In Life / Dream</h3>
          <p>To become a Full-Stack Developer and build software that makes a positive impact on the community.</p>
        </div>

        <div class="card">
          <h3>7. Picture Gallery</h3>
          <div class="gallery-placeholder">
            <div class="img-box">Image 1</div>
            <div class="img-box">Image 2</div>
            <div class="img-box">Image 3</div>
          </div>
        </div>
      </section>

      <aside class="sidebar">
        <div class="profile-pic">
           <div class="avatar">👤</div>
        </div>
        <div class="contact-info">
          <h4>Contact Details</h4>
          <p>📧 email@apc.edu.ph</p>
          <p>📍 Makati City, Philippines</p>
          <hr>
          <p><strong>Skills:</strong> Vue.js, Node.js, Git</p>
        </div>
      </aside>
    </main>

    <footer>
      <p>Asia Pacific College &copy; 2025</p>
    </footer>
  </div>
</template>

<script setup>
// You can add your logic here later!
</script>

<style scoped>
/* Scoped styles ensure they don't leak into other components */

.container {
  max-width: 1200px;
  margin: 0 auto;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  color: #333;
  background-color: #f4f7f6;
  padding: 20px;
}

header {
  text-align: center;
  padding: 40px 0;
  background: #003366; /* APC Blue */
  color: white;
  border-radius: 8px 8px 0 0;
  margin-bottom: 20px;
}

main {
  display: grid;
  grid-template-columns: 2fr 1fr; /* 2 parts content, 1 part sidebar */
  gap: 20px;
}

/* Responsive for mobile */
@media (max-width: 768px) {
  main {
    grid-template-columns: 1fr;
  }
}

.main-content {
  display: flex;
  flex-direction: column;
  gap: 20px;
}

.card {
  background: white;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  border-left: 5px solid #ffcc00; /* APC Yellow accent */
}

.sidebar {
  background: white;
  padding: 20px;
  border-radius: 8px;
  height: fit-content;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
}

.avatar {
  font-size: 80px;
  text-align: center;
  background: #eee;
  border-radius: 50%;
  width: 120px;
  height: 120px;
  margin: 0 auto 20px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.tags span {
  background: #e0e0e0;
  padding: 5px 12px;
  border-radius: 20px;
  margin-right: 5px;
  font-size: 0.9rem;
}

.gallery-placeholder {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 10px;
}

.img-box {
  background: #ddd;
  height: 100px;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 4px;
}

footer {
  margin-top: 30px;
  text-align: center;
  padding: 20px;
  font-weight: bold;
  border-top: 1px solid #ccc;
}
</style>