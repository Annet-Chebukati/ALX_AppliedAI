# Human Image Animation with Diffusion Models

## Introduction
Welcome to my journey of bringing imagination to life with human image animation. This cutting-edge technology allows us to create realistic and expressive characters in motion, transforming the realm of traditional animation studios. Now, anyone with a creative spark can tell their stories and share their vision with the world, regardless of technical expertise.

## Diffusion Models
At the heart of this revolution lies a powerful tool called a diffusion model. This sophisticated AI algorithm is like a magic paintbrush, capable of transforming simple noise into stunning visuals. Understanding the flow of information can gradually add details and shapes, ultimately breathing life into still images.

## Human Image Animation
Human image animation encompasses various techniques to create the illusion of movement in human figures. These techniques range from traditional frame-by-frame animation to more recent advancements like deep learning and artificial intelligence.

## Diffusion Models for Human Image Animation
Diffusion models have the potential to revolutionize human image animation by making it faster, easier, and more accessible. By providing the model with a reference image and a motion sequence, it can generate realistic animations of characters moving in the desired way.

## MagicAnimate
This groundbreaking research paper, titled "MagicAnimate: Temporally Consistent Human Image Animation using Diffusion Model", by the National University of Singapore and Bytedance, published in 2023, introduced [MagicAnimate](https://www.magicanimate.org/?ref=alxappliedai.com), a diffusion-based model capable of generating temporally consistent and highly realistic animations of human figures. It tackles the crucial challenge of temporal consistency, ensuring smooth and natural motion across animation sequences.

## Project Steps
1. **Setting the Stage**: We need a reference image and a motion sequence. The motion sequence will guide the movement of the character on the reference image when generating the animation.
2. **Generate Motion Sequence with vid2densepos**: Use [vid2densepos](https://github.com/Flode-Labs/vid2densepose?ref=alxappliedai.com) to generate your motion sequence. You can drag and drop your video into the file explorer of your Colab runtime. You can name your file anything but if it is not "input_video.mp4" make sure to change the INPUT_VIDEO_PATH. Click on the play button to install the required libraries and convert the input file into a Densepose file. This file will appear on the file explorer. Once you have done these steps, you can download your output motion sequence Densepose file. We will use this file later.
3. **Running the Magic**: MagicAnimate on Google Colab processes your files faster as you will be using your runtime. However, make sure you are using a very short motion sequence Densepose file (around 5 sec maximum). Once finished, you can access the MagicAnimate web app using the link provided.
4. **Generating the Magic**: Upload the following required files:
    - **Reference Image**: I'll be using an AI-generated image of a person, but you can use any image of your choice. For better results, please use a square image. You can generate such an image for free using several services such as [Bing Image Creator](https://www.bing.com/images/create?FORM=GDPGLP&ref=alxappliedai.com).
    - **Motion Sequence**: Here, you can go ahead and upload your previously generated motion sequence file or you can choose from the already provided example motion sequence files in the web app. If you are using your motion sequence file, I recommend making it with a square aspect ratio. You can use free tools to crop it before or after processing.
    Once you have uploaded the two files, click on "Animate" and wait for the magic to happen!

## Output Video
![Human Image Animation](https://github.com/Annet-Chebukati/ALX_AppliedAI/blob/master/Human_Image_Animation/Human_Image_Animation.png)

You can watch the output video of the project [here](https://youtu.be/w8b87GyMjWE).
