# Long Document Summarization

This is a project that i made for "Text mining" classes during my Master's studies at AGH University. The aim of this project was to create a summarizer that would be able to summarize long texts in English (e.g. blog posts, newspaper articles, etc.).

The program does summarization of a text on the basis of extraction or abstraction depending on the user's choice. Desired text is scraped from user's given URL thanks to BeautifulSoup library. Additionally, the completed summary is translated into Polish as an extra. The results are exported to an external file with the .txt extension.

Three pre-trained NLP models were used in this project:

1. Pegasus-XSum (abstraction approach)
2. Distilbart CNN (extraction approach)
3. OPUS Tatoeba English-Polish (Polish translation)
