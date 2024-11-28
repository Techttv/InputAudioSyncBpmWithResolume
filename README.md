# Free Tool for Syncinc in REAL TIME your input device audio BPM with Resolume Arena REAL TIME. 

Forked from https://github.com/zak-45/WLEDAudioSyncRTBeat and adjusted for Resolume.<br>
Sync your input audio bpm with Resolume Arena. The program detect it automatically and it sends it to the program.<br>
Make sure to select your input device under the preferencies in Resolume Arena and Windows. <br>
<br><br>

## Requirements:<br>

- Python installed and on the path<br>

## Usage: <br>
Download the .zip using the button above everywhere you want in your computer.<br>
![Techttv_WLEDAudioSyncRTBeatForResolume_ Real Time beat detection using aubio  Send BPM to OSC for Resolume  - Google Chrome 28_11_2024 16_59_38](https://github.com/user-attachments/assets/4e4149f4-ee95-4039-a13c-6f6f32b10849)<br>

Open ```Resolume Arena>Arena>Preferencies>OSC``` and enable OSC Input<br>
![Preferences 28_11_2024 16_43_29](https://github.com/user-attachments/assets/e72afb52-45d5-447b-86b5-342e69c5b736)

Unzip the folder, open it and then hit shift-right click. <br>
Select ```Open in Terminal```. <br>
Then Install required modules using
```
pip install -r requirements.txt
```
And then to run it
```
py WLEDAudioSyncRTBeat.py beat -s 127.0.0.1 7000 /composition/tempocontroller/tempo
```

Where `-s` stays for the server parameter with `127.0.0.1` (loopback) in case you're running Resolume on the same machine. `7000` it's the port in use.
Finally ```/composition/tempocontroller/tempo``` it's the path of OSC which controls the BPM. You can find it in Resolume Arena clicking on ```Shortcuts > EditOsc > Click on the pink BPM rectangle```
On the side it should appear the Shortcuts tab, in the dropdown menu select ```Output All OSC Messages```, if it's not already selected. Under you can find OSC Input
![Resolume Arena - example1 (1280 x 720) 28_11_2024 17_12_59](https://github.com/user-attachments/assets/5a4e4abf-3318-45bd-bcbf-1353e713cef4)

When you're finished exit the edit shorcut mode clicking ```Shortcuts > Stop```


For explaination and parameters refer to [WLEDAudioSyncRTBeat #Usage](https://github.com/zak-45/WLEDAudioSyncRTBeat?tab=readme-ov-file#usage "WLEDAudioSyncRTBeat #Usage").

Hope you enjoy.

##### P.S.
I think you can use a different input device for this tool just check the guide of the official repository.
