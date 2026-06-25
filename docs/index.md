---
icon: lucide/house
---

# \(\infty\)RETIS


\(\infty\)RETIS is a **enhanced sampling** method for rare events in molecular simulations, allowing efficient sampling of unbiased dynamical trajectories between metastable states and a rigorous route to rate constants, mean first-passage times, and transition mechanisms.

## How to Read This Documentation

### Background Theory
For the ones unaquainted with path sampling or Transition Interface Sampling
(TIS), understanding the theory behind \(\infty\)RETIS may be challenging. Here
we provide the fundamental background theory required for understanding \(\infty\)RETIS:

1. [MD, MC & Replica Exchange](background/md_and_mc.md)
2. [The Rare Event Problem](background/rare_events.md)
3. [TPS](background/transition_path_sampling.md)
4. [TIS & RETIS](background/transition_interface_sampling.md)

and also the two advancements defining \(\infty\)RETIS

* [Infinite Replica Exchange](background/infinite_replica_exchange.md)
* [Asynchronous Replica Exchange](background/async_replica_exchange.md)
* [Analysis](background/analysis.md)
* [Predictive Power](background/predictive_power.md)

and blablabla Inf-init

* [Inf-init](background/inf_init.md)

### \(\infty\)RETIS Software

## Publications

<script id="MathJax-script" src="https://unpkg.com/mathjax@3/es5/tex-mml-chtml.js"></script>
<script>
  window.MathJax = {
    tex: { inlineMath: [["\\(", "\\)"]], displayMath: [["\\[", "\\]"]], processEscapes: true },
    options: { ignoreHtmlClass: ".*|", processHtmlClass: "arithmatex" }
  };
  document$.subscribe(() => { MathJax.startup.output.clearCache(); MathJax.typesetClear(); MathJax.texReset(); MathJax.typesetPromise() })
</script>
