# Face-Generator-WebApp
Face Generator WebApp using Generative Adversarial Networks (GANS) Pre-trained models were used: PG-GAN and TL-GAN.

This project highlights Streamlit's new st.experimental_memo() and st.experimental_singleton() features with an app that calls on TensorFlow to generate photorealistic faces, using Nvidia's Progressive Growing of GANs and Shaobo Guan's Transparent Latent-space GAN method for tuning the output face's characteristics. For more information, check out the tutorial on Towards Data Science.

The Streamlit app is implemented in only 150 lines of Python and demonstrates the wide new range of objects that can be used safely and efficiently in Streamlit apps.



## How to run this demo
The demo requires Python 3.6 or 3.7 (the version of TensorFlow we use is not supported in Python 3.8+). We suggest creating a new virtual environment, then running:

      git clone https://github.com/streamlit/demo-face-gan.git
      cd demo-face-gan
      poetry install
      poetry run streamlit run streamlit_app.py

      
## Model Bias
Playing with the sliders, you will find biases that exist in this model. For example, moving the Smiling slider can turn a face from masculine to feminine or from lighter skin to darker. Apps like these that allow you to visually inspect model inputs help you find these biases so you can address them in your model before it's put into production.
