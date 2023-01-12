# WebRTC API Landscape
This is a free WebRTC API Landscape poster made with [Excalidraw](https://excalidraw.com/)

## APIs
The poster gathers the following APIs:
- WebRTC & Media Capture API
- Web Audio API
- HTML API (partial, linked to MediaElement)
- WebCodecs API
- Streams API
- Insertable Streams API

## Features
1. Interfaces
Each interface exposes its public properties, methods and events. Additionally, constants are defined even if they don't exist. 

2. Relations
Main relations between interfaces have been added with the meaning of: "From the interface X, you can access to the interface Y".

3. Level of standardization
3 levels have been retained:
- **Stable**: Major browsers have an implementation that follows the standard for most of the interfaces. You can use these APIs in production.

- **Implementing**: Specifications are in a good fit but browsers suffer from the implementation (but at least one browser has implemented these interfaces). Use them with care by checking first if they exist or rely on existing shimes.

- **Experimental** : APIs implementation is at early stage or a browser choice, interest to implement with at least a specification proposal (or an early stage of specification). Not recommended to use these APIs in production...

4. Browsers
Browser's logo has been added on themes where only certain browsers have an implementation available. No logo when the theme is implemented by all browsers.

5. Reference
The references to the standardization documents used have been added for all themes.

6. Format
The poster respects the A3 ratio.

## Poster

Here is the poster in **JPG** format

![WebRTC API Landscape](./webrtc-api.jpg "WebRTC API Landscape")

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is open source and available under the [MIT License](LICENSE).

  
