
# Pollution Data ML Project  

## Overview  
This project involves analyzing air, soil, and water pollution datasets, performing feature engineering, training machine learning models, and generating downloadable trained models for evaluation. The notebook runs entirely in Google Colab for simplicity and accessibility.  

---

## Requirements  
- Python 3.x  
- Google Colab account  
- Libraries:  
  ```bash
  pandas  
  numpy  
  scikit-learn  
  joblib  
  google.colab
  ```

---

## Workflow  
1. **Load Datasets**: Load air, soil, and water pollution datasets into DataFrames.  
2. **Feature Engineering**: Process raw data to create `*_df_fe` datasets.  
3. **Train-Test Split**: Split each dataset into 80% training and 20% testing.  
4. **Model Training**: Train RandomForest models for each dataset.  
5. **Save & Download**: Save trained models as `.pkl` files and download them locally.  
6. **Submission**: Upload code and models to GitHub and paste the repo link in LMS as per instructions.  

---

## How to Run in Google Colab  
1. Open the project Colab link:  
   ```
   https://colab.research.google.com/drive/1khgzr3S9aJPCHiTyUqet5bM883yO0Kq5
   ```  
2. Run cells sequentially from top to bottom.  
3. Models will be saved and downloaded automatically using:  
   ```python
   from google.colab import files
   files.download('model_name.pkl')
   ```  

---

## Submission Process  
As per the provided guidelines:  
- **Week 1 & Week 2**: Upload project source code on GitHub and submit the repo link in LMS.  
- **Final Submission**: Upload source code (`.ipynb` file) + final PPT in given template + trained model files to GitHub and share link in LMS.  

---
