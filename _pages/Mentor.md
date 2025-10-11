---
layout: archive
title: "Mentor"
permalink: /mentor/
author_profile: true
---

## 👩‍🏫 Students Mentored

<html>
<body>

<div class="student-gallery">

  <!-- ===== Student 1 ===== -->
  <div class="student-card">
    <img src="/images/Mingyang_Mao.jpg" alt="Student 1 photo">
    <div class="student-info">
      <strong>Mingyang Mao</strong><br>
      Ph.D. Student, University of South Florida<br>
    </div>
  </div>

  <!-- ===== Student 2 ===== -->
  <div class="student-card">
    <img src="/images/Boxun-2-225x300.jpg" alt="Student 2 photo">
    <div class="student-info">
      <strong>Boxun Hu</strong><br>
      Ph.D. Student, Johns Hopkins University<br>
    </div>
  </div>

  <!-- ===== Student 3 ===== -->
  <div class="student-card">
    <img src="/images/students/student3.jpg" alt="Student 3 photo">
    <div class="student-info">
      <strong>Chen Pan</strong><br>
      Undergraduate Research Assistant<br>
      <em>Research:</em> Terrain analysis and off-road navigation benchmarking.
    </div>
  </div>

</div>

</body>
</html>

<style>
.student-gallery {
  display: flex;
  flex-wrap: wrap;
  gap: 24px;
  margin-top: 20px;
}
.student-card {
  width: 260px;
  background: #f9f9f9;
  border-radius: 10px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.08);
  overflow: hidden;
  text-align: center;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}
.student-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 4px 10px rgba(0,0,0,0.15);
}
.student-card img {
  width: 100%;
  height: 260px;
  object-fit: cover;
}
.student-info {
  padding: 12px 14px;
  font-size: 0.95rem;
  line-height: 1.4;
}
.student-info strong {
  font-size: 1.05rem;
}
@media (max-width: 768px) {
  .student-gallery {
    flex-direction: column;
    align-items: center;
  }
  .student-card {
    width: 80%;
  }
}
</style>
