# condidate_shortlisting_system
You are developing a "candidate shortlisting system" that takes a folder as input containing 2-8 resumes in PDF format. The task is to develop a utility that can read and parse PDF files, extract text content and metadata such as email, phone numbers, and LinkedIn profiles, and generate a summarized CSV output.

Requirements:

Read and Parse Resumes in PDF Format:

The utility should be able to read PDF files and extract the text content from them.
Metadata extraction should include email addresses, phone numbers, and LinkedIn profiles.
Use any programming language of your choice (e.g., Python, Java) and suitable libraries like PyPDF2 for PDF parsing.
Generate Summarized CSV Output:

The output CSV should have columns for name, email, profile links, and a summary of the candidate including project summaries.
Implement a simple text summarization algorithm or use existing libraries such as summa for Python to generate summaries.
Additional Requirement (Good to Have):

Implement intelligence to rank resumes, such as detecting duplicate projects and tagging them with specific keywords.
You can use Hugging Face models or custom logic for this purpose.
