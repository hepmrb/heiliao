<template>
  <div class="static-page">
    <header class="page-header">
      <h1>欢迎来到我的网站</h1>
      <p>这是一个静态内容演示页面</p>
    </header>

    <section class="features">
      <h2>主要功能</h2>
      <div class="feature-grid">
        <div class="feature-card">
          <h3>简单易用</h3>
          <p>直观的界面设计，轻松上手</p>
        </div>
        <div class="feature-card">
          <h3>响应式布局</h3>
          <p>适配各种设备屏幕尺寸</p>
        </div>
        <div class="feature-card">
          <h3>高性能</h3>
          <p>快速加载，流畅体验</p>
        </div>
      </div>
    </section>

    <section class="gallery">
      <h2>图片展示</h2>
      <div class="image-grid">
        <img src="@/assets/placeholder1.jpg" alt="示例图片1">
        <img src="@/assets/placeholder2.jpg" alt="示例图片2">
        <img src="@/assets/placeholder3.jpg" alt="示例图片3">
      </div>
    </section>

    <footer class="page-footer">
      <p>© 2023 我的网站. 保留所有权利.</p>
    </footer>
  </div>
</template>

<script setup>
// 这是一个纯静态页面，不需要响应式数据
</script>

<style scoped>
.static-page {
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
  font-family: Arial, sans-serif;
  color: #333;
}

.page-header {
  text-align: center;
  padding: 40px 0;
  background-color: #f8f9fa;
  border-radius: 8px;
  margin-bottom: 30px;
}

.page-header h1 {
  font-size: 2.5rem;
  color: #2c3e50;
}

.features {
  margin: 40px 0;
}

.features h2 {
  text-align: center;
  margin-bottom: 30px;
  font-size: 2rem;
}

.feature-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 20px;
}

.feature-card {
  padding: 20px;
  border: 1px solid #eee;
  border-radius: 8px;
  text-align: center;
  transition: transform 0.3s ease;
}

.feature-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 5px 15px rgba(0,0,0,0.1);
}

.gallery {
  margin: 40px 0;
}

.gallery h2 {
  text-align: center;
  margin-bottom: 30px;
  font-size: 2rem;
}

.image-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 15px;
}

.image-grid img {
  width: 100%;
  height: 200px;
  object-fit: cover;
  border-radius: 8px;
}

.page-footer {
  text-align: center;
  padding: 20px;
  margin-top: 50px;
  background-color: #f8f9fa;
  border-radius: 8px;
}
</style>