# TRANSFER X 🚀

A ultra-fast, modern web-based file transfer application built with Node.js and WebSocket technology.

## Features

✨ **Super Fast Speed**
- Chunked file transfer for optimal performance
- Multi-threaded upload/download processing
- Streaming technology for large files
- Compression support for faster transfers
- Optimized buffer management

🎨 **Modern UI**
- Drag-and-drop file upload
- Real-time progress tracking
- Responsive design
- Clean, intuitive interface
- Live speed metrics

🔒 **Secure**
- File validation and sanitization
- Unique session IDs
- Optional encryption support
- No file size limitations
- CORS protection

## Installation

```bash
git clone https://github.com/mdasjadansari/TRANSFER-X.git
cd TRANSFER-X
npm install
```

## Usage

```bash
npm start
```

Visit `http://localhost:3000` in your browser.

## Technology Stack

- **Backend**: Node.js, Express.js, WebSocket
- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **File Transfer**: Streaming, Chunking, Compression
- **Performance**: Multi-threading, Direct Memory Access

## Project Structure

```
TRANSFER-X/
├── server.js
├── package.json
├── public/
│   ├── index.html
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── app.js
└── uploads/
```

## Configuration

Edit `server.js` to customize:
- Port number (default: 3000)
- Chunk size (default: 1MB)
- Max file size
- Upload directory

## License

MIT
