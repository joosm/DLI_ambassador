# DLI project: Clock Reader

![what_time_is_it](https://user-images.githubusercontent.com/3192324/185134059-e0fe20ed-ec36-47eb-93d5-946fd59c8208.png)

- Based on the Jetson Nano course material (classification model for thumbs-up/down)
- The original example from the course material has been modified to this project, "clock reader": given an image of analog clock face, the model reads the clock 
- Test setup: Jetson Xavier, Logitech C920 Webcam
- Two notebook scripts
 (i) clock_reader_interactive.ipynb: data collection/train/evaluate using live video stream from a webcam
 (ii) train_only.ipynb: train and visualization of train process, using collected data

![clock_reader](https://user-images.githubusercontent.com/3192324/192149994-68c34bb9-25d8-4319-a605-9343889c2299.png)

- Each time category (i.e. 1~12) has approx 50 images for training (in /data/clock_fingers_A folder)
- You can load and test an example model in the data folder
- The summary of test results can be found in the summary file: DLI_ambassador_project_description_R3.pdf
- The jupyter notebook file (clock_reader_interactive.ipynb) has been tested with Jetson SD card image (built with JetPack 4.6.1) on the Jetson board
- A short movie clip for model training: DLI_project_model_training_clip.mp4 (below)

https://user-images.githubusercontent.com/3192324/192693167-aba984c0-804c-4934-99f8-662a081baaf2.mp4

