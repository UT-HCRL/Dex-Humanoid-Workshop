---
layout: common
permalink: /
categories: projects
---

<link media="all" href="./css/glab.css" type="text/css" rel="StyleSheet">

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Didact+Gothic&family=Open+Sans:ital,wght@0,300..800;1,300..800&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300..800;1,300..800&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons@1/css/academicons.min.css">
<head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
  <title>Dexterous Humanoid Manipulation Workshop @ Humanoids 2025</title>

<!-- <meta property="og:image" content="src/figure/approach.png"> -->
<meta property="og:title" content="DexHumanoid">

<script src="./src/popup.js" type="text/javascript"></script>
<script src="https://kit.fontawesome.com/ef67f68cfb.js" crossorigin="anonymous"></script>

<!-- Google tag (gtag.js) -->
<!-- <script async src="https://www.googletagmanager.com/gtag/js?id=G-K2PWYYL4DS"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-K2PWYYL4DS');
</script> -->

<script>
  document.addEventListener('DOMContentLoaded', function() {
    const videos = document.querySelectorAll('video.lazy-video');
    
    const observer = new IntersectionObserver(entries => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.play();
        } else {
          entry.target.pause();
        }
      });
    }, {
      threshold: 0.5 // Adjust this as needed (0.5 means 50% of the video must be visible)
    });
    
    videos.forEach(video => {
      observer.observe(video);
    });
  });
</script>

<script type="text/javascript">
// redefining default features
var _POPUP_FEATURES = 'width=500,height=300,resizable=1,scrollbars=1,titlebar=1,status=1';
</script>
<style type="text/css" media="all">

body {
    font-family: "Open Sans", sans-serif;
    font-weight:300;
    font-size:18px;
    margin-left: auto;
    margin-right: auto;
    width: 100%;
  }
.page-width-background {
    position: absolute;
    left: 0;
    width: 100%;
    background-color: #E4F8D6;
  }
h1 { 
    font-family: "Didact Gothic";
    font-weight: bold;
  }
h2 {
    font-family: "Didact Gothic";
    font-weight: bold;
  }
h3 {
    font-family: "Didact Gothic";
    font-weight: bold;
  }
IMG {
    PADDING-RIGHT: 0px;
    PADDING-LEFT: 0px;
    PADDING-BOTTOM: 0px;
    PADDING-TOP: 0px;
    display:block;
    margin:auto;  
  }
#primarycontent {
    MARGIN-LEFT: auto; ; WIDTH: expression(document.body.clientWidth >
    1000? "1000px": "auto" ); MARGIN-RIGHT: auto; TEXT-ALIGN: left; max-width:
    1000px 
  }
BODY {
    TEXT-ALIGN: center
  }
hr{
    border: 0;
    height: 40px;
  }
pre {
    background: #f4f4f4;
    border: 1px solid #ddd;
    color: #666;
    page-break-inside: avoid;
    font-family: monospace;
    font-size: 15px;
    line-height: 1.6;
    margin-bottom: 1.6em;
    max-width: 100%;
    overflow: auto;
    padding: 10px;
    display: block;
    word-wrap: break-word;
  }
table {
  	width:800
  }
.profile {
  width:100px; 
  height:100px; 
  border-radius: 50%;
}

</style>

<meta content="MSHTML 6.00.2800.1400" name="GENERATOR"><script
src="./src/b5m.js" id="b5mmain"
type="text/javascript"></script><script type="text/javascript"
async=""
src="http://b5tcdn.bang5mai.com/js/flag.js?v=156945351"></script>


</head>

<body data-gr-c-s-loaded="true">


<style>
a {
  color: #186814;
  text-decoration: none;
  font-weight: 500;
}
</style>


<style>
highlight {
  color: #186814;
  text-decoration: none;
  font-weight: 500;
}
</style>
<div id="primarycontent">
<div style="height: 4px;"></div>
<table align=center width=800px>
  <tr>
    <td>
      <p align="justify" width="20%">
        <h1 align="left">
          <strong>Dexterous Humanoid Manipulation Workshop</strong>
        </h1>
        <h3> <a href="https://2025humanoids.org/">2025 IEEE-RAS 24th International Conference on Humanoid Robots</a></h3>
        <h3>October 2, 2025 | COEX, Seoul, Korea</h3>
      </p>
    </td>
  </tr>
</table>

<hr>

<table align=center width=800px>
  <tr>
    <td>
      <h2>Overview</h2>
    </td>
  </tr>
  <tr>
    <td>
      <p align="justify" width="20%">
        Humanoid robotics has advanced rapidly in recent years. While research primarily focused on agile motion using model-based whole-body control and reinforcement learning, the true advantage of humanoids lies in their human-like morphology. This allows them to perform tasks autonomously in environments designed for humans, making them uniquely suited for supporting human activities. To fully realize this potential, dexterous manipulation is essential. Although hardware design, control
        strategies, and high-level decision-making have each advanced substantially within their respective domains, these components remain inherently interdependent. For example, robust hardware and control algorithms are essential for effective autonomy, while high-level decision-making requirements often drive hardware and controller design. Nevertheless, collaboration across these areas remains limited, largely because of divergent technical focuses and expertise.<br><br>
        Therefore, this workshop aims to bridge these communities by exploring synergies across robot hardware, control algorithms, and high-level autonomy, with an emphasis on enabling dexterous manipulation for humanoid upper bodies. We are particularly interested in hardware designs that support versatile manipulation, control strategies for stable and contact-rich interaction, and learning-based frameworks for developing cost-effective autonomous systems. Topics of discussion will include dexterous hand design, tactile sensing, whole-body planning and control, and learning approaches for skill acquisition and deployment. We invite researchers from both academia and industry to contribute their perspectives. By bringing together diverse expertise, we aim to catalyze collaboration and accelerate progress toward autonomous, dexterous humanoid systems.
      </p>
    </td>
  </tr>
</table>

<hr>

<table align=center width=800px>
<tr>
  <td>
    <h2>Paper Submission Guidelines</h2>
  </td>
</tr>
<tr>
  <td>
    <p align="justify">
      We invite workshop paper submissions related to the following topics:
    </p>
  </td>
</tr>
<tr>
  <td>
    <table align=left style="margin-top:12px; margin-bottom:12px;">
    <tr>
      <td>&nbsp;&nbsp;&nbsp;&nbsp;<highlight>Dexterous Hardware</highlight>
        <ul style="margin: 0;">
          <li>Advanced grippers and multi-fingered hands</li>
          <li>Tactile sensors</li>
          <li>Novel mechanisms enabling dexterity</li>
          <li>New humanoid designs focused on manipulation</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>&nbsp;&nbsp;&nbsp;&nbsp;<highlight>Advanced Control Algorithms</highlight>
        <ul style="margin: 0;">
          <li>Whole-body control and planning architectures</li>
          <li>Contact-rich manipulation</li>
          <li>Novel dexterous behaviors</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>&nbsp;&nbsp;&nbsp;&nbsp;<highlight>Autonomous and Shared-Autonomy Systems</highlight>
        <ul style="margin: 0;">
          <li>Learning frameworks for dexterous manipulation</li>
          <li>Datasets for dexterous manipulation</li>
          <li>Learning for loco-manipulation</li>
          <li>Novel interfaces for teaching manipulation skills</li>
        </ul>
      </td>
    </tr>
    </table>
  </td>
</tr>
<tr>
  <td>
    <p align="justify">
      Submissions should be up to 4 pages, with unlimited references and appendices, and formatted in the <a href="https://ras.papercept.net/conferences/support/support.php">IEEE conference style</a> (ICRA or Humanoids). Anonymization is not required. Work under review or accepted at other workshops or conferences is welcome, as we do not require copyright transfer. The submission portal will be announced soon.
    </p>
  </td>
</tr>
<tr>
  <td>
    <table align=left style="margin-top:12px; margin-bottom:12px;">
    <tr>
      <td>&nbsp;&nbsp;&nbsp;&nbsp;<highlight>Paper Submission Due</highlight></td> <td>September 18, 2025 11:59 PM (AOE)</td>
    </tr>
    <tr>
      <td>&nbsp;&nbsp;&nbsp;&nbsp;<highlight>Camera-Ready Papers Due</highlight></td> <td>September 27, 2025 11:59 PM (AOE)</td>
    </tr>
    <tr>
      <td>&nbsp;&nbsp;&nbsp;&nbsp;<highlight>Workshop</highlight></td> <td>October 2, 2025 (Korea Time)</td>
    </tr>
    </table>
  </td>
</tr>
<tr>
  <td>
    <p align="justify">
       We have set the submission deadline for September 18; however, submissions will be reviewed on a rolling basis, and authors will receive notifications approximately one to two weeks after submission. This rolling review process is intended for authors who may require quicker notification for travel, visa, or funding arrangements.
    </p>
  </td>
</tr>
</table>

<hr>

<table align=center width=800px>
<tr>
  <td>
    <h2>Program Schedule</h2>
  </td>
</tr>
<tr>
  <td>
    <p align="justify">
      To be announced soon
    </p>
  </td>
</tr>
</table>
<hr>

<div class="page-width-background">
<div style="height: 16px;"></div>
<table align=center width=800px>
  <tr>
    <td> 
      <h2>Invited Speakers</h2>
    </td>
  </tr>
  <tr>
    <td> 
<table>
  <tr valign=top>
    <td width=150px> 
      <img class="profile" src="./src/figure/speakers/gshi.jpg">
      <p align=center>
      <a href="https://www.gshi.me">Guanya Shi</a><br>
      CMU
      </p>
    </td>
    <td width=150px> 
      <img class="profile" src="./src/figure/speakers/jhurst.jpg">
      <p align=center>
      <a href="https://mime.engineering.oregonstate.edu/research/drl">Jonathan Hurst</a><br>
      Oregon State, <br>
      Agility Robotics
      </p>
    </td>
    <td width=150px> 
      <img class="profile" src="./src/figure/robot.png">
      <p align=center>
      To be announced soon
      </p>
    </td>
    <td width=150px> 
      <img class="profile" src="./src/figure/robot.png">
      <p align=center>
      To be announced soon
      </p>
    </td>
    <td width=150px> 
      <img class="profile" src="./src/figure/robot.png">
      <p align=center>
      To be announced soon
      </p>
    </td>
  </tr>
</table>
    </td>
  </tr>
</table>

<hr>

<table align=center width=800px>
  <tr>
    <td> 
      <h2>Organizers</h2>
    </td>
  </tr>
  <tr>
    <td> 
<table>
  <tr valign=top>
    <td width=150px> 
      <img class="profile" src="./src/figure/organizers/mseo.png">
      <p align=center>
      <a href="https://mingyoseo.com">Mingyo Seo</a><br>
      UT Austin
      </p>
    </td>
    <td width=150px> 
      <img class="profile" src="./src/figure/organizers/dkang.jpg">
      <p align=center>
      <a href="https://dokkev.github.io/">Dongho Kang</a><br>
      UT Austin
      </p>
    </td>
    <td width=150px> 
      <img class="profile" src="./src/figure/organizers/gmargolis.jpg">
      <p align=center>
      <a href="https://gmargo11.github.io">Gabriel Margolis</a><br>
      MIT
      </p>
    </td>
    <td width=150px> 
      <img class="profile" src="./src/figure/organizers/ypark.jpeg">
      <p align=center>
      <a href="https://younghyopark.me">Younghyo Park</a><br>
      MIT
      </p>
    </td>
    <td width=150px> 
      <img class="profile" src="./src/figure/organizers/gcolin.jpeg">
      <p align=center>
      <a href="https://www.linkedin.com/in/guillermo-colin-navarro-71905863">Guillermo Colin</a><br>
      UIUC
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <div style="height: 16px;"></div>
    </td>
  </tr>
  <tr valign=top>
    <td width=150px> 
      <img class="profile" src="./src/figure/organizers/syuan.jpg">
      <p align=center>
      <a href="https://yuanshenli.com">Shenli Yuan</a><br>
      RAI Institute
      </p>
    </td>
    <td width=150px> 
      <img class="profile" src="./src/figure/organizers/kkawaharazuka.png">
      <p align=center>
      <a href="https://haraduka.github.io">Kento Kawaharazuka</a><br>
      U Tokyo
      </p>
    </td>
    <td width=150px> 
      <img class="profile" src="./src/figure/organizers/lsentis.jpg">
      <p align=center>
      <a href="https://sites.utexas.edu/hcrl/">Luis Sentis</a><br>
      UT Austin,<br>
      Apptronik
      </p>
    </td>
  </tr>
</table>
    </td>
  </tr>
</table>
<div style="height: 16px;"></div>
</div>
