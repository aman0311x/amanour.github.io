---
permalink: /
title: "👋 Introduction"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>

/* ---------------- GLOBAL 3D + GLASS STYLE ---------------- */
:root {
  --card-bg: rgba(255, 255, 255, 0.12);
  --card-border: rgba(255, 255, 255, 0.18);
  --glass-blur: blur(14px);
  --radius: 18px;
}

/* Paragraph styling for elegance */
body p {
  line-height: 1.7;
  font-size: 1.05rem;
}


/* ---------------- CARD CONTAINER ---------------- */
.cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 25px;
  margin-top: 25px;
}


/* ---------------- GLASS 3D NEWS CARDS ---------------- */
.card {
  background: var(--card-bg);
  border: 1px solid var(--card-border);
  padding: 22px;
  border-radius: var(--radius);
  backdrop-filter: var(--glass-blur);
  box-shadow: 0 10px 25px rgba(0,0,0,0.22);
  transition: transform .25s ease, box-shadow .25s ease;
}

.card:hover {
  transform: translateY(-10px) scale(1.03);
  box-shadow: 0 18px 40px rgba(0,0,0,0.35);
}


/* ---------------- BUTTON STYLE ---------------- */
.button {
  display: inline-block;
  margin-top: 12px;
  padding: 10px 16px;
  background: linear-gradient(135deg, #333436ff, #6e54ff);
  color: white !important;
  border-radius: 10px;
  font-weight: 600;
  text-decoration: none;
  transition: 0.25s ease;
}

.button:hover {
  transform: scale(1.05);
  box-shadow: 0 6px 18px rgba(0,0,0,0.25);
}


/* ---------------- HEADER TITLE ---------------- */
h2, h3 {
  font-weight: 700;
}

</style>





<div style="border-left: 4px solid #545458ff;text-align: justify ; padding: 18px 22px; margin-top: 15px; line-height: 1.7; font-size: 1.05rem; background: rgba(255,255,255,0.08); border-radius: 10px;">
I began my journey with a deep passion for computer science, which led me to pursue a Bachelor's degree in Computer Science and Engineering at AUST in 2022. From the very beginning of my academic career, I immersed myself in <a href="https://www.stopstalk.com/user/profile/aman0311" target="_blank">competitive programming</a>, sharpening my problem-solving skills and building a solid foundation in algorithms and data structures.<br><br>
Alongside my academic studies, I actively worked on various <a href="https://github.com/aman0311x" target="_blank">projects</a>, experimenting with different programming languages and frameworks. This hands-on experience allowed me to gain practical knowledge in web development and software engineering.<br><br>
However, as I delved deeper into the world of technology, I became increasingly fascinated by the field of Computer Vision, Image Processing, and Explainable AI. Driven by this passion, I decided to shift my focus towards AI research and development.<br><br>
Currently, I am in my final year, specializing in Image Processing for my thesis. I am exploring advanced techniques and working on innovative solutions to push the boundaries of AI in visual recognition and analysis.
</div>

<div style="height: 2cm;"></div>


# 📰 Recent News

<div class="cards">

  <div class="card">
    <h3>🚀 Brain Tumor Detection Pipeline Completed</h3>
    <p><strong>Date:</strong> October 2025</p>
    <p>Developed a YOLO + ViT-GRU hybrid pipeline achieving <strong>98.7% accuracy</strong> with explainability.</p>
    <a href="https://github.com/aman0311x" class="button">View Project →</a>
  </div>

  <div class="card">
    <h3>📝 Dengue Severity Prediction Paper Submitted</h3>
    <p><strong>Date:</strong> November 2025</p>
    <p>Submitted research paper <em>“Causal & Explainable DSS for Dengue Severity Prediction”</em> to ICECTE 2025.</p>
    <a href="#" class="button">View Paper →</a>
  </div>

  <div class="card">
    <h3>🤖 Multimodal CLIP + TinyLLaMA Research</h3>
    <p><strong>Date:</strong> September 2025</p>
    <p>Developing a multimodal CLIP-ViT + TinyLLaMA contrastive learning pipeline.</p>
    <a href="https://github.com/aman0311x" class="button">Roadmap →</a>
  </div>

  <div class="card">
    <h3>🎖 Reviewer Role for IEEE Access</h3>
    <p><strong>Date:</strong> August 2025</p>
    <p>Invited as a reviewer in the fields of Machine Learning & NLP.</p>
    <a href="#" class="button">Reviewer Profile →</a>
  </div>

</div>
