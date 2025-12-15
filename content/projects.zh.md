---
title: "个人作品"
date: 2025-12-15T20:44:22+08:00
draft: false
---

<style>
.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
  gap: 20px;
  margin-top: 40px;
}

.project-card {
  background: #ffffff;
  border: 1px solid #e5e7eb;
  border-radius: 12px;
  padding: 24px;
  display: flex;
  flex-direction: column;
  transition: all 0.2s ease;
  height: 100%;
  position: relative;
}

.project-card:hover {
  border-color: #9ca3af;
  transform: translateY(-2px);
}

.project-header {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  margin-bottom: 12px;
}

.project-title {
  font-size: 1.5rem;
  font-weight: 700;
  color: #111827;
  margin: 0;
  line-height: 1.2;
  letter-spacing: -0.02em;
}

.project-links {
  display: flex;
  gap: 10px;
  flex-shrink: 0;
  margin-left: 12px;
  padding-top: 4px; /* Align with title */
}

.btn-link {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  color: #6b7280;
  text-decoration: none !important;
  transition: color 0.2s;
}

.btn-link:hover {
  color: #111827;
}

.icon {
  width: 22px;
  height: 22px;
  stroke-width: 2px;
}

.project-desc {
  color: #4b5563;
  font-size: 1.1rem;
  line-height: 1.5;
  margin-bottom: 20px;
  flex-grow: 1;
}

.project-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 6px;
  margin-top: auto;
  line-height: 1;
}

.tag {
  background: #f3f4f6;
  color: #4b5563;
  font-size: 0.7rem;
  font-weight: 600;
  padding: 8px;
  border-radius: 4px;
  letter-spacing: 0.02em;
  text-transform: uppercase;
}

/* Dark mode overrides */
[data-dark-mode] .project-card {
  background: #1f2937;
  border-color: #374151;
}
[data-dark-mode] .project-card:hover {
  border-color: #6b7280;
}
[data-dark-mode] .project-title {
  color: #f9fafb;
}
[data-dark-mode] .project-desc {
  color: #9ca3af;
}
[data-dark-mode] .tag {
  background: #374151;
  color: #e5e7eb;
}
[data-dark-mode] .btn-link {
  color: #9ca3af;
}
[data-dark-mode] .btn-link:hover {
  color: #f3f4f6;
}
</style>

<div class="project-grid">
  <!-- Nuxt-Mkdirs -->
  <div class="project-card">
    <div class="project-header">
      <h3 class="project-title">Nuxt-Mkdirs</h3>
      <div class="project-links">
        <a href="https://github.com/PBHAHAHA" target="_blank" class="btn-link" aria-label="GitHub">
          <svg class="icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"><path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"></path></svg>
        </a>
        <a href="https://nuxt-mkdirs.com" target="_blank" class="btn-link" aria-label="Website">
          <svg class="icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"></path><polyline points="15 3 21 3 21 9"></polyline><line x1="10" y1="14" x2="21" y2="3"></line></svg>
        </a>
      </div>
    </div>
    <p class="project-desc">Nuxt 4 目录网站模板。包含支付集成、博客系统和响应式布局。</p>
    <div class="project-tags">
      <span class="tag">Nuxt 4</span>
      <span class="tag">Vue</span>
      <span class="tag">Template</span>
    </div>
  </div>
  
  <!-- iWali -->
  <div class="project-card">
    <div class="project-header">
      <h3 class="project-title">iWali</h3>
      <div class="project-links">
        <a href="https://github.com/PBHAHAHA" target="_blank" class="btn-link" aria-label="GitHub">
          <svg class="icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"><path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"></path></svg>
        </a>
        <a href="https://iwali.cn" target="_blank" class="btn-link" aria-label="Website">
          <svg class="icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"></path><polyline points="15 3 21 3 21 9"></polyline><line x1="10" y1="14" x2="21" y2="3"></line></svg>
        </a>
      </div>
    </div>
    <p class="project-desc">AI 智能周报生成器。利用人工智能帮助你总结工作和规划未来。</p>
    <div class="project-tags">
      <span class="tag">AI</span>
      <span class="tag">NestJS</span>
      <span class="tag">Nuxt</span>
    </div>
  </div>

  <!-- Herbs Insight -->
  <div class="project-card">
    <div class="project-header">
      <h3 class="project-title">Herbs Insight</h3>
      <div class="project-links">
        <a href="https://github.com/PBHAHAHA" target="_blank" class="btn-link" aria-label="GitHub">
          <svg class="icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"><path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"></path></svg>
        </a>
        <a href="https://www.herbsinsight.com/" target="_blank" class="btn-link" aria-label="Website">
          <svg class="icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"></path><polyline points="15 3 21 3 21 9"></polyline><line x1="10" y1="14" x2="21" y2="3"></line></svg>
        </a>
      </div>
    </div>
    <p class="project-desc">探索草本世界。药用植物、功效及传统用途的综合指南。</p>
    <div class="project-tags">
      <span class="tag">Nuxt</span>
      <span class="tag">Health</span>
      <span class="tag">Directory</span>
    </div>
  </div>
</div>
