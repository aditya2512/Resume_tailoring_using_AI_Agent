# Tailoring Job Resume with AI Agents

This project leverages AI Agents to personalize and enhance resumes based on specific job descriptions. The goal is to generate tailored, ATS-friendly, and role-optimized resumes that align with recruiter expectations and highlight relevant skills and achievements from a candidate's portfolio.

## Features

-  **Job Description Parsing**: Extracts key skills, responsibilities, and qualifications from raw job postings.
-  **Resume Matching**: Compares resume content with job requirements to identify gaps and opportunities.
-  **LLM-Driven Enhancement**: Uses GPT-based language models to generate bullet points, summaries, and optimized content tailored for specific roles.
-  **Skill & Keyword Alignment**: Highlights alignment with hard skills, frameworks, tools, and methodologies listed in the JD.
-  **Custom Resume Drafting**: Creates customized resumes ready for export or manual refinement.

## 🛠 Tech Stack

- **Language**: Python
- **Notebook**: Jupyter (`.ipynb`)
- **Libraries**:
  - `openai`: for leveraging GPT models
  - `re`, `json`: for text processing
  - `pandas`: for tabular resume structure (optional)
  - `pdfplumber` / `PyMuPDF`: for parsing PDF resumes (optional extension)
- **LLMs**: OpenAI GPT (with prompts crafted to simulate recruiter judgment and tailoring)

##  File Structure

- TailoringJobResume.ipynb # Main notebook containing preprocessing, prompting, and resume generation
- README.md # Project documentation
- job_description.txt # Example raw job description input
- resume.pdf # (Optional) Your source resume for tailoring
- output_resume.txt # Tailored resume output (can be saved manually from notebook)


## Example Use Cases

- Job seekers applying to roles like **ML Engineer**, **Data Scientist**, or **Software Developer**.
- Rapid iteration of customized resumes for **multiple companies** without manual re-editing.
- Highlighting experience in:
  - Recommender Systems
  - NLP / RAG Pipelines
  - Real-time ML Inference
  - DevOps & Cloud (AWS, GCP, Azure ML)

## Prompt Engineering Strategy

Prompts are engineered to:
- Emphasize achievements using **quantified metrics**.
- Align resume content with the **key themes** in the job description (e.g., personalization, experimentation, model deployment).
- Highlight **impact** using business-aligned vocabulary (e.g., “reduced MTTR by 30%”, “deflected 65% of HR tickets”).

## TODO

- [ ] Integrate PDF parsing to automatically extract resume content
- [ ] Auto-generate cover letters
- [ ] Build a Streamlit app for non-technical users
- [ ] Add company-specific tone customization 

