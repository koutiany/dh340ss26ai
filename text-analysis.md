---
layout: default
title: Text Analysis Project
---

<section class="hero" style="padding: 3rem 2rem;">
    <h1>Text Analysis Project</h1>
    <p>Comparing approaches to analyzing news articles on Michigan data centers</p>
</section>

<section class="section">
    <h2>The Project Overview</h2>
    <p>
        In our final collaborative project, the class compared two approaches of doing text analysis on 
        news articles about data centers in Michigan:
    </p>
    <ul>
        <li><strong>AI-Assisted Topic Modeling:</strong> Using ProQuest TDM's service</li>
        <li><strong>Python-Based LDA:</strong> Developing a Latent Dirichlet Allocation workflow in Jupyter notebook</li>
    </ul>
</section>

<section class="section">
    <figure class="image-placeholder" style="margin: 2rem 0; padding: 2rem; background: #f3f4f6; border-radius: 8px; text-align: center;">
        <p style="color: #6b7280; font-style: italic;">[IMAGE PLACEHOLDER: Topic modeling visualization or project screenshot]</p>
        <p style="font-size: 0.875rem; color: #6b7280;">Upload to: <code>assets/images/</code></p>
    </figure>
</section>

<section class="section">
    <h2>Topic Modeling Explained</h2>
    <div class="content-card">
        <h3>What is Topic Modeling?</h3>
        <p>
            Topic modeling is an unsupervised machine learning technique that automatically identifies 
            themes or "topics" within a collection of documents. It works by finding groups of words 
            that frequently appear together, assuming these represent coherent topics.
        </p>
    </div>
</section>

<section class="section">
    <h2>The Two Approaches</h2>
    
    <div class="two-column">
        <div class="content-card">
            <h3>ProQuest TDM Service</h3>
            <p>
                An AI-assisted topic modeling service that provides a user-friendly interface for 
                text analysis. The service handles preprocessing and topic extraction automatically.
            </p>
            <h4>Pros:</h4>
            <ul>
                <li>Easy to use, minimal coding required</li>
                <li>Quick results</li>
                <li>Handles preprocessing automatically</li>
            </ul>
            <h4>Considerations:</h4>
            <ul>
                <li>Less control over parameters</li>
                <li>"Black box" preprocessing decisions</li>
            </ul>
        </div>
        <div class="content-card">
            <h3>Python LDA Workflow</h3>
            <p>
                A custom Jupyter notebook workflow where students wrote Python code to implement 
                Latent Dirichlet Allocation from scratch.
            </p>
            <h4>Pros:</h4>
            <ul>
                <li>Full control over preprocessing</li>
                <li>Transparent methodology</li>
                <li>Customizable parameters</li>
            </ul>
            <h4>Considerations:</h4>
            <ul>
                <li>Requires programming knowledge</li>
                <li>More time investment</li>
            </ul>
        </div>
    </div>
</section>

<section class="section">
    <h2>Key Findings</h2>
    <div class="highlight-box">
        <h3>Why Transparency Matters</h3>
        <p>
            By comparing these two approaches, students discovered how preprocessing decisions and 
            parameter choices shape topic modeling outcomes. The same data can reveal different 
            "topics" depending on how it's processed and analyzed.
        </p>
    </div>
</section>

<section class="section">
    <h2>What We Learned</h2>
    <ol>
        <li>
            <strong>Preprocessing Matters:</strong> How text is cleaned, tokenized, and filtered 
            significantly affects results
        </li>
        <li>
            <strong>Parameter Sensitivity:</strong> The number of topics, iteration count, and other 
            parameters influence outcomes
        </li>
        <li>
            <strong>Interpretive Choices:</strong> Researchers make many implicit choices that shape 
            what the data "reveals"
        </li>
        <li>
            <strong>Reproducibility:</strong> Transparent code-based approaches enable others to 
            verify and build upon work
        </li>
    </ol>
</section>

<section class="section">
    <h2>Implications for Research</h2>
    <p>
        This project demonstrates that AI tools are not neutral—they embed assumptions and choices 
    that shape what we learn. For researchers, this means:
    </p>
    <ul>
        <li>Understanding how tools work is essential for critical interpretation</li>
        <li>Documentation and transparency support scholarly rigor</li>
        <li>Comparing methods reveals the influence of methodological choices</li>
    </ul>
</section>

<section class="section">
    <p><a href="{{ '/' | relative_url }}">&larr; Back to Home</a></p>
</section>
