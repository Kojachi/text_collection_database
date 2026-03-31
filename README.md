# Text Collection Database

## 🌍 English Version

A C++ based system for managing text document collections with full-text search capabilities. This project focuses on efficient data retrieval by implementing specialized indexing structures.

**Core Features:**
* **Collection Management**: Create new document collections and dynamically add new text documents.
* **Inverted Indexing**: Automatically builds inverted indexes for every collection to significantly accelerate search queries.
* **Full-Text Search**: Optimized searching of documents within a collection based on keyword queries.

**Technical Highlights:**
* **Data Structures**: Efficient use of C++ Standard Library and custom logic for index mapping.
* **Performance**: Designed to reduce search time from linear to logarithmic/constant time complexity depending on the query type through the use of pre-computed indexes.

---

### 🚀 How to Use

1. **Compilation**:
   Compile the source code using any modern C++ compiler (e.g., `g++`):
   ```bash
   g++ text_collection.cpp -o text_db

2. **Execution**:
   Run the compiled binary:
   ```bash
   ./text_db

3. **Functionality**:
   Follow the on-screen prompts to create collections, insert documents from the z_text directory, and perform searches across your data.

---

**Note:** This project was originally developed in an academic context in Ukraine. While the documentation is provided in English, the source code comments and internal UI messages remain in Ukrainian.
