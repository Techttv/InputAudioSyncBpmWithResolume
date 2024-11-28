### ## # Free CMD-Tool to Sync your input device audio BPM with Resolume BPM in REAL TIME. 

Forked from https://github.com/zak-45/WLEDAudioSyncRTBeat and adjusted for Resolume.<br>
Sync your input audio bpm with Resolume.<br>
Make sure to select your input device under the preferencies in Resolume and Windows. <br>
<br><br>
Usage: <br>
Open Resolume>Arena>Preferencies>OSC and enable OSC Input<br>
![Preferences 28_11_2024 16_43_29](https://github.com/user-attachments/assets/e72afb52-45d5-447b-86b5-342e69c5b736)

Then download this repositories not the release, unzip the folder and then hit shift-right click. <br>
Select "Open in Terminal". <br>
Then type `py WLEDAudioSyncRTBeat.py beat -s 127.0.0.1 7000 //composition/tempocontroller/tempo`

For explaination and parameters refer to [WLEDAudioSyncRTBeat #Usage](https://github.com/zak-45/WLEDAudioSyncRTBeat?tab=readme-ov-file#usage "WLEDAudioSyncRTBeat #Usage").

Hope you enjoy.

##### P.S.
I think you can use a different input device for this tool just check the guide of the official repository.
