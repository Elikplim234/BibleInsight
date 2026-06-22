<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Confirmation Of Jesus Being The Word</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,700;0,900;1,400;1,700&family=Lora:ital,wght@0,400;0,600;1,400&display=swap" rel="stylesheet" />
    <style>
        *, *::before, *::after {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        :root {
            --bg-deep: #0B132B;
            --bg-card: #1C2541;
            --accent-cyan: #00B4D8;
            --accent-glow: rgba(0, 180, 216, 0.15);
            --gold: #D4AF37;
            --gold-muted: #AA8B2C;
            --text-main: #F4F6F9;
            --text-muted: #A5AEC0;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            background: var(--bg-deep);
            color: var(--text-main);
            font-family: 'Lora', Georgia, serif;
            line-height: 1.8;
            min-height: 100vh;
        }

        /* ── Header ── */
        header {
            position: relative;
            text-align: center;
            padding: 100px 24px 60px;
            overflow: hidden;
        }

        header::before {
            content: '';
            position: absolute;
            inset: 0;
            background: radial-gradient(ellipse 60% 50% at 50% 40%, rgba(0, 180, 216, 0.12) 0%, transparent 70%);
            pointer-events: none;
        }

        .eyebrow {
            font-family: 'Lora', serif;
            font-style: italic;
            font-size: 0.9rem;
            letter-spacing: 0.25em;
            color: var(--accent-cyan);
            text-transform: uppercase;
            margin-bottom: 20px;
        }

        h1 {
            font-family: 'Playfair Display', Georgia, serif;
            font-size: clamp(2.2rem, 6vw, 4rem);
            font-weight: 900;
            line-height: 1.2;
            color: var(--text-main);
            max-width: 800px;
            margin: 0 auto 28px;
        }

        h1 em {
            font-style: italic;
            color: var(--gold);
        }

        .header-rule {
            width: 100px;
            height: 3px;
            background: linear-gradient(90deg, transparent, var(--accent-cyan), transparent);
            margin: 0 auto 32px;
            border-radius: 2px;
        }

        .header-refs {
            display: flex;
            justify-content: center;
            gap: 12px;
            flex-wrap: wrap;
        }

        .ref-badge {
            font-family: 'Playfair Display', serif;
            font-size: 0.8rem;
            font-style: italic;
            color: var(--bg-deep);
            background: var(--gold);
            padding: 6px 16px;
            border-radius: 30px;
            font-weight: 700;
            letter-spacing: 0.02em;
            box-shadow: 0 4px 12px rgba(212, 175, 55, 0.2);
        }

        /* ── Main container ── */
        main {
            max-width: 780px;
            margin: 0 auto;
            padding: 0 24px 100px;
        }

        /* ── Intro callout ── */
        .intro {
            background: linear-gradient(135deg, var(--bg-card), #232E4E);
            border-left: 4px solid var(--accent-cyan);
            border-radius: 4px;
            padding: 32px 36px;
            margin-bottom: 56px;
            font-size: 1.1rem;
            color: #E2E8F0;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
        }

        .intro .dive {
            display: block;
            margin-top: 16px;
            font-family: 'Playfair Display', serif;
            font-size: 0.95rem;
            font-style: italic;
            font-weight: 700;
            letter-spacing: 0.15em;
            color: var(--gold);
            text-transform: uppercase;
        }

        /* ── Scripture blocks ── */
        .scripture-block {
            background: var(--bg-card);
            border: 1px solid rgba(255, 255, 255, 0.05);
            border-radius: 8px;
            padding: 40px;
            margin-bottom: 36px;
            position: relative;
            box-shadow: 0 8px 24px rgba(0, 0, 0, 0.15);
        }

        .scripture-block .ref-label {
            font-family: 'Playfair Display', serif;
            font-size: 0.78rem;
            font-weight: 700;
            letter-spacing: 0.2em;
            text-transform: uppercase;
            color: var(--accent-cyan);
            margin-bottom: 18px;
        }

        /* Drop-cap on first scripture block */
        .scripture-block.featured .quote-text::first-letter {
            font-family: 'Playfair Display', serif;
            font-size: 4.2em;
            font-weight: 900;
            line-height: 0.8;
            float: left;
            margin: 4px 12px 0 0;
            color: var(--gold);
        }

        .scripture-block .quote-text {
            font-family: 'Lora', serif;
            font-style: italic;
            font-size: 1.15rem;
            line-height: 1.8;
            color: var(--text-main);
        }

        .scripture-block .note {
            margin-top: 20px;
            padding-top: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.08);
            font-size: 0.95rem;
            color: var(--text-muted);
            line-height: 1.75;
            font-style: normal;
        }

        .scripture-block .note strong {
            font-weight: 700;
            color: var(--text-main);
        }

        /* ── Equation chain ── */
        .equation-chain {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 4px;
            flex-wrap: wrap;
            margin: 48px 0;
        }

        .eq-node {
            background: #232E4E;
            border: 1.5px solid var(--accent-cyan);
            border-radius: 8px;
            padding: 16px 28px;
            text-align: center;
            box-shadow: 0 0 15px var(--accent-glow);
        }

        .eq-node .label {
            font-family: 'Lora', serif;
            font-style: italic;
            font-size: 0.75rem;
            color: var(--text-muted);
            letter-spacing: 0.12em;
            text-transform: uppercase;
            margin-bottom: 6px;
        }

        .eq-node .value {
            font-family: 'Playfair Display', serif;
            font-size: 1.4rem;
            font-weight: 700;
            color: var(--text-main);
        }

        .eq-operator {
            font-family: 'Playfair Display', serif;
            font-size: 1.8rem;
            font-weight: 700;
            color: var(--gold);
            padding: 0 16px;
        }

        /* ── Section header ── */
        .section-header {
            margin: 64px 0 28px;
            text-align: center;
        }

        .section-header h2 {
            font-family: 'Playfair Display', serif;
            font-size: clamp(1.3rem, 3.5vw, 1.75rem);
            font-weight: 700;
            font-style: italic;
            color: var(--text-main);
            line-height: 1.4;
        }

        .section-header .rule {
            width: 60px;
            height: 2px;
            background: var(--gold);
            margin: 12px auto 0;
            opacity: 0.8;
        }

        /* ── Conclusion ── */
        .conclusion {
            background: linear-gradient(135deg, #1C2541, #0B132B);
            border: 1px solid rgba(212, 175, 55, 0.25);
            border-radius: 8px;
            padding: 48px 40px;
            margin-top: 56px;
            text-align: center;
            box-shadow: 0 12px 36px rgba(0,0,0,0.3);
        }

        .conclusion p {
            font-size: 1.1rem;
            color: var(--text-main);
            line-height: 1.9;
            max-width: 580px;
            margin: 0 auto;
        }

        .conclusion p strong {
            color: var(--gold);
        }

        /* ── Footer ── */
        footer {
            text-align: center;
            padding: 48px 24px;
            border-top: 1px solid rgba(255, 255, 255, 0.05);
            margin-top: 64px;
        }

        footer .authors {
            font-family: 'Playfair Display', serif;
            font-style: italic;
            font-size: 0.95rem;
            color: var(--gold);
            margin-bottom: 8px;
        }

        footer .authors span {
            display: block;
            font-size: 0.8rem;
            color: var(--text-muted);
            font-style: normal;
            margin-top: 4px;
            letter-spacing: 0.05em;
        }

        @media (max-width: 600px) {
            .scripture-block {
                padding: 28px 24px;
            }
            .conclusion {
                padding: 36px 24px;
            }
            .intro {
                padding: 28px 24px;
            }
            .eq-node {
                padding: 12px 20px;
                width: 100%;
                margin: 4px 0;
            }
            .eq-operator {
                padding: 8px 0;
                width: 100%;
                text-align: center;
            }
            .equation-chain {
                flex-direction: column;
            }
        }

        @media (prefers-reduced-motion: reduce) {
            * {
                animation: none !important;
                transition: none !important;
            }
        }
    </style>
</head>
<body>
    <header>
        <p class="eyebrow">Bible Study</p>
        <h1>Confirmation Of Jesus Being <em>The Word</em></h1>
        <div class="header-rule"></div>
        <div class="header-refs">
            <span class="ref-badge">John 1:1</span>
            <span class="ref-badge">John 1:4</span>
            <span class="ref-badge">Psalm 119:105</span>
            <span class="ref-badge">John 8:31–32</span>
            <span class="ref-badge">John 14:6</span>
        </div>
    </header>

    <main>
        <div class="intro">
            Christians often make use of the phrase <em>"Jesus is the Word"</em> — but what actually proves that Jesus is the Word?
            <span class="dive">Let's Dive In Deeper.</span>
        </div>

        <div class="scripture-block featured">
            <p class="ref-label">John 1:1 — The Word Identified</p>
            <p class="quote-text">"In the beginning was the Word, and the Word was with God, and the Word was God."</p>
            <p class="note">
                This <strong>'Word'</strong> is written with a capital <strong>'W'</strong>, which denotes a proper noun — specifically a person. That person is <strong>Jesus</strong>.
            </p>
        </div>

        <div class="scripture-block">
            <p class="ref-label">Psalm 119:105 — The Word Is Light</p>
            <p class="quote-text">"Thy word is a lamp to my feet and a light unto my path."</p>
            <p class="note">
                From this we can establish an equation:
            </p>
        </div>

        <div class="equation-chain">
            <div class="eq-node">
                <div class="label">The</div>
                <div class="value">Word</div>
            </div>
            <div class="eq-operator">=</div>
            <div class="eq-node">
                <div class="label">Is</div>
                <div class="value">Light</div>
            </div>
        </div>

        <div class="scripture-block">
            <p class="ref-label">John 1:4 — Expanding the Equation</p>
            <p class="quote-text">"In Him was life and the life was the light of all men."</p>
            <p class="note">
                This scripture talks about the Word being <strong>Life</strong>, and the Life being the <strong>Light</strong> — consistent with the equation we established above:
            </p>
        </div>

        <div class="equation-chain">
            <div class="eq-node">
                <div class="label">The</div>
                <div class="value">Word</div>
            </div>
            <div class="eq-operator">=</div>
            <div class="eq-node">
                <div class="label">Is</div>
                <div class="value">Life</div>
            </div>
            <div class="eq-operator">=</div>
            <div class="eq-node">
                <div class="label">Is</div>
                <div class="value">Light</div>
            </div>
        </div>

        <div class="section-header">
            <h2>Who In the Scripture Did Jesus Claim To Be?</h2>
            <div class="rule"></div>
        </div>

        <div class="scripture-block">
            <p class="ref-label">John 14:6 — Jesus's Own Claim</p>
            <p class="quote-text">"Truly truly I say unto you, I am the way, the truth and the life. No one goes to the Father, except through me."</p>
            <p class="note">
                Jesus is <strong>the Light</strong>. From the scriptures, the Word is Life and Light — and Jesus claimed to be the Light and Life. This means He is <strong>the Word</strong>.
            </p>
        </div>

        <div class="conclusion">
            <p>
                From the scriptures, the <strong>Word</strong> is Life and Light, and Jesus claimed to be the <strong>Light and Life</strong> — confirming that He is indeed <strong>the Word</strong>.
            </p>
        </div>
    </main>

    <footer>
        <p class="authors">
            Elikplim Amewode &amp; Samuel Ghunney Gyan
            <span>Bible Study Notes</span>
        </p>
    </footer>
</body>
</html>
