# Models

This folder contains the trained deep learning models used in the Dog Skin Disease Classification project.

## Files

### `best_model.keras`

* Stores the model that achieved the best performance during training.
* This model can be used for evaluation and prediction.

### `final_deployment_model.keras`

* Stores the final model used for the Gradio demonstration and deployment.
* This model is loaded by the demo to classify uploaded dog skin images.

## Note

These models were trained on the cleaned and preprocessed Dog Skin Disease dataset and can be loaded directly using TensorFlow/Keras for inference or further evaluation.
