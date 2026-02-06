# CPU vs GPU Execution Time Analysis for ANN Training

## ⏱️ Runtime Performance Benchmarking

To evaluate execution efficiency, the same ANN-based churn prediction model was trained on two different environments using identical code, data, and hyperparameters.

## Environment	Runtime
- VS Code (Local Execution)	0.73 minutes
- Google Colab (Cloud Execution)	0.30 minutes

## obervations

Google Colab completed training significantly faster due to optimized compute resources.

Local execution time depends heavily on system hardware and background processes.

## 📌 Conclusion

Execution environment plays a crucial role in deep learning performance.
Cloud-based platforms can offer faster experimentation cycles and improved productivity.

## Practical Observation

Cloud-based platforms such as Google Colab can substantially reduce model training time, enabling faster experimentation and iteration compared to local execution.

---
This experiment reinforces the importance of environment-aware benchmarking when designing and optimizing deep learning workflows for training and deployment.
