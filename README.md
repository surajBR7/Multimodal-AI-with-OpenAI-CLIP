# **Multimodal AI with OpenAI CLIP**

This project demonstrates the power of OpenAI's CLIP (Contrastive Language-Image Pre-training) model in solving multimodal tasks by aligning images and text descriptions through cosine similarity and object recognition. It explores the zero-shot capabilities of CLIP and its robustness to distribution shifts while applying the model to custom datasets for evaluation and visualization.

---

## **Description**

The project is divided into two key tasks:  
1. **Task 1:** Understanding the foundational concepts of OpenAI's CLIP paper and writing a structured essay covering pre-training methods, workflow, zero-shot transfer, distribution shift, and limitations.  
2. **Task 2:** Interacting with the CLIP model to analyze and visualize image-text similarities using a custom dataset of 10 images from the COCO dataset.

---

## **Key Features**

1. **Cosine Similarity Matrix:**  
   - Heatmap representation of the similarity between text descriptions and image features.
   - Higher similarity scores highlighted using lighter colors, showcasing the strongest matches between text and image pairs.

2. **Probability-Based Object Detection:**  
   - Bar charts for each image visualizing the probability of detected objects.
   - Highlights the model's ability to identify diverse objects in varied contexts, from indoor settings (e.g., a laptop on a table) to outdoor environments (e.g., a ski slope).

3. **Zero-Shot Transfer Capabilities:**  
   - Demonstrates the power of CLIP to predict labels for unseen data without additional training.

4. **Robustness to Distribution Shift:**  
   - Explores CLIP's ability to generalize across different datasets and environments due to its large-scale pre-training on diverse text-image pairs.

---

## **Requirements**

To run this project, you need the following:  
- **Python Libraries:**
  - `numpy`
  - `matplotlib`
  - `torch`  
  Install them using:
  ```bash
  pip install numpy matplotlib torch
  ```
  Google Colab: Free cloud computing for running the Interacting_with_CLIP.ipynb notebook.

## Usage

1. **clone the Repository.**
   ```bash
   git clone https://github.com/surajBR7/Multimodal-AI-with-CLIP.git
    cd Multimodal-AI-with-CLIP
   ```
   ## **Download the COCO Dataset**

1. **Select 10 images** with specific prompts like "cat," "clock," or "bowl" from [COCO Dataset Explorer](https://cocodataset.org/#explore).
2. **Save them** in a folder named `image10`.

---

## **Run the Notebook on Colab**

1. Open `Interacting_with_CLIP.ipynb` on Google Colab.
2. Replace the default dataset with the **10 COCO images** and your **custom prompts**.
3. Execute the notebook to generate:
   - **Cosine similarity matrix** between text and image features.
   - **Probability-based object detection bar charts**.

---

## **Visualize Results**

1. The **heatmap** shows alignment between textual descriptions and images.
2. The **bar charts** display object detection probabilities.

---

## **Outputs**

### **Cosine Similarity Matrix**
- Showcases the alignment between text descriptions and images.

### **Probability Diagrams**
- Highlights the model's confidence in object detection for each image.

---

## **Project Insights**

### **Cosine Similarity Analysis**
- Notable high-similarity matches include:
  - **"A clock with no numbers attached to a wall"** with the clock image.
  - **"A group of people on a ski slope"** with the ski slope image.

### **Diverse Context Detection**
- The model effectively adapts to various scenarios, from identifying objects like "laptop" in indoor settings to "mountain" in outdoor environments.

### **Zero-Shot Learning**
- CLIP's zero-shot capabilities eliminate the need for task-specific training while achieving performance comparable to specialized models.

---

## **References**

1. **OpenAI CLIP:** [GitHub Repository](https://github.com/openai/CLIP)
2. **Dataset:** [COCO Dataset Explorer](https://cocodataset.org/#explore)

---

## **Author**

**Suraj Basavaraj Rajolad**  
Graduate Student at UMass Dartmouth


