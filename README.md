# BoletaTuya: Chatbot for Event Inquiries

**BoletaTuya** is a chatbot designed to answer questions about events users plan to attend or have already purchased tickets for. This chatbot does not handle ticket sales but focuses on providing detailed information about events. To ensure accurate and up-to-date responses, the bot leverages **Large Language Models (LLMs)** and extracts information directly from a predefined PDF file containing all event details.

## Key Features

- Answers questions about ticket purchases: claims, refunds, insurance.
- Extracts information directly from a PDF file.
- Natural language support through **Large Language Models (LLMs)**.
- Smooth and user-friendly interaction.
- Does not handle ticket sales, only responds to inquiries.

## How It Works

The chatbot utilizes **LLMs** to process user queries and search for answers within a PDF file containing all relevant information regarding ticket purchases. Since it does not handle ticket sales, the goal is to help users resolve any doubts before attending their event, such as event schedules, artist lineups, or entry restrictions.

## Prerequisites

Before running the project, make sure to have the following installed:

- Python 3.8 or higher
- pip (Python Package Manager)
- Access to a large language model (e.g., GPT-3 or similar)
- The `pdfplumber` package for PDF data extraction

## Operation

The system begins by loading a PDF file containing all relevant information about event ticket purchases. The chatbot processes user queries and uses a **large language model (LLM)** to interpret the questions and search for answers directly in the PDF. The PDF is scanned each time a new question is received, ensuring the information is always up to date according to the document's contents.

### Example of use

- User: *"How can I get a refund for missing the event?"*
- BoletaTuya: *"You must meet the established requirements: submit a written explanation for your absence along with supporting documents, the purchase invoice, and the buyer’s identification."*

