# Frequently Asked Questions (FAQ)

## General Questions

### What is the Virtual Assistant Store?
The Virtual Assistant Store is a centralized marketplace for AI-powered tools and assistants designed specifically for organizational use. It provides a consistent interface for accessing various AI capabilities through a familiar "app store" experience.

### What technologies power the Virtual Assistant Store?
The store uses local LLM models via Ollama for most interactions, with specialized vector databases for document analysis capabilities. The frontend is built with Streamlit for rapid iteration and ease of use.

### Is an internet connection required to use the tools?
The system is designed to run on the internal network with locally hosted models, so most functionality works without external internet access. Some advanced features may require internet connectivity for specific external APIs.

## Tool-Specific Questions

### What types of documents can the AIMS tool analyze?
Currently, the AIMS tool supports PDF documents. Future updates will include support for Word documents, Excel spreadsheets, and other common file formats.

### How accurate is the FAST (STAR format) tool?
The FAST tool produces high-quality output based on the input provided, but all outputs should be reviewed and edited before official use. The system includes warnings to remind users to verify generated content.

### Can I customize the chatbot models?
Yes, the Chat Different Models tool allows users to select from various available Ollama models that have been approved and installed in the organization.

### How is my document data handled in AIMS?
Documents uploaded to AIMS are processed in-memory and not permanently stored. The vector embeddings are maintained only for the duration of your session for privacy and security purposes.

## Technical Questions

### Does the system track usage metrics?
The system collects anonymous usage statistics to help improve tool performance and prioritize future development. No personally identifiable information is collected during normal operation.

### What happens if a tool encounters an error?
The system includes robust error handling and recovery mechanisms. If an error occurs, the application will attempt to recover automatically. Persistent errors are logged for review.
