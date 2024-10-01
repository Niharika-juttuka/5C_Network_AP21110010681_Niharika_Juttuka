# 5C_Network_AP21110010681_Niharika_Juttuka
Based on the assignment provided in the document, here’s a plan for implementation:

### **Project Breakdown:**
1. **Data Preprocessing:**
   - Apply CLAHE preprocessing to enhance metastasis visibility in MRI images.
   - Normalize and augment the dataset using techniques like flipping, rotation, and zoom to handle variations.

2. **Model Implementation:**
   - Implement **Nested U-Net (U-Net++)** and **Attention U-Net** architectures for metastasis segmentation.
   - Ensure the models are configured with appropriate loss functions, optimizers, and evaluation metrics like the DICE score.

3. **Model Training & Evaluation:**
   - Train both models using 80% of the dataset and evaluate on the remaining 20%.
   - Use the DICE score to compare the performance of both models.

4. **Web Application Development:**
   - Create a **FastAPI backend** to serve the best-performing segmentation model.
   - Build a **Streamlit UI** to allow users to upload MRI images and view segmentation results.

5. **Documentation & Submission:**
   - Document the project thoroughly in a README.md file.
   - Include a video demo, model comparison results, and a discussion on challenges and potential improvements.

### **Next Steps:**
I will start implementing the solution and push it to a GitHub repository. I’ll share the link to the repository here once it’s ready.
