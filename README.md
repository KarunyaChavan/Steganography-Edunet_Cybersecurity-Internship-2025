# Secure Data Hiding in Image Using Steganography

## 📌 Project Overview
This project implements **image steganography**, a technique used to hide secret messages inside an image without noticeable changes. The approach ensures secure communication by embedding the message at the pixel level and allowing retrieval using a passcode-based decryption mechanism. The application features a **GUI-based interface** built using Tkinter, making it user-friendly and accessible.

## 🚀 Features
✅ **Image-based Steganography:** Hides messages within images using pixel modifications.

✅ **GUI Interface:** Easy-to-use interface for selecting images, encrypting messages, and decrypting them securely.

✅ **Passcode Protection:** Ensures that only authorized users can decrypt the hidden message.

✅ **Minimal Image Distortion:** Embeds the message while preserving the original image quality.

✅ **Error Handling:** Includes input validation and exception handling for a seamless experience.

✅ **Support for PNG & JPG:** Works with common image formats for greater usability.

## 🛠️ Technologies Used
- **Programming Language:** Python
- **Libraries:** OpenCV, Tkinter, NumPy
- **Encryption Method:** Pixel-based data encoding
- **Platform Compatibility:** Windows, Linux, MacOS

## 📂 Project Structure
```
├── steganography.py  # Main application file
├── README.md         # Project documentation
├── drugSpec.jpg      # Sample input image
```

## 🔧 Installation & Setup
1. **Clone the Repository**
```sh
   git clone https://github.com/yourusername/Secure-Image-Steganography.git
   cd Secure-Image-Steganography
```

2. **Install Dependencies**
```sh
   pip install opencv
```
```sh
   pip install numpy
```
```sh
   pip install tkinter
```


3. **Run the Application**
```sh
   python steganography.py
```

## 📸 Usage Guide
### **1️⃣ Encrypt a Message**
1. Run the Python Application/Code.
2. Click on "Browse" to select an image.
3. Enter the secret message and passcode.
4. Click on "Encrypt & Save" to embed the message.
5. The encrypted image is saved as `encryptedImage.png`.

### **2️⃣ Decrypt a Message** (Image must be encrypted already)
1. Run the Python Application/Code.
2. Click on "Browse" and select the encrypted image.
3. Enter the correct passcode used during encryption.
4. Click on "Decrypt" to retrieve the hidden message.

## 🔒 Security Considerations
- The encryption relies on modifying pixel values, ensuring **low detectability**.
- **Passcode protection** prevents unauthorized access.
- For enhanced security, future versions can integrate **AES encryption** before embedding the message.

## 📈 Future Enhancements
🔹 **AI-Powered Steganography:** Implement machine learning models for more robust encoding.
🔹 **Support for Video & Audio:** Extend functionality beyond images.
🔹 **Cloud Storage Integration:** Store and retrieve encrypted images securely.
🔹 **Mobile App Development:** Implement steganography on iOS/Android.

## 👨‍💻 Contribution Guidelines
We welcome contributions to enhance this project. Follow these steps:
1. Fork the repository.
2. Create a new branch for your feature.
3. Commit your changes.
4. Submit a pull request.

