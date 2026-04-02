---
layout: archive
title: "Mentors & Mentees"
permalink: /mentor/
author_profile: true
---

## 👨‍🏫 Mentors & Collaborators

<html>
<body>

<div class="student-gallery">

  <!-- ===== Amarda Shehu ===== -->
  <div class="student-card">
    <img src="/images/amarda_shehu.jpg" alt="Amarda Shehu photo">
    <div class="student-info">
      <strong>Amarda Shehu</strong><br>
      Professor, George Mason University<br>
    </div>
  </div>

  <!-- ===== David Lattanzi ===== -->
  <div class="student-card">
    <img src="/images/david_lattanzi.jpg" alt="David Lattanzi photo">
    <div class="student-info">
      <strong>David Lattanzi</strong><br>
      Professor, George Mason University<br>
    </div>
  </div>

  <!-- ===== Erion Plaku ===== -->
  <div class="student-card">
    <img src="/images/erion_plaku.png" alt="Erion Plaku photo">
    <div class="student-info">
      <strong>Erion Plaku</strong><br>
      Professor, U.S. National Science Foundation<br>
    </div>
  </div>

  <!-- ===== Xuesu Xiao ===== -->
  <div class="student-card">
    <img src="/images/xuesu_xiao.jpg" alt="Xuesu Xiao photo">
    <div class="student-info">
      <strong>Xuesu Xiao</strong><br>
      Assistant Professor, George Mason University<br>
    </div>
  </div>

  <!-- ===== Nick Hawes ===== -->
  <div class="student-card">
    <img src="/images/nick_hawes.jpg" alt="Nick Hawes photo">
    <div class="student-info">
      <strong>Nick Hawes</strong><br>
      Professor, University of Oxford<br>
    </div>
  </div>

  <!-- ===== Tinoosh Mohsenin ===== -->
  <div class="student-card">
    <img src="/images/tinoosh_mohsenin.png" alt="Tinoosh Mohsenin photo">
    <div class="student-info">
      <strong>Tinoosh Mohsenin</strong><br>
      Professor, Johns Hopkins University<br>
    </div>
  </div>

  <!-- ===== Xiaomin Lin ===== -->
  <div class="student-card">
    <img src="/images/xiaomin.jpg" alt="Xiaomin Lin photo">
    <div class="student-info">
      <strong>Xiaomin Lin</strong><br>
      Assistant Professor, University of South Florida <br>
    </div>
  </div>

  <!-- ===== Chengzhi Mao ===== -->
  <div class="student-card">
    <img src="/images/chengzhimao.png" alt="Chengzhi Mao photo">
    <div class="student-info">
      <strong>Chengzhi Mao</strong><br>
      Assistant Professor, Rutgers University<br>
    </div>
  </div>

</div>

</body>
</html>

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
    <img src="/images/Rithvik.png" alt="Student 3 photo">
    <div class="student-info">
      <strong>Rithvik Jonna</strong><br>
      M.S. student, Johns Hopkins University<br>
    </div>
  </div>



</body>
</html>

<style>
/* ===== Gallery Layout ===== */
.student-gallery {
  display: flex;
  flex-wrap: wrap;
  gap: 28px;
  justify-content: flex-start;
  margin-top: 20px;
}

/* ===== Card Container ===== */
.student-card {
  width: 240px;             /* 固定宽度 */
  height: 340px;            /* 固定总高度 */
  background: #ffffff;
  border-radius: 10px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.08);
  overflow: hidden;
  display: flex;
  flex-direction: column;
  text-align: center;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}
.student-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 6px 14px rgba(0,0,0,0.15);
}

/* ===== Image Section ===== */
.student-card img {
  width: 100%;
  height: 220px;            /* 严格固定图片高度 */
  object-fit: cover;        /* 裁剪保持比例 */
  background: #f7f7f7;
}

/* ===== Text Section ===== */
.student-info {
  flex: 1;                  /* 固定高度剩余填充 */
  padding: 10px 12px;
  font-size: 0.92rem;
  line-height: 1.35;
  color: #333;
}
.student-info strong {
  font-size: 1.02rem;
  color: #000;
}
.student-info em {
  font-style: normal;
  color: #555;
}

/* ===== Responsive ===== */
@media (max-width: 768px) {
  .student-gallery {
    justify-content: center;
  }
  .student-card {
    width: 80%;
    height: auto;
  }
  .student-card img {
    height: 220px;
  }
}
</style>
