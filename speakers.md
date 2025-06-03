---
layout: default
permalink: /speakers.html
title: Speakers
nav: true
nav_order: 4
---

## Speakers

<style>
.speaker-flex {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 3vw;
  margin-bottom: 2vw;
}
.speaker-card {
  text-align: center;
  background: #f8f8f8;
  border-radius: 12px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.07);
  padding: 1.5em 1em 1em 1em;
  margin: 1em;
  width: min(90vw, 320px);
}
.speaker-img {
  width: min(22vw, 160px);
  height: min(22vw, 160px);
  border-radius: 50%;
  object-fit: cover;
  margin-bottom: 0.7em;
}
.speaker-name {
  font-weight: bold;
  font-size: 1.1em;
}
.speaker-designation {
  font-size: 0.97em;
  color: #555;
  margin-bottom: 0.7em;
}
.speaker-abstract {
  display: none;
  text-align: justify;
  margin-top: 0.7em;
  background: #fff;
  border-radius: 8px;
  padding: 0.8em;
  box-shadow: 0 1px 4px rgba(0,0,0,0.06);
}
.speaker-toggle-btn {
  background:rgb(25, 81, 102);
  color: #fff;
  border: none;
  border-radius: 5px;
  padding: 0.4em 1em;
  cursor: pointer;
  font-size: 0.97em;
  margin-bottom: 0.2em;
}
.speaker-toggle-btn:active {
  background: #005fa3;
}
</style>

<div class="speaker-flex">
  <!-- Example Speaker Card: Duplicate and edit for each speaker -->
  <div class="speaker-card">
    <img src="assets/speaker_images/elliott_ash.png" alt="Elliott Ash" class="speaker-img"/>
    <div class="speaker-name"><a href="https://elliottash.com/" target="_blank" rel="noopener">Elliott Ash</a></div>
    <div class="speaker-designation">Associate Professor, ETH Zurich</div>
    <button class="speaker-toggle-btn" onclick="toggleAbstract(this)">Show Abstract</button>
    <div class="speaker-abstract">
      <strong>AI, Preferences, and Economics</strong><br>
      The under-appreciated secret ingredient in modern AI systems is that they are not just models of language -- they are models of human preferences. That gives us insight into when and why aligned LLMs will be useful tools in the economy and for social-science research. It also opens the door for a productive synergy between AI design and a science of human preferences -- i.e., economics. 
    </div>
  </div>
  <!-- Add more speaker-card blocks as needed -->
    <div class="speaker-card">
    <img src="assets/speaker_images/tanmay.png" alt="Tanmoy Chakraborty" class="speaker-img"/>
    <div class="speaker-name"><a href="https://tanmoychak.com/" target="_blank" rel="noopener">Tanmoy Chakraborty</a></div>
    <div class="speaker-designation">Associate Professor, IIT Delhi</div>
    <button class="speaker-toggle-btn" onclick="toggleAbstract(this)">Show Abstract</button>
    <div class="speaker-abstract">
      <strong>Towards Enhanced Conversational Dynamics for Effective Virtual Therapist-Assistive Counseling</strong><br>
      The increasing demand for digital healthcare, coupled with current infrastructure limitations, requires digital therapeutic interventions. My talk will focus on the design and implementation of Virtual Mental Health Assistants modules that serve as therapist-assistive mechanisms to automate their complex work cycle. We work on building novel LLM-based methods for dialogue understanding, summarization, and generation, and our research captures the intricacies of therapeutic communication while incorporating signs into human behavior analysis. In support of this, we also develop datasets and resources, many of which are first-of-its-kind, including HOPE, MEMO, MENTAL-TRUST, MentalCLOUDS, and BeCOPe, all of which are available for research purposes. 
    </div>
  </div>





   <div class="speaker-card">
    <img src="assets/speaker_images/tommaso.png" alt="Tommaso Casell" class="speaker-img"/>
    <div class="speaker-name"><a href="https://www.rug.nl/staff/t.caselli/?lang=en" target="_blank" rel="noopener">Tommaso Casell</a></div>
    <div class="speaker-designation">Assistant professor, University of groningen</div>
    <button class="speaker-toggle-btn" onclick="toggleAbstract(this)">Show Abstract</button>
    <div class="speaker-abstract">
      <strong>Framing Perspectives on Environmental Sustainability</strong><br>
      Communication is at the core of every human activity. The way we speak, or narrate something, activates (consciously or unconsciously) perspectives on things that happen in the world. These perspectives are not simple points of view but they encode and influence our perception of events and phenomena. A ubiquitous device to encode and convey such perspectives is framing. The difference between "climate change" and "climate crisis" is primarily a difference in frames that these words activate in the minds of receivers: a "change" is more neutral and less urgent than a "crisis". In this talk, I will present and discuss ongoing research on frame activation and generation at the lexical level concerning the food transition and parliamentary debates on climate change in the European Union.
    </div>
  </div>
</div>

<script>
function toggleAbstract(btn) {
  var abs = btn.nextElementSibling;
  if (abs.style.display === "block") {
    abs.style.display = "none";
    btn.textContent = "Show Abstract";
  } else {
    abs.style.display = "block";
    btn.textContent = "Hide Abstract";
  }
}
</script>




[def]: ttp://elliottash.com/wp-content/uploads/2018/11/head-shot-DGESS-1-1.jp