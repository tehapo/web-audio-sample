web-audio-sample
================

Polymer-based web component to play audio samples through Web Audio API.

## Getting Started

### Installation
```bash
bower install web-audio-sample --save
```

### Usage Examples
```html
<web-audio-sample src="sine-wave.wav"></web-audio-sample>
<web-audio-sample src="sine-wave.wav" playback-rate="1.0"></web-audio-sample>
<web-audio-sample src="sine-wave.wav" autoplay></web-audio-sample>
```

### Development
 1. Run ```bower install```.
 2. Use ```polyserve``` during development as instructed in [Create a reusable element](https://www.polymer-project.org/1.0/docs/start/reusableelements.html) article.
