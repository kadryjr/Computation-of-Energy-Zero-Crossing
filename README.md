# Computation-of-Energy-Zero-Crossing
--------------------------------------
# Program Requirements:
Required is a program that divides any input speech signal into frames and computes for each frame its corresponding energy and zero crossing values.

# Inputs: 
1.	Audio File Path
2.	Frame size in seconds
3.	Overlap size in seconds
4.	Window type to be used

# Outputs:
1.	Vector containing the energy value for each frame. The vector’s length should be equal to the number of frames.
2.	Vector containing the zero crossing value for each frame. The vector’s length should be equal to the number of frames.
3.	A single diagram containing 3 plots:
a.	A plot of the framed signal. You can not plot the frames matrix since matrices are 2D and the plot function is used to plot 1D signals. Hence, to make the plot possible, the frames matrix should be used to fill a new vector which will be plotted. The new vector is constructed by concatenating consecutive frames.
b.	A plot of the energy vector.
c.	A plot of the zero crossing vector


