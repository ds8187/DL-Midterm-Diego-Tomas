# DL-Midterm-Diego-Tomas

# Outline:

* Provide 3 Notebooks (final submission also linked below along with model weights):

1. DL_Diego&Tomas_FinalSubmission.ipynb: Full Notebook which includes dataset cleaning, training, and inferance. Suggested to view the full scope of our model finetuning process. (linked in the readme to open directly in google colab)
3. Inference_Only.ipynb: Inferance Notebook which just need weights provided (linked below). Provided here to display how we ran inference model states from previous run times.
4. DataClean.ipynb: Data exploratory analysis and preprocessing Notebok which explores the intricate details of the dataset. Provided here to detail work done that was not in the original submission notebook.

How To Recreate Results:

The suggested method would be to open the notebook titled DL_Diego&Tomas_FinalSubmission.ipynb (either select the link below to open it directly in colab or download it from the repository). All code is set to be the exact same as the code that produced our best submission in the kaggle competition. You can simply start a run time and select run all (G4 GPU suggested).

Alternatively, you can use the notebook we provided titled Inference_Only.ipynb. If you choose that there is a couple of extra steps. You must download the model state (linked below), and save it to your MyDrive folder in google drive. You must then set the varibale titled "MODEL_PATH" to be equal to the path string to the model weights in 
your MyDrive. Lastly you can start a runtime and select run all (same as the prior method).


Note:

Outputs currently in notebook are not from our final submission. The only difference between the final submission and the code that produced the outputs is that in the generate_svg function, the do_sample parameter was set to False in our final submission, and True in the code that generated the output (it has been set to False again for convenience but the outputs were not cleared and the code was not re-run). 

Link to weights: https://drive.google.com/drive/folders/1risP-tYVyFsj-RQgAfMg-qJ-acrqf4sN?usp=sharing


Link to Notebook: https://colab.research.google.com/drive/1BW3LOQxSWRTRBxXcG_r3YFBNqM6QvtkG?usp=sharing
