# write-this-like-a-tv-character

### Overview
This dataset created for the paper "Your Task is to Write this Title Like a TV Character".
The original source of the data is TVR ([Lei et al., 2020](
https://tvr.cs.unc.edu/))

The dataset contains lines from scripted utterances of characters from six TV shows, taken from TVR.
We added for each line three additional attributes:
1) 'style_prob': a number between 0 and 1 indicating the degree to which style is present in each line.
2) 'neutral_line': a "destylized" version of the line.
3) 'content': a "destylized" description of the content of the line.

We provide three files:

- all_data.csv - all of the lines we augmented with 'style_prob', 'nuetral_line', and 'content'.
- fine_tuning_data.csv - the data we used for fine tuning.
- golden_test.csv - the data we used for test.

The full procedure of adding the additional attributes, splitting the data, and creating the golden test are described in the paper.