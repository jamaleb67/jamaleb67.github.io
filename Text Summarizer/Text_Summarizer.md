# Text Summarizer

- **Must first determine the purpose of the summarizer, i.e., a summarizer that:**
    - Covers all the topics in the document
    - Mines only frequent patterns
    - Discriminates a document from other documents
    - etc.

The answer wil determine how the summary will be generated

**Possibility**
The Python NLTK framework can be used to extract basic elements from a text, e.g.: **Extract**

- Most frequent words, or the most frequent N-grams (N-adjacent words) from the text
- Most relevant sentences using Term frequency-Inverse Document Frequency (TF-IDF), which simply gives higher 
  scores to sentences that tend to appear frequently in one document compared to another document.


