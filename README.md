Repository overview English-to-French Subtitle Translator (FIXED)

This project lets you translate .srt video subtitle files from English to French using a simple Jupyter Notebook. It runs inside a Docker container, so you don’t need to worry about setting up any dependencies.

How to Use:

Pull the image: docker pull ayshaz/srt-translator Run the container: docker run -p 8888 (or your port):8888 ayshaz/srt-translator Open the notebook: Once the container starts, you’ll see a link in your terminal like this:

http://127.0.0.1:8888/?token=⁠⁠... Copy and paste it into your browser to access JupyterLab.

Now you can: Upload .srt subtitle files

Translate lines from English to French using Hugging Face’s translation_en_to_fr pipeline

View translated lines in the notebook

Save the new subtitles as a .srt file

Tools Used: Python, Jupyter,Hugging Face, Transformers,Docker

This is a small tool for anyone who works with subtitles and wants a quick way to translate them into French. Great for testing out basic NLP workflows too.
