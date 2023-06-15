# <p align="center">b-ta.DavisDrozReplaceFactions</p>
<p align="center">Replaces all (seven) factions with Davis & Droz.</p>
<p align="center">This mod also adds an ID Card!</p>

By default it uses Droz's banner, but you can also change it to Davis' on line 96 in the [`cl_conversation.gnut`](https://github.com/Syampuuh/Titanfall2/blob/master/scripts/vscripts/conversation/cl_conversation.gnut#L96) file (that is included) by changing `caller_id_12` to `caller_id_10`.

In this file there's also [`const WAVEFORM_FADE_DURATION`](https://github.com/Syampuuh/Titanfall2/blob/master/scripts/vscripts/conversation/cl_conversation.gnut#L32) which controls for how long the ID card will be shown, if you change the value to a large number it will also react to the titan's voice (with the same banner), as well as about one grunt voice line (Take out those titans. Fire! Fire!)

To enable the ID card, [`cl_faction_dialogue.gnut`](https://github.com/Syampuuh/Titanfall2/blob/master/scripts/vscripts/conversation/cl_faction_dialogue.gnut#L250) is used, `return` is changed to `true` on 250 and 256 lines.

These changes don't affect Marvin's Finest Hour. The title on the banner is of the current faction.

The waveform also reacts to the audio override.

If any mod you have uses these files (`cl_conversation.gnut` & `cl_faction_dialogue.gnut`), change the values in it instead to avoid conflicts.

This mod is an edit of [**Cpone**](https://github.com/connieprice)'s DavisDrozReplaceGates, adding the ID card wouldn't have been possible without [**NachosChipeados**](https://github.com/NachosChipeados).

<p align="center"><img src="https://user-images.githubusercontent.com/99835765/154850352-2bc968e8-f340-4944-8ef2-1a0dd1ca1a9d.png" align="center" width="60%"></p>

<p align="center"><img src="https://github.com/begin-theadventure/N-DavisDrozReplaceFactions/assets/99835765/aa2f7933-4dad-48b9-b255-9d213216ba74" align="center" width="40%"></p>

<p align="center"><img src="https://github.com/begin-theadventure/N-DavisDrozReplaceFactions/assets/99835765/8fd98abf-b3dd-4b34-b890-7be3d9959c3a" align="center" width="40%"></p>
