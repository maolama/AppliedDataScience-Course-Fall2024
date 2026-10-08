# Applied Data Science — M.Sc. Coursework (Fall 2024)

Solutions to the graduate **Applied Data Science** course at the **Tehran Institute for Advanced Studies (TEIAS)**, Fall 2024 (Iranian year 1403).
The assignments were group work by **Mohammad Ali Olama** and **Mohammad Mehdi Zare**; the final project is individual.

The course covers the full data-science workflow: data cleaning, EDA, visualization, data collection, evaluation, classical ML, neural networks and generative AI. The work uses Python (pandas, scikit-learn, XGBoost/LightGBM, TensorFlow/Keras, PyTorch, Bokeh).

## Final Project — Predicting Housing Prices in Lyon
**[Final_Project/](Final_Project/)**: an end-to-end regression project on Lyon housing transactions, with a distance-to-metro feature built from station coordinates. It compares linear models, random forest, XGBoost, a neural network, and averaging and stacking ensembles. **XGBoost performs best (test R² 0.82, RMSE ≈ €66k).**

## Assignments
| # | Topic | Highlights |
|---|-------|-----------|
| [HW2](HW2/) | EDA and data cleaning | Large Iranian welfare (Refah) dataset: missing data, feature categorization, correlations |
| [HW3](HW3/) | Visualization and web scraping | Matplotlib/Seaborn/Bokeh charts; a Bama.ir car-ads scraper (~430 listings) |
| [HW5](HW5/) | Accuracy measures | Metrics for regression, binary and multi-class tasks |
| [HW6](HW6/) | Regression methods | Linear, kernel (poly/RBF), Ridge and Lasso (R² ≈ 0.92) |
| [HW8](HW8/) | Multi-class classification | SVM, logistic (multinomial vs. OvR), KNN, trees, XGBoost/LightGBM/AdaBoost (F1 ≈ 0.80) |
| [HW9](HW9/) | Neural networks | MLPs for breast-cancer classification and bike-sharing regression |
| [HW11](HW11/) | CNNs and transfer learning | Cross-validated CNN hyperparameter tuning on Fashion-MNIST; VGG19/ResNet |
| [HW12](HW12/) | Autoencoders and GenAI | Convolutional and denoising autoencoders; LLM text generation through the Groq API |

HW1, HW4, HW7 and HW10 are not included.

## Notes
- The notebooks were run on Google Colab, and paths point to Google Drive. Some datasets are included next to the notebooks; the Refah dataset is not.
- API keys have been removed.
