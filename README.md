                                          README

Your Own — Desktop Assistant

Is a (free, local, and uncensored )
desktop application that lets you chat with an AI model, record and transcribe audio, and save your conversation history — all inside a clean and lightweight GUI.

This app is designed to work out‑of‑the‑box with OpenAI-style endpoints, for local models, and requires no technical knowledge from end users.

_____________________________________________________________________________________________

🔹 What This App Does

✔ let you speak or text your inquires into a microphone to the Ai model
and get a text or spoken reply back from the Ai model

✔ Gives you a clean, simple, responsive interface
Modern buttons, real-time status bar.

✔ Auto-detect GPU/CPU (future-proof)
The app attempts to use GPU if available, otherwise CPU.

___________________________________________________________________________________

🔹Requirements
    LM Studio
   ⚠️ you must have LM Studio installed and running


🔹 PC Requirements
Component	Minimum	Recommended
OS	Windows 10 (64-bit)	Windows 11 (64-bit)
CPU	Dual Core	Quad Core or better
RAM	4 GB	8+ GB
GPU	Not required	NVIDIA GPU with CUDA (optional, for faster models)
Storage	~500 MB free	1 GB free
Internet	Not required for local models	Not required for local models

____________________________________________________________________________________


🔹 How to Install

1. Download the installer (YourOwnInstaller.exe).

2. Run it.

3. The app installs to:
C:\Users\<YourName>\AppData\Local\YourOwn

4. A Start Menu shortcut will appear under Your Own.

________________________________________________________________________________________


🔹 How to Use the App

1. Type or Record input Messages:
Type in the box and press Enter
or Click the Record button and say your inquiries
       Watch the status bar
Shows:

"Waiting" → idle

"Recording" → mic active

"Thinking…" → AI responding

and your response with appear in the window

2. you can just read the text response that's in the window
   or click the read out loud button to hear the response from the Ai model

3. to switch themes:
    just hit button light or dark mode button
    the half moon icon button for dark mode
    and the sun icon button for light mode

4. to delete the text on the screen just hit the delete button
   the trash can icon button

5. to add in an api/endpoint 
   just hit the connect LM button
   and then type in or paste the api/endpoint 
   and hit connect

6. to change voice for the default voice
   just hit the voice button and a voice picker
   area will appear with the default voice ED in it
   there is a drop down section in that area
   a small white arrow pointing down hit that 
   button and a list of voice will appear
   and that about the bottom of that list it's another
   arrow pointing down hit that arrow to see more voices
  
7. once you picked a voice you can hear how that voice
   sound with a quick voice test:
   just hit the Test voice button to test any voice you picked
   once done you can just hit the close button

8. to Analyze images or file
   Note: you must have a LM Studio Vision model for this to work
   hit the upload button select you image or file
   the Ai with acknowledge what you did and then you tell the Ai
   to analyze it or what you want it to do for you.
 

_________________________________________________________________________________________

🔹 Features (Simple Breakdown)

1.🎙 Voice-to-Text

2. 🔊 text to voice 

3. Theme switcher buttons
   change app theme
   from light mode to dark mode

4. Ai model voice changer
   you can change the ai voice
   to one you prefer 100 + to choose from

5. test voices
   you can quickly listen to a voices 
   with the test voice button

6. analyze images or file
   if using a Ai vision model

__________________________________________________________________________________________

🔹 Important Notes for Users
  
• Microphone Access

Recording will fail if:

no microphone is available

microphone is in use by another app


• Response Delay

AI responses depend on model speed:
local models on CPU may be slower


• Installer Uninstall

You can uninstall the app through:
Control Panel → Programs → Uninstall a program → Your Own

This removes all files and folders created by the installer.

_______________________________________________________________________________

🔹 Troubleshooting:

1. The app won't start

Try reinstalling. Some antivirus apps may block new executables.

2. Audio won’t record

Check:

microphone permissions

microphone is connected

3. AI doesn’t respond

Check:

your API key

your endpoint URL

This is the default endpoint for LM Studio's local server
try 
Default endpoint: http://localhost:1234/v1
if you got LM studio install and running
_______________________________________________________________________________________