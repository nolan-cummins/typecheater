# typecheater
Python script to cheat in Typeracer ([https://play.typeracer.com/](url)).

# how-to
In order to run this script, you need the following dependencies:
- google-cloud-vision
- numpy
- selenium

Make sure Firefox is also installed.

Typeracer has a built-in anti-cheat that this script circumvents in two ways:
1. Calculates a delay between each word based on the length of the word to introduce "randomness."
2. Uses the Google Vision API to complete an anti-bot image test.

In order to use Google Vision, you need to create a Google Cloud account and generate an API credentials .json file. See: [https://codelabs.developers.google.com/codelabs/cloud-vision-api-python#0](url). 
There are instructions in the Jupyter notebook on how to adjust the script accordingly.
