# Bibi Packer v1.2.0

A powerful, cross-platform batch compression application for images and videos. Built with Electron, Bibi Packer provides an intuitive interface for compressing multiple files at once while maintaining quality.

## 🚀 Features

- **Batch Processing**: Compress entire folders or individual files
- **Multiple Formats**: Support for PNG, JPG, GIF, MP4, and WebP
- **Smart Compression**: Optimized algorithms for different file types
- **Cross-Platform**: Works on Windows, macOS (Intel & Apple Silicon)
- **User-Friendly**: Simple, classic UI design
- **FFmpeg Integration**: Professional-grade video compression
- **Sharp Integration**: High-quality image processing

## 📱 Supported Platforms

- **Windows**: x64 (64-bit) - Windows 10/11
- **macOS**: Intel (x64) and Apple Silicon (ARM64) - macOS 10.15+

## 📦 Installation

### Windows Users

1. **Download**: Choose the appropriate Windows installer:
   - `Bibi Packer Setup.exe` - Standard installer with Start Menu shortcuts

2. **Install**:
   - **Installer**: Double-click `Bibi Packer Setup.exe` and follow the wizard

3. **Launch**: Find "Bibi Packer" in your Start Menu or Desktop shortcuts

### macOS Users

1. **Download**: Choose the appropriate macOS package:
   - `Bibi Packer-1.2.0.dmg` - Intel Macs
   - `Bibi Packer-1.2.0-arm64.dmg` - Apple Silicon Macs
   - `Bibi Packer-1.2.0-mac.zip` - Intel Macs (ZIP format)
   - `Bibi Packer-1.2.0-arm64-mac.zip` - Apple Silicon Macs (ZIP format)

2. **Install**:
   - **DMG**: Double-click the DMG file, drag Bibi Packer to Applications folder
   - **ZIP**: Extract and drag the app to Applications folder

3. **Launch**: Find "Bibi Packer" in your Applications folder or Spotlight search

## 🎯 How to Use

### Basic Workflow

1. **Select Input Type**:
   - **Process Folder**: Compress all files in a directory
   - **Single File**: Compress one specific file

2. **Choose Input**:
   - Click "Input" button to select folder or file
   - Supports images (PNG, JPG, GIF, WebP, etc.) and videos (MP4, MOV, AVI, etc.)

3. **Set Output**:
   - Click "Output" button to select destination folder
   - The app will create the folder if it doesn't exist

4. **Select Format**:
   - **PNG**: Optimized for graphics and UI elements (30-70% compression)
   - **JPG**: Best for photographs (20-40% compression)
   - **GIF**: Optimized with color correction (70% compression)
   - **MP4**: H.264 video compression (10-95% compression)
   - **WebP**: Modern format for images and animations (25-80% compression)

5. **Start Compression**:
   - Click "Start Compression" button
   - Monitor progress with the built-in progress bar
   - View detailed logs of the compression process

### Compression Notes

- **PNG**: Ideal for graphics, logos, and flat-color images
- **JPG**: Perfect for photographs and complex images
- **GIF**: Great for simple animations and graphics
- **MP4**: Converts most video formats to H.264 MP4
- **WebP**: Modern alternative to PNG/JPG with better compression

## 🔧 System Requirements

### Windows
- Windows 10 or later (64-bit)
- 4GB RAM minimum
- 500MB free disk space
- DirectX 11 compatible graphics

### macOS
- macOS 10.15 (Catalina) or later
- 4GB RAM minimum
- 500MB free disk space
- Intel processor or Apple Silicon

## 📁 File Structure

```
Bibi Packer/
├── bibi-packer.exe          # Main application (Windows)
├── Bibi Packer.app/         # Main application (macOS)
├── resources/               # Application resources
├── locales/                 # Language files
├── LICENSE                  # MIT License
└── [Other system files]
```

## 🚨 Troubleshooting

### Common Issues

1. **App won't start**:
   - Ensure you have the correct version for your system architecture
   - Check if antivirus software is blocking the application
   - Try running as administrator (Windows) or from Applications folder (macOS)

2. **Compression fails**:
   - Verify input files are not corrupted
   - Ensure sufficient disk space in output directory
   - Check file permissions

3. **Performance issues**:
   - Close other resource-intensive applications
   - Process smaller batches of files
   - Ensure adequate RAM availability

### Getting Help

- Check the application logs for detailed error messages
- Ensure you're using the latest version
- Verify system compatibility

## 📄 License

Bibi Packer is released under the MIT License. See the LICENSE file for details.

## 🤝 Support

For issues, questions, or feature requests:
- Check the troubleshooting section above
- Review the application logs
- Ensure you're using the correct version for your system

## 🔄 Version History

### v1.2.0 (Current)
- Initial public release
- Cross-platform support (Windows & macOS)
- Multiple compression formats
- Batch processing capabilities
- Professional-grade compression engines (FFmpeg + Sharp)

---

**Built with ❤️ using Electron, FFmpeg, and Sharp**
