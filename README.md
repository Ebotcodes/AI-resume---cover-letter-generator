# AI-resume-&-cover-letter-generator

#Overview

A Python application that uses AI (Together.ai's API) to generate tailored resumes and cover letters based on your existing resume and a job description. The tool supports PDF, DOCX, and TXT output formats, and includes features like keyword matching analysis and customizable tone/length options.

#Features

-AI-Powered Tailoring: Generates resumes and cover letters optimized for specific job descriptions

-Multiple Formats: Export to PDF, DOCX, or TXT

-Font Customization: Uses Roboto font for clean, professional documents

-Tone Control: Choose between formal, casual, or confident writing styles

-Keyword Analysis: Evaluates how well your resume matches the job description

-Modern UI: Built with CustomTkinter for a sleek interface

-Multi-threading: Prevents UI freezing during generation

#Technologies Used

-Python 3.13.2

-Together.ai API (Mixtral-8x7B-Instruct model)

-CustomTkinter (modern UI)

-python-docx (Word document handling)

-fpdf2 (PDF generation)

-pdfplumber (PDF text extraction)

