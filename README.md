## Denoising Low-Light Video with Deep Learning

This project leverages an overcomplete autoencoder to restore and enhance videos filmed in low-light environments. By tackling the prevalent issue of image noise, we improve visual clarity and prepare the video for downstream tasks.

Our method operates on a frame-by-frame basis:

Extract: The low-light video is broken down into individual frames.

Denoise: Each frame is passed through a powerful overcomplete autoencoder, which has been trained to separate noise from image content.

Reconstruct: The cleaned frames are reassembled to produce a final, denoised video.

The model's key strength lies in its architecture, which uses a higher-dimensional hidden layer and skip connections to learn detailed features and reconstruct images with high fidelity.
