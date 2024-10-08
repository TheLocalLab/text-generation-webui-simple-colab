# Simple Colab Text Generation Web UI Notebook

A Gradio web UI for Large Language Models that can be run for free or paid on Google Colab.

[The Local Lab Twitter](https://twitter.com/TheLocalLab_)

[Original Ooba Booga Text-Generation-WebUI Repo](https://github.com/oobabooga/text-generation-webui)

Simple Colab Notebook Link - [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Koz9mSsYp_hbp2jM_u2wl2clOqxYfyX1?usp=sharing)





|                                           ***Youtube Tutorial Link***                                              |   
| :------------------------------------------------------------------------------------------------------: | 
| [![Watch the video](https://img.youtube.com/vi/NNK6Kj_unOw/sddefault.jpg)](https://youtu.be/NNK6Kj_unOw) |

# Visuals

|![Image1](https://raw.githubusercontent.com/TheLocalLab/text-generation-webui-simple-colab/main/updatedcolab1.png) | ![Image2](https://raw.githubusercontent.com/TheLocalLab/text-generation-webui-simple-colab/main/updatedcolab2.png) |
|:---:|:---:|
|![Image1](https://raw.githubusercontent.com/TheLocalLab/text-generation-webui-simple-colab/main/updatedcolab.png) | ![Image2](https://raw.githubusercontent.com/TheLocalLab/text-generation-webui-simple-colab/main/SimpleColab3.png) |


This project provides a simple and convenient way to run the Ooba Booga WebUI for text generation right here on Google Colab! With just a few lines of code, you can set up and use the Ooba Booga text-generation-webui without modifying any program files.

# Project Description
The Ooba Booga text-generation-webui is a powerful tool that allows you to generate text using large language models such as transformers, GPTQ, llama.cpp (ggml/gguf), and Llama models. This project aims to provide step-by-step instructions on how to run the web UI in Google Colab, leveraging the benefits of the Colab environment.

# Getting Started
To get started with the Ooba Booga text-generation-webui, first open up a blank colab notebook, copy and paste each line below to its own unique cell and run each line in the same order as shown below:

1. Clone the text-generation-webui Git repository by running the following command:

```
!git clone https://github.com/oobabooga/text-generation-webui.git
```

2. Import the Python os module and change the current working directory to the text-generation-webui directory:
```
import os
os.chdir("./text-generation-webui")
```


3. Run the start_linux.sh module to start the web UI server:
```
!./start_linux.sh --share --verbose
```
Once the server is running, you will see a sharable Gradio link. Click on the link to open the text-generation interface and start generating text with various models. Have fun exploring the capabilities of the Ooba Booga text-generation-webui!

# Benefits of Running in Google Colab
Running the Ooba Booga text-generation-webui in Google Colab offers several benefits:

- Free GPU Resources: Google Colab provides free GPU resources, which are essential for running large language models. These resources can handle models up to 13B and 7B in size.

- Ease of Use: With the provided instructions, setting up and running the web UI in Google Colab is straightforward and requires minimal configuration.

- Shareability: The Gradio link generated by the web UI allows you to access the WebUI from anywhere.

# Upgrade to Google Colab Pro
If you require more GPU resources or want to run even larger models, you have the option to upgrade to Google Colab Pro. Colab Pro provides additional GPU resources, which can further enhance the performance and capacity of your text generation tasks.

# Compatibility
This project allows you to download and run any model compatible with the original Ooba Booga text-generation-webui. The instructions provided here will help you set up the web UI in Google Colab and unleash the power of text generation with a wide range of models.

# Disclaimer
Please note that this project is not affiliated with or endorsed by the original creators of the Ooba Booga text-generation-webui. The instructions provided here are for educational and convenience purposes only. Make sure to comply with any licensing and usage terms associated with the text-generation-webui and the models you use.

For more information and updates, you can visit my Twitter profile: @TheLocalLab_


Feel free to reach out to me if you have any questions or need assistance with the project. Enjoy generating text with the Ooba Booga text-generation-webui in Google Colab!
