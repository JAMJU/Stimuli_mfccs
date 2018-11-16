# Stimuli_mfccs
#### Description of the files
They have the same name as the original .wav files. I extracted MFCCs from the original files using the librosa function with the following parameters:
y=waveform, sr=fs, S=None, n_mfcc=13, fmin = 0, fmax = 8000

#### How to load the files
They are numpy arrays in .csv files with dimensions (nb_mfccs x time), to load them do: numpy.loadtxt($name of file$, delimiter=',')
