THREAT FORWARN


Web Forum Threat Intelligence Scraper
Indra's Eye is an automated threat intelligence system designed to proactively monitor web forums and discussion platforms. It detects leaked credentials, API keys, and discussions indicating planned cyber-attacks specifically targeting Indian critical infrastructure (Banking, Telecom, Power, Government).

Note: This tool is for educational and defensive purposes only. The developers do not endorse illegal scraping or the use of this tool for offensive cyber operations.

🚀 Key Features
Automated Monitoring:Continuously scrapes designated surface web and deep web forums.

Credential Dump Detection:Uses Regex and entropy analysis to identify username:password combos, API keys (AWS, Google Cloud), and config leaks.

NLP Threat Analysis: Differentiates between educational discussions and malicious intent using a fine-tuned BERT model.

Context-Aware Scoring:Assigns a "Severity Score" (0-100) based on source credibility, target specificity, and immediacy.

 🇮🇳 India-Specific Filters: Custom dictionaries to flag threats against entities like NPCI, RBI, Grid-India, and major ISPs.

 Real-time Dashboard:A React-based frontend to visualize threats and generate alerts.

🛠️ Tech Stack
Data Acquisition: Python, Selenium (Dynamic content), Scrapy, Tor (Anonymity/Onion routing).

Analysis Engine:

NLP: PyTorch, HuggingFace Transformers (BERT).

Entity Extraction: Spacy (NER).

Backend: FastAPI (High-performance API).

Database:

PostgreSQL: Metadata and user management.

Elasticsearch: Full-text search and analytics.

Frontend: React.js, Tailwind CSS.

Infrastructure: Docker, Kafka (Message Queuing).



Docker & Docker Compose

