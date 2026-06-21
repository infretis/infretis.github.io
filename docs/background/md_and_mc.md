---
icon: lucide/binary
---

# Molecular Dynamics, Monte Carlo & Replica Exchange

This page only introduces the ideas needed later for path sampling: MD generates physical trajectories, MC gives an accept/reject rule for sampling a target distribution, and replica exchange lets samples move between related ensembles.

<div style="display:flex; gap:1em; margin:1.2em 0;">
  <figure style="flex:1; margin:0; text-align:center;">
    <video controls muted loop playsinline style="width:100%; border-radius:6px;">
      <source src="../../media/md_cut.mp4" type="video/mp4">
    </video>
    <figcaption style="margin-top:0.4em; font-size:0.85em; color:var(--md-default-fg-color--light);">
      MD: deterministic dynamics from forces
    </figcaption>
  </figure>
  <figure style="flex:1; margin:0; text-align:center;">
    <video controls muted loop playsinline style="width:100%; border-radius:6px;">
      <source src="../../media/mc_cut.mp4" type="video/mp4">
    </video>
    <figcaption style="margin-top:0.4em; font-size:0.85em; color:var(--md-default-fg-color--light);">
      MC: trial moves accepted or rejected by probability
    </figcaption>
  </figure>
</div>

## Molecular Dynamics


## Monte Carlo


## Estimating ensemble properties

Both should equivalently calculate the same

* RDF and running difference.

## Replica Exchange Monte Carlo

## Replica Exchange Molecular Dynamics


<script id="MathJax-script" src="https://unpkg.com/mathjax@3/es5/tex-mml-chtml.js"></script>
<script>
  window.MathJax = {
    tex: { inlineMath: [["\\(", "\\)"]], displayMath: [["\\[", "\\]"]], processEscapes: true },
    options: { ignoreHtmlClass: ".*|", processHtmlClass: "arithmatex" }
  };
  document$.subscribe(() => { MathJax.startup.output.clearCache(); MathJax.typesetClear(); MathJax.texReset(); MathJax.typesetPromise() })
</script>
