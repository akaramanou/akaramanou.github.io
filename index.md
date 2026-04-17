---
layout: home
title:  Areti Karamanou
---

<div class="hero-section">
  <div class="hero-content">
    <p class="tagline">PhD Researcher</p>
    <p class="intro">Welcome to my personal website. Here you can find information about my research, publications, and academic work.</p>
    <p>I am a PhD Researcher based in Thessaloniki, Greece, with over 14 years of experience across research institutes (EKETA/ITI), industry, and higher education. My work focuses on Open Government Data, Machine Learning, and Artificial Intelligence in Public Administration, combining strong technical expertise with an in-depth understanding of governmental processes and citizen engagement. I have authored more than 30 publications in these fields and have actively contributed to over 15 European-funded and national research projects.</p>
    
    <!-- CTA Buttons -->
    <div class="cta-buttons">
      <a href="/papers" class="btn btn-primary">View My Publications</a>
      <a href="/projects" class="btn btn-secondary">Explore My Projects</a>
    </div>

    <!-- Research Areas -->
    <div class="research-areas">
      <p class="areas-label">Research Focus:</p>
      <div class="area-tags">
        <span class="tag">GenAI & LLMs</span>
        <span class="tag">Open Government Data</span>
        <span class="tag">Machine Learning</span>
      </div>
    </div>
  </div>
</div>

<!-- Featured Publications Section -->
<section class="featured-section">
  <h2>Featured Publications</h2>
  
  <div class="featured-publications">
    <div class="featured-item">
      <h3>Cardiology Knowledge Assessment of Retrieval-Augmented Open versus Proprietary Large Language Models</h3>
      <p class="publication-meta">PLOS Digital Health, 2026 | IF: 7.7</p>
      <p class="publication-desc">Evaluating the performance of open-source and proprietary LLMs in medical knowledge retrieval and cardiology applications.</p>
      <a href="/papers" class="read-more">View all publications →</a>
    </div>

    <div class="featured-item">
      <h3>Explainable Graph Neural Networks: An Application to Open Statistics Knowledge Graphs for Estimating House Prices</h3>
      <p class="publication-meta">Technologies, 2024 | IF: 4.2</p>
      <p class="publication-desc">Applying explainable AI techniques to linked open data for predictive modeling and interpretable results.</p>
      <a href="/papers" class="read-more">View all publications →</a>
    </div>

    <div class="featured-item">
      <h3>Graph Neural Networks and Open Government Data to Forecast Traffic Flow</h3>
      <p class="publication-meta">Information, 2023 | IF: 2.4</p>
      <p class="publication-desc">Leveraging public data and deep learning to improve transportation forecasting and planning.</p>
      <a href="/papers" class="read-more">View all publications →</a>
    </div>
  </div>

  <div class="view-all-link">
    <a href="/papers" class="btn btn-outline">View All Publications (33 total)</a>
  </div>
</section>

<!-- Quick Links Section -->
<section class="quick-links">
  <h2>Quick Navigation</h2>
  
  <div class="links-grid">
    <div class="link-card">
      <h3>Publications</h3>
      <p>Browse 11 journal articles and 22 conference papers</p>
      <a href="/papers">Explore →</a>
    </div>

    <div class="link-card">
      <h3>Research Projects</h3>
      <p>View active and completed research projects</p>
      <a href="/projects">Discover →</a>
    </div>
    </div>
</section>

<style>
.hero-section {
  text-align: center;
  padding: 4rem 2rem;
  background: linear-gradient(135deg, #F8FAFC 0%, #FFFFFF 100%);
  border-radius: 12px;
  margin-bottom: 3rem;
}

.hero-content h1 {
  font-size: 3rem;
  margin-bottom: 0.5rem;
  color: #0F172A;
  border-bottom: 3px solid #3B82F6;
  padding-bottom: 1rem;
  display: inline-block;
}

.tagline {
  font-size: 1.5rem;
  color: #3B82F6;
  font-weight: 600;
  margin-bottom: 1.5rem;
}

.intro {
  font-size: 1.1rem;
  color: #475569;
  max-width: 600px;
  margin: 0 auto 2rem;
  line-height: 1.8;
}

.cta-buttons {
  display: flex;
  gap: 1rem;
  justify-content: center;
  flex-wrap: wrap;
  margin-bottom: 2.5rem;
}

.btn {
  padding: 0.75rem 1.75rem;
  border-radius: 6px;
  text-decoration: none;
  font-weight: 600;
  font-size: 1rem;
  transition: all 0.2s ease;
  display: inline-block;
  cursor: pointer;
  border: none;
}

.btn-primary {
  background-color: #3B82F6;
  color: white;
}

.btn-primary:hover {
  background-color: #1E40AF;
  transform: translateY(-2px);
  box-shadow: 0 4px 12px rgba(59, 130, 246, 0.3);
}

.btn-secondary {
  background-color: transparent;
  color: #3B82F6;
  border: 2px solid #3B82F6;
}

.btn-secondary:hover {
  background-color: #EFF6FF;
  border-color: #1E40AF;
  color: #1E40AF;
}

.btn-outline {
  background-color: transparent;
  color: #3B82F6;
  border: 2px solid #3B82F6;
  padding: 0.75rem 1.5rem;
}

.btn-outline:hover {
  background-color: #EFF6FF;
  border-color: #1E40AF;
  color: #1E40AF;
}

.research-areas {
  margin-top: 2rem;
}

.areas-label {
  color: #0F172A;
  font-weight: 600;
  margin-bottom: 1rem;
}

.area-tags {
  display: flex;
  gap: 0.75rem;
  justify-content: center;
  flex-wrap: wrap;
}

.tag {
  display: inline-block;
  background-color: #E0E7FF;
  color: #1E40AF;
  padding: 0.5rem 1rem;
  border-radius: 20px;
  font-size: 0.9rem;
  font-weight: 500;
  transition: all 0.2s ease;
}

.tag:hover {
  background-color: #C7D2FE;
  transform: translateY(-1px);
}

.featured-section {
  margin-bottom: 4rem;
}

.featured-section h2 {
  font-size: 2rem;
  color: #0F172A;
  text-align: center;
  margin-bottom: 3rem;
  border-bottom: 3px solid #3B82F6;
  padding-bottom: 1rem;
  display: inline-block;
  width: 100%;
}

.featured-publications {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
  gap: 2rem;
  margin-bottom: 2rem;
}

.featured-item {
  background: #F8FAFC;
  padding: 1.75rem;
  border-radius: 8px;
  border-left: 4px solid #3B82F6;
  transition: all 0.3s ease;
}

.featured-item:hover {
  box-shadow: 0 8px 16px rgba(59, 130, 246, 0.1);
  transform: translateY(-4px);
}

.featured-item h3 {
  font-size: 1.1rem;
  color: #0F172A;
  margin-bottom: 0.75rem;
  line-height: 1.5;
}

.publication-meta {
  color: #64748B;
  font-size: 0.9rem;
  font-weight: 500;
  margin-bottom: 0.75rem;
}

.publication-desc {
  color: #475569;
  font-size: 0.95rem;
  line-height: 1.6;
  margin-bottom: 1rem;
}

.read-more {
  color: #3B82F6;
  text-decoration: none;
  font-weight: 600;
  font-size: 0.95rem;
  transition: color 0.2s ease;
}

.read-more:hover {
  color: #1E40AF;
  text-decoration: underline;
}

.view-all-link {
  text-align: center;
}

.quick-links {
  margin-bottom: 3rem;
}

.quick-links h2 {
  font-size: 2rem;
  color: #0F172A;
  text-align: center;
  margin-bottom: 3rem;
  border-bottom: 3px solid #3B82F6;
  padding-bottom: 1rem;
  display: inline-block;
  width: 100%;
}

.links-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 1.5rem;
}

.link-card {
  background: #FFFFFF;
  border: 2px solid #E2E8F0;
  border-radius: 8px;
  padding: 1.5rem;
  text-align: center;
  transition: all 0.3s ease;
}

.link-card:hover {
  border-color: #3B82F6;
  box-shadow: 0 4px 12px rgba(59, 130, 246, 0.15);
  transform: translateY(-2px);
}

.link-card h3 {
  color: #0F172A;
  margin-bottom: 0.75rem;
}

.link-card p {
  color: #475569;
  font-size: 0.95rem;
  margin-bottom: 1rem;
  line-height: 1.6;
}

.link-card a {
  color: #3B82F6;
  text-decoration: none;
  font-weight: 600;
  transition: color 0.2s ease;
}

.link-card a:hover {
  color: #1E40AF;
}

@media (max-width: 768px) {
  .hero-content h1 {
    font-size: 2rem;
  }

  .tagline {
    font-size: 1.2rem;
  }

  .cta-buttons {
    flex-direction: column;
    align-items: center;
  }

  .btn {
    width: 100%;
    max-width: 300px;
  }

  .area-tags {
    gap: 0.5rem;
  }

  .featured-section h2,
  .quick-links h2 {
    font-size: 1.5rem;
  }
}
</style>

