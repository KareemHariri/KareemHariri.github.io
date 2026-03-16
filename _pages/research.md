---
layout: archive-full
title: "Research"
permalink: /research/
author_profile: false
sidebar: false
classes: wide
---
<style>
  .gallery-wrap {
    max-width: 1100px;
    margin: 0 auto;
  }

  .gallery-center {
    text-align: center;
  }

  .gallery-row {
    display: flex;
    gap: 40px;
    align-items: center;
    margin: 60px 0;
  }

  .gallery-text {
    flex: 1;
    text-align: left;
  }

  .gallery-thumb {
    border-radius: 6px;
    cursor: zoom-in;
    display: block;
    height: auto;
  }

  .gallery-thumb.small {
    width: 220px;
  }

  .gallery-thumb.medium {
    width: 500px;
  }

  .gallery-thumb.large {
    width: 360px;
  }

  .gallery-thumb.poster {
    width: 420px;
  }

  .lightbox {
    display: none;
    position: fixed;
    z-index: 9999;
    inset: 0;
    background: rgba(0, 0, 0, 0.88);
    justify-content: center;
    align-items: center;
    padding: 30px;
  }

  .lightbox.open {
    display: flex;
  }

  .lightbox img {
    max-width: 92vw;
    max-height: 88vh;
    border-radius: 8px;
    box-shadow: 0 8px 30px rgba(0,0,0,0.35);
  }

  .lightbox-close {
    position: absolute;
    top: 18px;
    right: 24px;
    font-size: 34px;
    line-height: 1;
    color: white;
    cursor: pointer;
    user-select: none;
  }

  @media (max-width: 900px) {
    .gallery-row {
      flex-direction: column;
      text-align: center;
    }

    .gallery-text {
      text-align: center;
    }
  }
</style>

This page highlights selected directions. See also the [Publications](/publications/).
## Research Areas
<div class="gallery-row">
    <div class="gallery-text">
      <h2>1. Quantum-Enhanced Spectroscopy</h2>
      <p>
        <em>[Physical Review X 15, 041009  (2025)](https://journals.aps.org/prx/abstract/10.1103/plh2-cr8s) - Quantum Frequency Combs for Sensing </em><br>
        <div style="height:1.5px;"></div>
       Optical frequency combs have emerged as a cornerstone for a wide range of areas, including spectroscopy, ranging, optical clocks, time and frequency transfer, waveform synthesis, and communications. However, quantum-mechanical fluctuations of the optical carrier impose fundamental performance limits on the precision of classical optical frequency combs, particularly in their use for interferometry and spectroscopy. Entanglement, as a quintessential quantum resource, allows for surpassing the fundamental limits of classical systems. Here, we introduce entanglement into the realm of optical frequency combs, formulating entangled dual-comb spectroscopy (EDCS) that surmounts the fundamental limits of classical DCS. EDCS capitalizes on tailored entangled structures across the frequency comb, enabling simultaneous detection of all comb lines below the standard quantum limit of classical DCS. Applying EDCS in gas detection, we achieve a 2.6-dB enhancement in signal-to-noise ratio and a 1.7-fold reduction in integration time over classical DCS, rendering EDCS particularly suited for dynamic chemical and biological sensing, where fast, precise measurements subject to power constraints are required. EDCS opens a new avenue for exploiting quantum frequency combs, underscoring their prospects in a plethora of applications in precision metrology, spectroscopy, and timekeeping.
      </p>
    </div>

    <img src="/images/EntDual.png"
         alt="EntDual"
         class="gallery-thumb medium"
         onclick="openLightbox(this.src)">
  </div>
   <hr style="margin:15px 0;">
  <div class="gallery-row">
    <div class="gallery-text">
      <h2>2. On-Chip Quantum Light Sources</h2>
      <p>
        <em>a. Advanced Photonics Nexus, Vol. 5, Issue 2, 026019 (March 2026) - foundry-compatible squeezed light source </em><br>
        <div style="height:1.5px;"></div>
      Squeezed light is a fundamental resource for a broad spectrum of quantum technologies, including precision metrology, secure communication, and quantum simulation and computing. The integration of squeezed-light sources with photonic circuits presents a transformative approach—not only offering compactness, stability, and scalability, but also enabling seamless high-fidelity on-chip generation, manipulation, and processing of quantum states without being hampered by inter-component quantum decoherence arising from loss and noise. In this work, we report the experimental generation of a two-mode squeezed vacuum state on a thin-film silicon-nitride photonic integrated circuit with normal group velocity dispersion of 6.3 × 10 5 fs 2 / m . Quadrature squeezing of − 2.1 dB ± 0.09 dB and anti-squeezing of 7.1 dB ± 0.04 dB are directly measured. To fully understand the dynamics of the quantum process, a comprehensive theoretical model is developed to capture the squeezing performance, showing excellent agreement with experimental results. Our findings highlight the potential of the thin-film silicon nitride platform that capitalizes on fully foundry-compatible fabrication technologies to advance robust, large-scale, and manufacturing-ready quantum information processing systems.
      </p>
    </div>

    <img src="/images/thin_onchip.png"
         alt="thin_onchip"
         class="gallery-thumb medium"
         onclick="openLightbox(this.src)">
  </div>
  <div class="gallery-row">
    <div class="gallery-text">
      <p>
        <em>b. arXiv:2509.10445 (2025) - Wafer-Scale Squeezed-Light Chips </em><br>
        <div style="height:1.5px;"></div>
      Squeezed-light generation in photonic integrated circuits (PICs) is essential for scalable continuous-variable (CV) quantum information processing. By suppressing quantum fluctuations below the shot-noise limit, squeezed states enable quantum-enhanced sensing and serve as a standard resource for CV quantum information processing. While chip-level squeezed-light sources have been demonstrated, extending this capability to the wafer level with reproducible strong squeezing to bolster large-scale quantum-enhanced sensing and information processing has been hindered by squeezed light's extreme susceptibility to device imperfections. Here, we report wafer-scale fabrication, generation, and characterization of two-mode squeezed-vacuum states on a fully complementary metal-oxide-semiconductor (CMOS)-compatible silicon nitride (Si3N4) PIC platform. Across a 4-inch wafer, 8 dies yield 2.9-3.1 dB directly measured quadrature squeezing with <0.2 dB variation, demonstrating excellent uniformity. This performance is enabled by co-integrating ultralow-loss, strongly overcoupled high-Q microresonators, cascaded pump-rejection filters, and low-loss inverse-tapered edge couplers. The measurements agree with a first-principles theoretical model parameterized solely by independently extracted device parameters and experimental settings. The measured squeezing level can be further improved by enhancing the efficiencies of off-chip detection and chip-to-fiber coupling. These results establish a reproducible, wafer-scale route to nonclassical-light generation in integrated photonics and lay the groundwork for scalable CV processors, multiplexed entanglement sources, and quantum-enhanced sensing.
      </p>
    </div>

    <img src="/images/On-Chip1.jpg"
         alt="On-Chip1"
         class="gallery-thumb medium"
         onclick="openLightbox(this.src)">
    </div>
  <hr style="margin:15px 0;">
<div class="gallery-row">
    <div class="gallery-text">
      <h2>3. Quantum Optical Gyroscope</h2>
      <p>
        <em>In preparation - Quantum-enhanced Resonant Fiber-Optic gyroscope </em><br>
        <div style="height:1.5px;"></div>
       Resonant fiber optic gyroscopes (RFOGs) are key enablers of compact and precise rotation sensing across aerospace, navigation, and fundamental physics. However, quantum fluctuations intrinsic to coherent light impose a fundamental noise floor, limiting the performance of classical RFOGs, especially in high-finesse configurations where long-term stability is essential. Squeezed states of light, as a canonical quantum resource, enable the suppression of these fluctuations and offer a route toward surpassing classical sensitivity limits.
Here, we introduce amplitude-squeezed light into the domain of resonant fiber optic gyroscopes, realizing a quantum-enhanced RFOG architecture compatible with conventional power levels and device components. By injecting a bright amplitude-squeezed beam into the sensing mode of a fiber ring resonator, we suppress the contribution of shot noise. This quantum-enhanced configuration yields a 2~dB reduction in detector noise floor, as confirmed by Allan deviation analysis.
Operating under practical conditions, our system demonstrates the feasibility of leveraging squeezed light to enhance sensitivity in optical gyroscopes. The approach is fully compatible with scalable and integrated photonic implementations, opening new avenues for low-power, high-performance inertial sensors. Quantum-enhanced RFOGs thus represent a promising frontier for next-generation precision metrology and navigation technologies.
      </p>
    </div>

    <img src="/images/gyro.jpg"
         alt="gyro"
         class="gallery-thumb medium"
         onclick="openLightbox(this.src)">
  </div>
  <hr style="margin:15px 0;">
  <div class="gallery-row">
    <div class="gallery-text">
      <h2>4. Quantum Radar</h2>
      <p>
        <em>a. In review - Quantum-Enhanced Integrated Sensing and Communication </em><br>
        <div style="height:1.5px;"></div>
       Integrated sensing and communication (ISAC) is emerging as a key enabler for spectrum-efficient and hardwareconverged
wireless networks. However, classical radar systems within ISAC architectures face fundamental limitations under low signal power and high-noise conditions. This paper proposes a novel framework that embeds quantum illumination radar into a base station to simultaneously support full-duplex classical communication and quantum-enhanced target detection. The resulting integrated quantum sensing and classical communication (IQSCC) system is optimized via a sum-rate maximization formulation subject to radar sensing constraints. The non-convex joint optimization of transmit power and beamforming vectors is tackled using the successive convex approximation technique. Furthermore, we derive performance bounds for classical and quantum radar protocols under the statistical detection theory, highlighting the quantum advantage in low signal-to-interferenceplus-noise ratio regimes. Simulation results demonstrate that the proposed IQSCC system achieves a higher communication throughput than the conventional ISAC baseline while satisfying the sensing requirement.
      </p>
    </div>

    <img src="/images/5GQRadar.png"
         alt="5GQRadar"
         class="gallery-thumb medium"
         onclick="openLightbox(this.src)">
  </div>
  <div class="gallery-row">
    <div class="gallery-text">
      <p>
        <em>b. Physical Review A 112, 052613  (2025) - Quantum Illumination </em><br>
        <div style="height:1.5px;"></div>
      Quantum illumination (QI) provides entanglement-enabled target detection enhancement, despite operating in an entanglement-breaking environment. Existing experimental studies of QI have utilized a Bayesian approach, assuming that the target is equally likely to be present or absent before detection, to demonstrate an advantage over classical target detection. However, such a premise breaks down in practical operational scenarios in which the prior probability is unknown, thereby hindering QI's applicability to real-world target detection scenarios. In this work, we experimentally implement the phase-conjugate receiver architecture previously envisioned for quantum illumination based target detection, and adopt the Neyman-Pearson criterion in lieu of the error probability for equally likely target absence or presence as our figure of merit for QI. We experimentally demonstrate an unconditional quantum advantage over the optimal classical-illumination protocol as benchmarked by the receiver operating characteristic, which examines detection probability versus false-alarm probability without resorting to known prior probabilities. Our work represents a critical advancement in adapting quantum-enhanced sensing to practical operational settings.
      </p>
    </div>

    <img src="/images/QRadar.jpg"
         alt="QRadar"
         class="gallery-thumb medium"
         onclick="openLightbox(this.src)">
    </div>
  <hr style="margin:15px 0;">
<div class="gallery-row">
    <div class="gallery-text">
      <h2>5. Quantum Measurement of Signal Amplitude and Phase</h2>
      <p>
        <em>Physical Review A 100, 032119  (2019) - Schemes for measuring quantum systems </em><br>
        <div style="height:1.5px;"></div>
      The weak value, the average result of a weak measurement, has proven useful for probing quantum and
classical systems. Examples include amplifying small signals, investigating quantum paradoxes, and elucidating
fundamental quantum phenomena such as geometric phase. A key characteristic of the weak value is that it
can be complex, in contrast to a standard expectation value. However, typically only either the real or imaginary
component of the weak value is determined in a given experimental setup.Weak measurements can be used to, in
a sense, simultaneously measure noncommuting observables. This principle was used in the direct measurement
of the quantum wave function. However, the wave function’s real and imaginary components, given by a
weak value, are determined in different setups or on separate ensembles of systems, putting the procedure’s
directness in question. To address these issues, we introduce and experimentally demonstrate a general method
to simultaneously read out both components of the weak value in a single experimental apparatus. In particular,
we directly measure the polarization state of an ensemble of photons using weak measurement.With our method,
each photon contributes to both the real and imaginary parts of the weak-value average. On a fundamental level,
this suggests that the full complex weak value is a characteristic of each photon measured.
      </p>
    </div>

    <img src="/images/Weak.png"
         alt="Weak"
         class="gallery-thumb large"
         onclick="openLightbox(this.src)">
  </div>
  <hr style="margin:15px 0;">

## 6. Quantum Atomic Clock
<em>Ongoing Project</em><br>



<div id="lightbox" class="lightbox" onclick="closeLightbox(event)">
  <span class="lightbox-close" onclick="closeLightbox(event)">&times;</span>
  <img id="lightbox-img" src="" alt="Expanded gallery image">
</div>

<script>
  function openLightbox(src) {
    document.getElementById('lightbox-img').src = src;
    document.getElementById('lightbox').classList.add('open');
    document.body.style.overflow = 'hidden';
  }

  function closeLightbox(event) {
    if (
      event.target.id === 'lightbox' ||
      event.target.classList.contains('lightbox-close')
    ) {
      document.getElementById('lightbox').classList.remove('open');
      document.getElementById('lightbox-img').src = '';
      document.body.style.overflow = '';
    }
  }

  document.addEventListener('keydown', function (event) {
    if (event.key === 'Escape') {
      document.getElementById('lightbox').classList.remove('open');
      document.getElementById('lightbox-img').src = '';
      document.body.style.overflow = '';
    }
  });
</script>

