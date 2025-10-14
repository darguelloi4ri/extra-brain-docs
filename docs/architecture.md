# Architecture — Brain-Like AI across the Edge–Cloud Continuum

EXTRA-BRAIN’s architecture groups capabilities into three cooperating layers:

## 1) Brain-Like NN Design, Training, Validation & Benchmarking
- **Design:** Architectures inspired by cortical motifs (sparse activations/connectivity, local plasticity, recurrent motifs).  
- **Learning:** Hebbian/Bayesian local updates enabling unsupervised, semi-supervised, supervised and reward-based learning; few/one-shot and online adaptation by design.  
- **Benchmarking:** Task suites compare BLNNs to SOTA DNNs on accuracy, efficiency, scalability, and energy.

## 2) Data Integration, Processing & Management (Data Optimisation Spine, DOS)
- **APIs:** Secure, open interfaces for ingestion and harmonisation of multi-modal data.  
- **Optimisation:** Feature selection, augmentation and synthetic data, automatic labelling; privacy tooling.  
- **Visual analytics:** Built-in data understanding and model-explanation views.

## 3) Neuromorphic Systems Deployment Layer
- **HW/SW co-design:** Parameterisable RTL blocks mapped to FPGAs and ASIC libraries; variable precision.  
- **Orchestration:** Kubernetes/KubeEdge and WASM/WASI for lightweight, portable deployment across ECC.  
- **Human-in-the-loop:** Co-design/co-creation UIs; active-learning feedback; monitoring and retraining hooks.

!!! note "WP alignment"
    - WP3/WP5: NN framework and benchmarking  
    - WP4: DOS pipeline  
    - WP5: Co-design, orchestration, explainability, and human-centric tooling
