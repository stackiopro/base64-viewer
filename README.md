# Base64Viewer

It is a powerful tool that primarily offers two core features:

## Decode

The `decode` feature allows for decoding Base64 strings into text or images.

### Key Features

- **Text Decoding**: Convert Base64-encoded strings back to their original textual content.
- **Image Decoding**: If the Base64 string starts with `data:image`, it will decode into an image format, enabling direct display of the image.

### Use Cases

- **Text Decoding**: Useful for viewing Base64-encoded text data, such as those transmitted over network communication.
- **Image Decoding**: Useful for displaying images transmitted in Base64 format, such as those embedded in Data URIs.

## Encode

The `encode` feature allows for converting files or text into Base64 strings, useful in various special scenarios.

### Key Features

- **File Encoding**: Convert file contents into Base64-encoded strings.
- **Text Encoding**: Convert text content into Base64-encoded strings.

### Use Cases

- **File Encoding**: For instance, embedding images or other file data into HTML or CSS files using Base64 encoding.
- **Text Encoding**: For example, encoding data into Base64 strings for secure and complete data transmission over network requests.
