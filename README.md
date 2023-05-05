# Denoise-Human-Voice
This project aims to remove unwanted noise from human voice using a technique called band-limited noise. The idea behind this technique is to add a specific type of noise to the audio signal that we want to denoise. By doing so, we can create a training data set that can be used to train a machine learning model to distinguish between the noise and the actual audio signal.

The project uses Python and some popular libraries such as NumPy, SciPy, and Librosa. The main steps involved in the project include generating band-limited noise, adding the noise to the audio signal, reducing noise using the Noise Reduction (NR) technique, and finally normalizing the audio signals to the range from -1 to 1.
