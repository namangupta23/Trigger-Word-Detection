# Trigger-Word-Detection

This notebook is a programming exercise of the Deep Learning Specialization by Deeplearning.ai.  In this notebook, we will construct a speech dataset and implement an algorithm for trigger word detection (sometimes also called keyword detection, or wake word detection).

- Trigger word detection is the technology that allows devices like Amazon Alexa, Google Home and Apple Siri to wake up upon hearing a certain word.
- For this notebook, our trigger word will be &quot;Activate.&quot; Every time it hears us say &quot;activate,&quot; it will make a &quot;chiming&quot; sound.
- By the end of this assignment, we will be able to record a clip of ourselves talking, and have the algorithm trigger a chime when it detects you saying &quot;activate.&quot;

In this notebook we will learn to:

- Structure a speech recognition project
- Synthesize and process audio recordings to create train/dev datasets
- Train a trigger word detection model and make predictions
