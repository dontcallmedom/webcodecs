# WebCodecs

The [WebCodecs API](https://w3c.github.io/webcodecs/) allows web applications
to encode and decode audio and video.

Many Web APIs use media codecs internally to support APIs for particular uses:
- HTMLMediaElement and Media Source Extensions
- WebAudio (decodeAudioData)
- MediaRecorder
- WebRTC

But there’s no general way to flexibly configure and use these media codecs. 
Because of this, many web applications have resorted to implementing 
media codecs in JavaScript or WebAssembly, despite the disadvantages:
- Increased bandwidth to download codecs already in the browser.
- Reduced performance
- Reduced power efficiency 

It's great for:
- Live streaming
- Cloud gaming
- Media file editing and transcoding

See the [explainer](https://github.com/w3c/webcodecs/blob/main/explainer.md) for more info.

# Code samples

Please see https://w3c.github.io/webcodecs/samples/
