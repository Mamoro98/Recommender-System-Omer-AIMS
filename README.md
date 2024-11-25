# Recommender System  

## Overview  
This project demonstrates a **Movie Recommender System** built using collaborative filtering techniques, including Alternating Least Squares (ALS) with and without latent factors. The system efficiently predicts user ratings for movies and ranks recommendations.  

## Features  
- Implements data preprocessing for user and movie interactions.  
- Utilizes ALS for bias correction and latent factor modeling.  
- Visualizes movie traits using PCA for dimensionality reduction.  
- Identifies and ranks the most and least polarizing movies based on ratings.  

## Technologies Used  
- **Programming Languages**: Python  
- **Libraries**: NumPy, Pandas, Matplotlib, PyTorch  
- **Visualization**: Seaborn, PCA  
- **Data Handling**: Pickle, CSV  

## Getting Started  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/Mamoro98/Recommender-System-Omer-AIMS.git  
   ```  
2. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  
3. Run the Jupyter Notebook for step-by-step implementation and visualization.  

## Project Structure  
- **`Recommender system first draft.ipynb`**: Main implementation of the recommender system.  
- **Data files**: Includes ratings and movies datasets (link in the notebook).  

## Visualizations  
- Degree distribution for users and movies.  
- PCA-based movie trait vectors in 2D space.  
- Rating distributions by genre and polarization analysis.  

## Future Enhancements  
- Integrate hybrid recommendation techniques.  
- Extend to real-time recommendation systems.  

## License  
This project is open-source and available under the [MIT License](LICENSE).  

---