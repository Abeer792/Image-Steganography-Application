# Image Steganography Web Application

A modern web application for hiding secret messages within images using steganography techniques. Built with React, TypeScript, and Tailwind CSS.

![Image Steganography](https://images.unsplash.com/photo-1614064641938-3bbee52942c7?auto=format&fit=crop&q=80&w=2000)

## Features

- **Message Encoding**: Hide text messages within images using LSB (Least Significant Bit) steganography
- **Message Decoding**: Extract hidden messages from encoded images
- **Browser-based Processing**: All operations performed client-side for maximum privacy
- **Drag & Drop Interface**: Easy image upload functionality
- **Modern UI**: Responsive design with dark mode interface
- **Download Support**: Save encoded images directly to your device

## Technical Implementation

The application uses LSB (Least Significant Bit) steganography, which works by:
- Converting the secret message into binary data
- Modifying the least significant bits of image pixel data
- Preserving image quality while hiding data
- Including message length in the header for accurate extraction

## Security Considerations

- All processing happens locally in the browser
- No server-side storage of images or messages
- Original image quality is maintained
- Hidden messages are not visible to the naked eye

## Getting Started

1. Clone the repository
```bash
git clone [repository-url]
```

2. Install dependencies
```bash
npm install
```

3. Start the development server
```bash
npm run dev
```

## Usage

1. Upload an image using the drag & drop interface
2. Enter your secret message in the text area
3. Click "Encode Message" to hide the message in the image
4. Download the encoded image
5. To decode, upload an encoded image and click "Decode Message"

## Technologies Used

- React 18
- TypeScript
- Tailwind CSS
- Vite
- HTML5 Canvas API
- Lucide React Icons

## License

MIT License

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
