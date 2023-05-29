# Stable Diffusion custom workflow for rendering video


Developed a simple python script that leverages stable diffusion models to enhance video quality by post rendering a stylized frame. I discovered that by using Stable diffusion models and simple shadering I can improve rendering and post styling. This might be something that is getting interesting lately. By using gradio and stable diffusion 1.5 I rendered some stylized images.

Afterwards, i thought about integrating frame interpolation into the workflow and to add custom color correction to prevent flickering. By automatically inserting these extra frames, I achieved smoother and more natural motion in the videos plus keeping better overall structural stability.

The results are not incredible but promising.

