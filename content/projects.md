---
title: 'Projects'
date: 2025-06-20
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: collection
    content:
      title: Selected Projects
      text:
      filters:
        folders:
          - project
    design:
      view: article-grid
      fill_image: false
      columns: 3

  - block: markdown
    content:
      title: Figure Gallery
      text: |
        <div class="figure-gallery">
          <!-- Add figures here. Each figure follows this format:
          <figure class="gallery-item">
            <img src="/gallery-figs/your-image.png" alt="Description">
            <figcaption>Your caption goes here (1-2 sentences).</figcaption>
          </figure>
          -->

          <figure class="gallery-item">
            <img src="/gallery-figs/placeholder.png" alt="Placeholder figure">
            <figcaption>Add your first figure to <code>static/gallery-figs/</code> and update this caption.</figcaption>
          </figure>

        </div>
    design:
      columns: 1
---
