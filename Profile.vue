<template>
  <div class="card my-4">
    <div class="card-body">
      <div class="profile-header">
        <!-- Profile Image -->
        <img src="../assets/pares.png" alt="Profile Picture" class="profile-img" />

        <!-- Profile Information -->
        <div class="profile-info">
          <h5 class="card-title">Profile</h5>
          <p><strong>Objective:</strong> To become a Full Stack Developer</p>
          <p><strong>Name:</strong> Aaron Joseph Antonio</p>
          <p><strong>Course:</strong> Information Technology</p>
          <p><strong>Specialization:</strong> Web Development</p>
        </div>
      </div>

      <!-- Contact Information Section -->
      <div class="contact-info">
        <h6>Contact Information</h6>
        <ul>
          <li><i class="fas fa-envelope"></i> <strong>Email:</strong> <a href="mailto:aaronantonio@gmail.com">aaronantonio@gmail.com</a></li>
          <li><i class="fas fa-phone-alt"></i> <strong>Phone:</strong> <a href="tel:09213891934">09213891934</a></li>
          <li><i class="fab fa-linkedin"></i> <strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/aaronantonio" target="_blank">linkedin.com/in/aaron-antonio</a></li>
          <li><i class="fab fa-github"></i> <strong>GitHub:</strong> <a href="https://github.com/aaronantonio" target="_blank">github.com/aaronantonio</a></li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script setup>
// No additional script needed here
</script>

<style scoped>
.card {
  max-width: 900px;
  margin: 20px auto;
  border-radius: 12px;
  box-shadow: 0 6px 16px rgba(0, 0, 0, 0.15);
  background-color: #fff;
}

.card-body {
  padding: 30px;
  background-color: #fafafa;
  border-radius: 12px;
}

.profile-header {
  display: flex;
  align-items: center;
}

.profile-img {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  margin-right: 20px;
  border: 3px solid #007bff;
  box-shadow: 0 4px 10px rgba(0, 123, 255, 0.15);
}

.profile-info {
  flex: 1;
}

.card-title {
  font-size: 1.75rem;
  color: #333;
  font-weight: 700;
  margin-bottom: 20px;
  letter-spacing: 1px;
}

.card p {
  font-size: 1.1rem;
  line-height: 1.8;
  color: #555;
  margin-bottom: 12px;
}

.card strong {
  color: #007bff;
  font-weight: 600;
}

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

@media (max-width: 768px) {
  .card {
    max-width: 100%;
    margin: 15px;
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
