---
hide:
  - navigation
  - toc
---

<div class="home-hero">
  <p class="home-eyebrow">KNOWLEDGE BASE</p>
  <h1 class="home-title">Joey's Notes</h1>
  <p class="home-subtitle">A personal collection of study notes on GPU programming, deep learning, and computer vision.</p>
</div>

---

## Notes

<div class="topic-grid">

<div class="topic-card">
  <div class="topic-label">ACTIVE</div>
  <h3>Programming Massively Parallel Processors</h3>
  <p>Chapter-by-chapter notes on CUDA programming — memory coalescing,
  shared memory tiling, warp execution, and kernel optimization.
  Based on the 4th edition (Kirk &amp; Hwu).</p>
  <a href="PMPP/" class="md-button">Start Reading</a>
</div>

<div class="topic-card topic-card--empty">
  <div class="topic-label">COMING SOON</div>
  <h3>Deep Learning</h3>
</div>

<div class="topic-card topic-card--empty">
  <div class="topic-label">COMING SOON</div>
  <h3>3D Vision</h3>
</div>

</div>

<style>
.home-hero {
  text-align: center;
  padding: 4rem 1rem 2.5rem;
}

.home-eyebrow {
  font-size: 0.7rem;
  letter-spacing: 0.22em;
  color: var(--md-default-fg-color--light);
  margin-bottom: 1rem;
  font-weight: 600;
}

.home-title {
  font-size: 2.2rem;
  font-weight: 700;
  letter-spacing: -0.02em;
  margin: 0 0 0.75rem;
  border: none;
  color: var(--md-default-fg-color);
}

.home-subtitle {
  font-size: 0.95rem;
  color: var(--md-default-fg-color--light);
  margin: 0 auto;
  max-width: 480px;
  line-height: 1.7;
}

.md-content hr {
  margin: 2.5rem 0 1.5rem;
  border-color: var(--md-default-fg-color--lightest);
}

.topic-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 1px;
  background: var(--md-default-fg-color--lightest);
  border: 1px solid var(--md-default-fg-color--lightest);
  border-radius: 6px;
  overflow: hidden;
  margin: 1rem 0 2rem;
}

.topic-card {
  background: var(--md-default-bg-color);
  padding: 1.6rem 1.8rem 1.4rem;
}

.topic-card--empty {
  opacity: 0.4;
}

.topic-card h3 {
  font-size: 0.95rem;
  font-weight: 600;
  margin: 0.25rem 0 0.6rem;
  color: var(--md-default-fg-color);
}

.topic-card p {
  font-size: 0.83rem;
  color: var(--md-default-fg-color--light);
  line-height: 1.7;
  margin: 0 0 1.1rem;
}

.topic-label {
  font-size: 0.62rem;
  font-weight: 700;
  letter-spacing: 0.12em;
  color: var(--md-primary-fg-color);
  margin-bottom: 0.3rem;
}

.topic-card--empty .topic-label {
  color: var(--md-default-fg-color--light);
}

.topic-card .md-button {
  font-size: 0.75rem;
  padding: 0.4rem 1rem;
  display: inline-block;
  margin-top: 0.4rem;
}

@media (max-width: 600px) {
  .home-title { font-size: 1.7rem; }
  .topic-grid { grid-template-columns: 1fr; }
}
</style>