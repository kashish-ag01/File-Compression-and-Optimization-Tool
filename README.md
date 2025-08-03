# File Compression & Optimization Web App

A Flask-based web tool to compress, decompress, and optimize text files.  
Features include:
- Huffman Compression (lossless)
- Run-Length Encoding (RLE) Compression
- Huffman Decompression
- Duplicate Word Removal (File Optimization)

Built with:
- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Python (Flask)  
- **Core Engine:** C for fast processing

---

## Features
- User-friendly web interface for uploading text files.
- Multiple compression options.
- Quick and efficient processing using a C-based executable.
- Processed files ready for download.

---

## Installation & Usage
### Prerequisites
- Python 3.x
- Flask
- GCC (to compile C code)

### Steps
```bash
# Clone repository
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name

# Install dependencies
pip install -r requirements.txt

# Compile C program
gcc compressor.c -o compressor.exe

# Run Flask app
python app.py
