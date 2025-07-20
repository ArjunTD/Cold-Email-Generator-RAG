# Cold-Email-Generator-RAG

• Built a Retrieval-Augmented Generation (RAG) system to automate personalized cold email generation for job postings
using LLaMA-3 (via Groq) and LangChain Framework.
• Implemented prompt-based extraction of job roles, skills, and descriptions from scraped career page text using LLaMA-3
and structured the output into JSON for downstream processing.
• Used ChromaDB as a vector store to perform semantic search over technical portfolio items based on extracted
job-required skills, improving relevance and personalization.
• Based on the skills related to the job posting extracted from ChromaDB and the customized user’s background, LLM is
prompted again for the cold email.
• Developed a responsive Streamlit web app to accept URLs of job postings and display generated emails in realtime.
