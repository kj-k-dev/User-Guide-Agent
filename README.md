## Objective
This AI Agent is developed to aid users to use a particular app. It helps user a lot in the sense that users are no longer need to search through the user guide file or FAQ page to solve their problem on using an app.

## Architecture
There are 2 pipelines needed:
1. User Guide Upload pipeline, where user need to upload user guide files in PDF format into the web form created, then the documents will be vectorized and stored in ChromaDB.
2. Chat Querying pipeline, where user can enter their questions into the chatbot, and the actual guidance will be responded in text.

## Limitation
1. This workflow relies on the user guide provided by the users.
2. The vectorization is only performed on text data.
