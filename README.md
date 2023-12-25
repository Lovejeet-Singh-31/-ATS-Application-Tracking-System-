# -ATS-Application-Tracking-System-


PDF to Text Conversion and Preprocessing:

1. Utilized PyPDF2 library to extract text from a PDF file containing information about Lovejeet Singh.
Conducted preprocessing steps, including removal of non-alphanumeric characters, and converting the text to lowercase to standardize the data.
Tokenization and Stopword Removal:

2. Employed the Natural Language Toolkit (nltk) for tokenization, breaking down the text into individual words.
Removed common English stopwords to focus on essential content, enhancing the quality of the text data.
Text Vectorization using TF-IDF:

3. Utilized the sklearn library to vectorize the preprocessed text using the Term Frequency-Inverse Document Frequency (TF-IDF) technique.
Created a TF-IDF vector for the PDF content and a separate vector for a job role description by transforming and fitting the data.
Cosine Similarity Comparison and Result:

4. Calculated cosine similarity between the vectorized PDF content and the job role description to quantify their similarity.
Expressed the result as a percentage similarity, indicating how closely the PDF content aligns with the specified job role description.
