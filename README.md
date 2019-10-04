# Objective

The purpose of this project is to remove the drum tracks from a song using Machine Learning techniques. This is specially useful for drummers trying to create their drum covers.

As of now, most of the existing techniques hurt the quality of audio. So, a better technique is needed. 

# Plan

+ Gather the drum sounds (D) and drumless audios (A)

+ Combine each drum with each of the audio to create the input dataset (O)

+ The labels will be the actual drumless audio (i.e. A)

So, 

	X = Mix_Tracks (D , A)
	y = A

If we train our model M, the model should be able to give us the desired result i.e.
	
	drumless = M(song_with_drum)


# Source of Data

1. https://magenta.tensorflow.org/datasets/groove

Please contribute more datasources and ideas. The project is just started. We are looking for contributors to this project.

