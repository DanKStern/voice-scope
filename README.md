# Voice Scope

**[Open Voice Scope →](https://dankstern.github.io/voice-scope/)**

A kid-friendly oscilloscope for the voice, built as a companion tool for the *Technology for Young Learners* curriculum. It shows a child's voice from the microphone as a live picture, records four seconds, and plays the recording back split into four frequency bands (Bear < 300 Hz, Person 300–1000 Hz, Bird 1–3 kHz, Snake > 3 kHz) that can be switched on and off while it plays — letting a child hear and see that a voice is made of several parts at once.

**Privacy:** everything runs locally in the browser using the Web Audio API. Nothing is ever uploaded, recorded to a server, or saved anywhere — audio only exists on the page for as long as it takes to listen back, and disappears the moment the page is closed or a new recording is made.

**Requirements:** any modern desktop browser (Chrome, Edge, Firefox, Safari) with a microphone. No installation, no account, no app.

## Running it locally

Open `index.html` directly in a browser, or serve the folder (`python -m http.server`) and open `http://localhost:8000` — serving it is required if the browser blocks microphone access from a bare `file://` page. Add `?test` to the address to use a built-in test sound instead of the microphone.

## License

MIT — see [LICENSE](LICENSE).
