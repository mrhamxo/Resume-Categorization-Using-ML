# Advanced Resume Categorizer Application  

## Project Overview  
The **Advanced Resume Categorizer Application** is a powerful tool designed to streamline the process of analyzing, categorizing, and extracting key insights from resumes in bulk. This project utilizes machine learning models and natural language processing (NLP) techniques to categorize resumes into predefined roles, extract skills, experience, and location details, and organize them into structured output formats.  

## Objectives  
- **Automate Resume Categorization:** Classify resumes into predefined categories based on their content.  
- **Extract Key Information:** Identify skills, years of experience, and location details from resumes.  
- **Improve Organization:** Store categorized resumes in designated folders for easy management.  
- **Generate Structured Reports:** Create downloadable CSV and DOCX reports for further analysis.  

## Methodology/Methods  
1. **Input Handling:**  
   - Users upload multiple PDF or DOCX resumes via the Streamlit app.  
2. **Text Extraction:**  
   - For PDFs: Extract text using `PyPDF`.  
   - For DOCX: Extract text using `python-docx`.  
3. **Text Preprocessing:**  
   - Clean the extracted text by removing URLs, special characters, and non-ASCII characters.  
4. **Feature Extraction:**  
   - Use a pre-trained TF-IDF vectorizer to transform the cleaned text into feature vectors.  
5. **Categorization:**  
   - Predict the resume category using a pre-trained machine learning model.  
6. **Key Information Extraction:**  
   - Extract skills, years of experience, and location details using keywords and regex patterns.  
7. **Output Management:**  
   - Organize resumes into folders based on their predicted categories.  
   - Generate a comprehensive results table displayed in the app.  
   - Provide downloadable reports in CSV and DOCX formats.  

## How to Use It  
1. **Run the Application:**  
   - Execute the Streamlit app:  
     ```bash
     streamlit run app.py
     ```  

2. **Upload Resumes:**  
   - Use the file uploader in the app to select multiple resumes in PDF or DOCX formats.  

3. **Specify Output Directory:**  
   - Input the directory path where categorized resumes should be saved.  

4. **Categorize and Download Results:**  
   - Click "Categorize Resumes" to process resumes.  
   - Download the results as a CSV or DOCX report using the provided buttons.  


## User Interface Screenshot:
![1](https://github.com/user-attachments/assets/944e978d-22e7-45a6-8a9f-f169a4ecfe1e)

![2](https://github.com/user-attachments/assets/4ab0eb1d-c784-438c-abaf-ebbd5cea51ba)

## Conclusion  
The **Advanced Resume Categorizer Application** simplifies and automates the otherwise tedious process of analyzing and organizing resumes. By leveraging machine learning and NLP, it provides actionable insights and organized outputs, making it an indispensable tool for HR professionals and recruiters.  

## Future Enhancements  
- **NER Integration:** Incorporate Named Entity Recognition (NER) models for better location extraction.  
- **Skill Expansion:** Add more domain-specific skills to the keyword database.  
- **Interactive Dashboards:** Provide visual analytics for resume insights.

## **Contact**  
For questions or feedback, reach out to **[Muhammad Hamza](mailto:mr.hamxa942@gmail.com) or [Linkedin](https://www.linkedin.com/in/muhammad-hamza-khattak/)**.  
