# DocuLens - Automatic Document Verification Platform

DocuLens is an advanced document verification and extraction platform designed to streamline the verification process for RAC applicants. Using cutting-edge AI and machine learning techniques, the platform enables real-time document analysis, face detection, and automated discrepancy flagging, reducing manual intervention and improving operational efficiency.

## Features

- **Real-Time Document Verification**: Extract and verify information from uploaded documents, including face detection, in under 3 seconds using AI models.
- **Automated Text Extraction**: Automatically extract and process text from documents for comparison and verification purposes.
- **Discrepancy Flagging**: Automatically flag discrepancies in applicant data by comparing extracted text across multiple documents.
- **Efficiency Boost**: Reduces the need for manual checks by over 65%, improving both accuracy and operational efficiency.

## Installation

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/your-username/DocuLens-Automatic_Document_Verification_.git
    cd DocuLens-Automatic_Document_Verification_
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Set up any necessary environment variables for AI models or third-party APIs, such as API keys or model paths.

## Usage

1. Upload documents (e.g., PDF, image) through the platform's interface.
2. The system will process the document, perform face detection, and extract relevant data.
3. Discrepancies in the applicant data will be flagged automatically.
4. Review the processed results and manage flagged discrepancies using the platform’s dashboard.

## Technologies Used

- Python
- OpenCV (for face detection)
- Tesseract OCR (for text extraction)
- Machine Learning Models (for data verification)
- NodeJS (for backend API)
- React (for frontend, if applicable)
- MongoDB and Firebase (for Database)

## Contributing

We welcome contributions! If you'd like to contribute to DocuLens:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to your branch (`git push origin feature-branch`)
5. Submit a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
