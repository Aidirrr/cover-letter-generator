# AI-Powered Cover Letter Generator

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Google Generative AI](https://img.shields.io/badge/Google_Generative_AI-4285F4?style=for-the-badge&logo=google&logoColor=white)

A Streamlit web application that leverages **Google's Gemini AI** to generate professional, tailored cover letters. Users can input their personal information, job details, and upload their resume (PDF). The app extracts text from the resume, incorporates additional user-provided details (e.g., internship duration), and generates a polished cover letter. The output can be downloaded as a **PDF** or **DOCX** file.

---

## Features

- **AI-Generated Cover Letters**: Create personalized cover letters using Google's Gemini AI.
- **Resume Text Extraction**: Extract text from uploaded PDF resumes.
- **Additional Information**: Include extra details like internship duration or specific motivations.
- **Download Options**: Download the generated cover letter as a PDF or DOCX file.
- **User-Friendly Interface**: Built with Streamlit for an intuitive and seamless experience.

---

## Tech Stack

- **Python**: Core programming language.
- **Streamlit**: For building the web application interface.
- **Google Generative AI**: Powers the AI-based cover letter generation.
- **PyPDF2**: For extracting text from uploaded PDF resumes.
- **FPDF**: For generating PDF files.
- **python-docx**: For generating DOCX files.

---

## How It Works

1. **Input Personal Information**: Enter your name, address, email, phone number, and optional LinkedIn/GitHub profiles.
2. **Provide Job Details**: Add the company name, position, location, and job description.
3. **Upload Resume**: Upload your resume in PDF format for text extraction.
4. **Add Additional Information**: Include any extra details (e.g., internship duration, specific motivations).
5. **Generate Cover Letter**: Click the button to generate a professional cover letter tailored to your inputs.
6. **Download**: Download the cover letter as a PDF or DOCX file.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/aidirrr/ai-cover-letter-generator.git
   cd ai-cover-letter-generator
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up your Google Gemini API key:
   - Obtain an API key from [Google AI Studio](https://makersuite.google.com/).
   - Add the API key to the Streamlit app in the sidebar.

4. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

5. Open your browser and navigate to `http://localhost:8501` to use the app.

---

## Usage

1. Enter your **Gemini API Key** in the sidebar.
2. Fill in your **Personal Information**, **Job Details**, and **Additional Information**.
3. Upload your resume in PDF format.
4. Click **Generate Cover Letter** to create a tailored cover letter.
5. Download the cover letter as a PDF or DOCX file.

---

## Screenshots

![App Screenshot](images/app_screenshot.png)  
*Example of the app interface.*

---

## Contributing

Contributions are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeatureName`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeatureName`).
5. Open a pull request.

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- **Google Generative AI**: For providing the AI model used in this project.
- **Streamlit**: For making it easy to build and deploy web apps.
- **PyPDF2, FPDF, and python-docx**: For handling PDF and DOCX file operations.

---

## Author

👤 **Muhammad Khaidhir Bin Mohd Razin**  
- GitHub: [Aidirrr](https://github.com/Aidirrr)  
- LinkedIn: [Khaidhir](http://www.linkedin.com/in/khaidhir)  
- Email: khaidhirrazin04@gmail.com 

---

🌟 **Try it out and make your job applications stand out!** 🌟
