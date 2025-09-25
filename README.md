# ML-spotify-genre-classifier
# Spotify Genre Classifier (Kaggle)

LightGBM + Optuna pipeline to predict **top genre** on the CS98X Spotify classification data.

**Tech:** Python, LightGBM, Optuna, scikit-learn  
**Validation:** Stratified K-Fold + early stopping  
**Result:** <add your best CV accuracy or LB metric>

## Files
- `spotify_genre_classifier.ipynb` — full training & inference (Kaggle-ready paths)
- `spotify_genre_predictions.csv` — sample submission (optional)

## Reproduce (Kaggle)
Attach:
- `/kaggle/input/cs-985-6-spotify-classification-problem-2025/CS98XClassificationTrain.csv`
- `/kaggle/input/cs-985-6-spotify-classification-problem-2025/CS98XClassificationTest.csv`

Output is saved to `/kaggle/working/spotify_genre_predictions.csv`.
