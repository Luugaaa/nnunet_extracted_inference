# nnunet_extracted_inference

Code to run inference with nnUnet code in a Trainer agnostic way.

Add a checkpoint named `checkpoint.pth` under `inference_model`.

You can run `python extracted_inference_code/predict_from_raw_data.py -i data -o ./results --save_probabilities -device mps -inf_dir_path inference_model`

## Warning 
Warning : You should probably follow the nnUnet data pipeline (process the data into nnUnet format) and set the necessary environement varibales. 
