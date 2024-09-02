🔍 **Project Overview**

Welcome to the **LSB Steganography** project! This tool allows you to hide secret messages within images using the Least Significant Bit (LSB) technique. 
It’s a simple yet powerful way to encode information discreetly.
his project implements Least Significant Bit (LSB) Steganography in C, enabling you to securely hide and extract text messages within image files by altering the least significant bits of the pixel values—making the changes undetectable to the human eye. 

🚀 **How It Works**
1. **LSB Encoding**: The message is embedded into the image by altering the least significant bits of the pixel values. These small changes are not visible to the human eye
**Run the tool**:
    - **Encoding**: 
      ```bash
      ./steganography -e input_image.bmp secret_message.txt output_image.bmp
      ```
    - **Decoding**:
      ```bash
      ./steganography -d output_image.bmp
      ```

💡 **Use Cases** 
 - **Secure Communication**: Hide sensitive information in images to prevent unauthorized access.
 - **Digital Watermarking**: Embed ownership or copyright information within images.
 
🔧 **Future Enhancements**
- Support for additional image formats like PNG or JPEG.
- A graphical user interface (GUI) for easier use.
- Improved error handling and robustness.
