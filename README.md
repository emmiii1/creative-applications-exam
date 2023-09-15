# creative-applications-exam

# This code produces a random quote using the quotable API (https://docs.quotable.io/docs/api/ZG9jOjQ2NDA2-introduction) and turns it into RGB values, which are used for creating an image.
# The code for image generation is based off of this example using matplotlib: https://shamsfiroz.medium.com/creating-generative-art-with-numpy-737a9af8ffda

# It uses the notebook format, so that new images can be generated without running the entire code again. I mostly used Google Colab, but it works in Jupyter notebooks as well.

# You might need to install the required libraries using the following command:
pip install numpy
pip install matplotlib

# If you want to create an image based off of a custom text instead of a random quote, change this line and put in your text instead:
text = get_quote()
