# Coding-attention-mechanism-from-scratch

 ##  <b> 🔥 Demystifying Large Language Models: The Importance of Understanding "Under the Hood" </b> 

🎯 As large language models (LLMs) continue to transform the tech landscape, it's easy to focus solely on application building and overlook what's actually happening inside these complex systems. While creating innovative applications is exciting, I believe it's just as crucial to understand the mechanics behind LLMs. </br>

💡 That's why I created a Jupyter notebook that explores the attention mechanism from scratch, focusing on its role in language translation which is one of the earliest applications that revolutionized LLMs.

👉🏻 In this notebook, I demonstrate the difference between a simple encoder-decoder structure and an encoder-decoder with attention. By implementing the attention mechanism and comparing BLEU scores, I highlight how attention significantly enhances translation accuracy. This deeper dive into the inner workings of LLMs not only strengthens our knowledge but also guides us toward building more efficient applications.

## 📰 Reference research paper Links
<b>Paper 1</b>: Effective approach to attention based neural machine translation:
https://arxiv.org/pdf/1409.0473.pdf </br>
<b>Paper 2</b>: Neural Machine Translation by jointly learning to align and translate:
https://arxiv.org/pdf/1508.04025.pdf

### 📸 Global and local attention illustrations
* Here I have coded global attention for language translation of Italian to English </br>
<img width="700" caption="Global and local attention" src="https://github.com/Rohan-Thoma/Coding-attention-from-scratch/assets/98249384/9d1d1c42-7f38-46f4-ac60-52f35d90423b"> </br></br>

### 📊 Visualizing attention weights for 3 scoring functions Dot, General and Concat

<img width="230" caption="Attention weights plot for dot scoring function" src="https://github.com/Rohan-Thoma/Coding-attention-from-scratch/assets/98249384/fcf31418-b4db-4759-acd7-0c6b8c3bbeab">

<img width="230" caption="Attention weights plot for general scoring function" src="https://github.com/Rohan-Thoma/Coding-attention-from-scratch/assets/98249384/ffa52989-19cb-4f09-abb8-287d2db9bdc2">

<img width="230" caption="Attention weights plot for concat scoring function" src="https://github.com/Rohan-Thoma/Coding-attention-from-scratch/assets/98249384/12e61ef2-d4bd-4a40-a59f-41a456220d70">

### 🏆 BLEU score comparison between the models 

<img width="900" caption="Score comparison with and without attention" src="https://github.com/Rohan-Thoma/Coding-attention-from-scratch/assets/98249384/f5aab724-1f8d-413d-9968-8d94525d23cf">

