---
layout: default
title: Home
---

<section class="hero" id="home">
  <div class="container">
    <img src="{{ '/assets/images/kitchen1.jpg' | relative_url }}" alt="Beautiful kitchen with custom cabinets">
    <h2>{{ site.title }}</h2>
    <h3>Transform Your Space</h3>
    <p>At {{ site.title }}, we specialize in creating beautiful, functional kitchen spaces tailored to your lifestyle. From custom cabinetry to premium countertops and stylish windows, we bring your vision to life with expert craftsmanship and attention to detail.</p>
    <a href="{{ '/contact' | relative_url }}" class="cta-button">Get a Free Consultation</a>
  </div>
</section>

<section class="featured-projects" id="projects">
  <div class="container">
    <div class="section-title">
      <h2>Our Recent Projects</h2>
      <p>Browse through some of our latest kitchen transformations</p>
    </div>
    <div class="projects-grid">
      <div class="project-card">
        <img src="{{ '/assets/images/kitchen2.jpg' | relative_url }}" alt="Modern white kitchen">
        <div class="project-info">
          <h3>Modern White Kitchen</h3>
          <p>A sleek, contemporary kitchen featuring custom white cabinets, quartz countertops, and minimalist hardware.</p>
          <a href="#" class="read-more">View Project</a>
        </div>
      </div>
      <div class="project-card">
        <img src="{{ '/assets/images/kitchen3.jpg' | relative_url }}" alt="Traditional cherry kitchen">
        <div class="project-info">
          <h3>Traditional Cherry Kitchen</h3>
          <p>Warm and inviting kitchen with rich cherry cabinets, granite countertops, and classic details.</p>
          <a href="#" class="read-more">View Project</a>
        </div>
      </div>
      <div class="project-card">
        <img src="{{ '/assets/images/kitchen4.jpg' | relative_url }}" alt="Transitional gray kitchen">
        <div class="project-info">
          <h3>Transitional Gray Kitchen</h3>
          <p>The perfect blend of traditional and modern elements with shaker-style gray cabinets and marble-look countertops.</p>
          <a href="#" class="read-more">View Project</a>
        </div>
      </div>
    </div>
  </div>
</section>

{% include services.html %}
{% include about.html %}
{% include contact.html %} 