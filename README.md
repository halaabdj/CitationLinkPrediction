# :green_book: Citation Link Prediction in Scholarly Knowledge Graphs

##  :bookmark_tabs: Description
This project evaluates graph-based machine learning models for citation link prediction using the KG20C dataset.

###  Libraries Used
- Machine Learning: Scikit-learn, TensorFlow, PyTorch  
- Data Processing: Pandas, NumPy  
- Visualization: Matplotlib, Seaborn
  
##  :bookmark_tabs: Built With

* ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
* ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
* ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
* ![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
* ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
* ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
* ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
* ![Seaborn](https://img.shields.io/badge/Seaborn-4C8CBF?style=for-the-badge)
* ![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)


##  :bookmark_tabs: Dataset

The project uses the KG20C scholarly knowledge graph dataset.

Place the dataset files inside the `data/` folder:

- train.txt
- valid.txt
- test.txt
- all_entity_info.txt
- all_relation_info.txt

##  :bookmark_tabs: How to Run

pip install -r requirements.txt  
Open `notebooks/analysis.ipynb` and run all cells.

##  :bookmark_tabs: Models
- Logistic Regression
- Random Forest
- Neural Network
- TransE
- DistMult

## :bookmark_tabs: Repository Structure
- `data/` contains dataset files
- `results/figures/` contains plots and figures
- `notebooks/` contains the analysis notebook
- `paper/` contains the final IEEE-format PDF
