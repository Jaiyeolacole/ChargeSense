# Model

Planned contents:

- `load_data.py`: load and clean the MIT/Stanford cycle data
- `features.py`: extract charge-side features (capacity, resistance, CC/CV time, dQ/dV, temperature rise)
- `train.py`: train and compare models (small neural network, Random Forest, XGBoost, physics-based fade model)
- `quantize.py`: convert the selected model to an int8 format for the nRF54LM20
- `results/`: metrics tables and plots

Splits are made **by cell**, so no cell appears in both training and test sets.
