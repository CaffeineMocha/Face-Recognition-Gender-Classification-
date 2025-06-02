# Gender Classification Using 3 CNN Models (ResNet50, VGG19, and GoogLeNet)

This project performs gender classification on face images using three popular convolutional neural network (CNN) architectures:
- **ResNet50**
- **VGG19**
- **GoogLeNet (Inception v3)**

The models are trained and evaluated on a labeled face dataset, and the results are compared to determine the best-performing model.

---

## 📁 Project Files

- `Gender_Classification_Model.ipynb` – The complete Jupyter notebook with model training, evaluation, and comparisons.
- `Face_Recognition_Project_Presentation.pdf` – A project presentation summarizing goals, methods, and results.
- `requirements.txt` – Required Python packages to run the notebook.

---

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/CaffeineMocha/Face-Recognition-Gender-Classification-.git
   cd Face-Recognition-Gender-Classification-
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter notebook:**
   ```bash
   jupyter notebook Gender_Classification_Model.ipynb
   ```

---

## 📊 Models Used

| Model      | Description                      |
|------------|----------------------------------|
| ResNet50   | Deep residual network, 50 layers |
| VGG19      | Very deep CNN with 19 layers     |
| GoogLeNet  | Inception v3 architecture        |

Each model is trained on the same dataset, and their performance is evaluated using accuracy and loss metrics.

---

## 📌 Notes

- The training may take time depending on hardware (20+ epochs).
- Feel free to modify the notebook and use your own dataset.
- All models use transfer learning and are fine-tuned for gender classification.

---

## 📬 Contact

Created by [CaffeineMocha](https://github.com/CaffeineMocha)  
For questions, feel free to open an issue or contact via GitHub.
