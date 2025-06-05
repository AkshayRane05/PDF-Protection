# PDF Protection Tool 🔒

A simple and efficient command-line tool to encrypt PDF files with password protection using Python.

## 📋 Features

- 🛡️ **Password Protection**: Encrypt PDF files with custom passwords
- 🚀 **Simple CLI Interface**: Easy-to-use command-line interface
- ⚡ **Fast Processing**: Efficiently handles PDF files of various sizes
- 🔍 **Error Handling**: Comprehensive error detection and user feedback
- 📁 **Batch Processing Ready**: Can be easily integrated into scripts and workflows
- 🌐 **Cross-Platform**: Works on Windows, macOS, and Linux

## 🛠️ Installation

### Prerequisites

- Python 3.6 or higher
- pip package manager

### Install Dependencies

```bash
pip install PyPDF2
```

Or install from requirements file:

```bash
pip install -r requirements.txt
```

### Clone the Repository

```bash
git clone https://github.com/AkshayRane05/PDF_Protection_Tool.git
cd PDF_Protection_Tool
```

## 🚀 Usage

### Basic Syntax

```bash
python pdf_protection_tool.py <input_pdf> <output_pdf> <password>
```

### Examples

#### Encrypt a PDF with a simple password:

```bash
python pdf_protection_tool.py document.pdf encrypted_document.pdf mypassword123
```

#### Use a strong password with spaces:

```bash
python pdf_protection_tool.py report.pdf secure_report.pdf "My Super Strong Password!"
```

#### Encrypt with full file paths:

```bash
python pdf_protection_tool.py /path/to/input.pdf /path/to/output/encrypted.pdf secretpass
```

### Output Examples

**Successful encryption:**

```
[+] Password-protected PDF saved as encrypted_document.pdf
```

**Error handling:**

```
[-] The file input.pdf was not found.
[-] The file corrupted.pdf is not a valid PDF.
```

## 📁 Project Structure

```
PDF_Protection_Tool/
├── pdf_protection_tool.py    # Main script
├── requirements.txt          # Python dependencies
├── README.md                # This file
└── examples/                # Example files (optional)
```

## 🔧 Technical Details

### Dependencies

- **PyPDF2**: For PDF reading, writing, and encryption operations

### Supported PDF Features

- ✅ Multi-page PDFs
- ✅ Text content preservation
- ✅ Image preservation
- ✅ Formatting retention
- ✅ Metadata preservation

### Error Handling

The tool handles various error scenarios:

- File not found
- Invalid PDF files
- Corrupted PDF files
- Permission errors
- Invalid file paths

## 🔐 Security Notes

- **Password Strength**: Use strong passwords with a mix of uppercase, lowercase, numbers, and special characters
- **Original Files**: Your original PDF files remain unchanged
- **Storage**: Passwords are not stored or logged by this tool
- **Encryption**: Uses PyPDF2's built-in encryption (RC4 or AES depending on PDF version)

## 📖 Command Line Arguments

| Argument     | Description                                | Required |
| ------------ | ------------------------------------------ | -------- |
| `input_pdf`  | Path to the PDF file you want to encrypt   | Yes      |
| `output_pdf` | Path where the encrypted PDF will be saved | Yes      |
| `password`   | Password to protect the PDF with           | Yes      |

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

### Development Setup

```bash
# Clone your fork
git clone https://github.com/AkshayRane05/PDF_Protection_Tool.git
cd PDF_Protection_Tool

# Install development dependencies
pip install -r requirements.txt

# Run tests (if available)
python -m pytest tests/
```

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🐛 Issues and Support

If you encounter any issues or have questions:

1. Check the [Issues](https://github.com/AkshayRane05/PDF_Protection_Tool/issues) page
2. Create a new issue if your problem isn't already reported
3. Provide detailed information about your environment and the error

## 📊 Changelog

### v1.0.0 (Current)

- Initial release
- Basic PDF encryption functionality
- Command-line interface
- Error handling and validation

## 🙏 Acknowledgments

- [PyPDF2](https://github.com/py-pdf/PyPDF2) library for PDF manipulation
- Python community for excellent documentation and support

## 📞 Contact

- **GitHub**: [@AkshayRane05](https://github.com/AkshayRane05)
<!-- - **Email**: your.email@example.com -->

---

⭐ If this tool helped you, please consider giving it a star on GitHub!

<!-- ## 🔗 Related Projects

- [PDF Merger Tool](https://github.com/AkshayRane05/pdf-merger) - Merge multiple PDFs
- [PDF Splitter Tool](https://github.com/AkshayRane05/pdf-splitter) - Split PDFs into separate files -->
