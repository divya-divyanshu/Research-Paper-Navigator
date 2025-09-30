Step 1: Collect + Clean Data → Step 2: Generate Embeddings → Step 3: Clustering → Step 4: Summarization → Step 5: Integration with Backend/UI

------------------------------------------


Step 1: Data Collection and Cleaning
------------------------------------------

For this project, we use the ArXiv Metadata Dataset (available on Kaggle), which contains metadata of research papers across multiple domains. Since our system focuses on semantic search, clustering, and summarization, only the essential fields are extracted.

Selected Fields
------------------------------------------

Title – used for search and graph visualization.

Abstract – used for generating embeddings, semantic search, clustering, and summarization.

Categories – used to group papers into related topics or subfields.

Submission Date – used to order papers for “Learning Path Mode” (beginner → advanced).

Authors (optional) – used for display purposes only.

Cleaning Process
--------------------------------------------

Remove missing or incomplete records – drop entries without abstracts.

Remove duplicates – ensure each paper appears only once.

Field selection – keep only the required fields listed above.

Text normalization – convert abstracts to lowercase and remove unwanted symbols.
----------

This lightweight preprocessing ensures that the dataset is clean, structured, and ready for embedding generation in later stages.