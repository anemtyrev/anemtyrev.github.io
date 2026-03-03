<!-- Styling -->
<style> 
a {
    color: var(--link-color);
}

h1, h2, h3, h4, h5, h6 {
    font-style: normal;
    font-family: var(--title-font);
    color: var(--theme-color-dark);
}

.paper-entry {
    margin-bottom: 24px;
}

.paper-title {
    display: block;
    margin-bottom: 4px;
}

.paper-links {
    display: flex;
    align-items: baseline;
    gap: 12px;
}

.paper-links details {
    display: inline;
}

.paper-links details > summary {
    cursor: pointer;
    color: var(--link-color);
    text-decoration: underline;
    list-style: none;
    display: inline;
}

.paper-links details > summary::-webkit-details-marker {
    display: none;
}

.paper-links a {
    text-decoration: underline;
}

.abstract-text {
    margin-top: 8px;
    padding: 10px 14px;
    background: #f8fafc;
    border-left: 3px solid var(--link-color);
    border-radius: 0 4px 4px 0;
    font-size: 0.92em;
    line-height: 1.55;
}
</style>

<!-- Actual text -->

## Work in progress

<hr text-align="center" class="solid" width="100%">

<div class="paper-entry">
  <span class="paper-title"><strong>FOMC Responses to Credit Spreads</strong> [with Jeffrey Campbell] (2025).</span>
  <div class="paper-links">
    <details>
      <summary>Abstract</summary>
      <div class="abstract-text">Achieving the divine coincidence requires setting the private borrowing rate to its value under price flexibility, so the government borrowing rate should fall one-for-one with the private-government spread. Even when Phillips-curve shocks place the divine coincidence out of reach, tracking the natural rate on private borrowing reduces Keynesian fluctuations by offsetting IS-curve shocks. This paper uses an SVAR with the Gilchrist and Zakrajšek (2012) excess bond premium to measure the potential effects of such policy. We estimate that FOMC responses to credit spreads could reduce consumption fluctuations by 20 percent, inflation fluctuations by 10 percent, and unemployment fluctuations by 30 percent.</div>
    </details>
  </div>
</div>

<div class="paper-entry">
  <span class="paper-title"><strong>DSGE Identification and Estimation</strong> [with Jeffrey Campbell] (202X).</span>
</div>

<div class="paper-entry">
  <span class="paper-title"><strong>Targeted Local Projections</strong> [with Otilia Boldea] (2025).</span>
  <div class="paper-links">
    <details>
      <summary>Abstract</summary>
      <div class="abstract-text">Local projection (LP) and structural vector autoregression (SVAR) are commonly employed to estimate dynamic causal effects of macroeconomic policies at multiple horizons. With enough lags as controls, LP estimators have little bias but their variance can increase with the horizon due to accumulating additional shocks. Because they typically employ fewer lags or suffer from local misspecification, SVAR estimators typically incur higher bias, but their variance decreases with the horizon due to exponentiation. We propose to target the LP estimators towards their SVAR counterparts - constructed with fewer lags than LP at each horizon - to reduce their variance at the cost of incurring some bias. The resulting targeted LP estimator is a linear combination of the LP and SVAR estimators. We propose choosing this linear combination optimally to minimize the mean-squared error of the new estimator. Our simulations show that, under a locally misspecified SVAR model, targeting substantially reduces the LP variance at longer horizons while maintaining near-nominal coverage in small samples when a double bootstrap is employed.</div>
    </details>
    <a href="https://arxiv.org/abs/2603.00248">Paper</a>
  </div>
</div>