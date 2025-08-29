<template>
  <div class="card my-4">
    <div class="card-body">
      <h5 class="card-title">Education</h5>
      <ul class="education-list">
        <li><strong>Elementary:</strong> Balut Elementary School</li>
        <li><strong>JHS/SHS:</strong> Tomas Del Rosario College / Holy Angel University</li>
        <li><strong>College:</strong> Holy Angel University - Information Technology</li>
      </ul>
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

.card-title {
  font-size: 1.75rem;
  color: #333;
  font-weight: 700;
  margin-bottom: 20px;
  letter-spacing: 1px;
}

.education-list {
  list-style-type: none;
  padding-left: 0;
}

.education-list li {
  font-size: 1.1rem;
  color: #555;
  padding: 12px 0;
  border-bottom: 1px solid #ddd;
}

.education-list li:last-child {
  border-bottom: none;
}

.education-list strong {
  color: #007bff;
  font-weight: 600;
}

@media (max-width: 768px) {
  .card {
    max-width: 100%;
    margin: 15px;
  }
}
</style>
