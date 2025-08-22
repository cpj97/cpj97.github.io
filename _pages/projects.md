---
layout: single
title: "Projects"
permalink: /projects/
classes: wide
toc: false

# Card data (you can add more items to this list)
projects_cards:
  - image_path: /assets/img/projects/rag-shot.png
    alt: "Local RAG UI"
    title: "Local LLM RAG System"
    excerpt: "Qwen2 (0.6B, 4-bit) + Gradio UI for document Q&A. Panel to inspect retrieved sources."
    url: "https://github.com/<your-username>/<your-rag-repo>"
    btn_label: "View on GitHub"
    btn_class: "btn--primary"
    more_url: "/projects/local-rag/"        # link to the full write-up (optional)
    more_label: "Read details"

  - image_path: /assets/img/projects/saopaulo-maps.png
    alt: "Maps of police lethality"
    title: "Geospatial Analysis of Police Lethality in São Paulo"
    excerpt: "Census + mortality microdata; LISA clusters; spatial lag/error SAR models."
    url: "https://github.com/<your-username>/<your-saopaulo-repo>"
    btn_label: "View on GitHub"
    btn_class: "btn--primary"
    more_url: "/projects/police-saopaulo/"
    more_label: "Read details"

  - image_path: /assets/img/projects/bnn-plot.png
    alt: "BNN predictive intervals"
    title: "Modelling Uncertainty with Bayesian Neural Networks"
    excerpt: "Tutorial + case study showing predictive intervals vs point estimates."
    url: "https://github.com/<your-username>/<your-bnn-repo>"
    btn_label: "View on GitHub"
    btn_class: "btn--primary"
    more_url: "/projects/bnn-uncertainty/"
    more_label: "Read details"
---

{% comment %}
Renders a 3-across card row using the list above.
Each card shows an image (screenshot), title, short text, a GitHub button,
and (optionally) a “Read details” button to the project page.
{% endcomment %}

{% include feature_row id="projects_cards" %}
