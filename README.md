# Sphinx2023_hackathon
# Models
# <Strong>1.Genre prediction Model<br>
we trained our model on a <a href="https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification">Dataset</a> from kaggle.
We are preforming preprocessing and resampling using torchaudio before converting the dataset to a Huggingface transformers Dataset format.<br>
Further we are vectorising the data using the Meta’s <a href="https://huggingface.co/facebook/wav2vec2-base-960h">wav2vec2-base-960h</a> to extract features from the data
<b>Test-train split = 80:20<br>
Our model classifies the audio input into 10 classes<br>
-blues<br>
-classical<br>
-country<br>
-disco<br>
-hip-hop<br>
-jazz<br>
-metal<br>
-pop<br>
-reggae<br>
-rock<br>
<strong>Model metrics : <br>
<img width="790" alt="Screenshot 2023-11-05 at 10 24 37 AM" src="https://github.com/JayDeep1710/Sphinx2023_hackathon/assets/95349616/6de4cad2-265a-4edc-8bf0-eaaa301eb80b">

