# Automated Job Application Email Generator

This repository contains a tool that automates the creation of personalized job application emails using Large Language Models (LLM) like Llama 3.1. The tool scrapes job descriptions from career pages and uses the power of LLMs to generate customized emails that align with the job requirements and your portfolio.

## How It Works

1. **Extract Text from Career Page:**
   - The tool scrapes job postings from the target company's career page. The extracted text typically includes the job title, required skills, and a brief job description.

2. **Job Information Processing (LLM - Llama 3.1):**
   - The extracted job data is fed into an LLM (Llama 3.1) to process the information. The model interprets the job role, required skills, and the job description to create a structured job object.

3. **Portfolio Integration:**
   - The tool pulls relevant links from your portfolio stored in a ChromaDB database and integrates them with the job object.

4. **Personalized Email Generation (LLM - Llama 3.1):**
   - The LLM then generates a personalized email draft using the job object and portfolio links.

5. **Output:**
   - The final product is a well-structured email ready to be sent to the hiring manager.
