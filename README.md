# Q-Classify
Fraudulent digital communications threaten security and privacy. This study introduces Q-Classify, a hybrid system using QSVM and VQC for spam detection. Text data is vectorized, reduced, and classified via PennyLane quantum layers. Results: QSVM hit 92.02%, while a VQC–SVM ensemble achieved 94.24%, proving QML’s potential in cybersecurity.
Q-Classify: Quantum Spam Detection

Welcome to Q-Classify, a hybrid quantum–classical project that tackles spam detection using Variational Quantum Classifiers (VQC) and Quantum Support Vector Machines (QSVM).

✨ Powered by PennyLane, scikit-learn, and a dash of quantum magic.

📂 Project Files

VQC-SVM.ipynb → Main notebook with the complete pipeline (data preprocessing → quantum classification → evaluation).

Untitled38.ipynb → Scratchpad / demo code (quick experiments, useful for testing).

🚀 Quick Start

Clone this repo (or download ZIP):

git clone https://github.com/yourusername/q-classify.git
cd q-classify


Install dependencies:

pip install pennylane scikit-learn matplotlib


Run the notebook:
Open VQC-SVM.ipynb in Jupyter or VS Code and run cells step by step.

🎯 What’s Inside?

🔹 Data Preprocessing → Cleans and vectorizes spam/ham messages.
🔹 Dimensionality Reduction → Prepares compact embeddings for quantum circuits.
🔹 QSVM & VQC Models → Quantum classifiers trained on reduced feature sets.
🔹 Hybrid Ensemble → VQC + classical SVM = best performance (94.24%).
🔹 Results & Plots → Accuracy, confusion matrices, and learning curves.

🕹️ Try It Yourself

Change the dataset (any spam/ham text).

Adjust quantum circuit depth in the notebook.

Compare with purely classical models (like Logistic Regression).

👉 See how hybrid QML stacks up!

📊 Results (Highlights)

QSVM → 92.02% accuracy

VQC + Classical SVM Ensemble → 🚀 94.24% accuracy

🤝 Contributing

Want to improve the circuits, try larger datasets, or integrate other QML models?
Fork → Hack → Pull Request. Contributions welcome!

📜 License

MIT License © 2025

Do you want me to make this even more interactive by adding:

✅ Example code snippets with clickable Google Colab badge,

✅ Badges (like Python version, framework logos),

✅ GIF/diagram placeholders for visualization? 
