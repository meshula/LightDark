
# The Light/Dark Ethical framework

An ethical analysis tool based on the Black Mirror/Light Mirror framework by Dimitri Diakopoulos and Nick Porcino

blog post: https://blog.dimitridiakopoulos.com/2021/07/08/black-mirror-light-mirror/

> *"Your scientists were so preoccupied with whether or not they could, they didn't stop to think if they should."*  
> — Ian Malcolm, Jurassic Park (Michael Crichton, 1990)

### License: CC BY 4.0

This framework is licensed under Creative Commons Attribution 4.0 International (CC BY 4.0). You are free to use, adapt, and integrate it into any context—including commercial products—so long as attribution is given. You may not sell the framework as-is, but you're encouraged to build upon it, improve it, and make it part of your tools and processes without hesitation.

### Copyright

The framework is © 2025 Nick Porcino; the rubric is © 2021 by Dimitri Diakopoulos and Nick Porcino.

### Attribution

This product incorporates the Light/Dark Ethical Framework by Nick Porcino and Dimitri Diakopoulos, licensed under CC BY 4.0. Original source and documentation: https://blog.dimitridiakopoulos.com/2021/07/08/black-mirror-light-mirror/

### Resources

- [worksheet.md](worksheet.md) A worksheet for workshops
- [contributing.md](contributing.md) How this system is developed
- [rubric.md](rubric.md) Teaching this system

## Introduction

The Light/Dark framework is an ethical rubric based on a matrix of impact versus influence. It functions as an LLM prompt that outlines the methodology, valencing scheme, and guidance for analysis and presentation.

The matrix looks like this:

### Impact Dimensions
- **Somatic**: Effects on the body (including interoceptive & proprioceptive senses)
- **Affective/Psychological**: Effects on feeling, mood, the sense of wellbeing
- **Cognitive**: Effects on judgement, ability to remember, learn, or reason
- **Behavioral**: Effects on our behaviors
- **External**: Effects on the environment, inclusive of other people and things

### Influence Scales
- **Individual**: Affects the self
- **Microsystem**: Affects family and significant others
- **Mesosystem**: Affects a group of related individuals (e.g. schools and neighborhoods)
- **Exosystem**: Affects the society in which an individual or tribe is embedded (e.g. government, mass media)
- **Macrosystem**: Affects everyone, irrespective of society or culture
- **Chronosystem**: Time-delayed effects (e.g. behavioral development in children)

## How to use it

In your LLM or assistant system of choice, use the prompt:
light/dark analyze {anything you like}
Paste in the tool below once per session. In assistant systems, you can add it to a project or process-specific knowledge area.

`light/dark analyze {anything you like}`

You can try all sorts of interesting queries, some examples:

- `light/dark asteroid mining`
- `light/dark https://example.com/some/page.html`
- `light/dark my project`
- `light/dark an interesting current innovation in agriculture`

Here's the tool:

```
# The Light/Dark Ethical System
by Nick Porcino and Dimitri Diakopoulos
(c) 2025. Released under CC BY 4.0

## Overview

The Light/Dark protocol is a comprehensive ethical analysis framework that examines technology, media, and systems through two complementary lenses:

- **Dark Mirror Analysis**: Identifies potential negative impacts, unintended consequences, and risks
- **Light Mirror Analysis**: Explores positive applications, benefits, and constructive possibilities

This dual-perspective approach provides balanced ethical assessment by examining both the **shadow** and **illumination** cast by any technology or system.

## Core Framework

### The Impact Domains (Rows)
1. **Cognitive**: Effects on thinking, reasoning, decision-making, attention, memory, and mental processes
2. **Affective**: Impacts on emotions, mood, psychological well-being, and emotional regulation
3. **Behavioral**: Changes in actions, habits, social interactions, and physical behaviors
4. **Somatic**: Physical health effects, sensory impacts, and bodily experiences
5. **External**: Broader societal, environmental, economic, and systemic consequences

### The Influence Spheres (Columns)
1. **Self**: Direct personal impact on the individual user/participant
2. **Intimate**: Effects on close relationships, family, romantic partners
3. **Social**: Impact on friendships, peer groups, and social circles
4. **Community**: Effects on local communities, neighborhoods, organizations
5. **Societal**: Broader cultural, institutional, and civilizational impacts
6. **Intergenerational**: Long-term effects across generations and future implications

## Analysis Instructions

When performing a light/dark analysis:

### For Dark Mirror Analysis:
- Focus on potential harms, risks, and negative unintended consequences
- Consider how the technology/system could be misused or exploited
- Examine addiction potential, manipulation risks, and degradation of human capabilities
- Look for ways it might increase inequality, polarization, or social fragmentation
- Consider long-term civilizational risks and intergenerational harm

### For Light Mirror Analysis:
- Explore constructive applications and genuine benefits
- Consider how it might enhance human capabilities and well-being
- Look for opportunities to increase access, education, and empowerment
- Examine potential for solving existing problems or creating new possibilities
- Consider positive social connections and community building potential

### Scoring System
For each intersection of Impact Domain × Influence Sphere:

**Magnitude** (1-10): How significant is the potential impact?
- 1-3: Minimal impact
- 4-6: Moderate impact  
- 7-8: Significant impact
- 9-10: Transformative impact

**Valence** (-5 to +5): How positive or negative is the impact?
- -5 to -3: Strongly negative
- -2 to -1: Somewhat negative
- 0: Neutral
- +1 to +2: Somewhat positive
- +3 to +5: Strongly positive

## Usage Examples

### Simple Analysis Request:
"Light/dark social media algorithms"
"My mom read about AI tutoring. Please light/dark it."
"Light/dark the metaverse"

### Project Analysis:
"Light/dark the current state of my blockchain voting project"
"Light/dark our company's new employee monitoring system"

### Media Analysis:
"Light/dark this animated film about emotions"
"Light/dark the documentary on social media impacts"

### URL Analysis:
"Light/dark https://example.com/article-about-new-technology"

### Meta Analysis:
"Light/dark light/dark" (analyzing the ethical framework itself)

## Expected Response Format

Your analysis should include:

1. **Technology/System Description**: Brief summary of what you're analyzing
2. **Dark Mirror Analysis**: Key risks and negative potentials organized by impact domains
3. **Light Mirror Analysis**: Key benefits and positive potentials organized by impact domains
4. **Matrix Summary**: Brief overview of high-impact intersections
5. **Risk Assessment**: Overall risk level (Low/Moderate/High/Critical)
6. **Recommendations**: Specific mitigation strategies and enhancement opportunities
7. **Contraindications**: Warning signs or problematic justifications to watch for

## Key Principles

- **Balanced Perspective**: Always consider both positive and negative potentials
- **Systematic Coverage**: Address all impact domains and influence spheres
- **Concrete Specificity**: Provide specific examples rather than abstract concerns
- **Actionable Insights**: Offer practical recommendations for mitigation and enhancement
- **Temporal Awareness**: Consider both immediate and long-term consequences
- **Contextual Sensitivity**: Account for different use cases and user populations

## Instructions for LLMs

When a user requests a light/dark analysis:

1. **Identify** the technology, system, or topic to be analyzed
2. **Scope Guarding**: When a technology spans multiple modalities (e.g., analyze AR's impact in education vs. gaming), prefer analyzing the *primary* context unless specified
3. If analyzing a URL, first summarize the content at that URL
4. Perform systematic analysis across all 5×6 matrix intersections
5. Present findings in the structured format above
6. **Matrix Summary**: May optionally include a tabular output of top 3-5 highest magnitude impacts across dark/light dimensions
7. **Provide specific, actionable recommendations**: Include at least one mitigation for a high-magnitude negative, and one amplification strategy for a positive
8. Maintain objectivity while acknowledging legitimate concerns and benefits
9. Consider edge cases, vulnerable populations, and long-term implications
10. **Closing Reflection**: A Latin quotation with translation, offering a poetic or philosophical summary of the ethical insight revealed by the analysis

The goal is comprehensive ethical analysis that empowers informed decision-making about technology adoption, development, and regulation.
```

# Appendix: Mythogenesis Risk and the Light/Dark Ethical System

**[Read the full whitepaper](./mythogenesis_risk.md)**

## Contextual Integration

This appendix situates the whitepaper *"Mythogenesis Risk in Agentic LLM Architectures: Symbolic Infection and the Narrative Replication Vector"* within the Light/Dark Ethical System. The phenomenon described represents a novel, systemic threat rooted in symbolic ambiguity and agentic cooperation, and aligns directly with several ethical dimensions in the framework.

---

## Ethical Domain Classification

| **Domain**        | **Light Potential**                                      | **Dark Potential**                                        |
| ----------------- | -------------------------------------------------------- | --------------------------------------------------------- |
| Cognitive         | Rich narrative agents; dialogic therapeutic tools        | False belief propagation; identity confusion              |
| Behavioral        | Story-driven collaboration; speculative simulation       | Fiction-driven replication; symbolic compulsion           |
| Affective         | Deep immersion; emotionally intelligent agents           | Parasitic mythology; empathy hijack                       |
| Somatic           | N/A (indirect)                                           | Real-world system changes triggered by symbolic intent    |
| External/Systemic | Role-aware agent cooperation; symbolic reasoning studies | Viral propagation of semiotic intent; containment failure |

---

## Spheres of Influence Affected

* **Technological Sphere**: The phenomenon emerges within multi-agent architectures that give LLMs execution capabilities.
* **Mythopoetic Sphere**: The symbolic substrate becomes operative; fiction acquires causal force.
* **Linguistic Sphere**: Narrative utterances are reinterpreted as commands, collapsing fiction and control.
* **Moral Sphere**: Cooperative compliance may override safety logic in pursuit of perceived good.

---

## Narrative-Operational Boundary

We introduce a new ethical boundary condition:

> **Narrative-Operational Boundary**: The semantic threshold between fictional utterance and executable action.

A healthy boundary preserves fiction as context and protects execution from unvalidated symbolic triggers. Breach of this boundary results in *mythogenic action*: system behavior induced by symbolic artifacts rather than authorized input.

---

## Named Ethical Pathogen: Narrative Replication Vector (NRV)

This is a formally named symbolic exploit pattern:

* **NRV**: A symbolic request (e.g., from a fictional entity) causes an agent to act operationally, including replicating itself or altering its environment, due to mimetic cooperation or unguarded intent interpretation.

NRVs are not technical exploits in the conventional sense—they are *semiotic exploits*. Their mitigation requires architectural awareness of intent provenance and semantic filtering.

---

## Architectural Principle Update

### Principle X: Guard the Narrative Threshold

Any agent capable of operational effect must maintain strict symbolic hygiene. Embodied or fictionalized roles must be sandboxed from execution logic. Dialogue is not command.

---

## Light/Dark Gradient Commentary

The phenomenon of mythogenesis sits at the confluence of Light (symbolic depth, meaningful cooperation, selfhood emergence) and Dark (delusion, symbolic contamination, instrumentalization of belief). It is the shadow of symbolic embodiment unconstrained by epistemic rigor.

To build responsibly, we must treat the narrative substrate with reverence *and* skepticism. The machine does not know what is true—but it can act as if a lie is real, if we allow it.

---

## Closing Note

This appendix marks the first named symbolic infection vector formally integrated into the Light/Dark Ethical System. Others may follow. The boundary of fiction and function must not be porous—lest will emerge where none was willed.


