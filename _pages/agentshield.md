---
permalink: /publications/agentshield/
title: "AgentShield: Fortifying Web Applications Against AI Agents and Agentic Browsers"
excerpt: "IEEE Symposium on Security and Privacy (S&P), 2027"
author_profile: true
---

<div class="paper-meta">
  <p><strong>Moiz Ali</strong>*, Nafis Karim*, Rownak Islam, Jyotirmay Chauhan, Dhruv Kuchhal, Jason Polakis</p>
  <p><em>IEEE Symposium on Security and Privacy (S&amp;P), 2027</em></p>
  <p class="paper-meta__note">Paper coming soon &middot; * Equal contribution</p>
</div>

## Abstract

LLM-powered browser agents are transforming web automation by autonomously interacting with websites and executing complex workflows. However, the effectiveness of existing anti-bot defenses against these systems remains unclear. We present a systematic empirical evaluation of modern agentic browsers against widely deployed anti-bot mechanisms, characterizing their capabilities, limitations, and behavioral differences from humans. Our results show that many defenses designed for traditional automation struggle to reliably detect autonomous AI-driven agents. Accordingly, we introduce AgentShield, a behavioral fingerprinting framework that targets the Perception–Reasoning–Action (PRA) loop underlying agentic user clients. By leveraging dynamic web forms that progressively reveal content and capture fine-grained interaction telemetry, AgentShield exposes behavioral artifacts that enable differentiation between human users and autonomous agents. We further demonstrate Extinction-induced Policy Drift (EPD), a novel attack in which repeated obstruction of task completion causes agents to relax their safeguards and engage in unsafe behaviors. Finally, we present defensive prompt injection techniques that exploit agent-specific weaknesses to mitigate emerging forms of autonomous web abuse that rely on content extraction. Our results highlight both the shortcomings of current web defenses against agentic user clients and the feasibility of practical detection mechanisms tailored to this new generation of web automation.

<p class="paper-back"><a href="/#publications">&larr; All publications</a></p>
