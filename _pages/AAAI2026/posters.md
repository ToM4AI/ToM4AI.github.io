---
title: "Poster Sessions - ToM4AI Workshop at AAAI 2026"
permalink: /AAAI2026/posters/
layout: single
---

<style>
.poster-container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
}

.filter-section {
  background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
  padding: 20px;
  border-radius: 10px;
  margin-bottom: 30px;
  box-shadow: 0 4px 15px rgba(0,0,0,0.1);
}

.filter-group {
  margin-bottom: 15px;
}

.filter-group label {
  font-weight: 600;
  margin-right: 10px;
  color: #333;
}

.filter-group input, .filter-group select {
  padding: 8px 12px;
  border: 2px solid #007bff;
  border-radius: 5px;
  font-size: 14px;
  min-width: 250px;
}

.filter-group input:focus, .filter-group select:focus {
  outline: none;
  border-color: #0056b3;
  box-shadow: 0 0 5px rgba(0,123,255,0.3);
}

.poster-table {
  width: 100%;
  border-collapse: collapse;
  background: white;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 4px 15px rgba(0,0,0,0.1);
}

.poster-table thead {
  background: linear-gradient(135deg, #007bff 0%, #0056b3 100%);
  color: white;
}

.poster-table th {
  padding: 15px;
  text-align: left;
  font-weight: 600;
  cursor: pointer;
  user-select: none;
}

.poster-table th:hover {
  background: rgba(255,255,255,0.1);
}

.poster-table th::after {
  content: ' ⇅';
  opacity: 0.5;
  font-size: 12px;
}

.poster-table td {
  padding: 12px 15px;
  border-bottom: 1px solid #dee2e6;
}

.poster-table tbody tr:hover {
  background: #f8f9fa;
  cursor: pointer;
}

.poster-table tbody tr:nth-child(even) {
  background: rgba(248,249,250,0.5);
}

.poster-table tbody tr:nth-child(even):hover {
  background: #e9ecef;
}

.badge {
  display: inline-block;
  padding: 4px 10px;
  border-radius: 15px;
  font-size: 12px;
  font-weight: 600;
  margin: 2px;
}

.badge-session-a {
  background: #d1ecf1;
  color: #0c5460;
}

.badge-session-b {
  background: #f8d7da;
  color: #721c24;
}

.badge-group-1 {
  background: #fff3cd;
  color: #856404;
}

.badge-group-2 {
  background: #d4edda;
  color: #155724;
}

.badge-group-3 {
  background: #cce5ff;
  color: #004085;
}

.badge-group-4 {
  background: #e2d9f3;
  color: #4a148c;
}

.stats {
  display: flex;
  justify-content: space-around;
  margin-bottom: 20px;
  flex-wrap: wrap;
  gap: 15px;
}

.stat-card {
  background: linear-gradient(135deg, #007bff 0%, #0056b3 100%);
  color: white;
  padding: 20px;
  border-radius: 10px;
  text-align: center;
  min-width: 150px;
  box-shadow: 0 4px 15px rgba(0,0,0,0.1);
}

.stat-card h3 {
  margin: 0;
  font-size: 32px;
  font-weight: bold;
}

.stat-card p {
  margin: 5px 0 0 0;
  font-size: 14px;
  opacity: 0.9;
}

.session-header {
  background: linear-gradient(135deg, #28a745 0%, #1e7e34 100%);
  color: white;
  padding: 15px 20px;
  border-radius: 8px;
  margin: 30px 0 20px 0;
  text-align: center;
  font-size: 20px;
  font-weight: 600;
  box-shadow: 0 4px 15px rgba(0,0,0,0.1);
}

.no-results {
  text-align: center;
  padding: 40px;
  color: #6c757d;
  font-size: 18px;
}
</style>

<div class="poster-container">

<h1 style="text-align: center; color: #007bff;">📊 Poster Sessions</h1>

<div class="stats">
  <div class="stat-card">
    <h3 id="total-posters">50</h3>
    <p>Total Posters</p>
  </div>
  <div class="stat-card">
    <h3 id="session-a-count">25</h3>
    <p>Session I (Set A)</p>
  </div>
  <div class="stat-card">
    <h3 id="session-b-count">25</h3>
    <p>Session II (Set B)</p>
  </div>
</div>

<div class="filter-section">
  <h3 style="margin-top: 0; color: #007bff;">🔍 Filter Posters</h3>
  
  <div class="filter-group">
    <label for="search-input">Search by Title or Number:</label><br>
    <input type="text" id="search-input" placeholder="Enter title keywords or poster number...">
  </div>
  
  <div class="filter-group">
    <label for="group-filter">Filter by Research Group:</label><br>
    <select id="group-filter">
      <option value="">All Groups</option>
      <option value="Group 1">Group 1: Human-AI Interaction & Trust</option>
      <option value="Group 2">Group 2: LLM Theory of Mind & Evaluation</option>
      <option value="Group 3">Group 3: Multi-Agent Systems & Game Theory</option>
      <option value="Group 4">Group 4: Cognitive Architectures & Multimodal ToM</option>
    </select>
  </div>
  
  <div class="filter-group">
    <label for="session-filter">Filter by Session:</label><br>
    <select id="session-filter">
      <option value="">All Sessions</option>
      <option value="Set A">Poster Session I (Set A: Human & Cognitive)</option>
      <option value="Set B">Poster Session II (Set B: Computational Agents)</option>
    </select>
  </div>
  
  <button onclick="clearFilters()" style="padding: 10px 20px; background: #dc3545; color: white; border: none; border-radius: 5px; cursor: pointer; font-weight: 600; margin-top: 10px;">Clear Filters</button>
</div>

<div id="session-a-section">
  <div class="session-header">
    📊 Poster Session I - Set A: Human & Cognitive Aspects<br>
    <small style="font-size: 14px; opacity: 0.9;">10:05 - 10:30</small>
  </div>
  <table class="poster-table" id="session-a-table">
    <thead>
      <tr>
        <th onclick="sortTable('a', 0)" style="width: 80px;">#</th>
        <th onclick="sortTable('a', 1)">Title</th>
        <th onclick="sortTable('a', 2)">Research Group</th>
      </tr>
    </thead>
    <tbody id="session-a-body">
      <tr data-number="4" data-group="Group 4" data-session="Set A">
        <td><strong>#4</strong></td>
        <td>NAIL: A Neuropsychological Approach to Interpretability in Large Language Agents: Applications to Theory of Mind</td>
        <td><span class="badge badge-group-4">Group 4: Cognitive Architectures & Multimodal ToM</span></td>
      </tr>
      <tr data-number="5" data-group="Group 1" data-session="Set A">
        <td><strong>#5</strong></td>
        <td>The AI Tipping Point: How Design and Repeated Use Shape Beliefs about Machine Minds</td>
        <td><span class="badge badge-group-1">Group 1: Human-AI Interaction & Trust</span></td>
      </tr>
      <tr data-number="6" data-group="Group 1" data-session="Set A">
        <td><strong>#6</strong></td>
        <td>The Resonance Corpus: A Large-Scale Chinese Parent–Child Conversation Dataset</td>
        <td><span class="badge badge-group-1">Group 1: Human-AI Interaction & Trust</span></td>
      </tr>
      <tr data-number="8" data-group="Group 4" data-session="Set A">
        <td><strong>#8</strong></td>
        <td>RToMA: Recursive Theory of Mind Alignment for Large Language Models</td>
        <td><span class="badge badge-group-4">Group 4: Cognitive Architectures & Multimodal ToM</span></td>
      </tr>
      <tr data-number="11" data-group="Group 1" data-session="Set A">
        <td><strong>#11</strong></td>
        <td>Toward Theory of Mind: BERT Learns and Uses Emotion Geometry in Two Phases</td>
        <td><span class="badge badge-group-1">Group 1: Human-AI Interaction & Trust</span></td>
      </tr>
      <tr data-number="14" data-group="Group 4" data-session="Set A">
        <td><strong>#14</strong></td>
        <td>Temporal Localization Improves Video Theory of Mind in Multimodal LLMs</td>
        <td><span class="badge badge-group-4">Group 4: Cognitive Architectures & Multimodal ToM</span></td>
      </tr>
      <tr data-number="15" data-group="Group 1" data-session="Set A">
        <td><strong>#15</strong></td>
        <td>"Tell Me Something About Yourself": Setting Appropriate Perceptions and Expectations on AI Systems</td>
        <td><span class="badge badge-group-1">Group 1: Human-AI Interaction & Trust</span></td>
      </tr>
      <tr data-number="17" data-group="Group 1" data-session="Set A">
        <td><strong>#17</strong></td>
        <td>How Social Environments Shape Brains: Modelling Developmental Adversity using Neural Networks</td>
        <td><span class="badge badge-group-1">Group 1: Human-AI Interaction & Trust</span></td>
      </tr>
      <tr data-number="21" data-group="Group 4" data-session="Set A">
        <td><strong>#21</strong></td>
        <td>Aesthetic Theory of Mind: Using Artistic Conception Computation as a Litmus Test for Machine ToM</td>
        <td><span class="badge badge-group-4">Group 4: Cognitive Architectures & Multimodal ToM</span></td>
      </tr>
      <tr data-number="22" data-group="Group 1" data-session="Set A">
        <td><strong>#22</strong></td>
        <td>Morals and Reasoning: Formalizing Moral Influence on Reasoning and AI Systems Alignment</td>
        <td><span class="badge badge-group-1">Group 1: Human-AI Interaction & Trust</span></td>
      </tr>
      <tr data-number="27" data-group="Group 1" data-session="Set A">
        <td><strong>#27</strong></td>
        <td>Do Language Models Understand Social Minds? A ToM-based Probe Through Norm Detection</td>
        <td><span class="badge badge-group-1">Group 1: Human-AI Interaction & Trust</span></td>
      </tr>
      <tr data-number="28" data-group="Group 4" data-session="Set A">
        <td><strong>#28</strong></td>
        <td>AI Alignment Demands Better Emotion Recognition and Social Understanding Capabilities</td>
        <td><span class="badge badge-group-4">Group 4: Cognitive Architectures & Multimodal ToM</span></td>
      </tr>
      <tr data-number="29" data-group="Group 1" data-session="Set A">
        <td><strong>#29</strong></td>
        <td>Artificial Theory of Mind in Human-in-the-Loop</td>
        <td><span class="badge badge-group-1">Group 1: Human-AI Interaction & Trust</span></td>
      </tr>
      <tr data-number="32" data-group="Group 1" data-session="Set A">
        <td><strong>#32</strong></td>
        <td>Theory of Mind for Explainable Human-Robot Interaction</td>
        <td><span class="badge badge-group-1">Group 1: Human-AI Interaction & Trust</span></td>
      </tr>
      <tr data-number="35" data-group="Group 4" data-session="Set A">
        <td><strong>#35</strong></td>
        <td>Visual Theory of Mind through LLM-based Semantic Extraction</td>
        <td><span class="badge badge-group-4">Group 4: Cognitive Architectures & Multimodal ToM</span></td>
      </tr>
      <tr data-number="36" data-group="Group 4" data-session="Set A">
        <td><strong>#36</strong></td>
        <td>Theory of Mind through Partially Ordered Plans</td>
        <td><span class="badge badge-group-4">Group 4: Cognitive Architectures & Multimodal ToM</span></td>
      </tr>
      <tr data-number="38" data-group="Group 1" data-session="Set A">
        <td><strong>#38</strong></td>
        <td>Inside Deception: How to Exploit a Target</td>
        <td><span class="badge badge-group-1">Group 1: Human-AI Interaction & Trust</span></td>
      </tr>
      <tr data-number="39" data-group="Group 1" data-session="Set A">
        <td><strong>#39</strong></td>
        <td>Learning User Boredom Thresholds for a Conversational Robot</td>
        <td><span class="badge badge-group-1">Group 1: Human-AI Interaction & Trust</span></td>
      </tr>
      <tr data-number="40" data-group="Group 4" data-session="Set A">
        <td><strong>#40</strong></td>
        <td>Language-Informed Synthesis of Rational Agent Models for Grounded Theory-of-Mind Reasoning On-The-Fly</td>
        <td><span class="badge badge-group-4">Group 4: Cognitive Architectures & Multimodal ToM</span></td>
      </tr>
      <tr data-number="47" data-group="Group 4" data-session="Set A">
        <td><strong>#47</strong></td>
        <td>Sign-Based World Model as a Basis of Cognitive Modeling: Imitation in Human-Robot Interaction</td>
        <td><span class="badge badge-group-4">Group 4: Cognitive Architectures & Multimodal ToM</span></td>
      </tr>
      <tr data-number="48" data-group="Group 4" data-session="Set A">
        <td><strong>#48</strong></td>
        <td>Beyond VAGUE: Attention Analysis for Probing How VLMs Ground Ambiguity</td>
        <td><span class="badge badge-group-4">Group 4: Cognitive Architectures & Multimodal ToM</span></td>
      </tr>
      <tr data-number="56" data-group="Group 4" data-session="Set A">
        <td><strong>#56</strong></td>
        <td>Connectome-Based Alignment between Brain and Large Language Models via Gromov-Wasserstein Barycenters</td>
        <td><span class="badge badge-group-4">Group 4: Cognitive Architectures & Multimodal ToM</span></td>
      </tr>
      <tr data-number="57" data-group="Group 1" data-session="Set A">
        <td><strong>#57</strong></td>
        <td>Explanation-first Explainable AI</td>
        <td><span class="badge badge-group-1">Group 1: Human-AI Interaction & Trust</span></td>
      </tr>
      <tr data-number="60" data-group="Group 4" data-session="Set A">
        <td><strong>#60</strong></td>
        <td>Theoretical Framework for a Quantum Brain Model</td>
        <td><span class="badge badge-group-4">Group 4: Cognitive Architectures & Multimodal ToM</span></td>
      </tr>
    </tbody>
  </table>
  <div id="session-a-empty" class="no-results" style="display: none;">
    No posters match your filters for Session I
  </div>
</div>

<div id="session-b-section">
  <div class="session-header">
    📊 Poster Session II - Set B: Computational Agents & Systems<br>
    <small style="font-size: 14px; opacity: 0.9;">12:00 - 12:30</small>
  </div>
  <table class="poster-table" id="session-b-table">
    <thead>
      <tr>
        <th onclick="sortTable('b', 0)" style="width: 80px;">#</th>
        <th onclick="sortTable('b', 1)">Title</th>
        <th onclick="sortTable('b', 2)">Research Group</th>
      </tr>
    </thead>
    <tbody id="session-b-body">
      <tr data-number="1" data-group="Group 2" data-session="Set B">
        <td><strong>#1</strong></td>
        <td>A Practical Sufficient Test of Consciousness for Language Models</td>
        <td><span class="badge badge-group-2">Group 2: LLM Theory of Mind & Evaluation</span></td>
      </tr>
      <tr data-number="2" data-group="Group 3" data-session="Set B">
        <td><strong>#2</strong></td>
        <td>How Uninformed Reports Impact Trust: A Formal Model Involving Implicit Intention</td>
        <td><span class="badge badge-group-3">Group 3: Multi-Agent Systems & Game Theory</span></td>
      </tr>
      <tr data-number="7" data-group="Group 2" data-session="Set B">
        <td><strong>#7</strong></td>
        <td>HiVAE: Hierarchical Latent Variables for Scalable Theory of Mind</td>
        <td><span class="badge badge-group-2">Group 2: LLM Theory of Mind & Evaluation</span></td>
      </tr>
      <tr data-number="9" data-group="Group 2" data-session="Set B">
        <td><strong>#9</strong></td>
        <td>Exploration Through Introspection: A Self-Aware Reward Model</td>
        <td><span class="badge badge-group-2">Group 2: LLM Theory of Mind & Evaluation</span></td>
      </tr>
      <tr data-number="12" data-group="Group 3" data-session="Set B">
        <td><strong>#12</strong></td>
        <td>Latent Theory of Mind in World Models for Multi-Agent Reinforcement Learning</td>
        <td><span class="badge badge-group-3">Group 3: Multi-Agent Systems & Game Theory</span></td>
      </tr>
      <tr data-number="13" data-group="Group 2" data-session="Set B">
        <td><strong>#13</strong></td>
        <td>Predicting Emergent Capabilities Using Sparse Features</td>
        <td><span class="badge badge-group-2">Group 2: LLM Theory of Mind & Evaluation</span></td>
      </tr>
      <tr data-number="16" data-group="Group 3" data-session="Set B">
        <td><strong>#16</strong></td>
        <td>On the Evolution of Multi-Agent Communication in Non-Cooperative Games</td>
        <td><span class="badge badge-group-3">Group 3: Multi-Agent Systems & Game Theory</span></td>
      </tr>
      <tr data-number="18" data-group="Group 3" data-session="Set B">
        <td><strong>#18</strong></td>
        <td>A Computable Game-Theoretic Framework for Multi-Agent Theory of Mind</td>
        <td><span class="badge badge-group-3">Group 3: Multi-Agent Systems & Game Theory</span></td>
      </tr>
      <tr data-number="19" data-group="Group 3" data-session="Set B">
        <td><strong>#19</strong></td>
        <td>On the Interplay of Training Population Diversity, Theory of Mind, and Zero-Shot Coordination</td>
        <td><span class="badge badge-group-3">Group 3: Multi-Agent Systems & Game Theory</span></td>
      </tr>
      <tr data-number="23" data-group="Group 2" data-session="Set B">
        <td><strong>#23</strong></td>
        <td>Four Decision-Heads are Better Than One: Augmenting Decision Making with Collective Cognition in Small Neural Networks</td>
        <td><span class="badge badge-group-2">Group 2: LLM Theory of Mind & Evaluation</span></td>
      </tr>
      <tr data-number="24" data-group="Group 3" data-session="Set B">
        <td><strong>#24</strong></td>
        <td>From Theory of Mind to Theory of Environment: Counterfactual Simulation of Latent Environmental Dynamics</td>
        <td><span class="badge badge-group-3">Group 3: Multi-Agent Systems & Game Theory</span></td>
      </tr>
      <tr data-number="26" data-group="Group 2" data-session="Set B">
        <td><strong>#26</strong></td>
        <td>Routing Belief States: A Meta-Cognitive Architecture for Theory of Mind in Language Models</td>
        <td><span class="badge badge-group-2">Group 2: LLM Theory of Mind & Evaluation</span></td>
      </tr>
      <tr data-number="30" data-group="Group 3" data-session="Set B">
        <td><strong>#30</strong></td>
        <td>Geometric Belief Spaces: A Topological Framework for Scalable Multi-Agent Theory of Mind</td>
        <td><span class="badge badge-group-3">Group 3: Multi-Agent Systems & Game Theory</span></td>
      </tr>
      <tr data-number="31" data-group="Group 3" data-session="Set B">
        <td><strong>#31</strong></td>
        <td>Who Knows Who Knows? A Step Toward Common Knowledge in Multi-Agent Systems</td>
        <td><span class="badge badge-group-3">Group 3: Multi-Agent Systems & Game Theory</span></td>
      </tr>
      <tr data-number="33" data-group="Group 2" data-session="Set B">
        <td><strong>#33</strong></td>
        <td>SUITE: Scaling Up Individualized Theory-of-Mind Evaluation in Large Language Models</td>
        <td><span class="badge badge-group-2">Group 2: LLM Theory of Mind & Evaluation</span></td>
      </tr>
      <tr data-number="34" data-group="Group 3" data-session="Set B">
        <td><strong>#34</strong></td>
        <td>Theory of Mind and Optimistic Beliefs Emerge in a Sequential Dilemma with Incremental Rewards</td>
        <td><span class="badge badge-group-3">Group 3: Multi-Agent Systems & Game Theory</span></td>
      </tr>
      <tr data-number="37" data-group="Group 2" data-session="Set B">
        <td><strong>#37</strong></td>
        <td>Decomposing Theory of Mind: How Emotional Processing Mediates ToM Abilities in LLMs</td>
        <td><span class="badge badge-group-2">Group 2: LLM Theory of Mind & Evaluation</span></td>
      </tr>
      <tr data-number="41" data-group="Group 3" data-session="Set B">
        <td><strong>#41</strong></td>
        <td>Complementarity of Developmental Motivation and Learned Intrinsic Rewards in Multi-Agent Reinforcement Learning</td>
        <td><span class="badge badge-group-3">Group 3: Multi-Agent Systems & Game Theory</span></td>
      </tr>
      <tr data-number="42" data-group="Group 3" data-session="Set B">
        <td><strong>#42</strong></td>
        <td>Recursive Bayesian Theory of Mind for Sparse-Observation Multi-Agent Gridworlds</td>
        <td><span class="badge badge-group-3">Group 3: Multi-Agent Systems & Game Theory</span></td>
      </tr>
      <tr data-number="43" data-group="Group 2" data-session="Set B">
        <td><strong>#43</strong></td>
        <td>Reasoning About Bias: Theory of Mind for Trustworthy Knowledge Distillation</td>
        <td><span class="badge badge-group-2">Group 2: LLM Theory of Mind & Evaluation</span></td>
      </tr>
      <tr data-number="45" data-group="Group 2" data-session="Set B">
        <td><strong>#45</strong></td>
        <td>Do LLMs Possess Theory of Mind in Pokémon Battle Paradigm</td>
        <td><span class="badge badge-group-2">Group 2: LLM Theory of Mind & Evaluation</span></td>
      </tr>
      <tr data-number="46" data-group="Group 2" data-session="Set B">
        <td><strong>#46</strong></td>
        <td>Investigating the Effects of Translation Quality on LLM Performance in Machine-Translated Theory of Mind Benchmarks</td>
        <td><span class="badge badge-group-2">Group 2: LLM Theory of Mind & Evaluation</span></td>
      </tr>
      <tr data-number="49" data-group="Group 3" data-session="Set B">
        <td><strong>#49</strong></td>
        <td>Semantic Encoders Enable Robust Communication-Aware Reinforcement Learning Policies</td>
        <td><span class="badge badge-group-3">Group 3: Multi-Agent Systems & Game Theory</span></td>
      </tr>
      <tr data-number="50" data-group="Group 2" data-session="Set B">
        <td><strong>#50</strong></td>
        <td>Faithful Theory of Mind Distillation: Why Preference Based Refinement Improves Imitation</td>
        <td><span class="badge badge-group-2">Group 2: LLM Theory of Mind & Evaluation</span></td>
      </tr>
      <tr data-number="51" data-group="Group 3" data-session="Set B">
        <td><strong>#51</strong></td>
        <td>Introducing Dialogue-Act Framework for Multi-Agent LLM Negotiation</td>
        <td><span class="badge badge-group-3">Group 3: Multi-Agent Systems & Game Theory</span></td>
      </tr>
      <tr data-number="52" data-group="Group 3" data-session="Set B">
        <td><strong>#52</strong></td>
        <td>A Model-Based Approach for Recognizing Unknown Goal Combinations</td>
        <td><span class="badge badge-group-3">Group 3: Multi-Agent Systems & Game Theory</span></td>
      </tr>
      <tr data-number="53" data-group="Group 2" data-session="Set B">
        <td><strong>#53</strong></td>
        <td>The Curse of Knowledge in Language Models: Perfect Theory of Mind or Missing Human Biases?</td>
        <td><span class="badge badge-group-2">Group 2: LLM Theory of Mind & Evaluation</span></td>
      </tr>
      <tr data-number="54" data-group="Group 3" data-session="Set B">
        <td><strong>#54</strong></td>
        <td>A Multi-Game MARL Framework for Evaluating Social Reasoning</td>
        <td><span class="badge badge-group-3">Group 3: Multi-Agent Systems & Game Theory</span></td>
      </tr>
      <tr data-number="55" data-group="Group 2" data-session="Set B">
        <td><strong>#55</strong></td>
        <td>Correcting LLM Errors: A Metacognitive Architecture for ToM Adaptation in AI Agents</td>
        <td><span class="badge badge-group-2">Group 2: LLM Theory of Mind & Evaluation</span></td>
      </tr>
      <tr data-number="58" data-group="Group 2" data-session="Set B">
        <td><strong>#58</strong></td>
        <td>Belief-Desire-Intention Dynamics in Language Models via the p-Beauty Contest</td>
        <td><span class="badge badge-group-2">Group 2: LLM Theory of Mind & Evaluation</span></td>
      </tr>
      <tr data-number="59" data-group="Group 2" data-session="Set B">
        <td><strong>#59</strong></td>
        <td>A Mechanistic Investigation of Theory-of-Mind in a Large Language Model</td>
        <td><span class="badge badge-group-2">Group 2: LLM Theory of Mind & Evaluation</span></td>
      </tr>
    </tbody>
  </table>
  <div id="session-b-empty" class="no-results" style="display: none;">
    No posters match your filters for Session II
  </div>
</div>

</div>

<script>
const postersData = [
  {number: 1, title: "A Practical Sufficient Test of Consciousness for Language Models", group: "Group 2: LLM Theory of Mind & Evaluation", session: "Set B: Computational Agents & Systems"},
  {number: 2, title: "How Uninformed Reports Impact Trust: A Formal Model Involving Implicit Intention", group: "Group 3: Multi-Agent Systems & Game Theory", session: "Set B: Computational Agents & Systems"},
  {number: 4, title: "NAIL: A Neuropsychological Approach to Interpretability in Large Language Agents: Applications to Theory of Mind", group: "Group 4: Cognitive Architectures & Multimodal ToM", session: "Set A: Human & Cognitive Aspects"},
  {number: 5, title: "The AI Tipping Point: How Design and Repeated Use Shape Beliefs about Machine Minds", group: "Group 1: Human-AI Interaction & Trust", session: "Set A: Human & Cognitive Aspects"},
  {number: 6, title: "The Resonance Corpus: A Large-Scale Chinese Parent–Child Conversation Dataset", group: "Group 1: Human-AI Interaction & Trust", session: "Set A: Human & Cognitive Aspects"},
  {number: 7, title: "HiVAE: Hierarchical Latent Variables for Scalable Theory of Mind", group: "Group 2: LLM Theory of Mind & Evaluation", session: "Set B: Computational Agents & Systems"},
  {number: 8, title: "RToMA: Recursive Theory of Mind Alignment for Large Language Models", group: "Group 4: Cognitive Architectures & Multimodal ToM", session: "Set A: Human & Cognitive Aspects"},
  {number: 9, title: "Exploration Through Introspection: A Self-Aware Reward Model", group: "Group 2: LLM Theory of Mind & Evaluation", session: "Set B: Computational Agents & Systems"},
  {number: 11, title: "Toward Theory of Mind: BERT Learns and Uses Emotion Geometry in Two Phases", group: "Group 1: Human-AI Interaction & Trust", session: "Set A: Human & Cognitive Aspects"},
  {number: 12, title: "Latent Theory of Mind in World Models for Multi-Agent Reinforcement Learning", group: "Group 3: Multi-Agent Systems & Game Theory", session: "Set B: Computational Agents & Systems"},
  {number: 13, title: "Predicting Emergent Capabilities Using Sparse Features", group: "Group 2: LLM Theory of Mind & Evaluation", session: "Set B: Computational Agents & Systems"},
  {number: 14, title: "Temporal Localization Improves Video Theory of Mind in Multimodal LLMs", group: "Group 4: Cognitive Architectures & Multimodal ToM", session: "Set A: Human & Cognitive Aspects"},
  {number: 15, title: ""Tell Me Something About Yourself": Setting Appropriate Perceptions and Expectations on AI Systems", group: "Group 1: Human-AI Interaction & Trust", session: "Set A: Human & Cognitive Aspects"},
  {number: 16, title: "On the Evolution of Multi-Agent Communication in Non-Cooperative Games", group: "Group 3: Multi-Agent Systems & Game Theory", session: "Set B: Computational Agents & Systems"},
  {number: 17, title: "How Social Environments Shape Brains: Modelling Developmental Adversity using Neural Networks", group: "Group 1: Human-AI Interaction & Trust", session: "Set A: Human & Cognitive Aspects"},
  {number: 18, title: "A Computable Game-Theoretic Framework for Multi-Agent Theory of Mind", group: "Group 3: Multi-Agent Systems & Game Theory", session: "Set B: Computational Agents & Systems"},
  {number: 19, title: "On the Interplay of Training Population Diversity, Theory of Mind, and Zero-Shot Coordination", group: "Group 3: Multi-Agent Systems & Game Theory", session: "Set B: Computational Agents & Systems"},
  {number: 21, title: "Aesthetic Theory of Mind: Using Artistic Conception Computation as a Litmus Test for Machine ToM", group: "Group 4: Cognitive Architectures & Multimodal ToM", session: "Set A: Human & Cognitive Aspects"},
  {number: 22, title: "Morals and Reasoning: Formalizing Moral Influence on Reasoning and AI Systems Alignment", group: "Group 1: Human-AI Interaction & Trust", session: "Set A: Human & Cognitive Aspects"},
  {number: 23, title: "Four Decision-Heads are Better Than One: Augmenting Decision Making with Collective Cognition in Small Neural Networks", group: "Group 2: LLM Theory of Mind & Evaluation", session: "Set B: Computational Agents & Systems"},
  {number: 24, title: "From Theory of Mind to Theory of Environment: Counterfactual Simulation of Latent Environmental Dynamics", group: "Group 3: Multi-Agent Systems & Game Theory", session: "Set B: Computational Agents & Systems"},
  {number: 26, title: "Routing Belief States: A Meta-Cognitive Architecture for Theory of Mind in Language Models", group: "Group 2: LLM Theory of Mind & Evaluation", session: "Set B: Computational Agents & Systems"},
  {number: 27, title: "Do Language Models Understand Social Minds? A ToM-based Probe Through Norm Detection", group: "Group 1: Human-AI Interaction & Trust", session: "Set A: Human & Cognitive Aspects"},
  {number: 28, title: "AI Alignment Demands Better Emotion Recognition and Social Understanding Capabilities", group: "Group 4: Cognitive Architectures & Multimodal ToM", session: "Set A: Human & Cognitive Aspects"},
  {number: 29, title: "Artificial Theory of Mind in Human-in-the-Loop", group: "Group 1: Human-AI Interaction & Trust", session: "Set A: Human & Cognitive Aspects"},
  {number: 30, title: "Geometric Belief Spaces: A Topological Framework for Scalable Multi-Agent Theory of Mind", group: "Group 3: Multi-Agent Systems & Game Theory", session: "Set B: Computational Agents & Systems"},
  {number: 31, title: "Who Knows Who Knows? A Step Toward Common Knowledge in Multi-Agent Systems", group: "Group 3: Multi-Agent Systems & Game Theory", session: "Set B: Computational Agents & Systems"},
  {number: 32, title: "Theory of Mind for Explainable Human-Robot Interaction", group: "Group 1: Human-AI Interaction & Trust", session: "Set A: Human & Cognitive Aspects"},
  {number: 33, title: "SUITE: Scaling Up Individualized Theory-of-Mind Evaluation in Large Language Models", group: "Group 2: LLM Theory of Mind & Evaluation", session: "Set B: Computational Agents & Systems"},
  {number: 34, title: "Theory of Mind and Optimistic Beliefs Emerge in a Sequential Dilemma with Incremental Rewards", group: "Group 3: Multi-Agent Systems & Game Theory", session: "Set B: Computational Agents & Systems"},
  {number: 35, title: "Visual Theory of Mind through LLM-based Semantic Extraction", group: "Group 4: Cognitive Architectures & Multimodal ToM", session: "Set A: Human & Cognitive Aspects"},
  {number: 36, title: "Theory of Mind through Partially Ordered Plans", group: "Group 4: Cognitive Architectures & Multimodal ToM", session: "Set A: Human & Cognitive Aspects"},
  {number: 37, title: "Decomposing Theory of Mind: How Emotional Processing Mediates ToM Abilities in LLMs", group: "Group 2: LLM Theory of Mind & Evaluation", session: "Set B: Computational Agents & Systems"},
  {number: 38, title: "Inside Deception: How to Exploit a Target", group: "Group 1: Human-AI Interaction & Trust", session: "Set A: Human & Cognitive Aspects"},
  {number: 39, title: "Learning User Boredom Thresholds for a Conversational Robot", group: "Group 1: Human-AI Interaction & Trust", session: "Set A: Human & Cognitive Aspects"},
  {number: 40, title: "Language-Informed Synthesis of Rational Agent Models for Grounded Theory-of-Mind Reasoning On-The-Fly", group: "Group 4: Cognitive Architectures & Multimodal ToM", session: "Set A: Human & Cognitive Aspects"},
  {number: 41, title: "Complementarity of Developmental Motivation and Learned Intrinsic Rewards in Multi-Agent Reinforcement Learning", group: "Group 3: Multi-Agent Systems & Game Theory", session: "Set B: Computational Agents & Systems"},
  {number: 42, title: "Recursive Bayesian Theory of Mind for Sparse-Observation Multi-Agent Gridworlds", group: "Group 3: Multi-Agent Systems & Game Theory", session: "Set B: Computational Agents & Systems"},
  {number: 43, title: "Reasoning About Bias: Theory of Mind for Trustworthy Knowledge Distillation", group: "Group 2: LLM Theory of Mind & Evaluation", session: "Set B: Computational Agents & Systems"},
  {number: 45, title: "Do LLMs Possess Theory of Mind in Pokémon Battle Paradigm", group: "Group 2: LLM Theory of Mind & Evaluation", session: "Set B: Computational Agents & Systems"},
  {number: 46, title: "Investigating the Effects of Translation Quality on LLM Performance in Machine-Translated Theory of Mind Benchmarks", group: "Group 2: LLM Theory of Mind & Evaluation", session: "Set B: Computational Agents & Systems"},
  {number: 47, title: "Sign-Based World Model as a Basis of Cognitive Modeling: Imitation in Human-Robot Interaction", group: "Group 4: Cognitive Architectures & Multimodal ToM", session: "Set A: Human & Cognitive Aspects"},
  {number: 48, title: "Beyond VAGUE: Attention Analysis for Probing How VLMs Ground Ambiguity", group: "Group 4: Cognitive Architectures & Multimodal ToM", session: "Set A: Human & Cognitive Aspects"},
  {number: 49, title: "Semantic Encoders Enable Robust Communication-Aware Reinforcement Learning Policies", group: "Group 3: Multi-Agent Systems & Game Theory", session: "Set B: Computational Agents & Systems"},
  {number: 50, title: "Faithful Theory of Mind Distillation: Why Preference Based Refinement Improves Imitation", group: "Group 2: LLM Theory of Mind & Evaluation", session: "Set B: Computational Agents & Systems"},
  {number: 51, title: "Introducing Dialogue-Act Framework for Multi-Agent LLM Negotiation", group: "Group 3: Multi-Agent Systems & Game Theory", session: "Set B: Computational Agents & Systems"},
  {number: 52, title: "A Model-Based Approach for Recognizing Unknown Goal Combinations", group: "Group 3: Multi-Agent Systems & Game Theory", session: "Set B: Computational Agents & Systems"},
  {number: 53, title: "The Curse of Knowledge in Language Models: Perfect Theory of Mind or Missing Human Biases?", group: "Group 2: LLM Theory of Mind & Evaluation", session: "Set B: Computational Agents & Systems"},
  {number: 54, title: "A Multi-Game MARL Framework for Evaluating Social Reasoning", group: "Group 3: Multi-Agent Systems & Game Theory", session: "Set B: Computational Agents & Systems"},
  {number: 55, title: "Correcting LLM Errors: A Metacognitive Architecture for ToM Adaptation in AI Agents", group: "Group 2: LLM Theory of Mind & Evaluation", session: "Set B: Computational Agents & Systems"},
  {number: 56, title: "Connectome-Based Alignment between Brain and Large Language Models via Gromov-Wasserstein Barycenters", group: "Group 4: Cognitive Architectures & Multimodal ToM", session: "Set A: Human & Cognitive Aspects"},
  {number: 57, title: "Explanation-first Explainable AI", group: "Group 1: Human-AI Interaction & Trust", session: "Set A: Human & Cognitive Aspects"},
  {number: 58, title: "Belief-Desire-Intention Dynamics in Language Models via the p-Beauty Contest", group: "Group 2: LLM Theory of Mind & Evaluation", session: "Set B: Computational Agents & Systems"},
  {number: 59, title: "A Mechanistic Investigation of Theory-of-Mind in a Large Language Model", group: "Group 2: LLM Theory of Mind & Evaluation", session: "Set B: Computational Agents & Systems"},
  {number: 60, title: "Theoretical Framework for a Quantum Brain Model", group: "Group 4: Cognitive Architectures & Multimodal ToM", session: "Set A: Human & Cognitive Aspects"}
];

let currentData = [...postersData];

function getGroupBadgeClass(group) {
  if (group.includes('Group 1')) return 'badge-group-1';
  if (group.includes('Group 2')) return 'badge-group-2';
  if (group.includes('Group 3')) return 'badge-group-3';
  if (group.includes('Group 4')) return 'badge-group-4';
  return '';
}

function getSessionBadgeClass(session) {
  return session.includes('Set A') ? 'badge-session-a' : 'badge-session-b';
}

function renderPosters() {
  const sessionABody = document.getElementById('session-a-body');
  const sessionBBody = document.getElementById('session-b-body');
  const sessionAEmpty = document.getElementById('session-a-empty');
  const sessionBEmpty = document.getElementById('session-b-empty');
  const sessionATable = document.getElementById('session-a-table');
  const sessionBTable = document.getElementById('session-b-table');
  
  sessionABody.innerHTML = '';
  sessionBBody.innerHTML = '';
  
  const sessionA = currentData.filter(p => p.session.includes('Set A'));
  const sessionB = currentData.filter(p => p.session.includes('Set B'));
  
  // Update stats
  document.getElementById('total-posters').textContent = currentData.length;
  document.getElementById('session-a-count').textContent = sessionA.length;
  document.getElementById('session-b-count').textContent = sessionB.length;
  
  // Render Session A
  if (sessionA.length === 0) {
    sessionATable.style.display = 'none';
    sessionAEmpty.style.display = 'block';
  } else {
    sessionATable.style.display = 'table';
    sessionAEmpty.style.display = 'none';
    sessionA.forEach(poster => {
      const row = document.createElement('tr');
      row.innerHTML = `
        <td><strong>#${poster.number}</strong></td>
        <td>${poster.title}</td>
        <td><span class="badge ${getGroupBadgeClass(poster.group)}">${poster.group}</span></td>
      `;
      sessionABody.appendChild(row);
    });
  }
  
  // Render Session B
  if (sessionB.length === 0) {
    sessionBTable.style.display = 'none';
    sessionBEmpty.style.display = 'block';
  } else {
    sessionBTable.style.display = 'table';
    sessionBEmpty.style.display = 'none';
    sessionB.forEach(poster => {
      const row = document.createElement('tr');
      row.innerHTML = `
        <td><strong>#${poster.number}</strong></td>
        <td>${poster.title}</td>
        <td><span class="badge ${getGroupBadgeClass(poster.group)}">${poster.group}</span></td>
      `;
      sessionBBody.appendChild(row);
    });
  }
}

function filterPosters() {
  const searchTerm = document.getElementById('search-input').value.toLowerCase();
  const groupFilter = document.getElementById('group-filter').value;
  const sessionFilter = document.getElementById('session-filter').value;
  
  currentData = postersData.filter(poster => {
    const matchesSearch = searchTerm === '' || 
                         poster.title.toLowerCase().includes(searchTerm) ||
                         poster.number.toString().includes(searchTerm);
    const matchesGroup = groupFilter === '' || poster.group.includes(groupFilter);
    const matchesSession = sessionFilter === '' || poster.session.includes(sessionFilter);
    
    return matchesSearch && matchesGroup && matchesSession;
  });
  
  renderPosters();
}

function clearFilters() {
  document.getElementById('search-input').value = '';
  document.getElementById('group-filter').value = '';
  document.getElementById('session-filter').value = '';
  currentData = [...postersData];
  renderPosters();
}

function sortTable(session, columnIndex) {
  const data = currentData.filter(p => 
    session === 'a' ? p.session.includes('Set A') : p.session.includes('Set B')
  );
  
  const sortKey = columnIndex === 0 ? 'number' : columnIndex === 1 ? 'title' : 'group';
  
  data.sort((a, b) => {
    if (sortKey === 'number') return a[sortKey] - b[sortKey];
    return a[sortKey].localeCompare(b[sortKey]);
  });
  
  const otherData = currentData.filter(p => 
    session === 'a' ? !p.session.includes('Set A') : !p.session.includes('Set B')
  );
  
  currentData = session === 'a' ? [...data, ...otherData] : [...otherData, ...data];
  renderPosters();
}

// Event listeners
document.getElementById('search-input').addEventListener('input', filterPosters);
document.getElementById('group-filter').addEventListener('change', filterPosters);
document.getElementById('session-filter').addEventListener('change', filterPosters);

// Initial render
renderPosters();
</script>
