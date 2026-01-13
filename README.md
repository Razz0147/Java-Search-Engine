# üîç Java Desktop Search Engine

A Java-based desktop search engine that indexes local files and retrieves relevant results using keyword-based queries. This project demonstrates core **Information Retrieval (IR)** concepts including inverted indexing, tokenization, file crawling, and ranking.

---

## üìå Overview

This project was developed over the course of a semester to explore how real-world search engines work at a smaller scale. The system scans directories, extracts text from files, builds an efficient inverted index, and returns relevant results nearly instantly.

It focuses on:
- Speed and efficiency  
- Clean indexing and search design  
- Practical application of data structures and algorithms  

---

## üöÄ Features

- üìÅ Recursive directory crawling  
- üìÑ Text extraction from local files  
- üß† Inverted index for fast searching  
- üîé Keyword and multi-word query support  
- üìä Results ranked by relevance (term frequency)  
- ‚ö° Near-instant search on hundreds of files  

---

## üõ†Ô∏è Technologies Used

- Java  
- Java NIO (file walking)  
- HashMaps & Lists (indexing)  
- Buffered I/O  
- Object-Oriented Programming  

---

## üèóÔ∏è System Architecture

```
File Crawler ‚Üí Text Parser ‚Üí Tokenizer ‚Üí Inverted Index ‚Üí Search Engine ‚Üí Ranked Results
```

---

## üìÇ Project Structure (example)

```
/src
   /crawler
   /parser
   /index
   /search
Main.java

README.md
```

---

## ‚ñ∂Ô∏è How to Run

### 1. Clone the repository
```bash
git clone https://github.com/Razz0147/<your-repo-name>.git
cd <your-repo-name>
```

### 2. Compile the project
```bash
javac *.java
```

(or compile from your IDE)

### 3. Run the program
```bash
java Main
```

### 4. Select a directory and start searching

Enter keywords to retrieve matching files ranked by relevance.

---

## üß™ Example Capabilities

- Indexes hundreds of files efficiently  
- Searches return almost instantly  
- Handles duplicate words and multi-keyword queries  
- Works well for documents, notes, and code folders  

---

## üìà Results & Performance

- Successfully crawls large directories  
- Builds a fast inverted index  
- Optimized indexing using buffered I/O  
- Improved speed and accuracy throughout development  

---

## ‚ö†Ô∏è Limitations

- Basic ranking (term frequency only)  
- Limited file format support  
- No real-time background indexing  
- Command-line based interface  

---

## üîÆ Future Improvements

- PDF and DOCX parsing  
- TF-IDF ranking  
- JavaFX/Swing GUI  
- Real-time file monitoring  
- Result previews and keyword highlighting  

---

## üë®‚Äçüíª Author

**Raj Budhathoki**  
Computer Science @ Youngstown State University  

- GitHub: https://github.com/Razz0147  
- LinkedIn: https://www.linkedin.com/in/raj-budhathoki-0871392a2/  

---

## üìú License

This project is licensed under the MIT License.

<img width="462" height="642" alt="image" src="https://github.com/user-attachments/assets/b10a1528-f0e7-44ed-b068-6a0ccafbb8e7" />
