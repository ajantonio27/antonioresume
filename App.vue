<script setup>
// Import components
import Profile from './components/Profile.vue'
import Education from './components/Education.vue'
import Skills from './components/Skills.vue'
// import HelloWorld from './components/HelloWorld.vue'
// import TheWelcome from './components/TheWelcome.vue'  // Uncomment if needed
</script>

<template>
  <main>
    <div class="container">
      <h1 class="text-center my-4">My Resume</h1>
      
      <!-- Profile Component -->
      <Profile />
      
      <!-- Education Component -->
      <Education />
      
      <!-- Skills Component -->
      <Skills />
    </div>
  </main>
</template>

<style scoped>
/* Global body styles */
body, html {
  height: 100%;
  margin: 0;
  font-family: 'Arial', sans-serif;
  background-color: #f4f7fc;
  color: #333;
  display: flex;
  justify-content: center;
  align-items: center;
}

/* Main container for resume content */
.container {
  width: 100%;
  max-width: 900px;
  padding: 20px;
  background-color: #fff;
  border-radius: 12px;
  box-shadow: 0 6px 16px rgba(0, 0, 0, 0.1);
}

/* Heading styles */
h1 {
  font-size: 2.5rem;
  color: #2c3e50;
  margin-bottom: 30px;
  text-align: center;
  font-weight: bold;
}

/* Card Styles for each section */
.card {
  border: none;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.05);
  margin-bottom: 20px;
}

.card-body {
  padding: 25px;
  background-color: #f9fafb;
}

.card-title {
  font-size: 1.8rem;
  color: #2c3e50;
  font-weight: bold;
  margin-bottom: 15px;
}

.card-text,
.card-list {
  font-size: 1rem;
  color: #555;
}

/* List group items */
.list-group-item {
  font-size: 1.1rem;
  color: #444;
  padding: 10px 15px;
  border: 1px solid #ddd;
  border-radius: 6px;
  background-color: #f9fafb;
  margin-bottom: 10px;
}

.list-group-item:hover {
  background-color: #eceff1;
}

/* Contact info section styles */
.contact-info {
  margin-top: 20px;
}

.contact-info h6 {
  font-size: 1.5rem;
  font-weight: 700;
  margin-bottom: 15px;
  color: #333;
}

.contact-info ul {
  list-style-type: none;
  padding-left: 0;
}

.contact-info li {
  font-size: 1.1rem;
  color: #555;
  padding: 8px 0;
}

.contact-info a {
  color: #007bff;
  text-decoration: none;
}

.contact-info a:hover {
  text-decoration: underline;
}

.contact-info i {
  color: #007bff;
  margin-right: 10px;
  font-size: 1.3rem;
}

/* Responsive styling for smaller screens */
@media (max-width: 768px) {
  .container {
    padding: 15px;
  }

  .profile-header {
    flex-direction: column;
    align-items: center;
  }

  .profile-img {
    margin-bottom: 15px;
  }
}
</style>
