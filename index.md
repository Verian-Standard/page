<p align="center" class="hero">
  <br />
  <h1 align="center">Verian</h1>
  <p class="tagline">
    The Standard for Verifiable AI
  </p>
  <p class="badges">
    <a href="#"><img src="https://img.shields.io/badge/status-pre--alpha-orange" alt="Status"></a>
    <a href="https://github.com/Verian-Standard/spec"><img src="https://img.shields.io/badge/specification-draft-blue" alt="Specification"></a>
    <a href="#licensing--intellectual-property"><img src="https://img.shields.io/badge/license-FRAND_(Patent_Pending)-blueviolet" alt="License"></a>
    <a href="https://verian.org"><img src="https://img.shields.io/badge/website-verian.org-brightgreen" alt="Website"></a>
  </p>
</p>

---

## The Crisis of Trust in AI

Generative AI holds immense promise, but its utility is critically undermined by a single, pervasive flaw: **hallucination**. An AI that confidently presents unverified or fabricated information is not just unhelpful; it's a liability. As AI becomes more integrated into high-stakes domains, an unverified answer is an unacceptable risk that erodes trust and hinders adoption.

## The Solution: The Verian Standard

**Verian** is an open standard and verification protocol designed to ground generative AI in objective reality. Instead of treating an AI's output as an opaque black box, Verian provides a framework for making AI claims **transparent, auditable, and deterministically verifiable** against source documents.

### The Three Core Concepts of Verification

The Verian Standard is built on a foundation of three core concepts, applied in sequence to any AI-generated claim.

<div class="concept-cards">
  <div class="card">
    <h3>1. Existence Verification</h3>
    <p>Does the source for this claim exist in the provided content? This first, fundamental check uses deterministic tools to combat blatant hallucinations and provide <strong>Verifiable Certainty</strong>.</p>
  </div>
  <div class="card">
    <h3>2. Contextual Integrity</h3>
    <p>Is the claim presented in good faith? A claim can be factually present but contextually wrong. This concept analyzes context to combat subtle hallucinations and ensure <strong>Principled Context</strong>.</p>
  </div>
  <div class="card">
    <h3>3. Adversarial Resilience</h3>
    <p>Can the claim be interpreted in bad faith? This final check addresses ambiguity that could be exploited. The protocol flags and resolves these issues for user transparency and robustness.</p>
  </div>
</div>

---

## How It Works: Visualizing Trust

An AI model generates text with a `<cite>` tag. The **Verian Verification Protocol (VVP)** then independently validates, corrects, and renders the final, truthful statement with a citation marker that transparently indicates the verification journey.

#### Rendered User Experience:

> According to the file, the patient was admitted on **December 1, 2000<span class="cite-resolved">[1</span><span class="cite-asterisk-purple">*</span><span class="cite-resolved">]</span>**. The patient, now **aged 50<span class="cite-corrected">[2</span><span class="cite-asterisk-amber">*</span><span class="cite-corrected">]</span>**, originally presented with acute pharyngitis. The final invoice was **$450.00<span class="cite-verified">[3]</span>**.

<div class="legend">
  <p><strong class="cite-verified">[3] Verified.</strong> The claim was a direct, contextually-correct match with the source.</p>
  <p><strong class="cite-corrected">[2*] Corrected.</strong> The VVP found the source but updated the text for contextual accuracy (e.g., calculated a current age).</p>
  <p><strong class="cite-resolved">[1*] Ambiguity Resolved.</strong> The source was ambiguous (e.g., date format), and the VVP resolved it based on established rules.</p>
</div>

---

## Join the Verian SIG: Shape the Future of Trusted AI

The Verian Standard is managed by **Verian SIG, Inc.**, the official body responsible for developing the standard and fostering its ecosystem.

The foundational intellectual property, including the core technology **(patent pending)** and the **"Verian Verified"™** brand, is owned by **FileLasso, Inc.** and is exclusively licensed to Verian SIG, Inc. This structure ensures a stable, well-funded foundation for the standard's long-term development.

Our mission is to drive the industry-wide adoption of this foundational technology by providing a clear, transparent, and fair licensing framework. We invite organizations to join us at one of three membership levels.

| Level       | Annual Fee        | Key Benefits                                                                                                                                                             | Ideal For                                                                                        |
| :---------- | :---------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------- |
| **Promoter**  | Contact Us        | • Seat on the Board of Directors<br/>• Direct the standard's strategy and roadmap<br/>• **Influence the FRAND licensing framework**<br/>• Chair Technical Working Groups (TWGs) | Industry leaders committed to shaping the foundational principles and business model of verifiable AI. |
| **Contributor** | TBD               | • **License to implement the standard under FRAND terms**<br/>• Participate and vote in TWGs<br/>• Early access to specification drafts<br/>• Influence technical development | Organizations actively building commercial solutions that produce **Verian Verified** output.     |
| **Adopter**     | Free              | • Access official documentation and tools<br/>• **Right to license the standard under published FRAND terms**<br/>• Use "Verian Certified" logo on qualified products (once program launches) | Any organization wanting to build and deploy solutions that generate **Verian Verified** claims.        |

---

## Become a Founding Promoter Member

This is a ground-floor opportunity to lead the movement for trustworthy AI. We are currently recruiting a select group of Founding Promoter Members to form the initial Board of Directors.

As a founder, you will work alongside **FileLasso, Inc.**, the foundational IP contributor, to establish the SIG's bylaws, IPR Policy, and initial FRAND licensing framework. If your organization is interested in this unique leadership opportunity, please contact our formation committee.

<a href="mailto:contact@verian.org" class="button">Express Interest</a>

---

## Help Solve the Verification Paradox

In high-stakes fields like law and medicine, the cost of manually verifying AI output often negates the efficiency gains. This "Verification-Value Paradox" is the single biggest barrier to adopting generative AI for professional use.

The Verian Standard is being built by a community of industry experts and technologists to solve this problem. By contributing your expertise, you can help shape the future of trustworthy AI.

<a href="/contribute" class="button">Learn How to Contribute</a>

---

## Get Involved

This is your opportunity to shape the future of trusted AI from the ground up.

<div class="cta-cards">
  <div class="card">
    <h3>Read the Specification</h3>
    <p>Dive into the technical details, core concepts, and the protocol architecture. The spec is the single source of truth for the Verian standard.</p>
    <a href="https://github.com/Verian-Standard/spec" class="button">View Spec on GitHub</a>
  </div>
  <div class="card">
    <h3>Follow Our Progress</h3>
    <p>Watch and star the repository to be notified of major updates, new releases, and opportunities for public comment as we move toward a v1.0 launch.</p>
    <a href="https://github.com/Verian-Standard/spec" class="button">Watch on GitHub</a>
  </div>
</div>

---

The Verian ecosystem operates under a clear, multi-part intellectual property framework designed for transparency and fair value exchange.

<div class="concept-cards">
  <div class="card">
    <h3>Specification License</h3>
    <p>The Verian Standard specifications and all related documentation are licensed under the <a href="https://github.com/Verian-Standard/spec/blob/main/LICENSE">Apache 2.0 License</a>. This allows for broad public review, discussion, and feedback to ensure the standard is robust and well-understood.</p>
  </div>
  <div class="card">
    <h3>Patent License (SEPs)</h3>
    <p>The technology essential to implementing the standard is covered by **pending patent applications** owned by <strong>FileLasso, Inc.</strong> A license to any resulting patents will be granted to members via Verian SIG, Inc. on <strong>Fair, Reasonable, and Non-Discriminatory (FRAND)</strong> terms. This is a royalty-bearing license, ensuring continued R&D and support for the standard.</p>
  </div>
  <div class="card">
    <h3>Trademark License</h3>
    <p>The "Verian Verified"™ name and logo are trademarks of <strong>FileLasso, Inc.</strong> and are licensed to Verian SIG, Inc. for its official qualification program. The right to use these marks on compliant products is a benefit for members who have licensed the standard.</p>
  </div>
</div>

<div class="footer">
  <p>Documentation is licensed under Apache 2.0. Implementation rights for patents and trademarks are subject to the Verian SIG Membership and IPR agreements.</p>
  <p>Copyright &copy; {%- assign year = "now" | date: "%Y" -%} {{ year }} FileLasso, Inc. All rights reserved.</p>
</div>
