**README: Image Text Extractor using Drive OCR**

### Introduction:
This project aims to provide a convenient solution for uploading images to Google Drive, extracting text from these images, and creating a text file containing the extracted text. To achieve this, a virtual environment (venv) needs to be set up, and specific Python packages must be installed.

### Getting Started:
Follow these steps to set up the virtual environment and install the required packages:

1. Create a virtual environment:
   ```bash
   python -m venv venv
   ```

2. Activate the virtual environment:
     ```bash
     source venv/bin/activate
     ```

3. Install necessary packages:
   ```bash
   pip install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib
   ```

### Usage:
After setting up the virtual environment and installing the required packages, you can use the provided script to upload images to Google Drive, extract text, and create a text file.

```bash
python main.py
```

### What it Does:
The script performs the following tasks:

1. **Upload Image to Drive:**
   - Allows users to upload images to their Google Drive account.

2. **Extract Text from Image:**
   - Utilizes Google's API to extract text from the uploaded images.
4. **Delete image after extracting Text:**
    - it delet the image after it done with the extracting text part.
3. **Create Text File:**
   - Generates a text file containing the extracted text from the images.

### Dependencies:
- `google-api-python-client`
- `google-auth-httplib2`
- `google-auth-oauthlib`

### Note:
Ensure that you have the necessary authentication credentials set up in your Google Cloud Console for proper functioning.

Feel free to explore and modify the script according to your needs. For any issues or improvements, please refer to the project's repository or open an issue. Contributions are welcome!

Happy coding!
