🎸🎶 Musical genre classification using Convolutional Neural Networks 🎸🎶

Both of us being huge fans of music, choosing this problem was a natural thing. There are many research papers and articles out there regarding this subject, but most of these approaches try to solve the problem with simple feed-forward neural network with metadata extract from the music, like zero-crossing-rate, tempo, spectral centroid and such. We thought running the spectrograms of music through a convolutional neural network might yield more accurate results (and would be a quite exciting experiment to do 😁)

💾 The Dataset 💾

The dataset we found to be the most promising (to say so) is the GTZAN Genre Collection dataset. This dataset was used in numerous research papers, such as [Musical genre classification of audio signals](https://ieeexplore.ieee.org/document/1021072) by G. Tzanetakis and P. Cook.

The dataset consists of 10 genres, each consisting of 100 samples with a length of 30 seconds. The genres are the following:

    'reggae' 🌈
    'country' 🤠
    'metal' 🤘
    'classical' 🎻
    'jazz' 🎺
    'rock' 🎸
    'hiphop' 💿
    'disco' 🕺
    'pop' 🍿
    'blues' 🎸

The most notable drawback of this dataset is that it is quite old (year 2001), therefore a model trained using this might not adapt correctly to let's say the pop music of the 2010's, but... yeah, we'll see. ( ͡° ͜ʖ ͡°)


To setup and run the sample learning, just do the following steps in order:

1. Make a copy of this folder in your drive: [GTZAN](https://drive.google.com/open?id=1qj1dsctHEFp3y37ZHwcNNkxskHlCHOUF).  
Make sure to save the datset into the **root** folder!
2. Run the "Step 1" in the Juniper notebook and follow the instructions to mount the dataset.
3. Once the dataset is mounted, just continue running the Juniper notebook command cells.

Every step has a short description and comments for better understanding and visibility.
The downloading of the sample songs might take some time due to their great number.
If needed, the number of songs used in the learning process can easily be changed. 


The learning process takes some time, due to the great number of training sample.