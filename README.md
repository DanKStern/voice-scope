# Voice Scope

A kid-friendly oscilloscope for the voice. A single static page (`index.html`): it shows the microphone waveform live, records 4 seconds, and plays the recording back split into four frequency bands (Bear < 300 Hz, Person 300–1000 Hz, Bird 1–3 kHz, Snake > 3 kHz) that can be switched on and off while it plays.

Everything runs in the browser using the Web Audio API. No audio is uploaded or saved.

Run it by opening `index.html` in Chrome, or by serving the folder (`python -m http.server`) and opening `http://localhost:8000`. Add `?test` to the address to use a built-in test sound instead of the microphone.
