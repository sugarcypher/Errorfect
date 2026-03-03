errorfect.com
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Errorfect - The Linguistic Autopsy</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }

    body {
      font-family: 'Courier New', monospace;
      background: #0a0a0a;
      color: #e0e0e0;
      line-height: 1.6;
      overflow-x: hidden;
    }

    .hero {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      padding: 2rem;
      background: radial-gradient(circle at center, #1a1a2e 0%, #0a0a0a 100%);
      position: relative;
    }

    .glitch-container {
      position: relative;
      font-size: clamp(3rem, 10vw, 8rem);
      font-weight: bold;
      margin-bottom: 2rem;
      text-align: center;
    }

    .glitch {
      position: relative;
      color: #ff006e;
      text-shadow: 0 0 20px rgba(255, 0, 110, 0.5);
    }

    .word-mask {
      color: #666;
      opacity: 0.3;
      text-decoration: line-through;
      display: inline-block;
      margin-right: 1rem;
    }

    .subtitle {
      font-size: clamp(1rem, 2.5vw, 1.5rem);
      color: #8892b0;
      text-align: center;
      margin-bottom: 3rem;
      max-width: 900px;
    }

    .scroll-indicator {
      font-size: 2rem;
      animation: bounce 2s infinite;
      color: #00f5ff;
    }

    @keyframes bounce {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(10px); }
    }

    section {
      max-width: 1200px;
      margin: 0 auto;
      padding: 4rem 2rem;
    }

    h2 {
      font-size: clamp(2rem, 5vw, 3rem);
      color: #ff006e;
      margin-bottom: 2rem;
      position: relative;
      display: inline-block;
    }

    h2::after {
      content: '';
      position: absolute;
      bottom: -10px;
      left: 0;
      width: 100%;
      height: 3px;
      background: linear-gradient(90deg, #ff006e, #00f5ff);
    }

    .reveal-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 3rem;
      margin: 3rem 0;
    }

    .reveal-card {
      background: #16213e;
      padding: 2rem;
      border-radius: 8px;
      border: 1px solid #ff006e33;
      transition: all 0.3s ease;
    }

    .reveal-card:hover {
      transform: translateY(-5px);
      border-color: #ff006e;
      box-shadow: 0 10px 30px rgba(255, 0, 110, 0.2);
    }

    .word-reveal {
      font-size: 2.5rem;
      font-weight: bold;
      margin-bottom: 1rem;
    }

    .masked-letter {
      color: #ff006e;
      text-decoration: line-through;
      opacity: 0.5;
    }

    .revealed-word {
      color: #00f5ff;
      display: block;
      font-size: 1.5rem;
      margin: 1rem 0;
    }

    .mechanism {
      color: #8892b0;
      font-size: 1rem;
      line-height: 1.8;
    }

    .art-gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
      gap: 2rem;
      margin: 3rem 0;
    }

    .art-piece {
      position: relative;
      border-radius: 8px;
      overflow: hidden;
      border: 2px solid #ff006e33;
      transition: all 0.3s ease;
    }

    .art-piece:hover {
      border-color: #00f5ff;
      box-shadow: 0 0 40px rgba(0, 245, 255, 0.3);
    }

    .art-piece img {
      width: 100%;
      height: auto;
      display: block;
    }

    .art-caption {
      position: absolute;
      bottom: 0;
      left: 0;
      right: 0;
      background: rgba(0, 0, 0, 0.9);
      padding: 1rem;
      color: #00f5ff;
      font-size: 0.9rem;
      transform: translateY(100%);
      transition: transform 0.3s ease;
    }

    .art-piece:hover .art-caption {
      transform: translateY(0);
    }

    /* renamed from .manifesto (banned word) */
    .field-notes {
      background: linear-gradient(135deg, #16213e 0%, #0f3460 100%);
      padding: 3rem;
      border-radius: 8px;
      border-left: 4px solid #ff006e;
      margin: 3rem 0;
    }

    .field-notes p {
      font-size: 1.1rem;
      margin-bottom: 1.5rem;
      color: #ccd6f6;
    }

    .key-insight {
      background: #0a0a0a;
      padding: 2rem;
      border-radius: 8px;
      border: 2px solid #00f5ff;
      margin: 2rem 0;
      font-size: 1.2rem;
      color: #00f5ff;
      text-align: center;
      font-weight: bold;
    }

    .surgical {
      color: #ff006e;
      font-style: italic;
    }

    .tag {
      display: inline-block;
      font-size: 0.85rem;
      padding: 0.25rem 0.6rem;
      border-radius: 999px;
      border: 1px solid #00f5ff55;
      color: #00f5ff;
      margin: 0.2rem 0.35rem 0 0;
      background: rgba(0, 245, 255, 0.06);
      white-space: nowrap;
    }

    .micro-protocol {
      margin-top: 1rem;
      padding: 1rem;
      border-radius: 8px;
      border: 1px dashed #00f5ff55;
      background: rgba(0, 0, 0, 0.35);
      color: #ccd6f6;
      line-height: 1.7;
    }

    .micro-protocol strong { color: #00f5ff; }

    footer {
      text-align: center;
      padding: 3rem 2rem;
      border-top: 1px solid #ff006e33;
      color: #8892b0;
    }

    @media (max-width: 768px) {
      .art-gallery { grid-template-columns: 1fr; }
      .reveal-grid { grid-template-columns: 1fr; }
    }

    .arrow {
      display: inline-block;
      color: #ff006e;
      margin: 0 1rem;
      font-size: 1.5rem;
    }
  </style>
</head>

<body>
  <div class="hero">
    <div class="glitch-container">
      <div class="glitch">
        <span class="word-mask">Perfect</span> ERRORFECT
      </div>
    </div>
    <div class="subtitle">
      Removing the first letter reveals the mechanism hiding inside the concept; the “mask” isn’t decoration — it’s social acceptability engineered into language.
    </div>
    <div class="scroll-indicator">↓</div>
  </div>

  <section>
    <h2>The Discovery</h2>
    <div class="field-notes">
      <p>
        We use words like <strong>perfect</strong>, <strong>normal</strong>, and <strong>control</strong> as if they describe reality. They rarely do.
        They behave more like <span class="surgical">cognitive operators</span>: they compress ambiguity, create ranking, and assign blame without announcing they’ve done it.
      </p>
      <p>
        In Errorfect, the first letter functions as <strong>linguistic camouflage</strong>. Remove it and the machinery becomes visible — which matters because visibility is the prerequisite for choice.
      </p>
    </div>

    <div class="key-insight">
      The mask isn’t part of the truth; it’s what makes the mechanism socially wearable.
    </div>
  </section>

  <section>
    <h2>The Autopsy</h2>
    <div class="reveal-grid">
      <div class="reveal-card">
        <div class="word-reveal">
          <span class="masked-letter">P</span>erfect
        </div>
        <div class="revealed-word">
          <span class="arrow">→</span> Er(ror)fect
        </div>
        <div class="mechanism">
          “Perfect” smuggles in a hidden standard; then it quietly charges interest when you can’t pay it.
          Seen cleanly: perfectionism is an <strong>error-producing loop</strong> — not excellence. The pursuit becomes the mistake.
        </div>
      </div>

      <div class="reveal-card">
        <div class="word-reveal">
          <span class="masked-letter">N</span>ormal
        </div>
        <div class="revealed-word">
          <span class="arrow">→</span> Or Mal (or bad)
        </div>
        <div class="mechanism">
          “Normal” manufactures a center and then declares the edges defective.
          Mechanism: <strong>social comparison + exclusion</strong>. It isn’t a measurement term; it’s a sorting term.
        </div>
      </div>

      <div class="reveal-card">
        <div class="word-reveal">
          <span class="masked-letter">C</span>ontrol
        </div>
        <div class="revealed-word">
          <span class="arrow">→</span> On Trol(l)
        </div>
        <div class="mechanism">
          “Control” implies stable command over unstable systems; reality laughs and you pay the anxiety tax.
          Mechanism: <strong>threat response management</strong> disguised as mastery.
        </div>
      </div>
    </div>
  </section>

  <!-- NEW: Use-cases + mental/therapeutic framing -->
  <section>
    <h2>Use Cases: Mental, Personal, Therapeutic</h2>

    <div class="field-notes">
      <p>
        Errorfect is a language-based intervention: not a diagnosis tool, not a moral philosophy, not a vibe.
        It’s a repeatable method for <span class="surgical">metacognitive de-fusion</span> — separating you from the spell a word is casting so you can decide what you actually mean.
      </p>
      <p>
        Clinically adjacent terms (used here in their standard meanings): <strong>cognitive reframing</strong> (CBT),
        <strong>cognitive defusion</strong> (ACT),
        <strong>externalization</strong> (narrative therapy),
        <strong>shame resilience</strong>,
        <strong>perfectionism reversal</strong>,
        and <strong>locus-of-control calibration</strong>.
      </p>
    </div>

    <div class="reveal-grid">
      <div class="reveal-card">
        <div class="word-reveal" style="font-size: 1.6rem;">
          Perfectionism reversal
        </div>
        <div class="mechanism">
          <span class="tag">CBT: cognitive distortions</span>
          <span class="tag">ACT: defusion</span>
          <span class="tag">Self-compassion</span>
          <div class="micro-protocol">
            <strong>When it hits:</strong> “This must be perfect.”<br />
            <strong>Run Errorfect:</strong> “Perfect” → “Errorfect.”<br />
            <strong>Translate:</strong> “A hidden standard is attacking me.”<br />
            <strong>Replace with a usable target:</strong> “Functional,” “clear,” “safe,” “version 1,” “good-enough-for-now.”<br />
            <strong>Therapeutic payoff:</strong> reduces shame spirals, procrastination, and compulsive checking by collapsing the false binary (perfect vs failure).
          </div>
        </div>
      </div>

      <div class="reveal-card">
        <div class="word-reveal" style="font-size: 1.6rem;">
          Norm pressure detox
        </div>
        <div class="mechanism">
          <span class="tag">Social comparison</span>
          <span class="tag">Minority stress lens</span>
          <span class="tag">Boundary clarity</span>
          <div class="micro-protocol">
            <strong>When it hits:</strong> “Be normal.” / “That’s not normal.”<br />
            <strong>Run the autopsy:</strong> “Normal” → “or mal.”<br />
            <strong>Translate:</strong> “A sorting rule is being enforced.”<br />
            <strong>Ask the only question that matters:</strong> “Normal for whom, in what context, by what metric?”<br />
            <strong>Therapeutic payoff:</strong> restores agency; converts vague social coercion into a debatable claim with missing measurement.
          </div>
        </div>
      </div>

      <div class="reveal-card">
        <div class="word-reveal" style="font-size: 1.6rem;">
          Control-anxiety calibration
        </div>
        <div class="mechanism">
          <span class="tag">Threat response</span>
          <span class="tag">Uncertainty tolerance</span>
          <span class="tag">Locus of control</span>
          <div class="micro-protocol">
            <strong>When it hits:</strong> “I must control this.”<br />
            <strong>Run the autopsy:</strong> “Control” → “on troll.”<br />
            <strong>Translate:</strong> “I’m trying to command a complex system from fear.”<br />
            <strong>Swap ‘control’ → ‘influence’:</strong> identify one lever you can pull now; release the rest.<br />
            <strong>Therapeutic payoff:</strong> reduces hypervigilance; replaces impossible total command with tractable influence.
          </div>
        </div>
      </div>

      <div class="reveal-card">
        <div class="word-reveal" style="font-size: 1.6rem;">
          Shame externalization (fast)
        </div>
        <div class="mechanism">
          <span class="tag">Narrative therapy</span>
          <span class="tag">De-shaming</span>
          <span class="tag">Identity separation</span>
          <div class="micro-protocol">
            <strong>Move:</strong> treat the word as the actor, not you.<br />
            <strong>Example:</strong> “Perfect is attacking me” (not “I’m failing”).<br />
            <strong>Then:</strong> name the mechanism (“standard injection,” “sorting,” “threat-response”).<br />
            <strong>Therapeutic payoff:</strong> interrupts identity fusion (“I am broken”) by relocating the problem to a linguistic device.
          </div>
        </div>
      </div>

      <div class="reveal-card">
        <div class="word-reveal" style="font-size: 1.6rem;">
          Relationship repair language
        </div>
        <div class="mechanism">
          <span class="tag">Nonviolent communication adjacent</span>
          <span class="tag">De-escalation</span>
          <span class="tag">Precision requests</span>
          <div class="micro-protocol">
            <strong>Spot it:</strong> “You always…” “Be normal…” “Just control yourself…”<br />
            <strong>Convert the spell into data:</strong> ask for the observable behavior + timeframe.<br />
            <strong>Replace absolutes:</strong> “always/never” → “often/this week/last time.”<br />
            <strong>Therapeutic payoff:</strong> reduces conflict driven by vague global judgments; turns accusations into actionable specifics.
          </div>
        </div>
      </div>

      <div class="reveal-card">
        <div class="word-reveal" style="font-size: 1.6rem;">
          Creative / artistic self-permission
        </div>
        <div class="mechanism">
          <span class="tag">Process orientation</span>
          <span class="tag">Flow protection</span>
          <span class="tag">Iteration</span>
          <div class="micro-protocol">
            <strong>Reframe:</strong> error isn’t a failure-state; it’s the engine-state.<br />
            <strong>Rename drafts:</strong> “prototype,” “field test,” “trial form.”<br />
            <strong>Therapeutic payoff:</strong> keeps the nervous system out of courtroom mode so the work can actually happen.
          </div>
        </div>
      </div>
    </div>

    <div class="key-insight">
      Errorfect is a measurement move: it turns “vibes with authority” into claims that require a metric — and most coercive words evaporate when asked to show their units.
    </div>

    <div class="field-notes">
      <p>
        A clean caution: this is not a substitute for professional care when someone is in crisis, dissociation, or severe mood instability.
        Used responsibly, it’s a precision tool for day-to-day cognition: defusing loaded language, reducing shame fuel, and restoring choice at the exact moment a word tries to seize the steering wheel.
      </p>
    </div>
  </section>

  <section>
    <h2>Visual Evidence</h2>
    <div class="art-gallery">
      <div class="art-piece">
        <img src="2C085A63-6E1D-4681-8980-BE6E655BCA72.png" alt="Errorfect artwork: glitch mechanism" />
        <div class="art-caption">
          The glitching isn’t aesthetic — it’s the mechanism breaking down, the error generating itself.
        </div>
      </div>
      <div class="art-piece">
        <img src="6148930D-E07F-49A3-BE78-7BE72B076ECF.jpeg" alt="Burning letters: masks destroyed" />
        <div class="art-caption">
          The burning P and N: arrows destroying the masks — iconoclasm aimed at false authority.
        </div>
      </div>
    </div>
  </section>

  <section>
    <h2>The Implications</h2>
    <div class="field-notes">
      <p>
        When someone says “perfection is here,” they may be activating an <span class="surgical">error-generating machine</span>.
        The packaging can be spiritual, corporate, parental, romantic — the machinery stays the same: a hidden metric that produces inadequacy.
      </p>
      <p>
        These words function like incantations. They work because we don’t see the mechanism.
        The <strong>P</strong> in perfect, the <strong>N</strong> in normal, the <strong>C</strong> in control — not just letters: masks that make coercion aspirational.
      </p>
      <p>
        This isn’t about “using the words incorrectly.” Often the words <em>are</em> the incorrectness: a mechanism pretending to be a description.
      </p>
    </div>

    <div class="key-insight">
      See the word without the mask; reclaim the steering wheel.
    </div>
  </section>

  <section>
    <h2>The Inversion</h2>
    <div class="field-notes">
      <p>
        Once you understand the mechanism, you can use it in <strong>reverse</strong>.
      </p>
      <p>
        Instead of stripping masks to reveal damage, you can <span class="surgical">build names whose surface and substrate agree</span> —
        where removing the mask doesn’t expose shame; it exposes the same intent, just more plainly.
      </p>
    </div>

    <div class="key-insight">
      If stripping the name reveals hope instead of harm,<br />
      the “mask” loses its power — both versions remain true.
    </div>

    <div class="reveal-grid">
      <div class="reveal-card">
        <h3 style="color: #ff006e; margin-bottom: 1.5rem;">The Given Name</h3>
        <div class="word-reveal">
          <span class="masked-letter">B</span>riar
          <span class="masked-letter">M</span>organ
          <span class="masked-letter">G</span>reenway
        </div>
        <div class="revealed-word">
          <span class="arrow">→</span> Riar Organ Reenway
        </div>
        <div class="mechanism">
          Beautiful surface (protected, rooted, moving forward)<br />
          Hidden mechanism: <strong>wreckage, biological function, endless cycles</strong>
        </div>
      </div>

      <div class="reveal-card">
        <h3 style="color: #00f5ff; margin-bottom: 1.5rem;">The Chosen Name</h3>
        <div class="word-reveal">
          <span style="color: #00f5ff;">A</span>xel
          <span style="color: #00f5ff;">T</span>win
          <span style="color: #00f5ff;">A</span>value
        </div>
        <div class="revealed-word">
          <span class="arrow">→</span> xel win value
        </div>
        <div class="mechanism">
          Intentional surface (pivot, mirroring, possessing worth)<br />
          Hidden mechanism: <strong>excel, victory, value</strong>
        </div>
      </div>
    </div>

    <div class="field-notes">
      <p>
        <strong>Axel</strong> works whether you say it or strip it — you get “excel” either way.
        The first letter becomes cosmetic, not camouflage; excellence remains.
      </p>
      <p>
        <strong>Twin → win</strong>: doubling collapses into victory — repetition becomes outcome.
      </p>
      <p>
        <strong>Avalue → value</strong>: possession of worth reveals worth itself; the substrate isn’t damage, it’s treasure.
      </p>
      <p style="color: #00f5ff; font-weight: bold; margin-top: 2rem;">
        This is the surgery in reverse: building language where the hidden layer reinforces life instead of undermining it.
      </p>
    </div>
  </section>

  <footer>
    <p>Errorfect © 2026 | A linguistic autopsy</p>
    <p style="margin-top: 1rem; font-size: 0.9rem;">The first letter is camouflage for what these concepts actually do</p>
  </footer>

  <script>
    // Subtle glitch effect on scroll
    window.addEventListener('scroll', () => {
      const scrolled = window.pageYOffset;
      const glitch = document.querySelector('.glitch');
      if (!glitch) return;
      if (scrolled > 100) {
        glitch.style.textShadow = `${Math.random() * 5}px ${Math.random() * 5}px 20px rgba(255, 0, 110, 0.5)`;
      }
    });

    // Reveal animation on scroll
    const observerOptions = {
      threshold: 0.2,
      rootMargin: '0px 0px -100px 0px'
    };

    const observer = new IntersectionObserver((entries) => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.style.opacity = '1';
          entry.target.style.transform = 'translateY(0)';
        }
      });
    }, observerOptions);

    document.querySelectorAll('.reveal-card, .art-piece, .field-notes, .key-insight').forEach(el => {
      el.style.opacity = '0';
      el.style.transform = 'translateY(30px)';
      el.style.transition = 'all 0.6s ease';
      observer.observe(el);
    });
  </script>
</body>
</html>
