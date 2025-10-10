---
layout: archive
title: ""
permalink: /publications/
author_profile: true
googlescholar: https://scholar.google.com/citations?user=BVwGPdQAAAAJ&hl=en
---

<div class="content-container">
  <div id="pub-container">
    <h1 class="subtitle">Publications
    (
      <a id="publication-by-selected" href="javascript:;" onClick="publicationBySelected();">show selected</a> /
      <a id="publication-by-date" href="javascript:;" onClick="publicationByDate();">show all by date</a> /
      <a id="publication-by-topic" href="javascript:;" onClick="publicationByTopic();">show all by topic</a>
    )
    </h1>

    <p class="subtitle-aux"><b>Topics:</b>
      <a href="#topic-motion-planning" onClick="return publicationByTopicSpecific(this)" data-topic="motion-planning">Motion Planning</a> /
      <a href="#topic-learning-based-navigation" onClick="return publicationByTopicSpecific(this)" data-topic="learning-based-navigation">Learning-based Navigation</a> /
      <a href="#topic-benchmarks-datasets" onClick="return publicationByTopicSpecific(this)" data-topic="benchmarks-datasets">Benchmarks & Datasets</a> /
      <a href="#topic-machine-learning" onClick="return publicationByTopicSpecific(this)" data-topic="machine-learning">Machine Learning</a>
      <br />
    </p>

    <div id="pub-card-container" class="activated hide">

      <!-- ========== 2026 ========== -->
      <!-- ICRA 2026 (under review) -->
      <div class="pub-card" data-topic="learning-based-navigation" data-year="2026" data-selected="true">
        <div class="paper-box">
          <div class="paper-box-image">
            <div>
              <div class="badge">ICRA 2026</div>
              <img src="/images/pubs/adp.gif" alt="Adaptive Dynamics Planning teaser">
            </div>
          </div>
          <div class="paper-box-text" markdown="1">
            <div class="title">Adaptive Dynamics Planning for Robot Navigation</div>
            <div class="meta">Y. Lu, L. Wang, T. Xu, X. Xiao — under review at IEEE ICRA 2026</div>
            将自适应动力学建模与学习型局部规划器结合，在受限环境中实现高效、稳健的导航。
            <p class="links">
              <a href="https://arxiv.org/pdf/2510.05330" target="_blank">paper</a>
            </p>
          </div>
        </div>
      </div>

      <!-- ========== 2025 ========== -->
      <!-- IROS 2025 (accepted) -->
      <div class="pub-card" data-topic="motion-planning" data-year="2025" data-selected="true">
        <div class="paper-box">
          <div class="paper-box-image">
            <div>
              <div class="badge">IROS 2025</div>
              <img src="/images/pubs/ddp.png" alt="Decremental Dynamics Planning teaser">
            </div>
          </div>
          <div class="paper-box-text" markdown="1">
            <div class="title">Decremental Dynamics Planning for Robot Navigation</div>
            <div class="meta">Y. Lu, T. Xu, L. Wang, N. Hawes, X. Xiao — IROS 2025 (accepted)</div>
            分层动态重配置，实现面向实时导航的高效再规划。
            <p class="links">
              <a href="https://arxiv.org/pdf/2503.20521" target="_blank">paper</a>
            </p>
          </div>
        </div>
      </div>

      <!-- ICRA 2025 (BARN Challenge Competition Track) -->
      <div class="pub-card" data-topic="motion-planning" data-year="2025" data-selected="true">
        <div class="paper-box">
          <div class="paper-box-image">
            <div>
              <div class="badge">ICRA 2025 (BARN)</div>
              <img src="/images/pubs/barn.gif" alt="BARN challenge teaser">
            </div>
          </div>
          <div class="paper-box-text" markdown="1">
            <div class="title">Autonomous Ground Navigation in Highly Constrained Spaces: Lessons Learned from the Fourth BARN Challenge at ICRA 2025</div>
            <div class="meta">Y. Lu, et al. — ICRA 2025, Competition Track</div>
            大规模受限空间导航基准中的方法总结与经验分析。
            <p class="links">
              <a href="https://cs.gmu.edu/~xiao/papers/barn25_report.pdf" target="_blank">paper</a>
            </p>
          </div>
        </div>
      </div>

      <!-- IROS 2025 (accepted) Reward Training Wheels -->
      <div class="pub-card" data-topic="learning-based-navigation" data-year="2025" data-selected="true">
        <div class="paper-box">
          <div class="paper-box-image">
            <div>
              <div class="badge">IROS 2025</div>
              <img src="/images/pubs/rtw.png" alt="Reward Training Wheels teaser">
            </div>
          </div>
          <div class="paper-box-text" markdown="1">
            <div class="title">Reward Training Wheels: Adaptive Auxiliary Rewards for Robotics Reinforcement Learning</div>
            <div class="meta">L. Wang, T. Xu, Y. Lu, X. Xiao — IROS 2025 (accepted)</div>
            自适应辅助奖励整形，并在训练后自动退场，避免策略退化。
            <p class="links">
              <a href="https://arxiv.org/pdf/2503.15724" target="_blank">paper</a>
            </p>
          </div>
        </div>
      </div>

      <!-- arXiv 2025 Multi-goal ML + Sampling -->
      <div class="pub-card" data-topic="motion-planning,learning-based-navigation" data-year="2025" data-selected="true">
        <div class="paper-box">
          <div class="paper-box-image">
            <div>
              <div class="badge">arXiv 2025</div>
              <img src="/images/pubs/mgmpd_2025.png" alt="Multi-goal motion planning arXiv teaser">
            </div>
          </div>
          <div class="paper-box-text" markdown="1">
            <div class="title">Combining Machine Learning and Sampling-Based Search for Multi-Goal Motion Planning with Dynamics</div>
            <div class="meta">Y. Lu, E. Plaku — arXiv preprint, 2025</div>
            结合机器学习先验与采样搜索，实现带动力学约束的多目标规划加速。
            <p class="links">
              <a href="https://arxiv.org/abs/2503.20530" target="_blank">paper</a>
            </p>
          </div>
        </div>
      </div>

      <!-- ========== 2025 (Journal) ========== -->
      <!-- RA-L 2025 Verti-bench -->
      <div class="pub-card" data-topic="benchmarks-datasets" data-year="2025" data-selected="true">
        <div class="paper-box">
          <div class="paper-box-image">
            <div>
              <div class="badge">RA-L 2025</div>
              <img src="/images/pubs/verti-bench.png" alt="Verti-bench teaser">
            </div>
          </div>
          <div class="paper-box-text" markdown="1">
            <div class="title">Verti-bench: A General and Scalable Off-road Mobility Benchmark for Vertically Challenging Terrain</div>
            <div class="meta">T. Xu, C. Pan, M. B. Rao, A. Datar, A. Pokhrel, Y. Lu, X. Xiao — IEEE RA-L, 2025</div>
            面向垂直挑战地形的越野移动能力基准，覆盖多样地形与平台。
            <p class="links">
              <a href="https://arxiv.org/pdf/2502.11426" target="_blank">paper</a>
            </p>
          </div>
        </div>
      </div>

      <!-- ========== 2024 ========== -->
      <!-- ICRA 2024 Motion Memory -->
      <div class="pub-card" data-topic="motion-planning,learning-based-navigation" data-year="2024" data-selected="true">
        <div class="paper-box">
          <div class="paper-box-image">
            <div>
              <div class="badge">ICRA 2024</div>
              <img src="/images/pubs/motion-memory.gif" alt="Motion Memory teaser">
            </div>
          </div>
          <div class="paper-box-text" markdown="1">
            <div class="title">Motion Memory: Leveraging Past Experiences to Accelerate Future Motion Planning</div>
            <div class="meta">D. Das, Y. Lu, E. Plaku, X. Xiao — ICRA 2024, pp. 16467–16474</div>
            利用过往经验构建先验以加速后续规划（CNN 路径先验）。
            <p class="links">
              <a href="https://arxiv.org/pdf/2310.06198" target="_blank">paper</a>
            </p>
          </div>
        </div>
      </div>

      <!-- arXiv 2024 Traffic (work zones) -->
      <div class="pub-card" data-topic="machine-learning" data-year="2024" data-selected="true">
        <div class="paper-box">
          <div class="paper-box-image">
            <div>
              <div class="badge">arXiv 2024</div>
              <img src="/images/pubs/traffic_workzone.png" alt="Work zone traffic forecasting teaser">
            </div>
          </div>
          <div class="paper-box-text" markdown="1">
            <div class="title">Accounting for Work Zone Disruptions in Traffic Flow Forecasting</div>
            <div class="meta">Y. Lu, A. Shehu, D. Lattanzi — arXiv preprint, 2024</div>
            将施工/车道关闭等非重复性扰动纳入交通流预测。
            <p class="links">
              <a href="https://arxiv.org/abs/2407.11407" target="_blank">paper</a>
            </p>
          </div>
        </div>
      </div>

      <!-- ========== 2023 ========== -->
      <!-- IROS 2023 -->
      <div class="pub-card" data-topic="motion-planning,learning-based-navigation" data-year="2023" data-selected="true">
        <div class="paper-box">
          <div class="paper-box-image">
            <div>
              <div class="badge">IROS 2023</div>
              <img src="/images/pubs/mgmpd_2023.png" alt="Multi-goal with dynamics teaser">
            </div>
          </div>
          <div class="paper-box-text" markdown="1">
            <div class="title">Leveraging Single-goal Predictions to Improve the Efficiency of Multi-goal Motion Planning with Dynamics</div>
            <div class="meta">Y. Lu, E. Plaku — IROS 2023, pp. 850–857</div>
            用单目标预测作为先验，加速带动力学约束的多目标规划。
            <p class="links">
              <a href="https://ieeexplore.ieee.org/document/10341945" target="_blank">paper</a>
            </p>
          </div>
        </div>
      </div>

      <!-- ========== 2022 ========== -->
      <!-- IROS 2022 -->
      <div class="pub-card" data-topic="motion-planning,learning-based-navigation" data-year="2022" data-selected="true">
        <div class="paper-box">
          <div class="paper-box-image">
            <div>
              <div class="badge">IROS 2022</div>
              <img src="/images/pubs/runtime_pred_2022.png" alt="Runtime prediction teaser">
            </div>
          </div>
          <div class="paper-box-text" markdown="1">
            <div class="title">Improving the Efficiency of Sampling-based Motion Planners via Runtime Predictions for Motion-planning Problems with Dynamics</div>
            <div class="meta">H. D. Bui, Y. Lu, E. Plaku — IROS 2022, pp. 4486–4491</div>
            运行时预测辅助采样式规划器，提高带动力学问题的效率。
            <p class="links">
              <a href="https://ieeexplore.ieee.org/document/9981753" target="_blank">paper</a>
            </p>
          </div>
        </div>
      </div>

      <!-- ========== 2024/2021 Traffic (arXiv 2021贴在你给定年份 2024) ========== -->
      <!-- arXiv 2024 Traffic (maintenance downtime; 原始 arXiv:2110.01535) -->
      <div class="pub-card" data-topic="machine-learning" data-year="2024" data-selected="true">
        <div class="paper-box">
          <div class="paper-box-image">
            <div>
              <div class="badge">arXiv 2024</div>
              <img src="/images/pubs/traffic_mcastgcn.png" alt="Traffic with maintenance downtime teaser">
            </div>
          </div>
          <div class="paper-box-text" markdown="1">
            <div class="title">Traffic Flow Forecasting with Maintenance Downtime via Multi-Channel Attention-Based Spatio-Temporal Graph Convolutional Networks</div>
            <div class="meta">Y. Lu, P. Kamranfar, D. Lattanzi, A. Shehu — arXiv preprint, 2024</div>
            多通道注意力式时空图卷积，用于设备维护停机时的交通流预测。
            <p class="links">
              <a href="https://arxiv.org/abs/2110.01535" target="_blank">paper</a>
            </p>
          </div>
        </div>
      </div>

      <!-- ========== 2021 ========== -->
      <!-- BIBM 2021 -->
      <div class="pub-card" data-topic="machine-learning" data-year="2021" data-selected="true">
        <div class="paper-box">
          <div class="paper-box-image">
            <div>
              <div class="badge">BIBM 2021</div>
              <img src="/images/pubs/chem_gen_2021.png" alt="Controllable molecule generation teaser">
            </div>
          </div>
          <div class="paper-box-text" markdown="1">
            <div class="title">Deep Latent-variable Models for Controllable Molecule Generation</div>
            <div class="meta">Y. Du, Y. Wang, F. Alam, Y. Lu, X. Guo, L. Zhao, A. Shehu — BIBM 2021, pp. 1303–1310</div>
            可控分子生成的潜变量模型方法。
            <p class="links">
              <a href="https://ieeexplore.ieee.org/document/9669692" target="_blank">paper</a>
            </p>
          </div>
        </div>
      </div>

    </div>
  </div>
</div>

<!-- ===== Paper Box + Grid styles ===== -->
<style>
  .paper-box {
    display: flex;
    gap: 16px;
    align-items: flex-start;
    padding: 14px 0;
    border-bottom: 1px solid #eee;
  }
  .paper-box-image {
    flex: 0 0 360px;          /* 按页面宽度可调 320~420 */
    max-width: 100%;
  }
  .paper-box-image > div {
    position: relative;
    width: 100%;
    aspect-ratio: 16/9;       /* 保持一致外观；不想裁剪可把 img 的 object-fit: contain */
    overflow: hidden;
    border-radius: 8px;
    background: #f7f7f7;
  }
  .paper-box-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;         /* 全图显示可改 contain，并加 background:#fff; */
    display: block;
  }
  .badge {
    position: absolute;
    top: 10px;
    left: 10px;
    padding: 4px 10px;
    background: #111;
    color: #fff;
    font-size: 0.8rem;
    border-radius: 6px;
    opacity: 0.9;
  }
  .paper-box-text {
    flex: 1 1 auto;
    min-width: 0;
  }
  .paper-box-text .title {
    font-weight: 600;
    font-size: 1.05rem;
    margin: 0 0 4px 0;
  }
  .paper-box-text .meta {
    color: #666;
    font-style: italic;
    margin: 2px 0 8px 0;
    display: block;
  }
  .paper-box-text .links a {
    margin-right: 10px;
  }
  /* 兼容原有 .pub-card 样式（让筛选脚本可用） */
  #pub-card-container .pub-card { padding: 0; border: none; }
  #pub-card-container .pub-card + .pub-card { margin-top: 8px; }

  /* 移动端 */
  @media (max-width: 768px) {
    .paper-box { flex-direction: column; }
    .paper-box-image { flex: none; width: 100%; aspect-ratio: 16/9; }
  }
</style>

<!-- ===== 你的筛选脚本（原样保留，稍作清理） ===== -->
<script src="https://code.jquery.com/jquery-3.1.1.min.js" crossorigin="anonymous"></script>
<script type="text/javascript">
function isInViewport(element) {
  var elementTop = $(element).offset().top;
  var elementBottom = elementTop + $(element).outerHeight();
  var viewportTop = $(window).scrollTop();
  var viewportBottom = viewportTop + $(window).height();
  return elementBottom > viewportTop && elementTop < viewportBottom;
}
var allPublications = null, allTopicsLink = null, allTopics = [];

function publicationBySelected() {
  var a = $("#publication-by-selected");
  if (a.hasClass("activated")) return;
  $("#pub-container .subtitle a").removeClass("activated");
  $("#pub-container .subtitle-aux a").removeClass("activated");
  a.addClass("activated");
  $("#pub-card-container").html("");
  for (var i = 0; i < allPublications.length; i++) {
    var pub = $(allPublications[i]);
    if (pub.data("selected") == true) $("#pub-card-container").append(pub).append("<br>");
  }
}
function publicationByDate() {
  var a = $("#publication-by-date");
  if (a.hasClass("activated")) return;
  $("#pub-container .subtitle a").removeClass("activated");
  $("#pub-container .subtitle-aux a").removeClass("activated");
  a.addClass("activated");
  $("#pub-card-container").html("");
  for (var i = 0; i < allPublications.length; i++) {
    if (i == 0 || $(allPublications[i-1]).data("year") != $(allPublications[i]).data("year")) {
      var year = $(allPublications[i]).data("year");
      $("#pub-card-container").append($("<h2 id='year-" + year + "'>" + year + "</h2>"));
    }
    $("#pub-card-container").append(allPublications[i]).append("<br>");
  }
}
function publicationByTopicInner() {
  var a = $("#publication-by-topic");
  if (a.hasClass("activated")) return;
  $("#pub-container .subtitle a").removeClass("activated");
  a.addClass("activated");
  $("#pub-card-container").html("");
  for (var t in allTopics) {
    var topic = allTopics[t].name, topicTitle = allTopics[t].title;
    $("#pub-card-container").append($("<h2 id='topic-" + topic + "'>" + topicTitle + "</h2>"));
    for (var i = 0; i < allPublications.length; i++) {
      var pub = $(allPublications[i]);
      if ((pub.data("topic") + "").indexOf(topic) != -1) $("#pub-card-container").append(pub).append("<br>");
    }
  }
}
function publicationByTopicSpecificInner(a) {
  if ($(a).hasClass("activated")) return false;
  $("#pub-container .subtitle-aux a").removeClass("activated");
  $(a).addClass("activated");
}
function publicationByTopic() {
  publicationByTopicInner();
  publicationByTopicSpecificInner($("#pub-container .subtitle-aux a:first"));
  return true;
}
function publicationByTopicSpecific(a) {
  publicationByTopicInner();
  publicationByTopicSpecificInner(a);
  var hash = a.hash;
  $(hash).prop('id', hash.substr(1) + '-noscroll');
  window.location.hash = hash;
  $(hash + '-noscroll').prop('id', hash.substr(1));
  if (!isInViewport(hash)) {
    $('html, body').animate({ scrollTop: $(hash).offset().top }, 800, function(){});
  }
  return false;
}
$(function() {
  allPublications = $("#pub-card-container .pub-card");
  allTopicsLink = $("#pub-container .subtitle-aux a");
  for (var i = 0; i < allTopicsLink.length; i++) {
    allTopics.push({name: $(allTopicsLink[i]).data("topic"), title: $(allTopicsLink[i]).html()});
  }
  $("#publication-by-selected").click();
  $("#pub-card-container").removeClass("hide");
});
</script>
