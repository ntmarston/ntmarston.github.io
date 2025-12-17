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
            <img src="/gallery-figs/impact-synthetic.png" alt="Figure">
            <figcaption>Radius inflation effects of giant impacts on sub-Neptunes (2025).</figcaption>
          </figure>

            <figure class="gallery-item">
              <img src="/gallery-figs/SamsingIlanFig4Reprod.png" alt="Figure">
              <figcaption>A reproduction of one of the Samsing and Ilan (10.1093/mnras/sty197) black hole binary-single scattering experiments (2025).</figcaption>
            </figure>

            <figure class="gallery-item">
              <img src="/gallery-figs/Section3-ExampleCurve.png" alt="Figure">
              <figcaption>Most feasible interior structures for the set of known cold super-puffs (2025).</figcaption>
            </figure>

            <figure class="gallery-item">
              <img src="/gallery-figs/Section3-Synthetic.png" alt="Figure">
              <figcaption> A set of modeled $\Mcore-R_p$ relation curves for TOI-1338 b which reproduce the planet's mass and radius observations. The inset shows the point where several of the curves achieve TOI-1338 b's measured radius (2025).</figcaption>
            </figure>

        </div>
    design:
      columns: 1
---
