# Low-Light-Image-Restoration
This project was the part of competition Low-prep Challenge in Inter Bhawan Tech Meet, for which my team won the gold medal. The problem was that we had to develop a generalized model that can convert low-light images to high-quality, well-lit images, thus improving the quality of images taken in dim light.

For this first, we looked for the diferent approaches available like histogram equalization, contrast stretching and gamma correction and state-of-art models available. However most of the available models had problem of high inference time and were for medical purposes not for general purpose. 

To tackle this, we employed transfer learning by using the weights of LLFlow model and finetuned it on the custom dataset created by adding noise to VE-LOL dataset and trained the model for 6 epoches. 

Lastly, we applied gamma correction, which further improved the results and we got PSNR of 26.92.
