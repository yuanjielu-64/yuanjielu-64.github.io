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
        <a href="#topic-bioinformatics" onClick="return publicationByTopicSpecific(this)" data-topic="bioinformatics">Bioinformatics</a>
        <br />
    </p>

    <!-- 卡片容器（页面加载后 JS 会根据不同模式重排） -->
    <div id="pub-card-container" class="activated hide">

      <!-- 2026 -->
      <div class="pub-card" data-topic="motion-planning,learning-based-navigation" data-year="2026" data-selected="true">
        <strong>Adaptive Dynamics Planning for Robot Navigation</strong><br>
        <em><b>Y. Lu</b>, L. Wang, T. Xu, X. Xiao</em><br>
        under review at IEEE International Conference on Robotics and Automation (ICRA), 2026
        <!-- | <a href="#">paper</a> -->
      </div>

      <!-- 2025 -->
      <div class="pub-card" data-topic="motion-planning" data-year="2025" data-selected="true">
        <strong>Autonomous Ground Navigation in Highly Constrained Spaces: Lessons Learned from the Fourth BARN Challenge at ICRA 2025</strong><br>
        <em><b>Y. Lu</b>, et al.</em><br>
        IEEE International Conference on Robotics and Automation (ICRA) 2025, Competition Track (BARN Challenge), 2025
        <!-- | <a href="#">paper</a> -->
      </div>

      <div class="pub-card" data-topic="motion-planning,learning-based-navigation" data-year="2025" data-selected="true">
        <strong>Decremental Dynamics Planning for Robot Navigation</strong><br>
        <em><b>Y. Lu</b>, T. Xu, L. Wang, N. Hawes, X. Xiao</em><br>
        IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) 2025, accepted, 2025
        <!-- | <a href="#">paper</a> -->
      </div>

      <div class="pub-card" data-topic="learning-based-navigation" data-year="2025" data-selected="true">
        <strong>Reward Training Wheels: Adaptive Auxiliary Rewards for Robotics Reinforcement Learning</strong><br>
        <em>L. Wang, T. Xu, <b>Y. Lu</b>, X. Xiao</em><br>
        IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) 2025, accepted, 2025
        <!-- | <a href="#">paper</a> -->
      </div>

      <div class="pub-card" data-topic="benchmarks-datasets" data-year="2025" data-selected="false">
        <strong>Verti-bench: A General and Scalable Off-road Mobility Benchmark for Vertically Challenging Terrain</strong><br>
        <em>T. Xu, C. Pan, M. B. Rao, A. Datar, A. Pokhrel, <b>Y. Lu</b>, X. Xiao</em><br>
        IEEE Robotics and Automation Letters (RA-L), 2025
        <!-- | <a href="#">paper</a> -->
      </div>

      <!-- 2024 -->
      <div class="pub-card" data-topic="motion-planning,learning-based-navigation" data-year="2024" data-selected="true">
        <strong>Motion Memory: Leveraging Past Experiences to Accelerate Future Motion Planning</strong><br>
        <em>D. Das, <b>Y. Lu</b>, E. Plaku, X. Xiao</em><br>
        IEEE International Conference on Robotics and Automation (ICRA), pp. 16467–16474, 2024
        <!-- | <a href="#">paper</a> -->
      </div>

      <!-- 2023 -->
      <div class="pub-card" data-topic="motion-planning,learning-based-navigation" data-year="2023" data-selected="true">
        <strong>Leveraging Single-goal Predictions to Improve the Efficiency of Multi-goal Motion Planning with Dynamics</strong><br>
        <em><b>Y. Lu</b>, E. Plaku</em><br>
        IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), pp. 850–857, 2023
        <!-- | <a href="#">paper</a> -->
      </div>

      <!-- 2022 -->
      <div class="pub-card" data-topic="motion-planning,learning-based-navigation" data-year="2022" data-selected="true">
        <strong>Improving the Efficiency of Sampling-based Motion Planners via Runtime Predictions for Motion-planning Problems with Dynamics</strong><br>
        <em>H. D. Bui, <b>Y. Lu</b>, E. Plaku</em><br>
        IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), pp. 4486–4491, 2022
        <!-- | <a href="#">paper</a> -->
      </div>

      <!-- 2021 (Bioinformatics) -->
      <div class="pub-card" data-topic="bioinformatics" data-year="2021" data-selected="false">
        <strong>Deep Latent-variable Models for Controllable Molecule Generation</strong><br>
        <em>Y. Du, Y. Wang, F. Alam, <b>Y. Lu</b>, X. Guo, L. Zhao, A. Shehu</em><br>
        IEEE International Conference on Bioinformatics and Biomedicine (BIBM), pp. 1303–1310, 2021
        <!-- | <a href="#">paper</a> -->
      </div>

    </div> <!-- end #pub-card-container -->
  </div>
</div>

<!-- jQuery（和你的示例一致） -->
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
            if (String(pub.data("topic")).indexOf(topic) != -1) {
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
        $('html, body').animate({ scrollTop: $(hash).offset().top }, 500);
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
    $("#publication-by-selected").click();  // 默认显示“selected”
    $("#pub-card-container").removeClass("hide");
});
</script>
</body>
</html>
