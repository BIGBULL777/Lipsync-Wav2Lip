# Lipsync-Wav2Lip

This repository contains code for the Lipsync-Wav2Lip project.

## Description

The Lipsync-Wav2Lip project aims to synchronize lip movements in videos with a given input speech signal, using pretrained model Wave2Lip from https://github.com/Rudrabha/Wav2Lip. 

## Computation Issues

Due to computation issues, the video length in this project has been reduced to 30 seconds. Please note that the provided code and resources are optimized for processing videos of this duration.

## Usage

To run the Lipsync-Wav2Lip project, follow these steps:

1. Prepare your input video and speech data.
2. The input video must be less than 30 sec inorder to be able generate output without colab pro, the results are better if we use the muted version of input video.

4. Similarly it's better to have a audio file with same length.

5. Execute the code provided in the `LipSync.ipynb` notebook.

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or improvements, please feel free to submit a pull request or open an issue.

#Output
The generated video with lipsync can be found on the master branch of the same git repository.
