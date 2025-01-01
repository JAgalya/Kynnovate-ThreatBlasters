# Kynnovate-ThreatBlasters
# Multi-Modal Sentiment Analysis

This project performs sentiment analysis using multiple modalities: text, audio, and visual inputs. It combines state-of-the-art Natural Language Processing (NLP), speech recognition, and facial emotion detection to analyze the sentiment from different sources.

The goal is to provide a unified approach to sentiment analysis that can process text, speech, and images, making it highly applicable for diverse applications such as customer feedback, social media analysis, and mental health monitoring.

What the Project Does

The Multi-Modal Sentiment Analysis project integrates multiple modalities to perform sentiment analysis. It processes:
- Text: Analyzes the sentiment of textual input using NLP techniques.
- Audio: Converts speech from audio files to text and analyzes the sentiment.
- Visual: Analyzes emotions from images by detecting facial expressions.

By combining these different sources of input, the project provides a comprehensive view of sentiment, offering more accurate and nuanced insights than traditional sentiment analysis methods that rely on a single input source.

Why the Project is Useful

This project is useful because it allows users to analyze sentiment across multiple communication channels—text, speech, and images. It is ideal for applications such as:
- Customer feedback analysis: Understanding customer satisfaction from various feedback sources.
- Social media sentiment tracking: Analyzing sentiments from text, speech, and images across platforms.
- Mental health monitoring: Detecting emotional states through speech and facial expression analysis.

With the increasing amount of multi-modal data, this project can improve the understanding of sentiment, providing more comprehensive insights.

How Users Can Get Started with the Project

To get started, follow these steps:

  1.Install the required dependencies:

  2.bash
   pip install -r requirements.txt

  3.Prepare input files:

Text input: A string of text you want to analyze.
Audio input: A path to an audio file (e.g., .wav or .mp3).
Image input: A path to an image file (e.g., .jpg or .png).

Run script:
# Example input
text_input = "I love this product! It's amazing."
audio_input = "path_to_audio_file.wav"  # Replace with the actual audio file path
image_input = "path_to_image.jpg"  # Replace with the actual image path

# Call the multi-modal sentiment analysis function
combined_results = multi_modal_sentiment_analysis(text_input, audio_input, image_input)

# Print results
print("Combined Sentiment Results:")
print(combined_results)

python multi_modal_sentiment_analysis.py

4.Output:
{
    'text_sentiment': [{'label': 'POSITIVE', 'score': 0.9999}],
    
    'audio_transcription': 'I love this product, it is amazing.',
    
    'audio_sentiment': [{'label': 'POSITIVE', 'score': 0.998}],

    'face_emotion': 'happy',
    
    'face_score': 0.85
}

This project is maintained by Agalya and the team member of Threat Blasters.


