# MonReader

This repository combines many notebooks encompassing computer vision problems to generating audio from extracted text.

The order of notebooks is as followed:
    * submodule 'vcrr...' which experiments with convolutional neural networks (CNN's)
    * text_extraction.ipynb looks at early models that extracts text from images
    * sesame_audio.ipynb looks at one of the latest text-to-speech (TTS) models that will be used for fine-tuning purposes later on
    * dia_audio.ipynb experiments with another latest TTS mode that was used for generating a synthetic dataset that was used for the fine-tuning process
    * Sesame_Fine_Tune.ipynb ran the fine-tuning of Sesame's CSM
    * submodule 'imagespeaker' that houses the end application

The final product was an application that is able to extract text from an uploaded image and then uses the fine-tuned Sesame model to generate human like audio from that text.