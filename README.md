## ✔ PyVolSuggester Package
- A Python package to provide suggestion on volume at which the music audio file needs to be played for better experience and feeling.
- In backend, it extracts various generic features for particular audio and analyze among them and provide feedback on volumne on it.  
- This tools helps in maintaining goob vibes along the music playout.

<p align = "center">
	<img src = "https://img.shields.io/badge/Pypi Package-PyVolSuggester-green?style=plastic&logo=appveyor", alt = "PyVolSuggester">
	<img src = "https://img.shields.io/badge/PyPi-Python Package Index-green?style=plastic&logo=appveyor", alt = "PyPi">
</p>
<p align = "center">
	<img src = "https://img.shields.io/github/stars/akash-rajak/PyVolSuggester?style=social", alt = "GitHub Repo stars">
	<img src = "https://img.shields.io/github/forks/akash-rajak/PyVolSuggester?style=social", alt = "GitHub Repo forks">
	<img src = "https://img.shields.io/github/watchers/akash-rajak/PyVolSuggester?style=social", alt = "GitHub Repo watchers">
	<img src = "https://img.shields.io/github/contributors/akash-rajak/PyVolSuggester?style=social", alt = "GitHub contributors">
</p>
<p align = "center">
	<img src = "https://img.shields.io/github/languages/count/akash-rajak/PyVolSuggester?style=social", alt = "GitHub language count">
	<img src = "https://img.shields.io/github/languages/top/akash-rajak/PyVolSuggester?style=social", alt = "GitHub top language">
	<img src = "https://img.shields.io/github/directory-file-count/akash-rajak/PyVolSuggester?style=social", alt = "GitHub repo file count">
	<img src = "https://img.shields.io/github/repo-size/akash-rajak/PyVolSuggester?style=social", alt = "GitHub repo size">
</p>
<p align = "center">
	<img src = "https://img.shields.io/github/issues/akash-rajak/PyVolSuggester", alt = "GitHub issues">
	<img src = "https://img.shields.io/github/issues-closed/akash-rajak/PyVolSuggester", alt = "GitHub closed issues">
	<img src = "https://img.shields.io/github/issues-pr/akash-rajak/PyVolSuggester", alt = "GitHub pull requests">
	<img src = "https://img.shields.io/github/issues-pr-closed/akash-rajak/PyVolSuggester", alt = "GitHub closed pull requests">
</p>
<p align = "center">
	<img src = "https://img.shields.io/github/commit-activity/t/akash-rajak/PyVolSuggester", alt = "GitHub commit activity">
	<img src = "https://img.shields.io/github/commit-activity/y/akash-rajak/PyVolSuggester", alt = "GitHub commit activity/year">
	<img src = "https://img.shields.io/github/commit-activity/m/akash-rajak/PyVolSuggester", alt = "GitHub commit activity/month">
	<img src = "https://img.shields.io/github/commit-activity/w/akash-rajak/PyVolSuggester", alt = "GitHub commit activity/week">
	<img src = "https://img.shields.io/github/last-commit/akash-rajak/PyVolSuggester", alt = "GitHub last commit">
	<img src = "https://img.shields.io/github/discussions/akash-rajak/PyVolSuggester", alt = "GitHub Discussions">
</p>
<p align = "center">
	<img src = "https://img.shields.io/pypi/dd/PyVolSuggester", alt = "PyPI - Downloads per day">
	<img src = "https://img.shields.io/pypi/dw/PyVolSuggester", alt = "PyPI - Downloads per week">
	<img src = "https://img.shields.io/pypi/dm/PyVolSuggester", alt = "PyPI - Downloads per month">
</p>
<p align = "center">
	<img src = "https://img.shields.io/pypi/v/PyVolSuggester", alt = "PyPI Version">
	<img src = "https://img.shields.io/pypi/implementation/PyVolSuggester", alt = "PyPI - Implementation">
	<img src = "https://img.shields.io/pypi/pyversions/PyVolSuggester", alt = "PyPI - Python Version">
	<img src = "https://img.shields.io/pypi/format/PyVolSuggester", alt = "PyPI - Format">
	<img src = "https://img.shields.io/pypi/status/PyVolSuggester", alt = "PyPI - Status">
</p>
<p align = "center">
	<img src = "https://img.shields.io/github/downloads/akash-rajak/PyVolSuggester/total", alt = "GitHub all releases">
	<img src = "https://img.shields.io/github/v/release/akash-rajak/PyVolSuggester", alt = "GitHub release version (latest by date)">
	<img src = "https://img.shields.io/github/v/tag/akash-rajak/PyVolSuggester", alt = "GitHub tag (latest by date)">
	<img src = "https://img.shields.io/github/release-date/akash-rajak/PyVolSuggester", alt = "GitHub Release Date">
	<img src = "https://img.shields.io/github/release-date-pre/akash-rajak/PyVolSuggester", alt = "GitHub (Pre-)Release Date">
</p>
<p align = "center">
	<img src = "https://img.shields.io/github/license/akash-rajak/PyVolSuggester", alt = "Github">
</p>

![image](https://github.com/akash-rajak/Volume-Suggester/assets/57003737/1d332d56-b26a-4ba6-8b72-46efca4f1deb)

****

### 📌How this Script works :
- First user need to download the script and run Volume Suggester.py in the local system.
- After running it, user will be prompted to select an audio file(mp3 file) using dialog box.
- Once user has selected the audio file, following feature extraction and analysis graph will be generated at the backend.
	- Generic Audio Features:
		- `Channels` : (number of channels; 1 for mono, 2 for stereo audio)
		- `Sample Width` : (number of bytes per sample; 1 means 8-bit, 2 means 16-bit)
		- `Frame Rate / Sample Rate` : (frequency of samples used (in Hertz))
		- `Frame Width` : (Number of bytes for each “frame”. One frame contains a sample for each channel.)
		- `Audio Length / Duration` : (audio file length (in milliseconds))
		- `Frame Count` : (the number of frames from the sample)
		- `Intensity` : (loudness in dBFS (dB relative to the maximum possible loudness))
	- Plot on `Amplitude over Time` Analysis
	- Following Derived Audio Features:
		- `Spectogram`
		- `RMS/Energy Spectogram`
		- `Zero Crossing Rate`
		- `Mel Frequency Cepstral Coefficients`
		- `Mel Frequency Spectogram`
		- `Chroma Feature`
		- `Tempogram`
- After these feature extraction is done, user will be able to Play/Pause(using CTRL button) and Stop(using ESC button) the selected song.
	
****

### 📌Input/Output Deliverables:
```
- Input: 
    - Single Audio File (.mp3)

- Output:
    - Output Folder consisting of different feature extraction
```

****

### 📌Features:
- Implemented following features in the package:
    1. Generic Audio Features:
        - `Channels` : (number of channels; 1 for mono, 2 for stereo audio)
		- `Sample Width` : (number of bytes per sample; 1 means 8-bit, 2 means 16-bit)
		- `Frame Rate / Sample Rate` : (frequency of samples used (in Hertz))
		- `Frame Width` : (Number of bytes for each “frame”. One frame contains a sample for each channel.)
		- `Audio Length / Duration` : (audio file length (in milliseconds))
		- `Frame Count` : (the number of frames from the sample)
		- `Intensity` : (loudness in dBFS (dB relative to the maximum possible loudness))

    2. Derived Audio Features:
		- `Amplitude over Time`
        - `Spectogram`
		- `RMS/Energy Spectogram`
		- `Zero Crossing Rate`
		- `Mel Frequency Cepstral Coefficients`
		- `Mel Frequency Spectogram`
		- `Chroma Feature`
		- `Tempogram`

    3. Player for playing selected audio file
	
	4. Suggestion on volume on the basis of various feature extraction.

****

### 📌Prerequisites:
- In order to use this package, one need to ensure the following requirements:
    - Python 3.7 or later installed on your machine.

****

### 📌Package Usage
```
- from PyVolSuggester import Suggester
    - This command will install all the uninstalled required libraries used in script.
- Suggester.main()
    - This will prompt user for input of audio file selection.
- Suggester.extract()
	- This will extract the generic features of the selected audio file.
- Suggester.play_pause_stop()
	- This will allow user to play, plause and stop the audio file.
- Suggester.amplitude_wave()
	- This will generate a amplitude over time plot and save it as an image to output directory.
- Suggester.spectogram()
	- This will generate a spectogram plot and save it as an image to output directory.
- Suggester.rms_energy_spectogram()
	- This will generate a RMS/Energy Spectogram plot and save it as an image to output directory.
- Suggester.zero_crossing_rate()
	- This will generate a Zero Crossing Rate plot and save it as an image to output directory.
- Suggester.mel_frequency_cepstral_coefficients()
	- This will generate a Mel Frequency Cepstral Coefficients plot and save it as an image to output directory.
- Suggester.mel_frequency_spectogram()
	- This will generate a Mel Frequency Spectogram plot and save it as an image to output directory.
- Suggester.chroma_feature()
	- This will generate a Chroma Feature plot and save it as an image to output directory.
- Suggester.tempogram()
	- This will generate a tempogram plot and save it as an image to output directory.
- Suggester.suggest_volume()
	- This will suggest user the most feasible volume for that particular audio.

```

****

### 📌Package Installation
```bash
pip install PyVolSuggester
```

****


### 🌟Stargazers Over Time:
[![Stargazers over time](https://starchart.cc/akash-rajak/PyVolSuggester.svg)](https://starchart.cc/akash-rajak/PyVolSuggester)

****

### 📌Contributors:
<a href="https://github.com/akash-rajak/PyVolSuggester/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=akash-rajak/PyVolSuggester" />
</a>
