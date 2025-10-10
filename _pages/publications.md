---
layout: archive
title: ""
permalink: /publications/
author_profile: true
googlescholar: https://scholar.google.com/citations?user=BVwGPdQAAAAJ&hl=en
---

<html>
<body>

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
    </p>

    <div id="pub-card-container" class="activated hide">

      <!-- Example 1 -->
      <div class="pub-card" data-topic="learning-based-navigation" data-year="2026" data-selected="true">
        <div class="pub-media">
          <div class="badge badge-icra">ICRA 2026</div>
          <img src="/images/pubs/adp.gif" alt="Adaptive Dynamics Planning">
        </div>
        <div class="pub-info">
          <strong>Adaptive Dynamics Planning for Robot Navigation</strong><br>
          <em>Y. Lu, L. Wang, T. Xu, X. Xiao</em><br>
          under review at IEEE International Conference on Robotics and Automation (ICRA), 2026
          | <a href="https://arxiv.org/pdf/2510.05330" target="_blank">paper</a>
        </div>
      </div>

      <!-- Example 2 -->
      <div class="pub-card" data-topic="motion-planning" data-year="2025" data-selected="true">
        <div class="pub-media">
          <div class="badge badge-iros">IROS 2025</div>
          <img src="/images/pubs/ddp.png" alt="Decremental Dynamics Planning">
        </div>
        <div class="pub-info">
          <strong>Decremental Dynamics Planning for Robot Navigation</strong><br>
          <em>Y. Lu, T. Xu, L. Wang, N. Hawes, X. Xiao</em><br>
          IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2025
          | <a href="https://arxiv.org/pdf/2503.20521" target="_blank">paper</a>
        </div>
      </div>

      <div class="pub-card" data-topic="motion-planning" data-year="2025" data-selected="true">
        <div class="pub-media">
          <div class="badge badge-icra">ICRA 2025</div>
          <img src="/images/pubs/barn.gif" alt="BARN Challenge">
        </div>
        <div class="pub-info">
          <strong>Autonomous Ground Navigation in Highly Constrained Spaces: Lessons Learned from the Fourth BARN Challenge</strong><br>
          <em>Y. Lu, et al.</em><br>
          IEEE ICRA 2025, Competition Track
          | <a href="https://cs.gmu.edu/~xiao/papers/barn25_report.pdf" target="_blank">paper</a>
        </div>
      </div>

      <div class="pub-card" data-topic="learning-based-navigation" data-year="2025" data-selected="true">
        <div class="pub-media">
          <div class="badge badge-iros">IROS 2025</div>
          <img src="/images/pubs/rtw.png" alt="Reward Training Wheels">
        </div>
        <div class="pub-info">
          <strong>Reward Training Wheels: Adaptive Auxiliary Rewards for Robotics Reinforcement Learning</strong><br>
          <em>L. Wang, T. Xu, Y. Lu, X. Xiao</em><br>
          IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2025
          | <a href="https://arxiv.org/pdf/2503.15724" target="_blank">paper</a>
        </div>
      </div>

      <div class="pub-card" data-topic="benchmarks-datasets" data-year="2025" data-selected="true">
        <div class="pub-media">
          <div class="badge badge-ral">RA-L 2025</div>
          <img src="/images/pubs/verti-bench.png" alt="Verti-bench">
        </div>
        <div class="pub-info">
          <strong>Verti-bench: A General and Scalable Off-road Mobility Benchmark</strong><br>
          <em>T. Xu, C. Pan, M. Rao, A. Datar, A. Pokhrel, Y. Lu, X. Xiao</em><br>
          IEEE Robotics and Automation Letters (RA-L), 2025
          | <a href="https://arxiv.org/pdf/2502.11426" target="_blank">paper</a>
        </div>
      </div>

      <div class="pub-card" data-topic="machine-learning" data-year="2024" data-selected="true">
        <div class="pub-media">
          <div class="badge badge-arxiv">arXiv</div>
          <img src="/images/pubs/traffic_mcastgcn.png" alt="Traffic Flow Forecasting">
        </div>
        <div class="pub-info">
          <strong>Traffic Flow Forecasting with Maintenance Downtime via Multi-Channel ST-GCN</strong><br>
          <em>Y. Lu, P. Kamranfar, D. Lattanzi, A. Shehu</em><br>
          arXiv preprint, 2024 | <a href="https://arxiv.org/abs/2110.01535" target="_blank">paper</a>
        </div>
      </div>

    </div>
  </div>
</div>

<!-- ✅ Styling -->
<style>
  #pub-card-container .pub-card {
    display: flex;
    gap: 18px;
    align-items: flex-start;
    padding: 18px 0;
    border-bottom: 1px solid #eee;
  }
  .pub-media {
    flex: 0 0 360px;
    position: relative;
    aspect-ratio: 16 / 9;
    border-radius: 6px;
    overflow: hidden;
    background: #f6f6f6;
  }
  .pub-media img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }
  .pub-info strong {
    font-size: 1.05rem;
  }
  .badge {
    position: absolute;
    top: 10px;
    left: 10px;
    background: #555;
    color: #fff;
    font-size: 0.75rem;
    font-weight: 600;
    padding: 4px 8px;
    border-radius: 4px;
    text-transform: uppercase;
  }
  .badge-icra { background: #e74c3c; }
  .badge-iros { background: #2980b9; }
  .badge-ral { background: #27ae60; }
  .badge-arxiv { background: #7f8c8d; }
  @media (max-width: 768px) {
    .pub-card { flex-direction: column; }
    .pub-media { width: 100%; }
  }
</style>

<!-- ✅ Enhanced JavaScript for Topic Filtering -->
<script src="https://code.jquery.com/jquery-3.1.1.min.js" crossorigin="anonymous"></script>
<script type="text/javascript">
$(function() {
  // Load attributes manually
  $("#pub-card-container .pub-card").each(function() {
    $(this).data("topic", $(this).attr("data-topic"));
    $(this).data("year", $(this).attr("data-year"));
    $(this).data("selected", $(this).attr("data-selected") === "true");
  });

  allPublications = $("#pub-card-container .pub-card");
  allTopicsLink = $("#pub-container .subtitle-aux a");
  allTopics = [];

  for (var topicId = 0; topicId < allTopicsLink.length; topicId++) {
    allTopics.push({
      name: $(allTopicsLink[topicId]).data("topic"),
      title: $(allTopicsLink[topicId]).html()
    });
  }

  function publicationBySelected() {
    var a = $("#publication-by-selected");
    if (a.hasClass("activated")) return;
    $("#pub-container .subtitle a, #pub-container .subtitle-aux a").removeClass("activated");
    a.addClass("activated");
    $("#pub-card-container").html("");
    allPublications.each(function() {
      if ($(this).attr("data-selected") === "true") $("#pub-card-container").append($(this).clone());
    });
  }

  function publicationByDate() {
    var a = $("#publication-by-date");
    if (a.hasClass("activated")) return;
    $("#pub-container .subtitle a, #pub-container .subtitle-aux a").removeClass("activated");
    a.addClass("activated");
    $("#pub-card-container").html("");
    var sorted = allPublications.sort((a, b) => $(b).data("year") - $(a).data("year"));
    var currentYear = null;
    sorted.each(function() {
      var year = $(this).attr("data-year");
      if (year !== currentYear) {
        $("#pub-card-container").append("<h2>" + year + "</h2>");
        currentYear = year;
      }
      $("#pub-card-container").append($(this).clone());
    });
  }

  function publicationByTopicInner() {
    var a = $("#publication-by-topic");
    if (a.hasClass("activated")) return;
    $("#pub-container .subtitle a").removeClass("activated");
    a.addClass("activated");
    $("#pub-card-container").html("");
    for (var topicId in allTopics) {
      var topic = allTopics[topicId].name;
      var topicTitle = allTopics[topicId].title;
      $("#pub-card-container").append("<h2 id='topic-" + topic + "'>" + topicTitle + "</h2>");
      allPublications.each(function() {
        if (($(this).attr("data-topic") || "").includes(topic)) {
          $("#pub-card-container").append($(this).clone());
        }
      });
    }
  }

  window.publicationBySelected = publicationBySelected;
  window.publicationByDate = publicationByDate;
  window.publicationByTopic = function() {
    publicationByTopicInner();
    return true;
  };
  window.publicationByTopicSpecific = function(a) {
    publicationByTopicInner();
    var hash = a.hash;
    $("html, body").animate({ scrollTop: $(hash).offset().top }, 600);
    return false;
  };

  publicationBySelected();
  $("#pub-card-container").removeClass("hide");
});
</script>
</body>
</html>
