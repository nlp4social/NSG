---
layout: default
permalink: /speakers.html
title: Speakers
nav: true
nav_order: 4
---

## Keynote Speakers

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
    <div class="speaker-name"><a href="https://www.rug.nl/staff/t.caselli/?lang=en" target="_blank" rel="noopener">Tommaso Caselli</a></div>
    <div class="speaker-designation">Assistant professor, University of Groningen, Netherlands</div>
    <button class="speaker-toggle-btn" onclick="toggleAbstract(this)">Show Abstract</button>
    <div class="speaker-abstract">
      <strong>Framing Perspectives on Environmental Sustainability</strong><br>
      Communication is at the core of every human activity. The way we speak, or narrate something, activates (consciously or unconsciously) perspectives on things that happen in the world. These perspectives are not simple points of view but they encode and influence our perception of events and phenomena. A ubiquitous device to encode and convey such perspectives is framing. The difference between "climate change" and "climate crisis" is primarily a difference in frames that these words activate in the minds of receivers: a "change" is more neutral and less urgent than a "crisis". In this talk, I will present and discuss ongoing research on frame activation and generation at the lexical level concerning the food transition and parliamentary debates on climate change in the European Union.
    </div>
  </div>
  </div>

----
## Invited Speakers

<div class="speaker-flex">
  <!-- Example Speaker Card: Duplicate and edit for each speaker -->
  <div class="speaker-card">
    <img src="assets/speaker_images/Hasan.jpg" alt="Mohammad Rashedul Hasan" class="speaker-img"/>
    <div class="speaker-name"><a href="https://www.linkedin.com/in/rashedhasan00/" target="_blank" rel="noopener">Mohammad Rashedul Hasan</a></div>
    <div class="speaker-designation">Early Career Researcher, University of Nebraska-Lincoln</div>
    <button class="speaker-toggle-btn" onclick="toggleAbstract(this)">Show Abstract</button>
    <div class="speaker-abstract">
      <strong>Bridging Modalities, Improving Lives: How Multimodal AI Systems Can Enhance Educational Equity and Outcomes</strong><br>
      This talk explores the transformative potential of multimodal AI systems, integrating natural language processing and vision capabilities, to advance educational interventions and improve learning outcomes. At the Human-First Artificial Intelligence Lab (HAL 2.0), our research on modeling complex longitudinal experiential (LE) data, capturing students' cognitive, emotional, and behavioral dynamics over time, has highlighted significant challenges in achieving generalizable insights. Drawing from our NSF-supported research on the "Messages From A Future You" AI system, which initially explored methods like large language models for analyzing noisy, sparse, and heterogeneous student data collected throughout an academic semester, we encountered limitations in generalizing predictive models across student cohorts and contexts. To overcome these fundamental challenges inherent in LE data modeling, we developed a novel multimodal framework, leveraging vision-language models. By transforming LE data into complementary textual narratives and visual representations, our approach is specifically designed to capture intricate structural dynamics and overcome data limitations, enabling forecasting of learning outcomes and behavioral attributes with greater precision and robust generalizability. This multimodal AI framework shows promising potential for delivering personalized interventions informed by the nuanced variations in students' learning experiences, thereby enhancing educational equity and outcomes, while establishing a foundational paradigm that can extend beyond education to healthcare, mental wellness, and other domains where understanding complex human experiences is essential for positive social impact.
    </div>
  </div>
  <!-- Add more speaker-card blocks as needed -->
  <div class="speaker-card">
    <img src="assets/speaker_images/shivani.png" alt="Shivani Kumar" class="speaker-img"/>
    <div class="speaker-name"><a href="https://www.si.umich.edu/people/shivani-kumar" target="_blank" rel="noopener">Shivani Kumar</a></div>
    <div class="speaker-designation">Postdoctoral Fellow, University of Michigan</div>
    <button class="speaker-toggle-btn" onclick="toggleAbstract(this)">Show Abstract</button>
    <div class="speaker-abstract">
      <strong>Are Rules Meant to be Broken? Understanding Multilingual Moral Reasoning as a Computational Pipeline with UniMoral</strong><br>
      Moral reasoning is fundamental to human decision-making, influencing social interactions, policy-making, and ethical AI development. However, its computational study remains fragmented, with existing NLP research relying on disparate datasets and isolated tasks. To advance NLP for social good, we introduce UniMoral, a multilingual dataset designed to facilitate the development of AI systems that understand and navigate ethical dilemmas in diverse cultural settings. UniMoral integrates psychologically grounded and real-world moral dilemmas from social media, annotated with action choices, ethical principles, contributing factors, and consequences, alongside annotators’ moral and cultural profiles. Recognizing the cultural relativity of moral reasoning, UniMoral spans six languages—Arabic, Chinese, English, Hindi, Russian, and Spanish—enabling cross-cultural analysis. We assess its impact through benchmark evaluations of three large language models (LLMs) across four tasks: action prediction, moral typology classification, factor attribution analysis, and consequence generation. Our findings highlight that while LLMs can leverage implicit moral contexts, significant challenges remain in ensuring these models reason ethically across diverse sociocultural landscapes. UniMoral lays the foundation for more equitable, context-aware AI systems, fostering NLP applications that promote fairness, inclusivity, and ethical awareness in automated decision-making.
    </div>
  </div>
    <div class="speaker-card">
    <img src="assets/speaker_images/shubham.png" alt="Shubham Kumar Nigam" class="speaker-img"/>
    <div class="speaker-name"><a href="https://sites.google.com/view/shubhamkumarnigam/" target="_blank" rel="noopener">Shubham Kumar Nigam</a></div>
    <div class="speaker-designation">PhD. Student, Indian Institute of Technology, Kanpur</div>
    <button class="speaker-toggle-btn" onclick="toggleAbstract(this)">Show Abstract</button>
    <div class="speaker-abstract">
      <Strong>NyayaSutra: Enabling Reliable and Interpretable Legal Judgment through Structured Thinking</Strong>strong
      In high-stakes domains like law, opaque AI models pose a significant barrier to real-world adoption. Legal professionals demand not just accurate predictions but interpretable reasoning paths that align with judicial logic. While explainability techniques have emerged to address this, they often provide post-hoc justifications rather than surfacing the actual reasoning that led to a decision, leading to a growing gap between model outputs and human trust.

NyayaSutra introduces an interpretable and reliable AI framework for legal judgment prediction and reasoning, tailored to the Indian judiciary. It leverages a structured thinking paradigm, breaking down judgments into rhetorical segments, Facts, Issues, Arguments, Reasoning, and Decision, to ensure transparency and traceability. The system employs hybrid legal retrieval, instruction-tuned LLMs trained on annotated Indian judgments, and GRPO-based optimization using structured “thinking tokens.”

By making legal reasoning interpretable from the ground up, NyayaSutra empowers legal professionals, researchers, and policymakers with factual, explainable, and trustworthy AI outputs, contributing meaningfully to the larger vision of NLP for Social Good.
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




