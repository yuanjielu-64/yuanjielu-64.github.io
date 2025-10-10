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
        <a href="#topic-bioinformatics" onClick="return publicationByTopicSpecific(this)" data-topic="machine-learning">machine-learning</a>
        <br />
    </p>

    <div id="pub-card-container" class="activated hide">

      <!-- ICRA 2026 (under review) -->
      <div class="pub-card" data-topic="learning-based-navigation" data-year="2026" data-selected="true">
        <div class="pub-media">
          <img src="/images/pubs/adp.gif" alt="Adaptive Dynamics Planning teaser">
        </div>
        <div class="pub-info">
          <strong>Adaptive Dynamics Planning for Robot Navigation</strong><br>
          <em class="meta">Y. Lu, L. Wang, T. Xu, X. Xiao — under review at ICRA 2026</em>
          <span>
            Integrates adaptive dynamics modeling with learning-based local planners for efficient navigation in constrained environments.
            | <a href="https://arxiv.org/pdf/2510.05330" target="_blank">paper</a>
          </span>
        </div>
      </div>

      <!-- IROS 2025 (accepted) -->
      <div class="pub-card" data-topic="motion-planning" data-year="2025" data-selected="true">
        <div class="pub-media">
          <img src="/images/pubs/ddp.png" alt="Decremental Dynamics Planning teaser">
        </div>
        <div class="pub-info">
          <strong>Decremental Dynamics Planning for Robot Navigation</strong><br>
          <em class="meta">Y. Lu, T. Xu, L. Wang, N. Hawes, X. Xiao — IROS 2025 (accepted)</em>
          <span>
            Hierarchical dynamic reconfiguration enabling real-time replanning.
            | <a href="https://arxiv.org/pdf/2503.20521" target="_blank">paper</a>
          </span>
        </div>
      </div>

      <!-- ICRA 2025 Competition Track (BARN) -->
      <div class="pub-card" data-topic="motion-planning" data-year="2025" data-selected="true">
        <div class="pub-media">
          <img src="/images/pubs/barn.gif" alt="BARN challenge teaser">
        </div>
        <div class="pub-info">
          <strong>Autonomous Ground Navigation in Highly Constrained Spaces: Lessons Learned from the Fourth BARN Challenge at ICRA 2025</strong><br>
          <em class="meta">Y. Lu, et al. — ICRA 2025 (Competition Track)</em>
          <span>
            Report and analysis from large-scale constrained-space navigation benchmarking.
            | <a href="https://cs.gmu.edu/~xiao/papers/barn25_report.pdf" target="_blank">paper</a>
          </span>
        </div>
      </div>

      <!-- IROS 2025 (accepted) -->
      <div class="pub-card" data-topic="learning-based-navigation" data-year="2025" data-selected="true">
        <div class="pub-media">
          <img src="/images/pubs/rtw.png" alt="Reward Training Wheels teaser">
        </div>
        <div class="pub-info">
          <strong>Reward Training Wheels: Adaptive Auxiliary Rewards for Robotics Reinforcement Learning</strong><br>
          <em class="meta">L. Wang, T. Xu, Y. Lu, X. Xiao — IROS 2025 (accepted)</em>
          <span>
            Adaptive auxiliary reward shaping that phases out to avoid policy degradation.
            | <a href="https://arxiv.org/pdf/2503.15724" target="_blank">paper</a>
          </span>
        </div>
      </div>

      <!-- RA-L 2025 -->
      <div class="pub-card" data-topic="benchmarks-datasets" data-year="2025" data-selected="true">
        <div class="pub-media">
          <img src="/images/pubs/verti-bench.png" alt="Verti-bench teaser">
        </div>
        <div class="pub-info">
          <strong>Verti-bench: A General and Scalable Off-road Mobility Benchmark for Vertically Challenging Terrain</strong><br>
          <em class="meta">T. Xu, C. Pan, M. B. Rao, A. Datar, A. Pokhrel, Y. Lu, X. Xiao — IEEE RA-L, 2025</em>
          <span>
            Benchmark for vertical mobility across heterogeneous terrain profiles.
            | <a href="https://arxiv.org/pdf/2502.11426" target="_blank">paper</a>
          </span>
        </div>
      </div>

      <!-- ICRA 2024 -->
      <div class="pub-card" data-topic="motion-planning,learning-based-navigation" data-year="2024" data-selected="true">
        <div class="pub-media">
          <img src="/images/pubs/motion-memory.gif" alt="Motion Memory teaser">
        </div>
        <div class="pub-info">
          <strong>Motion Memory: Leveraging Past Experiences to Accelerate Future Motion Planning</strong><br>
          <em class="meta">D. Das, Y. Lu, E. Plaku, X. Xiao — ICRA 2024</em>
          <span>
            Experience reuse via CNN-based path priors to speed up planning.
            | <a href="https://arxiv.org/pdf/2310.06198" target="_blank">paper</a>
          </span>
        </div>
      </div>

      <!-- IROS 2023 -->
      <div class="pub-card" data-topic="motion-planning,learning-based-navigation" data-year="2023" data-selected="true">
        <div class="pub-media">
          <img src="/images/pubs/mgmpd_2023.png" alt="Multi-goal with dynamics teaser">
        </div>
        <div class="pub-info">
          <strong>Leveraging Single-goal Predictions to Improve the Efficiency of Multi-goal Motion Planning with Dynamics</strong><br>
          <em class="meta">Y. Lu, E. Plaku — IROS 2023, pp. 850–857</em>
          <span>
            Single-goal predictors as priors to accelerate multi-goal planning with dynamics constraints.
            | <a href="https://ieeexplore.ieee.org/document/10341945" target="_blank">paper</a>
          </span>
        </div>
      </div>

      <!-- IROS 2022 -->
      <div class="pub-card" data-topic="motion-planning,learning-based-navigation" data-year="2022" data-selected="true">
        <div class="pub-media">
          <img src="/images/pubs/runtime_pred_2022.png" alt="Runtime prediction teaser">
        </div>
        <div class="pub-info">
          <strong>Improving the Efficiency of Sampling-based Motion Planners via Runtime Predictions for Motion-planning Problems with Dynamics</strong><br>
          <em class="meta">H. D. Bui, Y. Lu, E. Plaku — IROS 2022, pp. 4486–4491</em>
          <span>
            Runtime predictions informing sampling-based planning under dynamics.
            | <a href="https://ieeexplore.ieee.org/document/9981753" target="_blank">paper</a>
          </span>
        </div>
      </div>

      <!-- BIBM 2021 -->
      <div class="pub-card" data-topic="machine-learning" data-year="2021" data-selected="true">
        <div class="pub-media">
          <img src="/images/pubs/chem_gen_2021.png" alt="Controllable molecule generation teaser">
        </div>
        <div class="pub-info">
          <strong>Deep Latent-variable Models for Controllable Molecule Generation</strong><br>
          <em class="meta">Y. Du, Y. Wang, F. Alam, Y. Lu, X. Guo, L. Zhao, A. Shehu — BIBM 2021, pp. 1303–1310</em>
          <span>
            Controllable molecule generation via latent-variable models.
            | <a href="https://ieeexplore.ieee.org/document/9669692" target="_blank">paper</a>
          </span>
        </div>
      </div>

      <!-- arXiv 2025 -->
      <div class="pub-card" data-topic="motion-planning,learning-based-navigation" data-year="2025" data-selected="true">
        <div class="pub-media">
          <img src="/images/pubs/mgmpd_2025.png" alt="Multi-goal motion planning arXiv teaser">
        </div>
        <div class="pub-info">
          <strong>Combining Machine Learning and Sampling-Based Search for Multi-Goal Motion Planning with Dynamics</strong><br>
          <em class="meta">Y. Lu, E. Plaku — arXiv preprint, 2025</em>
          <span>
            Hybrid ML + sampling-based pipeline for dynamic multi-goal navigation.
            | <a href="https://arxiv.org/abs/2503.20530" target="_blank">paper</a>
          </span>
        </div>
      </div>

      <!-- arXiv 2024 (traffic 1) -->
      <div class="pub-card" data-topic="machine-learning" data-year="2024" data-selected="true">
        <div class="pub-media">
          <img src="/images/pubs/traffic_mcastgcn.png" alt="Traffic forecasting with maintenance downtime teaser">
        </div>
        <div class="pub-info">
          <strong>Traffic Flow Forecasting with Maintenance Downtime via Multi-Channel Attention-Based Spatio-Temporal Graph Convolutional Networks</strong><br>
          <em class="meta">Y. Lu, P. Kamranfar, D. Lattanzi, A. Shehu — arXiv preprint, 2024</em>
          <span>
            Multi-channel attention-based ST-GCN for traffic forecasting under downtime.
            | <a href="https://arxiv.org/abs/2110.01535" target="_blank">paper</a>
          </span>
        </div>
      </div>

      <!-- arXiv 2024 (traffic 2) -->
      <div class="pub-card" data-topic="machine-learning" data-year="2024" data-selected="true">
        <div class="pub-media">
          <img src="/images/pubs/traffic_workzone.png" alt="Accounting for work zone disruptions teaser">
        </div>
        <div class="pub-info">
          <strong>Accounting for Work Zone Disruptions in Traffic Flow Forecasting</strong><br>
          <em class="meta">Y. Lu, A. Shehu, D. Lattanzi — arXiv preprint, 2024</em>
          <span>
            Incorporating non-recurring disruptions (work zones, lane closures) into traffic forecasting.
            | <a href="https://arxiv.org/abs/2407.11407" target="_blank">paper</a>
          </span>
        </div>
      </div>

    </div>
  </div>
</div>

<!-- Layout CSS for left-media / right-info -->
<style>
  #pub-card-container .pub-card {
    display: flex;
    gap: 16px;
    align-items: flex-start;
    padding: 14px 0;
    border-bottom: 1px solid #eee;
  }
  #pub-card-container .pub-card .pub-media {
    flex: 0 0 360px;          /* 根据页面宽度可调 320~420 */
    max-width: 100%;
    position: relative;
    aspect-ratio: 16 / 9;
    overflow: hidden;
    border-radius: 6px;
    background: #f7f7f7;
  }
  #pub-card-container .pub-card .pub-media img {
    width: 100%;
    height: 100%;
    object-fit: cover;        /* 尽量铺满；若想完整显示改为 contain */
    display: block;
  }
  #pub-card-container .pub-card .pub-info {
    flex: 1 1 auto;
    min-width: 0;
  }
  #pub-card-container .pub-card .pub-info strong {
    font-size: 1.02rem;
  }
  #pub-card-container .pub-card .meta {
    color: #666;
    font-style: italic;
    margin: 2px 0 6px 0;
    display: block;
  }
  @media (max-width: 768px) {
    #pub-card-container .pub-card {
      flex-direction: column;
    }
    #pub-card-container .pub-card .pub-media {
      width: 100%;
      flex: none;
      aspect-ratio: 16 / 9;
    }
  }

  /* --- 新增: venue 徽章样式（不修改原结构，仅叠加显示） --- */
  #pub-card-container .pub-card .pub-media .venue-badge {
    position: absolute;
    top: 8px;
    left: 8px;
    display: inline-block;
    padding: 4px 8px;
    font-size: 12px;
    line-height: 1;
    border-radius: 12px;
    background: #222;       /* 深色底 */
    color: #fff;            /* 白字 */
    opacity: 0.92;
    pointer-events: none;   /* 不拦截点击 */
    white-space: nowrap;
  }

  /* 可选：不同会议轻度配色（保持克制） */
  #pub-card-container .pub-card[data-venue^="ICRA"] .venue-badge { background: #0f6; color: #111; }
  #pub-card-container .pub-card[data-venue^="IROS"] .venue-badge { background: #6cf; color: #111; }
  #pub-card-container .pub-card[data-venue^="RA-L"] .venue-badge { background: #fc6; color: #111; }
  #pub-card-container .pub-card[data-venue^="arXiv"] .venue-badge { background: #e55; color: #fff; }
  #pub-card-container .pub-card[data-venue*="Competition"] .venue-badge { background: #a78bfa; color:#111; }
</style>

<script src="https://code.jquery.com/jquery-3.1.1.min.js" crossorigin="anonymous"></script>
<script type="text/javascript">
function isInViewport(element) {
    var elementTop = $(element).offset().top;
    var elementBottom = elementTop + $(element).outerHeight();
    var viewportTop = $(window).scrollTop();
    var viewportBottom = viewportTop + $(window).height();
    return elementBottom > viewportTop && elementTop < viewportBottom;
}
var allPublications = null;
function publicationBySelected() {
    var a = $("#publication-by-selected");
    if (a.hasClass("activated")) return;
    $("#pub-container .subtitle a").removeClass("activated");
    $("#pub-container .subtitle-aux a").removeClass("activated");
    a.addClass("activated");
    $("#pub-card-container").html("");
    for (var pubId = 0; pubId < allPublications.length; pubId++) {
        var pub = $(allPublications[pubId]);
        if (pub.data("selected") == true) {
            $("#pub-card-container").append(pub).append("<br>");
        }
    }
}
function publicationByDate() {
    var a = $("#publication-by-date");
    if (a.hasClass("activated")) return;
    $("#pub-container .subtitle a").removeClass("activated");
    $("#pub-container .subtitle-aux a").removeClass("activated");
    a.addClass("activated");
    $("#pub-card-container").html("");
    for (var pubId = 0; pubId < allPublications.length; pubId++) {
        if (pubId == 0 || $(allPublications[pubId-1]).data("year") != $(allPublications[pubId]).data("year")) {
            var year = $(allPublications[pubId]).data("year");
            $("#pub-card-container").append($("<h2 id='year-" + year.toString() + "'>" + year.toString() + "</h2>"));
        }
        $("#pub-card-container").append(allPublications[pubId]).append("<br>");
    }
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
        $("#pub-card-container").append($("<h2 id='topic-" + topic + "'>" + topicTitle + "</h2>"));
        for (var pubId = 0; pubId < allPublications.length; pubId++) {
            var pub = $(allPublications[pubId]);
            if (pub.data("topic").indexOf(topic) != -1) {
                $("#pub-card-container").append(pub).append("<br>");
            }
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
        $('html, body').animate({ scrollTop: $(hash).offset().top }, 1000, function(){});
    }
    return false;
}
$(function() {
    allPublications = $("#pub-card-container .pub-card");
    allTopicsLink = $("#pub-container .subtitle-aux a");
    allTopics = [];
    for (var topicId = 0; topicId < allTopicsLink.length; topicId++) {
        allTopics.push({name: $(allTopicsLink[topicId]).data("topic"), title: $(allTopicsLink[topicId]).html()});
    }
    $("#publication-by-selected").click();
    $("#pub-card-container").removeClass("hide");
});

/* -------- 新增：Venue 解析与徽章渲染（不改动原条目结构，仅追加节点） -------- */
function parseVenueFromMeta(metaText) {
    var t = (metaText || "").replace(/\s+/g, " ").trim();

    // 精确优先（含年份或赛道等）
    var rules = [
        { re: /\bICRA\s*2026\b/i, venue: "ICRA 2026" },
        { re: /\bICRA\s*2025\b.*Competition Track\b/i, venue: "ICRA 2025 Competition" },
        { re: /\bICRA\s*2025\b/i, venue: "ICRA 2025" },
        { re: /\bIROS\s*2025\b/i, venue: "IROS 2025" },
        { re: /\bIROS\s*2023\b/i, venue: "IROS 2023" },
        { re: /\bIROS\s*2022\b/i, venue: "IROS 2022" },
        { re: /\bIEEE\s*RA-?L\b.*2025\b/i, venue: "RA-L 2025" },
        { re: /\bBIBM\s*2021\b/i, venue: "BIBM 2021" },
        { re: /\barXiv\b/i, venue: "arXiv" }
    ];
    for (var i = 0; i < rules.length; i++) {
        if (rules[i].re.test(t)) return rules[i].venue;
    }

    // 回退：常见会议缩写 + 年份
    var m = t.match(/\b(ICRA|IROS|RA-?L|BIBM|arXiv)\b/i);
    if (m) {
        var base = m[0].toUpperCase().replace("RA-L", "RA-L");
        var y = t.match(/\b(20\d{2})\b/);
        return y ? (base + " " + y[1]) : base;
    }
    return null;
}

function renderVenueBadges() {
    $("#pub-card-container .pub-card").each(function () {
        var $card = $(this);
        if ($card.find(".venue-badge").length) return;  // 防重复

        var metaText = $card.find(".meta").text();
        var venue = parseVenueFromMeta(metaText);
        if (!venue) return;

        // 写入 data-venue 便于样式控制
        $card.attr("data-venue", venue);

        // 徽章叠加到左侧媒体图容器
        var $media = $card.find(".pub-media");
        if ($media.length) {
            var $badge = $('<span class="venue-badge"></span>').text(venue);
            $media.append($badge);
        }
    });
}

// 独立 ready，避免改动你原来的初始化逻辑
$(function () {
    renderVenueBadges();
});
</script>
</body>
</html>
