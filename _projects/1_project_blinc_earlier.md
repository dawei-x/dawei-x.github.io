---
layout: page
title: CLARA
description: An agentic analytics system that extracts semantic representations as shared analytics artifacts to support agent retrieval and reasoning.
img: assets/img/blinc_earlier_view.png
importance: 3
category: prototypes
---


**Paper:** [CLARA: An AI-Augmented Analytics Dashboard for Collaboration Literacy](https://link.springer.com/chapter/10.1007/978-3-032-29755-6_23) &middot; [arXiv](https://arxiv.org/abs/2605.17259)

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/clara_workflow.png" title="CLARA system overview" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
System Workflow. (A) CLARA transcribes discussion in real time, computes psycholinguistic metrics, and invokes the LLM to produce collaboration assessments and concept maps. (B) Transcripts and artifacts are embedded and indexed in distinct database collections. (C) Users can interact with LLM-produced artifacts through the dashboard; (D) The CLARA Agent reasons and iteratively calls tools to query different artifacts for synthesizing responses; (E) The interface where users chat with the agent.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/blinc_earlier_view.png" title="Earlier dashboard iteration (BLINC)" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    An earlier iteration of the dashboard (BLINC), showing the psycholinguistic metrics and the <em>Discussion Pulse</em> rolling summaries.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/clara_screenshot.png" title="CLARA interface" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    The current CLARA interface.
</div>
