---
layout: single
title: "Projects"
permalink: /projects/
classes: wide
toc: false

# Card data (you can add more items to this list)
projects_cards:
  - image_path: /assets/img/projects/splitter.png
    alt: "Splitter App"
    title: "Debt Settlement App"
    excerpt: "Full-stack web app for tracking and settling debts between users."
    url: "https://elena3er.pythonanywhere.com/"
    btn_label: "View Prototype"
    btn_class: "btn--primary"
    more_url: "/projects/splitter-app/"
    more_label: "Read details"

  - image_path: /assets/img/projects/uncertainty.png
    alt: "BNN predictive intervals"
    title: "Modelling Uncertainty with Bayesian Neural Networks"
    excerpt: "Tutorial and implementation of BNNs  a focus on uncertainty in the context of energy demand forecasting."
    url: "https://github.com/hertie-data-science-lab/tutorial-group_4"
    btn_label: "View on GitHub"
    btn_class: "btn--primary"
    more_url: "/projects/bnn-uncertainty/"
    more_label: "Read details"

  - image_path: /assets/img/projects/liar.png
    alt: "LIAR Topic"
    title: "LDA topic modeling on fake news detection"
    excerpt: "Application of LDT topic modeling on fake news detection using the LIAR dataset."
    url: "https://github.com/cpj97/LIAR_topics"
    btn_label: "View on GitHub"
    btn_class: "btn--primary"
    more_url: "/projects/liar-topic/"
    more_label: "Read details"

  - image_path: /assets/img/projects/bayesian.png
    alt: "Bayesian Modeling"
    title: "Hierarchical Bayesian Approach to undestrand violence in Colombia"
    excerpt: "Research on the relationship between ecomoic development violence in Colombia using a hierarchical Bayesian model."
    url: "https://github.com/cpj97/bayesian_modeling"
    btn_label: "View on GitHub"
    btn_class: "btn--primary"
    more_url: "/projects/bayesian-modeling/"
    more_label: "Read details"
---

{% comment %}
Renders a 3-across card row using the list above.
Each card shows an image (screenshot), title, short text, a GitHub button,
and (optionally) a “Read details” button to the project page.
{% endcomment %}

{% include feature_row id="projects_cards" %}
