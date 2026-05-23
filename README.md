# Amir Masoud Almasi
ML/AI Engineer | M.Sc. in Data Science @ Politecnico di Torino | B.Sc. in Mathematics | Ex-Data Analyst @ MCI (1+ year)

<hr>

### Tech Stack

<div align="center">
  <table width="100%" style="line-height: 2;">
    <tr>
      <td align="right" valign="middle" width="30%"><b>Languages & Development</b></td>
      <td align="left" valign="middle">
        &nbsp;&nbsp; Python &nbsp;|&nbsp; C &nbsp;|&nbsp; SQL &nbsp;|&nbsp; Git &nbsp;|&nbsp; Streamlit &nbsp;|&nbsp; LaTeX
      </td>
    </tr>
    <tr>
      <td align="right" valign="middle" width="30%"><b>Machine & Deep Learning</b></td>
      <td align="left" valign="middle">
        &nbsp;&nbsp; PyTorch &nbsp;|&nbsp; Hugging Face &nbsp;|&nbsp; Scikit-Learn &nbsp;|&nbsp; OpenCV
      </td>
    </tr>
    <tr>
      <td align="right" valign="middle" width="30%"><b>LLMs & Generative AI</b></td>
      <td align="left" valign="middle">
        &nbsp;&nbsp; LangChain &nbsp;|&nbsp; LangGraph &nbsp;|&nbsp; LlamaIndex &nbsp;|&nbsp; Ollama
      </td>
    </tr>
    <tr>
      <td align="right" valign="middle" width="30%"><b>Data Analytics & Visualization</b></td>
      <td align="left" valign="middle">
        &nbsp;&nbsp; Power BI &nbsp;|&nbsp; Excel &nbsp;|&nbsp; Pandas &nbsp;|&nbsp; NumPy &nbsp;|&nbsp; Matplotlib &nbsp;|&nbsp; Seaborn
      </td>
    </tr>
    <tr>
      <td align="right" valign="middle" width="30%"><b>Data Management & Big Data</b></td>
      <td align="left" valign="middle">
        &nbsp;&nbsp; PySpark &nbsp;|&nbsp; Hadoop &nbsp;|&nbsp; SQL Server &nbsp;|&nbsp; MongoDB &nbsp;|&nbsp; ChromaDB
      </td>
    </tr>
  </table>
</div>

<hr>

### Selected Projects

#### [Multi-Agent Historical Fact-Checking RAG](https://github.com/ameermasood/MultiAgentRAGHistoricus) (In Development)
Python &nbsp;&nbsp; |&nbsp;&nbsp; LangChain &nbsp;&nbsp; |&nbsp;&nbsp; LangGraph &nbsp;&nbsp; |&nbsp;&nbsp; LlamaIndex &nbsp;&nbsp; |&nbsp;&nbsp; ChromaDB &nbsp;&nbsp; |&nbsp;&nbsp; DeepEval

* **Objective:** Build a fact-checking system that can verify historical claims using RAG.
* **Architecture:** Cyclic **LangGraph** workflow with specialized agents (Router, Librarian, Historian, Judge) over a **ChromaDB** + **LlamaIndex** retrieval stack with **Nomic** embeddings.

#### [RGB-D 6D Object Pose Estimation](https://github.com/ameermasood/HeatNet)
PyTorch &nbsp;&nbsp; |&nbsp;&nbsp; YOLO &nbsp;&nbsp; |&nbsp;&nbsp; ResNet &nbsp;&nbsp; |&nbsp;&nbsp; OpenCV &nbsp;&nbsp; |&nbsp;&nbsp; NumPy &nbsp;&nbsp; |&nbsp;&nbsp; Pandas

* **Objective:** Texture-less 3D object pose estimation targeting robotics and autonomous manipulation.
* **Architecture:** **YOLOv10m** detection combined with a **ResNet18** heatmap regression network and multi-stage **RGB-D cross-fusion**.
* **Result:** **92.4% mean ADD** accuracy on LINEMOD, outperforming the RGB-only baseline by **+7.9%**.

#### [Multimodal Speech Emotion Recognition](https://github.com/ameermasood/MultimodalSpeechEmotionRecognition)
PyTorch &nbsp;&nbsp; |&nbsp;&nbsp; Torchaudio &nbsp;&nbsp; |&nbsp;&nbsp; Hugging Face (Transformers, PEFT)

* **Objective:** High-fidelity speech emotion recognition evaluated on the complex ESD and IEMOCAP speech corpuses.
* **Architecture:** **Voxtral-mini-3B** audio-language model fine-tuned with **LoRA** and **DoRA** PEFT on ESD & IEMOCAP.
* **Result:** **0.84 macro-F1** in-domain and **0.63 zero-shot** cross-domain generalization.

#### [Figurative Language Sentiment Detection](https://github.com/ameermasood/FigLangUnderstanding)
PyTorch &nbsp;&nbsp; |&nbsp;&nbsp; Hugging Face &nbsp;&nbsp; |&nbsp;&nbsp; RoBERTa &nbsp;&nbsp; |&nbsp;&nbsp; Adapters

* **Objective:** Detecting sarcasm, irony, and sentiment under severe dialectal and domain shifts.
* **Architecture:** **RoBERTa-Large** ensemble with **Mixture-of-Adapters (MoA)** and a **Tensor-of-Cues (ToC)** prompt-tuning mechanism.
* **Result:** **+16%** cross-variety sarcasm classification and **+18%** zero-shot dialect adaptation.