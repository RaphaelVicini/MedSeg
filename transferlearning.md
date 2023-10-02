# Transfer Learning

Transfer learning enables the fine tunning of an existing model. For instance, if a user trained their model with 10 images and wishes to include an additional 5 cases, there's no need to retrain an entirely new model from scratch. 

To employ transfer learning:

1. Add the additional images to the existing project.
2. Click the 'train model' button and ensure the parameters match those of the model you wish to refine.
3. The name of the new training session must match the original model's name. This signals the script to use the existing model, incorporate the new images, and enhance it.

After the training concludes, the updated model will be named in the format: 'MODELNAME_TL_v1'. If you opt for transfer learning on 'MODEL_NAME_TL_v1', then name the next trained model similarly. It will subsequently generate a model named 'MODELNAME_TL_v2', and so on.
