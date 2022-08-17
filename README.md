# DLI ambassador project: Clock Reader

![what_time_is_it](https://user-images.githubusercontent.com/3192324/185134059-e0fe20ed-ec36-47eb-93d5-946fd59c8208.png)

- Based on the Jetson Nano course material (classification model for thumbs-up/down)
- The original example from the course material has been modified to this project, "clock reader": given an image of analog clock face, the model reads the clock 

![clock_reader](https://user-images.githubusercontent.com/3192324/185050448-337f6bed-e5c6-493f-9f19-bf715a508b90.png)

- Each time category (i.e. 1~12) has approx 50 images for training (in /data/clock_fingers_A folder)
- You can load and test an example model in the data folder
- The summary of test results can be found in the summary file: DLI_ambassador_project_description_R1.pdf
- A short movie clip for model training: DLI_project_model_training_clip.mp4
- The jupyter notebook file (clock_reader_interactive.ipynb) has been tested with Jetson SD card image (built with JetPack 4.6.1) on Jetson board
