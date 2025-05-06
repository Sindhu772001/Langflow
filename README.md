# Langflow LLM Workflow Collection

This repository contains a set of Langflow-based visual workflows designed for real-world automation and classification tasks using large language models (LLMs). Each flow addresses a specific business use case and can be extended or integrated as needed.

## Included Workflows

- **Email Classification**: Categorizes emails (e.g., enquiry, complaint, general).
- **Booking Assistant**: Handles booking-related queries and actions.
- **RateCloud Integration**: Manages rate request and response flows.
- **Ticket Classification**: Categorizes support tickets by type and urgency.
- **Ticket Classification with RAG**: Enhances ticket classification using retrieval-augmented context.
- **RAG (Retrieval-Augmented Generation)**: Fetches relevant documents to support LLM responses.
- **Invoice Processing**: Extracts key fields from invoice documents.
- **Helpdesk Assistant**: Responds to common support queries.

## Usage

1. Install Langflow:
**pip install langflow**

2. Run the Langflow server:
**langflow run**

3. Open `http://localhost:7860` in your browser and import any `.flow.json` file from the `flows/` directory.

 ## Requirements

- Python 3.8+
- Langflow
- Optional: OCR tools (for invoices), vector DB (for RAG)
