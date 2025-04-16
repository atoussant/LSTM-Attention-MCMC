# Time Series Generation with LSTM + Attention

This project generates synthetic time series using an LSTM architecture with attention. Useful for augmenting datasets or modeling hypothetical market behaviors.

## Model Architecture
- LSTM with Attention Layer
- Uses Financial data to extract learning patterns and create realistic generated pricing data using a Monte Carlo approach.
- Compares results to the fBM-GARCH model
- Uses a non-standard loss to better predict market movements

## Sample Output
<p align="center">
  <img src="eval/synthetic_sample.png" width="500">
</p>

## Training
```bash
python training/train_model.py --epochs 100
