# Rust File Compressor 🗜️

## Overview
Rust File Compressor is a web application that allows users to compress files efficiently using a Rust-powered backend and a sleek, modern frontend.

# Step 1:
![Rust File Compressor UI 1](Assets/Screenshot%202024-11-26%20194419.png)

# Step 2:
![Rust File Compressor UI 2](Assets/Screenshot%202024-11-26%20194339.png)

# Step 3:
![Rust File Compressor UI 3](Assets/Screenshot%202024-11-26%20194356.png)

## Features ✨
- 📁 File compression with adjustable compression levels
- 🌐 Web-based interface
- 🚀 Fast and efficient compression
- 📊 Compression level control (0-9)
- 💾 Custom output file naming

## Prerequisites 🛠️
- Rust (latest stable version)
- Cargo package manager
- Web browser
- Basic web server (for hosting)

## Project Structure 📂
```
rust-file-compressor/
│
├── frontend/
│   ├── index.html
│   ├── styles.css
│   └── script.js
│
├── src/
│   └── main.rs           # Rust backend implementation
│
├── Cargo.toml            # Rust project configuration
└── README.md
```

## Installation 🔧

### Backend Setup
1. Install Rust
```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

2. Clone the repository
```bash
git clone https://github.com/Mahesh7741/Compress-File.git
cd Compress-File
```

3. Build the project
```bash
cargo build --release
```

### Frontend Setup
- No additional setup required
- Use a simple web server to serve the files

## Usage 🖥️
1. Select a file to compress
2. Choose compression level (0-9)
3. Specify output file name
4. Click "Compress File"

## Technology Stack 🔬
- **Frontend**: 
  - HTML5
  - CSS3
  - Vanilla JavaScript
  - Remix Icons

- **Backend**:
  - Rust
  - Cargo
  - File compression libraries

## Compression Levels 📈
- 0: No compression
- 1-3: Faster compression
- 4-6: Balanced compression (Default)
- 7-9: Maximum compression (Slower)

## Performance 🚀
- Fast file compression
- Minimal server-side processing
- Low memory footprint

## Security 🔒
- Server-side file handling
- Temporary file management
- Limited file size support

## Contributions 🤝
Contributions are welcome! Please follow these steps:
1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License 📄
MIT License

## Contact 📧
- Mahesh Pal
- Email: maheshsavant8799@gmail.com
- Project Link: https://github.com/Mahesh7741/Compress-File

---

**Note**: Ensure you have the screenshot images in the Assets folder for the README to render correctly.