# Ion-Switching

Many diseases, including cancer, are believed to have a contributing factor in common. Ion channels are pore-forming proteins present in animals and plants. They encode learning and memory, help fight infections, enable pain signals, and stimulate muscle contraction. If scientists 
could better study ion channels, which may be possible with the aid of machine learning, it could have a far-reaching impact. 

When ion channels open, they pass electric currents. Existing methods of detecting these state changes are slow and laborious. Humans must supervise the analysis, which imparts considerable bias, in addition to being tedious. 
These difficulties limit the volume of ion channel current analysis that can be used in research. Scientists hope that technology could enable rapid automatic detection of ion channel current events in raw data.

The University of Liverpool’s Institute of Ageing and Chronic Disease is working to advance ion channel research. Their team of scientists have asked for your help. In this competition, you’ll use ion channel data to better model automatic identification methods. 
If successful, you’ll be able to detect individual ion channel events in noisy raw signals. The data is simulated and injected with real world noise to emulate what scientists observe in laboratory experiments.

Technology to analyze electrical data in cells has not changed significantly over the past 20 years. If we better understand ion channel activity, the research could impact many areas related to cell health and migration. 
From human diseases to how climate change affects plants, faster detection of ion channels could greatly accelerate solutions to major world problems.


## Data

In this competition, you will be predicting the number of open_channels present, based on electrophysiological signal data.

IMPORTANT: While the time series appears continuous, the data is from discrete batches of 50 seconds long 10 kHz samples (500,000 rows per batch).
In other words, the data from 0.0001 - 50.0000 is a different batch than 50.0001 - 100.0000, and thus discontinuous between 50.0000 and 50.0001.

You can find detailed information about the data from the paper Deep-Channel uses deep neural networks to detect single-molecule events from patch-clamp data.

### Files

 * train.csv - the training set
 * test.csv - the test set; you will be predicting open_channels from the signal data in this file
 * sample_submission.csv - a sample submission file in the correct format
 
 
 You can find detailed information from [here](<https://www.kaggle.com/c/liverpool-ion-switching/overview>)
