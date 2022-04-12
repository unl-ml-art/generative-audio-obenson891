# Project 2 Generative Audio

Olivia Benson obenson2@huskers.unl.edu 


## Abstract

My roommate, Elizabeth, has been working on a musical album. However, said album has been kept top secret. She will not let me listen to anything from this album or even know any of the lyrics. All I know about it is the title and the names of the songs. It has been in the works for a long time now and my curiosity has grown.

For this project, I wanted to create a voice clone of Elizabeth combined with generative music to sample what this album could sound like. 

To achieve this, I took the existing song titles and asked GPT-3 to write short lyrics to accompany the title. I then took those lyrics and combined them with a recording of Elizabeth speaking to create a clone of her voice speaking those lyrics. I used Performance RNN to create random short piano accompaniments for each piece and edited it all together in Adobe Premiere with the album cover. 

## Model/Data

Included in this repo:
- Voice clone training jupiter file
- Final edited video showcasing the instrumentals combined with the voice clone
- All the generated instrumental songs
- All the voice clone text to speech files
- PDF of the results/inputs used to create lyrics in GPT-3
- Performance RNN file used to create instrumentals
- Cover photo for the album "Greatest Hits" created by Elizabeth 

## Code

- CoLab: Performance_RNN.ipynb
- Jupyter notebooks: YourTTS_zeroshot_TTS_demo.ipynb

## Results

Video output, editing together the generated instrumentals with their "singing" counterparts.
- Generative Audio.mp4

## Technical Notes

Requires:
- Jupiter Notebook
- CoLab
- Adobe Premire
- OpenAi GPT-3

## Reference


