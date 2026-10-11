# Models

## baseline_fraud_mlp

The lab's baseline fraud classifier: a PyTorch multilayer perceptron (29 → 64 → 32 → 2, ReLU) trained on the `train` partition of `datasets/creditcard_fraud_sample.csv.gz`.

| File | Contents |
| --- | --- |
| `baseline_fraud_mlp.pt` | PyTorch `state_dict` (weights only) |
| `baseline_fraud_mlp.json` | Model card: architecture, features, preprocessing (scaler mean and scale), training settings, test metrics, and the SHA-256 hash of the `.pt` file |

Notebooks verify the SHA-256 hash against the model card before loading, and load the weights with `torch.load(..., weights_only=True)`.
