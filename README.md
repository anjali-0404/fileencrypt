🔐 Secure File Encryption/Decryption Tool
A modern, responsive web-based file encryption and decryption tool that provides military-grade security using AES-256 encryption. This tool allows users to securely encrypt sensitive files and decrypt them when needed, all within their browser without any server-side processing.
✨ Features
🔒 Security Features

AES-256 Encryption: Uses Advanced Encryption Standard with 256-bit keys
Client-Side Processing: All encryption/decryption happens locally in your browser
No Data Transmission: Your files and passwords never leave your device
Password Protection: Strong password-based encryption with confirmation
File Integrity: Maintains original file format, name, and metadata

🎨 User Interface

Modern Design: Clean, intuitive interface with contemporary styling
Responsive Layout: Works seamlessly on desktop, tablet, and mobile devices
Drag & Drop: Easy file selection with drag-and-drop functionality
Progress Indicators: Real-time progress bars during encryption/decryption
Visual Feedback: Success/error notifications and loading animations
Password Visibility Toggle: Option to show/hide passwords during entry

📱 Cross-Platform Compatibility

Browser Support: Works with all modern browsers (Chrome, Firefox, Safari, Edge)
Device Compatibility: Desktop, laptop, tablet, and mobile devices
No Installation Required: Runs directly in web browsers
Offline Capable: Can work without internet connection once loaded

🚀 Getting Started
Prerequisites

Any modern web browser with JavaScript enabled
No additional software installation required

Installation

Download: Save the HTML file to your computer
Open: Double-click the file or open it in your preferred browser
Start Using: The tool is ready to use immediately

Quick Start Guide
Encrypting a File

Click on the "Encrypt Files" tab
Select File: Either drag & drop a file or click to browse
Enter Password: Type a strong password
Confirm Password: Re-enter the same password
Click Encrypt: The encrypted file will download automatically with .enc extension

Decrypting a File

Click on the "Decrypt Files" tab
Select Encrypted File: Choose the .enc file you want to decrypt
Enter Password: Type the password used for encryption
Click Decrypt: The original file will download automatically

🔧 Technical Specifications
Encryption Details

Algorithm: Advanced Encryption Standard (AES)
Key Size: 256 bits
Mode: CBC (Cipher Block Chaining)
Padding: PKCS#7
Key Derivation: PBKDF2 (handled by CryptoJS)

File Handling

Supported File Types: All file types (documents, images, videos, archives, etc.)
File Size Limit: Limited only by browser memory (typically several GB)
Metadata Preservation: Original filename, file type, and size are preserved
Binary Support: Full support for binary files

Dependencies

CryptoJS v4.1.1: For AES encryption/decryption
FileSaver.js v2.0.5: For file download functionality
Material Icons: For UI icons

📖 Usage Examples
Example 1: Encrypting a Document
1. Select "document.pdf" from your computer
2. Enter password: "MySecurePassword123!"
3. Confirm password: "MySecurePassword123!"
4. Click "Encrypt File"
5. Downloads: "document.pdf.enc"
Example 2: Decrypting the Document
1. Select "document.pdf.enc" file
2. Enter password: "MySecurePassword123!"
3. Click "Decrypt File"
4. Downloads: "document.pdf" (original file restored)
🛡️ Security Best Practices
Password Recommendations

Length: Use at least 12 characters
Complexity: Include uppercase, lowercase, numbers, and symbols
Uniqueness: Use a unique password for each encrypted file
Storage: Store passwords securely (password manager recommended)

File Handling

Backup: Keep encrypted backups of important files
Verification: Test decryption immediately after encryption
Secure Deletion: Securely delete original files if needed
Access Control: Limit access to encrypted files

⚠️ Important Warnings
Password Recovery

No Password Recovery: If you forget your password, your files cannot be recovered
No Backdoors: There are no master keys or backdoors built into this tool
Responsibility: You are solely responsible for remembering your passwords

Security Considerations

Browser Security: Ensure your browser is up-to-date and secure
Device Security: Use the tool on trusted, malware-free devices
Network Security: While processing is local, ensure secure network when downloading
File Cleanup: Clear browser cache/downloads if using on shared computers

🔍 Troubleshooting
Common Issues
Decryption Fails

Solution: Verify password is correct (case-sensitive)
Check: Ensure the file is a valid encrypted file created by this tool
Try: Clear browser cache and reload the page

File Won't Upload

Solution: Check file size (very large files may cause browser issues)
Try: Use a different browser
Check: Ensure sufficient disk space for processing

Download Doesn't Start

Solution: Check browser's download settings
Allow: Enable downloads from the page if blocked
Try: Use a different browser or disable ad blockers

Error Messages

"Passwords do not match": Re-enter passwords carefully
"Decryption failed": Wrong password or corrupted file
"Please select a file": Choose a file before proceeding

🔄 Version History
v1.0.0 (Current)

Initial release with AES-256 encryption
Responsive web interface
Drag & drop file support
Progress indicators and visual feedback
File metadata preservation
Cross-platform compatibility
