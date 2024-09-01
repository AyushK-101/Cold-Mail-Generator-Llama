# Cold Mail Generator
Cold email generator for services company using groq, langchain and streamlit. It allows users to input the URL of a company's job opening. The tool then extracts the relevant details from that page and generates personalized cold emails. These emails include relevant portfolio links sourced from a vector database, based on the specific job descriptions. 

**Imagine a scenario:**

- Nike needs a Senior Machine Learning Engineer and is spending time and resources in the hiring process, on boarding, training etc
- Turing company can provide a dedicated software development engineer to Nike. So, the business development executive (Ayush) from Turing is going to reach out to Nike via a cold email.

## Try It Out 
https://coldmail.streamlit.app/

## Sample Response
![Screenshot 2024-09-01 165037](https://github.com/user-attachments/assets/5b261123-9e3b-4e5a-be13-8e65d4f51bcc)

## Set-up
1. To get started we first need to get an API_KEY from here: https://console.groq.com/keys. Inside `app/.env` update the value of `GROQ_API_KEY` with the API_KEY you created. 


2. To get started, first install the dependencies using:
    ```commandline
     pip install -r requirements.txt
    ```
   
3. Run the streamlit app:
   ```commandline
   streamlit run app/main.py
   ```

