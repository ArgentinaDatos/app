---
toc: false
---


<style>

.hero {
  display: flex;
  flex-direction: column;
  align-items: center;
  font-family: var(--sans-serif);
  padding: 4rem 0;
  text-wrap: balance;
  text-align: center;
}

.hero h1 {
  padding: 2rem 0;
  max-width: none;
  font-size: 14vw;
  font-weight: 900;
  line-height: 1;
  background: linear-gradient(30deg, var(--theme-foreground-focus), currentColor);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

.hero h2 {
  padding: 0;
  max-width: 34em;
  font-size: 20px;
  font-style: initial;
  font-weight: 500;
  line-height: 1.5;
  color: var(--theme-foreground-muted);
}

@media (min-width: 640px) {
  .hero h1 {
    font-size: 90px;
  }
}

</style>

<div class="hero">
  <h1>Argentina Datos</h1>
  <h2>Visualizaciones de datos de Argentina</h2>
</div>

<div class="grid grid-cols-2" style="grid-auto-rows: 504px;">

[//]: # (  <div class="card">${)

[//]: # (    resize&#40;&#40;width&#41; => Plot.plot&#40;{)

[//]: # (      title: "Brecha cambiaria",)

[//]: # (      subtitle: "Dólar oficial vs. Dólar informal en los últimos 5 años",)

[//]: # (      width,)

[//]: # (      y: {grid: true, label: "Brecha cambiaria"},)

[//]: # (      marks: [)

[//]: # (        Plot.ruleY&#40;[0]&#41;,)

[//]: # (        Plot.lineY&#40;dolares, {x: "fecha", y: "venta", stroke: "casa", tip: true}&#41;,)

[//]: # (        Plot.rectY&#40;brechaCambiariaPorDia, {x: "fecha", y: "brecha", strokeWidth: 1}&#41;)

[//]: # (      ])

[//]: # (    }&#41;&#41;)

[//]: # (  }</div>)

[//]: # (  <div class="card">${)

[//]: # (    resize&#40;&#40;width&#41; => Plot.plot&#40;{)

[//]: # (      title: "How big are penguins, anyway? 🐧",)

[//]: # (      width,)

[//]: # (      grid: true,)

[//]: # (      x: {label: "Body mass &#40;g&#41;"},)

[//]: # (      y: {label: "Flipper length &#40;mm&#41;"},)

[//]: # (      color: {legend: true},)

[//]: # (      marks: [)

[//]: # (        Plot.linearRegressionY&#40;penguins, {x: "body_mass_g", y: "flipper_length_mm", stroke: "species"}&#41;,)

[//]: # (        Plot.dot&#40;penguins, {x: "body_mass_g", y: "flipper_length_mm", stroke: "species", tip: true}&#41;)

[//]: # (      ])

[//]: # (    }&#41;&#41;)

[//]: # (  }</div>)
</div>

---

