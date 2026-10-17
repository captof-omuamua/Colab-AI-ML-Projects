# Speech

| Notebook | What it covers | Stage |
| --- | --- | --- |
| [22_tamil_whisper_finetuning.ipynb](22_tamil_whisper_finetuning.ipynb) | Prepare paired audio/transcripts and fine-tune a Tamil Whisper model with a WER metric. | Project experiment |
| [25_hindi_xlsr_ctc_finetuning.ipynb](25_hindi_xlsr_ctc_finetuning.ipynb) | Common Voice Hindi preparation, character vocabulary, XLS-R/Wav2Vec2 CTC training and WER. | Project experiment |
| [26_malayalam_whisper_finetuning.ipynb](26_malayalam_whisper_finetuning.ipynb) | Common Voice Malayalam preparation, Whisper training and transcription experiments. | Project experiment |
| [31_tamil_speaker_attribute_classification.ipynb](31_tamil_speaker_attribute_classification.ipynb) | Tamil speech features using MFCCs, chromagrams and mel spectra, with classifier comparisons. | Project experiment |
| [36_tamil_audio_feature_exploration.ipynb](36_tamil_audio_feature_exploration.ipynb) | Audio exploration and feature matrices for Tamil speech classification. | Earlier experiment |
| [39_speech_waveform_and_spectrum_analysis.ipynb](39_speech_waveform_and_spectrum_analysis.ipynb) | Waveform, spectral and time-frequency analysis of a supplied speech recording. | Learning experiment |
| [40_speech_spectrogram_visualization.ipynb](40_speech_spectrogram_visualization.ipynb) | Librosa waveform and spectrogram plots for an audio sample. | Learning experiment |
| [45_discrete_fourier_transform.ipynb](45_discrete_fourier_transform.ipynb) | Explicit DFT implementation and short-time analysis of supplied audio. | Learning experiment |
| [48_speech_and_egg_channel_analysis.ipynb](48_speech_and_egg_channel_analysis.ipynb) | Separate and inspect speech and electroglottographic channels in a supplied recording. | Prototype |

## Running these notebooks

Librosa, NumPy and Matplotlib for audio features; Datasets, Transformers, PyTorch and Evaluate for ASR; scikit-learn/TensorFlow for classification. Supply the referenced audio/transcripts or obtain the dataset through your own account.

Open one notebook in Colab or Jupyter, read its setup cells, set the input paths, and then run the sections you need. Training and network operations are not run automatically by this repository.
