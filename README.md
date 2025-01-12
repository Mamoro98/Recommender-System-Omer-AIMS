# 🎬 Movie Recommender System

## 📜 Overview  
This project presents an enhanced **Movie Recommender System** leveraging collaborative filtering techniques, specifically the Alternating Least Squares (ALS) algorithm with biases and latent factor models. The system is designed for scalability and accuracy, achieving a Root Mean Square Error (RMSE) of 0.81 on the MovieLens dataset.

## ⚙️ Features  
- **Advanced ALS Modeling**: Incorporates user and item biases with latent factor models.
- **Efficient Data Handling**: Implements optimized data structures for efficient ALS training.
- **Vectorized Computations**: Uses vectorization for faster bias and latent factor updates.
- **Polarization Analysis**: Identifies and ranks the most and least polarizing movies.
- **Movie Embedding Visualization**: Visualizes movie relationships in latent space.

## 🛠️ Technologies Used  
- **Programming Languages**: Python 🐍  
- **Libraries**: NumPy, Pandas, Matplotlib, Scikit-learn 📊  
- **Visualization**: Seaborn, Matplotlib 📉  
- **Data Handling**: Pickle, CSV 📂  

## 🚀 Getting Started  
Run the Jupyter Notebook for step-by-step implementation and visualization.

## 📁 Project Structure  
- **`Recommender system Notebook.ipynb`**: Updated implementation with vectorized ALS and bias integration.  
- **Data files**: MovieLens dataset for training and evaluation ([MovieLens Dataset](https://grouplens.org/datasets/movielens/)).  
- **Research Report**: Detailed methodology and results (`omer_mlas.pdf`).  

## 📊 Visualizations  
- Degree distribution for users and movies.
- Zipf's Law analysis of rating distributions.
- Latent space visualization of movie embeddings.
- Polarization analysis using standard deviation of ratings and latent norms.

## 🔮 Results  
- **RMSE Achieved**: 0.81  
- **Bias-Only Model**: Efficient baseline for rating predictions.  
- **Bias + Latent Factor Model**: Enhanced accuracy and personalization.
- **Polarization Insights**: Identification of highly divisive and universally liked movies.


## 📚 Live Demo & Repositories

- **Live Web Application**: Movie Recommender Web App

- **Frontend Repository**: GitHub - Frontend

- **Backend Repository**: GitHub - Backend



## 🔮 Future Enhancements  
- **Hybrid Recommendation**: Integrate content-based filtering with collaborative filtering.
- **Real-Time Recommendations**: Transition to dynamic recommendation generation.
- **Web Application**: Interactive web interface built with Next.js and Flask.  
- **JAX Integration**: Re-implement ALS using JAX for performance optimization.  
- **Temporal Dynamics**: Incorporate time-based user preference modeling.

## 📝 License  
This project is open-source and available under the [MIT License](LICENSE).

