**Project Overview**

An end-to-end brain-computer interface system that allows users to interactively explore how the brain responds to different mental tasks. Users select imagined actions (e.g., "move left hand") and the system predicts and visualizes brain activity in real-time using machine learning and low-level optimized signal processing.


**Key Features**

Interactive Brain Control: Select mental tasks and watch predicted brain regions activate in real-time
Sub-50ms Latency: Custom C++ signal processing kernels with lock-free data structures for real-time performance

ML-Powered Predictions: PyTorch-based classifier trained on motor imagery EEG data predicts brain activity patterns

3D Brain Visualization: Interactive topographic maps and 3D brain models showing active regions
Real-Time Signal Streaming: Simulates 64-channel EEG data at 160Hz with multi-threaded processing pipeline


**Problem Statement**

Brain-computer interfaces require real-time processing of neural signals with minimal latency while providing intuitive user experiences. This project demonstrates a complete BCI pipeline from low-level signal processing to high-level user interaction, addressing key challenges in neural interface development:

Real-time constraints: Processing 64 channels of EEG data with <50ms latency
User experience: Making complex brain data interpretable and interactive
Predictive modeling: Using ML to map mental tasks to expected brain activity patterns
System performance: Optimizing the entire stack from C++ to web frontend


