---
layout: default2
title: home
permalink: /
title: <h3  align="center">Workshop on Deployable RL</h3>
nav_order: 1
---


<html lang="en">

<div class="news-box">
  <h4>Announcements</h4>
  <ol>
  <li>We've posted the <a href="/call">call for papers</a>! The paper submission deadline is <b>May 8, 2024</b>.</li>
  <li>We've posted a <a href="#schedule">tentative schedule</a> for the full-day event on <b>August 9, 2024</b> in <b>Amherst, MA</b>.</li>
  </ol>

  <!-- <p>1. <b>Recordings</b> are available on the <a href="https://neurips.cc/virtual/2023/workshop/66498" target="_blank">NeurIPS website</a> (NeurIPS registration required). They will be made public after one month (Jan 2024).<br>
  2. <b>Talk slides</b> are posted on the <a href="/speakers">speakers page</a>.<br>
  3. Congratuations to <a href="#paper-awards">paper award winners</a>!<br>
  4. <b>Workshop highlights and photos</b> can be found on our <a href="https://twitter.com/itif_workshop">Twitter</a>.
  <br><br> 
  </p>-->
</div>
</html>

<br>

Real-world applications pose distinct challenges for decision-making algorithms, especially during the <i>deployment phase</i>. These include high-dimensional observation and action spaces, tasks that may be partially observable or non-stationary, and feedback that is often unspecified, delayed, or corrupted. Furthermore, feedback rarely comes in the form of a scalar reward function, exploration is often prohibitively costly, and safety considerations are a prerequisite for trained models to be deployed.

Reinforcement learning (RL) and contextual bandit (CB) algorithms have been studied in many settings, including healthcare, recommender and advertising systems, resource allocation and operations management, hardware and engineering design, and more recently, large foundation models. Despite many studies focusing on applying RL to such domains, the majority of solutions are <i>not</i> eventually deployed. An important question for the RL community to ask is:
<div class="focus-box">
<p>What pieces of the puzzle are we missing and what new methods are needed to push these ideas forward so that they become truly deployable?</p>
</div>

This workshop aims to place a spotlight on this topic, with the goal of advancing RL and CB algorithms towards becoming a widespread industry standard. To this end, we invite contributions on theory and practice of RL aimed at facilitating deployment to real-world problems, examples of which include but are not limited to:
* __Methods to enable deployability in RL:__ offline RL, offline policy evaluation (OPE), offline to online RL, safe learning and exploration, preference learning, learning in partially observable settings, interpretable policies in high-stakes settings, and methods for improving deployment efficiency.
* __Applications in personalization and recommendation systems:__ applications of RL and CB methods in technology platforms that interact with humans (e.g., audio and video recommendations, online advertising, LLMs).
* __Applications in industrial automation__: applications of RL and CB methods in the control of physical systems or allocation of resources (e.g., inventory management, ride-sharing, commercial cooling systems, data center congestion control).
* __Applications in decision systems for healthcare:__ applications of RL and CB methods in healthcare (e.g., managing chronic conditions, digital treatment recommendations, human-in-the-loop RL).

The above are only a handful of suitable topics. We welcome submissions on any topic that focuses on the RL deployment process. The submissions can be <b>4-8 pages in length</b> and be of either a theoretical/methodological or empirical nature.

<br>

## Keynote Speakers
<!-- Check talk details (title, abstract, speaker bio, slides) at this [page](speakers)! -->
<html>
    <div class="team-container">
        <div class="team-member">
            <img src="/assets/img/speakers/hamsa.jpg" alt="Hamsa Bastani">
            <p><a href="https://hamsabastani.github.io/">Hamsa Bastani</a>
            <br>Wharton, University of Pennsylvania</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/minmin.jpeg" alt="Minmin Chen">
            <p><a href="https://mchen24.github.io/">Minmin Chen</a>
            <br>Google Deepmind</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/aviral.jpg" alt="Aviral Kumar">
            <p><a href="https://aviralkumar2907.github.io/">Aviral Kumar</a>
            <br>Google DeepMind<br>CMU</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/john_langford.jpg" alt="Name 4">
            <p><a href="https://www.microsoft.com/en-us/research/people/jcl/">John Langford</a>
            <br>Microsoft Research NYC</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/hong.png" alt="Name 1">
            <p><a href="https://hsnamkoong.github.io/">Hongseok Namkoong</a>
            <br>Columbia Business School</p>
        </div>
    </div>
</html>


## Panel
<!-- ##### Challenges in RL deployment 
Time: 10:45-11:30 -->
<html>
    <div class="team-container">
        <div class="team-member">
            <img src="/assets/img/speakers/bill.jpg" alt="Zheqing (Bill) Zhu">
            <p><a href="https://www.zheqingbillzhu.com/">Zheqing (Bill) Zhu</a>
            <br>Meta<br><b>Moderator</b></p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/remi.png" alt="Remi Cadane">
            <p><a href="http://remicadene.com/">Remi Cadane</a>
            <br>Hugging Face</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/dhruv.jpg" alt="Dhruv Madeka">
            <p><a href="https://dhruvmadeka.com/">Dhruv Madeka</a>
            <br>Amazon</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/kaushik.jpg" alt="Kaushik Subramanian">
            <p><a href="https://ai.sony/people/Kaushik-Subramanian/">Kaushik Subramanian</a>
            <br>Sony AI</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/blank.png" alt="TBA">
            <p>More panelists to be announced!</p>
        </div>
    </div>
</html>


## Schedule

The schedule below is still tentative and subject to change.

|-------------|:-------------|
|__AM__&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;||
| 08:55 - 09:00 | Opening remarks |
| 09:00 - 09:35 | Keynote 1 + Q&A |
| 09:35 - 10:10 | Keynote 2 + Q&A |
| 10:10 - 11:25 | Morning poster session + coffee break |
| 11:25 - 12:00 | Keynote 3 + Q&A |



|-------------|:-------------|
|__PM__&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;||
| 12:00 - 01:00 | Lunch break
| 01:00 - 01:35 | Keynote 4 + Q&A |
| 01:35 - 02:10 | Keynote 5 + Q&A |
| 02:10 - 03:10 | Afternoon poster session + coffee break |
| 03:10 - 03:55 | Panel: Challenges surrounding RL deployment |
| 03:55 - 04:00 | Concluding remarks |

<br>


## Organizers
<html>
    <div class="team-container">
        <div class="team-member">
            <img src="/assets/img/organizers/jalaj.jpg" alt="Jalaj Bhandari">
            <a href="http://www.columbia.edu/~jb3618/">Jalaj Bhandari</a>
            <p>Meta</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/organizers/yonathan.jpg" alt="Yonathan Efroni">
            <p><a href="https://sites.google.com/view/yonathan-efroni/home">Yonathan Efroni</a>
            <br>Meta</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/organizers/mohammad.jpeg" alt="Mohammad Ghavamzadeh">
            <p><a href="https://mohammadghavamzadeh.github.io/">Mohammad Ghavamzadeh</a>
            <br>Amazon</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/organizers/daniel.jpeg" alt="Daniel R. Jiang">
            <p><a href="https://danielrjiang.github.io/">Daniel R. Jiang</a>
            <br>Meta</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/organizers/aldo.jpg" alt="Aldo Pacchiano">
            <p><a href="https://www.aldopacchiano.ai/">Aldo Pacchiano</a>
            <br>Boston University</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/organizers/yi.jpg" alt="Yi Wan">
            <p><a href="https://sites.google.com/view/yi-wan">Yi Wan</a>
            <br>Meta</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/organizers/kelly.jpeg" alt="Kelly W. Zhang">
            <p><a href="https://kellywzhang.github.io/">Kelly W. Zhang</a>
            <br>Columbia Business School</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/organizers/angela.jpg" alt="Angela Zhou">
            <p><a href="https://angelamzhou.github.io/">Angela Zhou</a>
            <br>Marshall School of Business, USC</p>
        </div>
    </div>
</html>


<!-- ## Sponsors

<html>
    <div class="sponsor-container">
        <div class="sponsor">
            <img src="/assets/img/sponsors/ubiquant.jpg" alt="Ubiquant">
            <p class="caption"><a href="https://www.ubiquant.com/website/home">Ubiquant</a></p>
        </div>
        <div class="sponsor" >
            <img src="/assets/img/sponsors/sambanova.png" alt="SambaNova Systems" max-width=300px>
            <p class="caption"><a href="https://sambanova.ai/">SambaNova Systems</a></p>
        </div>
        <div class="sponsor" >
            <img src="/assets/img/sponsors/apple.png" alt="Apple" max-width=300px>
            <p class="caption"><a href="https://www.apple.com/">Apple</a></p>
        </div>
        <div class="right-half"></div> Empty right-half

    </div>
</html> -->

<style>
    /* Style for the team container */
.team-container {
    display: grid;
    grid-template-columns: repeat(5, 1fr); /* Display 3 members per row */
    gap: 5px;
    max-width: 1000px;
    padding: 20px;
}


@media (max-width: 768px) {
    .team-container {
        grid-template-columns: repeat(2, 1fr); /* Display 2 members per row on smaller screens */
    }
}

/* Style for each team member */
.team-member {
    text-align: center;
    background-color: #fff;
    padding: 0px;
    width: 175px; /* Set a fixed width for consistent circle appearance */
    height: 260px; /* Set a fixed height for consistent circle appearance */
    /* box-shadow: 0px 3px 6px rgba(0, 0, 0, 0.1); */
    overflow: hidden; /* Hide any image overflow */
}


.team-member h3 {
    font-size: 16px;
    color: #333;
}

.team-member img {
  object-fit: cover;
  border-radius:50%;
  width: 150px;
  height: 150px;
  padding: 10px;
}

.sponsor-container {
    display: flex;
    gap: 5px;
}

.sponsor {
    flex: 1;
    margin: 10px;
    text-align: center;
    box-sizing: border-box;
    height: 50px;
    width: 50px;
}

.sponsor img {  
    width: 100%; /* Make the image take up 100% of the figure's width */
    height: 100%;
    object-fit: contain; 
}

.caption {
    margin-top: 12px; /* Adjust the margin to control the gap between the figure and the caption */
}

.right-half {
    flex: 1; /* Each figure takes up 50% of the available width */
    height: 500px; /* Set a fixed height for all figures (adjust the value as needed) */
}

.news-box {
    border: 1px solid #ccc;
    padding: 10px;
    width: 700px;
    margin: 0 auto;
    background-color: #f9f9f9;
}

.focus-box {
    border: 0px;
    padding: 0px;
    max-width: 600px;
    margin: 0 auto;
    text-align: center;
    font-style: italic;
}


@media (max-width: 700px) {
    .news-box {
        width: 100%; /* Adjust width to fit the screen */
    }
}
</style>

<br><br>