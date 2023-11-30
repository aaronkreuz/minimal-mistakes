---
layout: splash
permalink: /
hidden: true
classes: wide
header:
  #overlay_color: "#000"
  #TODO: Style class with smaller images (80%), i.e. page__hero small
  #small_image: true
  # image: /assets/images/logo_wide.jpg
  # actions:
  #  - label: "<i class='fas fa-download'></i> Install now"
  #    url: "/docs/quick-start-guide/"
feature_row:
  - image_path: /assets/images/info_symbol_crop.jpg
    alt: "topic 1"
    title: "Infos"
    excerpt: "Alle Neuigkeiten und allgemeinen Informationen findet ihr hier!"
    url: "/info/"
    btn_class: "btn--primary"
    btn_label: "Zu den Infos"
  - image_path: /assets/images/anreise_symbol_crop.jpg
    alt: "topic 2"
    title: "Anreise"
    excerpt: "Alle Infos über Anreise und Austragungsort findet ihr hier!"
    url: "/anfahrt/"
    btn_class: "btn--primary"
    btn_label: "Zur Anreise"
  - image_path: /assets/images/archive_symbol_crop.jpg
    alt: "topic 3"
    title: "Archiv"
    excerpt: "Alle vergangenen Posts auf einen Blick findet ihr hier!"
    url: "/archive/"
    btn_class: "btn--primary"
    btn_label: "Zum Archiv"
---


{% include figure image_path="/assets/images/DAM_logo_black_small.jpg" alt="DAM logo" class="page__hero-image-xsmall" %}

{% include feature_row %}

<h2 id="page-title" class="page__title p-name" itemprop="headline">
Kommentare
</h2>

<p class="notice--info"><strong>&#x1F6C8;</strong> Kommentare müssen manuell freigegeben werden. Daher kann es bis zu einem Tag dauern bis diese hier erscheinen.</p>

<script defer src="https://85.215.39.85/js/commento.js"></script>
<div id="commento"></div>