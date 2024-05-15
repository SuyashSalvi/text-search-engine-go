### Build A Text Search Engine with Go

This project demonstrates building a full-text search engine in Go. The aim is to enable developers to implement search functionality in their applications without relying on complex systems like Elasticsearch or Algolia, particularly suited for small to mid-scale applications.

#### Overview
- This repository contains the source code and accompanying materials for a video tutorial on building a text search engine in Go.
- The project emphasizes modularity, scalability, and efficiency in searching through large datasets.

#### Features
- **Efficient Search**: Capable of searching through a dataset of 600,000 documents in less than a second.
- **Modular Design**: Structured in a modular way, allowing developers to easily understand and extend the functionality.
- **Tokenization**: Utilizes tokenization to break down text into individual tokens, facilitating efficient searching.
- **Stemming**: Implements stemming to reduce words to their base form, improving search accuracy.

#### Installation
1. Clone the repository: `git clone https://github.com/your-username/text-search-engine-go.git`
2. Navigate to the project directory: `cd text-search-engine-go`
3. Install dependencies: `go mod tidy`

#### Usage
1. Load documents: Use the provided dataset or replace it with your own. Run `go run main.go --dump <path-to-dataset>` to load documents into the search engine.
2. Search documents: After loading documents, search for specific terms using `go run main.go --query "<search-term>"`.

Data dump from here - https://dumps.wikimedia.org/enwiki/latest/enwiki-latest-abstract1.xml.gz
