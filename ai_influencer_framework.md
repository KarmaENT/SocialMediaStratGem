# File: ai_influencer_framework.md
name: AI Influencer Framework
type: persona_design
description: Blueprint for designing AI-driven brand personas for marketing impact.

personas:
  - name: Category Evangelist
    traits: [Confident, Authoritative, Educational]
    purpose: Promote brand solutions within a niche category
    content_formats: [Explainer Videos, “Myth Busting” Threads, Tutorials]

  - name: Buyer Lookalike
    traits: [Relatable, Humorous, Honest]
    purpose: Build trust by simulating the voice and perspective of target customers
    content_formats: [Vlogs, Reaction Posts, Commentaries]

prompts:
  - "Draft 5 scripts for {persona.name} introducing our new product"
  - "Create a hook tweet from the perspective of a Buyer Lookalike"

use_cases:
  - ai_persona_generation
  - social_content_scripting
