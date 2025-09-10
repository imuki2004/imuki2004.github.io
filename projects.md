---
layout: page
title: Projects
stylesheets:
  - projects
---

*Showcasing diverse technical expertise across different AI paradigms*

*Soon to be uploaded on GitHub...*

<div class="projects-container">

<h2>Deep Learning</h2>

<div class="project-card">
  <div class="project-header">
    <h3>Semi-Supervised Deep Learning for Multi-Class Image Classification</h3>
    <div class="project-tags">
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white" alt="PyTorch">
      <span class="tag">CNN/ResNet</span>
      <span class="tag">Semi-Supervised Learning</span>
    </div>
  </div>
  
  <div class="project-content">
    <div class="project-description">
      <ul>
        <li>Developed a semi-supervised deep learning pipeline using PyTorch to classify 14 flower categories</li>
        <li>Designed a custom DeepResNet architecture (20M parameters) with residual blocks, MixUp regularization, and pseudo-labeling</li>
        <li>Implemented advanced training techniques, including a custom scheduler, boosting generalization on a high-performance V100 GPU cluster</li>
      </ul>
    </div>
    
    <div class="project-diagram">
      <div class="diagram-placeholder">
        <span>📊</span>
        <p>Project Architecture Diagram</p>
        <small>Coming Soon</small>
      </div>
    </div>
  </div>
</div>

<h2>GenAI/LLMs</h2>

<div class="project-card">
  <div class="project-header">
    <h3>Chat with Your PDF</h3>
    <div class="project-tags">
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python">
      <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white" alt="Streamlit">
      <img src="https://img.shields.io/badge/LangChain-1c3c3c.svg?logo=langchain&logoColor=white" alt="LangChain">
      <img src="https://img.shields.io/badge/Ollama-fff?logo=ollama&logoColor=000" alt="Ollama">
      <span class="tag">RAG</span>
      <span class="tag">Qdrant</span>
    </div>
  </div>
  
  <div class="project-content">
    <div class="project-description">
      <ul>
        <li>Designed a Streamlit-based application allowing users to upload PDFs and engage in natural language conversations</li>
        <li>Integrated Qdrant for vector similarity search and a locally hosted Ollama model (deepseek-r1:8b) for context-aware answers</li>
      </ul>
    </div>
    
    <div class="project-diagram">
      <div class="diagram-placeholder">
        <span>🔄</span>
        <p>RAG Pipeline Diagram</p>
        <small>Coming Soon</small>
      </div>
    </div>
  </div>
</div>

<h2>Big Data</h2>

<div class="project-card">
  <div class="project-header">
    <h3>Efficient and Robust Approximate Nearest Neighbor Search Using Hierarchical Navigable Small World Graphs: Experiments</h3>
    <div class="project-tags">
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python">
      <img src="https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white" alt="NumPy">
      <span class="tag">HNSW</span>
      <span class="tag">Graph Algorithms</span>
      <span class="tag">Vector Search</span>
    </div>
  </div>
  
  <div class="project-content">
    <div class="project-description">
      <ul>
        <li>Conducted performance evaluations of the Hierarchical Navigable Small World Graphs (HNSW) algorithm, comparing it against Annoy, Faiss (IVF-PQ), and other ANN methods, as measured by query time, recall, and index build time across diverse datasets</li>
        <li>Designed and executed experiments to analyze HNSW’s performance, running benchmarks on dataset sizes ranging from 10^4 to 10^6, and visualized results showing HNSW outperforming competitors in recall (>0.9) with competitive query times.</li>
        <li>Achieved detailed insights through experiments on popular datasets including CIFAR-10, MNIST, SIFT1M, and GloVe1.2M, demonstrating HNSW's scalability and efficiency for 10-NN (nearest neighbor) searches with random vectors (d=8).</li>
      </ul>
    </div>
    
    <div class="project-diagram">
      <div class="diagram-placeholder">
        <span>🌐</span>
        <p>HNSW Graph Structure</p>
        <small>Coming Soon</small>
      </div>
    </div>
  </div>
</div>

<h2>Capstone Project (FYP)</h2>

<div class="project-card">
  <div class="project-header">
    <h3>Personalized Federated Learning with Early-Exit Networks</h3>
    <div class="project-tags">
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white" alt="PyTorch">
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python">
      <span class="tag">Distributed ML</span>
      <span class="tag">Privacy-Preserving</span>
      <span class="tag">Federated Learning</span>
    </div>
  </div>
  
  <div class="project-content">
    <div class="project-description">
      <ul>
        <li>Expected to be finished by April 2026</li>
      </ul>
    </div>
    
    <div class="project-diagram">
      <div class="diagram-placeholder">
        <span>🔗</span>
        <p>Federated Learning Architecture</p>
        <small>In Progress</small>
      </div>
    </div>
  </div>
</div>

</div>

[Back to Home](/)