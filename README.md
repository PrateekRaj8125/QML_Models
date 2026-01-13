# Quantum Machine Learning for Strategic Decision Making

This repository is currently under developement for implementation of quantum machine learning on strategic decision making for optimal output

## Stage 1 — Learn Only the Needed Quantum Basics

- **Goal**: Understand enough quantum computing to implement QML.

    *Day 1–2*: Minimum QC Theory

    Everyone learns:

    - Qubits & superposition
    - Basic gates (X, Y, Z, H, CNOT, Rotation gates)
    - Measurement
    - Quantum circuits

    Use:
    - Qiskit textbook (free)
    - PennyLane “Intro to Quantum” tutorials

    *Day 3–4*: What is QML?

    Learn:
    - Angle embedding
    - Amplitude embedding
    - Variational Quantum Circuits (VQC)
    - Quantum Neural Networks (QNNs)
    - Hybrid quantum-classical training

    Watch:
    - Xanadu PennyLane QML crash course
    - Qiskit ML playlist

    *Day 5–7*: Divide Topics for Literature Review
    Each member summarizes 3–4 papers.

    Topics:
    - QML basics
    - VQC for classification
    - QRL (Quantum Reinforcement Learning)
    - Quantum advantage claims
    - Applications in strategy: finance, optimization, multi-agent systems

    Deliverables by end of Week 1:  
    ✔ Literature survey  
    ✔ Understand VQC models  
    ✔ Choose QML framework: PennyLane (recommended)  

    *Week 2* — Build QML Foundations

- **Goal**: Implement small QML models so your team becomes comfortable.

    Choose one framework:
    - PennyLane + PyTorch (easiest)
    - Qiskit Machine Learning

    *Day 8–10*: Everyone Implements a Simple QML Classifier
    
    Example tutorial to follow:
    - PennyLane “Variational Classifier”
    - Build model on Iris dataset
    - Team Member B leads.

    *Day 11–13*: Play With More Complex QML Models

    Optional models:
    - Quantum Kernel-based SVM
    - QAOA for optimization
    - VQC for regression

    *Day 14*: Decide the Final Experiment Setup
    
    Pick ONE for your research experiment:
    - Option A: QML for Game-Theoretic Decisions
        - Predict opponent action
        - Quantum classifier for rock-paper-scissors strategy
    - Option B: QML for Multi-Armed Bandit Decisions (Best choice)
        - Use a VQC to predict best arm
        - Compare with classical models
        - wShow regret curves
    - Option C: QML for Supply Chain / Pricing decision
    - Classify optimal pricing or inventory action
    - Team D finalizes choice and dataset.

    Deliverables by end of Week 2:  
    ✔ Working QML models  
    ✔ Classical ML baseline models ready  
    ✔ Final idea + dataset/environment chosen  

    *Week 3* — Implement the Strategic Decision-Making Model

- **Goal**: Apply QML to your decision-making task.

    *Day 15–17*: Build Problem Environment

    Examples:
    - If multi-armed bandit:
    - Simulate reward distributions
    - Encode context as angles
    - Use QML model to choose arm

    If game theory:
    - Encode opponent behavior vectors
    - Train QML model to classify best response

    *Day 18–20*: Train & Evaluate QML Model

    Train with gradient descent

    Use 4–8 qubits only (for simulators)
    Track:
    - accuracy
    - reward
    - regret
    - stability

    *Day 21*: Compare with Classical Models
    
    Team C leads baseline models:
    - Logistic regression
    - Shallow neural network
    - SVM

    Make comparison plots:
    - Accuracy vs iterations
    - Reward vs episodes
    - Decision quality

    Deliverables by end of Week 3:  
    ✔ Fully trained QML and classical models  
    ✔ Performance comparison  
    ✔ Preliminary results  
