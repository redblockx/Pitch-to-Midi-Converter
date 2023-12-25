- Project Objectives: The project involves developing a software module for professional Digital Audio Workstation (DAW) applications,
capable of determining the pitch of a musical audio signal originating from either a musical instrument or a voice captured with a microphone and associating it with a musical note.
The goal of this project is to create a fully functional plugin that can be used in any DAW to streamline the creative process for composers and artists, enabling them to translate their ideas quickly and easily.

- Project Implementation and Results: For this application, we will employ the method of signal autocorrelation to determine the pitch of the input sound.
A calculation window of 20 milliseconds will be used for autocorrelation, where the fundamental period of the signal will be calculated.
Subsequently, this value will be converted into a MIDI language-specific number, and NoteOn and NoteOff events will be generated to produce musical notes.

- Usage:
- Before the plugin, apply a noise gate with the treshold of at least -35db.
- Set the input to audio and output to MIDI.
- If you are singing with your voice, try using only vowels.
