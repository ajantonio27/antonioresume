<template>
  <div class="card my-4">
    <div class="card-body">
      <h5 class="card-title">Skills</h5>
      <ul class="list-group">
        <li class="list-group-item"><strong>Training:</strong> React, Node.js</li>
        <li class="list-group-item"><strong>Seminars:</strong> Web Development Bootcamp, JavaScript for Beginners</li>
        <li class="list-group-item"><strong>Technologies:</strong> HTML, CSS, React, Node.js, Express</li>
        <li class="list-group-item"><strong>Programming Languages:</strong> JavaScript, Python, Java</li>
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

.list-group {
  padding-left: 0;
}

.list-group-item {
  font-size: 1.1rem;
  padding: 18px 20px;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 8px;
  margin-bottom: 12px;
  transition: all 0.3s ease;
}

.list-group-item:hover {
  background-color: #f4f4f4;
  border-color: #007bff;
  box-shadow: 0 4px 12px rgba(0, 123, 255, 0.2);
}

.list-group-item strong {
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
