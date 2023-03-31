## Technology used

- The UI is built using [Svelte](https://svelte.dev/). Svelte rocks, and for an experimental UI like this, is a pleasure to use.
- Uses [`MediaDevice` API](https://developer.mozilla.org/en-US/docs/Web/API/MediaDevices) for capturing screen, webcam, and mic.
- Uses [`AudioContext` API](https://developer.mozilla.org/en-US/docs/Web/API/AudioContext) for audio visualizations.
- Uses HTML canvas for drawing the video and audio visualizations, and `CanvasRenderingContext2D`'s `captureStream` for capturing the canvas as a media stream.
- Uses [`MediaRecorder` API](https://developer.mozilla.org/en-US/docs/Web/API/MediaRecorder) for recording the media stream as a WebM.