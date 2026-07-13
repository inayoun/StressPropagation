# Stress Propagation

## Context

In clinical medicine, physiology is often divided into specialties such as cardiology, neurology, and endocrinology. Similarly, wearable devices present heart rate, respiration, stress, and sleep as separate dashboards or tabs. However, lived experience does not occur in isolated systems. Stress, calmness, and emotion emerge as whole-body states through interactions between multiple physiological processes.

This project explores how biosignals might be represented as an interconnected, symbiotic system rather than as independent metrics.

Inspired by the idea of approaching data as a sensory medium—an approach embraced by data artist **Ryoji Ikeda**—this project investigates how biosignals can be experienced as an integrated physiological state instead of a collection of separate plots. Rather than reducing stress to a single marker, such as cortisol or heart rate changes, the visualization combines multiple physiological systems into a unified representation.

Like Ikeda's work, which evokes meaning beyond technical graphs, this visualization aims to reveal the relationships between physiological systems collected through wearable devices. Ultimately, the project became an exploration of how visualization influences the way we conceptualize the body. If we always see separate graphs, we think in separate systems. If we instead see relationships and synchrony, we begin to understand physiology as a networked organism.

---

## Process

### Early Iterations


The initial concepts represented each physiological system as a moving orb connected by dynamic lines, drawing inspiration from node-and-edge network visualizations. While the approach successfully illustrated relationships, the constantly changing connections became visually noisy and failed to communicate the underlying sense of continuity.

Subsequent iterations explored alternative forms where systems expanded and contracted, searching for a visual metaphor that better expressed interconnectedness.

### Final Prototype

The final design evolved into a radial graph with a shared circular baseline to represent unity and continuity across physiological systems. Each system expresses increases and decreases through wave-like motions that ebb and flow around the circle.

Relationships between systems are communicated through two forms of animated connections:

- **Shared directional movement** indicates systems moving in synchrony.
- **Push–pull motion** indicates systems moving in opposition.

Rather than emphasizing individual values, the visualization focuses on how physiological systems influence one another over time.

---

## Dataset

- **WESAD (Wearable Stress and Affect Detection Dataset)**
  - https://www.kaggle.com/datasets/orvile/wesad-wearable-stress-affect-detection-dataset

---

## Technology

### Signal Processing

- Python
- NumPy
- NeuroKit2
- SciPy

### Visualization

- TypeScript
- D3.js

### Statistical Processing

- Z-score normalization
- Normalized slope calculation
- Windowed means
- Temporal smoothing

---

## Reflection

- **Final Prototype**
  - https://inayoun.github.io/StressPropagation/
  
This project offered a different perspective on both physiology and data visualization.

When biosignals are presented as separate charts, we naturally think about the body as separate systems. By emphasizing relationships instead of isolated measurements, the visualization encourages a view of physiology as a network of interacting processes.

One of the most significant lessons was that representing relationships is considerably more difficult than representing values. Concepts such as synchrony, co-regulation, and interaction are inherently abstract, making their communication highly dependent on choosing effective visual metaphors and motion.


