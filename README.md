# generate-audio-scale
In the [Jupyter](https://jupyter.org/)-notebook ```create_wav_files.ipynb``` you can create audi-files in the wav-format for the following scales and the following temperatures.

Temperatures:
- arithmetic (i.e. subdivision of the octave into 13 tones according to an arithmetical sequence)
- geometric, also known as well-tempered (i.e. subdivision of the octave into 13 tones according to an geometric sequence)
- harmonic (i.e. subdivision of the octaveb into 13 tones according to a harmonic sequence)
- pythagorean (i.e. subdivision of the octaveb into 13 tones according to pure quints)

Scales:
- semitone
- major
- minor

# Installation and use
- Download and install [Python 3](https://www.python.org/downloads/release/python-376/)
- Clone the repo with ```git clone https://github.com/jlieberherr/generate-audio-scale.git```
- Create a [virtual environment](https://realpython.com/python-virtual-environments-a-primer/)
- Install the required Python modules with ```pip install -r requirements.txt```
- Start Jupyter-lab with ```jupyter lab```
- Within Jupyter-lab open the notebook ```create_wav_files.ipynb``` and run the cells with ```Ctrl-Shift```
- Download [Audacity](https://www.audacity.de/)
- Open Audacity, drag and drop the created wav-files to Audacity and listen to the different scales

In Audacity it should look like this:
![](doc/screenshot_audacity.PNG)

In the ```create_wav_files.ipynb``` you can see the underlying:
![](doc/screenshot_notebook.PNG)
