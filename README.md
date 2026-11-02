Scientific Description

SotiCode is an experimental software project that explores an alternative visual representation of digital audio data through binary image encoding.

The system converts the binary data of an MP3 file into a two-dimensional black-and-white image, where individual pixels represent binary values. It also implements a decoding mechanism intended to extract binary data from the generated image and reconstruct the original audio file.

The project investigates the intersection of digital signal storage, binary data representation, and visual encoding using web technologies such as JavaScript and HTML5 Canvas.

Rather than introducing a new audio compression format, SotiCode explores the possibility of representing existing digital audio data in a visual, pixel-based form.

The original implementation is preserved as an experimental proof of concept, providing a foundation for future research, evaluation, and independent development.

Scope and Limitations

- The project operates on binary data rather than directly processing audio signals.
- The image acts as a visual representation of the encoded data.
- The current implementation has limitations regarding data integrity, file reconstruction, and supported input sizes.
- Lossless reconstruction and byte-for-byte equivalence have not been established.
- Further development and testing are required before considering it suitable for reliable data storage or transmission.
