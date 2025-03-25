# MasterChef

MasterChef is a deep learning-powered (Transformer Architecture Based) application that transforms food images into personalized recipes using computer vision and natural language processing. Built with Streamlit for the frontend, it integrates advanced image processing and text generation techniques to deliver accurate dish identification and step-by-step cooking instructions. Simply snap a photo, let our AI analyze it, and discover a world of culinary possibilities.

### Interface

<p align="center">
  <img src="https://github.com/Hussainaquib/MasterChef/blob/main/data/images/2.png" alt="MasterChef">
</p>

### Results

<p align="center">
  <img src="https://github.com/Hussainaquib/MasterChef/blob/main/data/images/3.png" alt="Food Image">
</p>
<p align="center">
  <img src="https://github.com/Hussainaquib/MasterChef/blob/main/data/images/4.png" alt="Recipe Generation">
</p>

### Architecture of Transformer

<p align="center">
  <img src="https://github.com/Hussainaquib/MasterChef/blob/main/data/images/5.png" alt="Transformer">
</p>

### How this Architecture works ❓ 

1️⃣ Image → CNN Encoder (ResNet-101 + Conv Projection):
Extracts spatial features and produces (x, y, z) output.

2️⃣ Encoder output → Passed to Transformer Decoder’s Cross-Attention:
Used as Key (K) and Value (V) in cross-attention.

3️⃣ Decoder’s Multi-Head Cross-Attention:
Matches decoder's queries with encoder's keys and values.

4️⃣ Final Softmax Layer Outputs Probabilities:
Decoder generates text/tokens conditioned on encoded image features


