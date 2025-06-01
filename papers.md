---
layout: default
permalink: /papers.html
title: Accepted papers
# description: This is just another page
nav: true
nav_order: 3
---


## List of Accepted Papers

<style>
.paper-list-flex {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 1.5em;
  margin-top: 2em;
}
.paper-card {
  background: #f8f8f8;
  border-radius: 12px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.07);
  padding: 1.2em 1.2em 1em 1.2em;
  width: 60vw;
}
.paper-title {
  font-weight: bold;
  font-size: 1.08em;
  margin-bottom: 0.3em;
}
.paper-authors {
  font-size: 0.97em;
  color: #555;
  margin-bottom: 0.7em;
}
.paper-details {
  display: none;
  text-align: justify;
  margin-top: 0.7em;
  background: #fff;
  border-radius: 8px;
  padding: 0.8em;
  box-shadow: 0 1px 4px rgba(0,0,0,0.06);
}
.paper-toggle-btn {
  background:rgb(10, 100, 107);
  color: #fff;
  border: none;
  border-radius: 5px;
  padding: 0.4em 1em;
  cursor: pointer;
  font-size: 0.97em;
  margin-bottom: 0.2em;
}
.paper-toggle-btn:active {
  background: #005fa3;
}
</style>

<div class="paper-list-flex">
  <!-- Example Paper Card: Duplicate and edit for each paper -->
  <div class="paper-card">
    <div class="paper-title">An Exploratory Analysis of Open Large Language Model on Conversational Safety Annotations</div>
    <div class="paper-authors">Raina Cao, UBC Canada | Lisa Yw Tang, Northeastern University</div>
    <button class="paper-toggle-btn" onclick="togglePaperDetails(this)">Show Details</button>
    <div class="paper-details">
      <strong>Abstract:</strong> This is the abstract or details of the paper.
    </div>
  </div>
  <!-- Add more paper-card blocks as needed -->
</div>

<script>
function togglePaperDetails(btn) {
  var details = btn.nextElementSibling;
  if (details.style.display === "block") {
    details.style.display = "none";
    btn.textContent = "Show Details";
  } else {
    details.style.display = "block";
    btn.textContent = "Hide Details";
  }
}
</script>


