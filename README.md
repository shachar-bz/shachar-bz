# Hi, I'm Shachar Ben Zur

**Software Engineer building AI-powered systems.**

I enjoy building AI applications that bring models, data, and software together. My work spans LLM agents, multimodal retrieval, and computer vision, including the data pipelines and backend infrastructure that support them.

## Experience

### Software Developer | ZebeAI

[ZebeAI](https://zebeai.info/en) is a research project by The Open University of Israel that monitors AI-generated and AI-manipulated content in Israeli election campaigns.

Contributions included:

- Optimized system performance through PostgreSQL indexing, query optimization, compression, and progressive loading.
- Strengthened the reliability of an ingestion pipeline processing thousands of scraped social media posts weekly by improving failure handling, retries, and reprocessing.
- Developed a face-recognition pipeline by integrating and evaluating multiple face detection and embedding models, testing performance across different scenarios, and tuning hyperparameters for the platform's use case.
- Conducted in-depth media analysis using LLM-based systems and custom-built analysis tools.
- Collaborated with the research team to translate research requirements into technical solutions deployed in production.

## Projects

### VidSeek AI

**Ask any video anything.**

A multimodal AI agent that helps you understand and navigate videos on almost any website. Ask about what’s said, what happens on screen, or what’s written on slides and whiteboards, and jump straight to the relevant moments with clickable timestamps. Built as a Chrome extension and web app.

[GitHub](https://github.com/shachar-bz/VidSeek-AI) · [Demo Video](https://drive.google.com/file/d/190IBrqsLmJo0ctHglXR8zCOwi_hUDnVc/view?usp=sharing)

### Face Detection & Recognition

An evaluation study and reusable pipeline for detecting faces and identifying people against a known-person reference database.

Compared detection models, face embeddings, matching strategies, and decision thresholds using benchmark images and social media data from ZebeAI. The evaluation informed the choice of models and matching configuration, which were then packaged into a runnable pipeline.

[GitHub](https://github.com/shachar-bz/FaceDetection)

### Negation in Hebrew Text Embeddings

An NLP research project investigating a negation blind spot in Hebrew text embeddings, where a sentence and its negation can receive higher semantic similarity scores than a meaning-preserving paraphrase. Explored two approaches: amplifying a negation-related direction in the embedding space, and fine-tuning a pretrained Hebrew language model for natural language inference (NLI) to rerank similarity scores, while aiming to preserve general semantic similarity.

[Research Report](https://drive.google.com/file/d/1hnFQ8-mAh2-n0UVFCMe-UOexcWP596Bt/view?usp=sharing) · [Presentation Video](https://drive.google.com/file/d/1HqGrc4WJArpV0QT5pkrYRttYuMZPK_Se/view?usp=sharing)

### Base Analyzer

A team of AI imagery analysts that investigates suspected military sites from satellite imagery

[GitHub](https://github.com/shachar-bz/Base-analyzer) · [Demo Video](https://drive.google.com/file/d/1DPgL3iMF_eJqtKJVdCbukuu-qYrRjKpR/view?usp=sharing)

### LLM Tool-Calling Agent

A Python agent built directly on OpenAI's tool-calling API, combining image extraction, text-to-SQL, calculations, web search, and file output. Includes recovery from tool failures and bounded execution for multi-step tasks.

[GitHub](https://github.com/shachar-bz/llm-tool-calling-agent)

### LangGraph Self-Correcting Code Generation

LangGraph agent that turns natural-language data questions into Python, executes it, validates the answer, and self-corrects via LLM reflection

[GitHub](https://github.com/shachar-bz/langgraph-self-correcting-codegen)

### TCP Dynamics - University of Birmingham

A network performance study completed for the **University of Birmingham** (UOB), using Wireshark and curl to examine TCP behavior under increasing packet loss. Compared throughput, transfer times, and completion rates across repeated experiments, and analyzed retransmissions, timeouts, and congestion control.

[Report](https://drive.google.com/file/d/1_QEWnnc1XDJOaaCaaKHWZWeThJDxLhZJ/view?usp=sharing)

### Real-Time Multiplayer Trivia

Real-time multiplayer trivia race with live lobbies, in-game chat and bot opponents. Python, aiohttp and Socket.IO backend with a Next.js frontend.

[GitHub](https://github.com/shachar-bz/Real-time-multiplayer-trivia-competition) · [Demo Video](https://drive.google.com/file/d/1-NjY4ruv6jFekOEYbsQ2E8Iw9xg1wqAF/view?usp=sharing)

### Nand2Tetris

Completed the full Nand2Tetris course, building a computer system from logic gates through a working compiler and operating system.

[Official Course Repository](https://github.com/nand2tetris/projects)

## Technical Background

**AI:** Fine-tuning language models, embeddings, RAG, OCR, LangGraph, LangChain, OpenAI, Anthropic, and Gemini SDKs.

**Software & Web:** Python, TypeScript, JavaScript, C#, SQL, HTML, CSS, FastAPI, React, Next.js, PostgreSQL, and Git.

**Cloud:** Google Cloud Platform (GCP).

**Data Collection:** Web scraping and data extraction using third-party services (such as Bright Data and Firecrawl), alongside custom-built scrapers.

**Selected coursework:**

| Course | Grade |
| --- | ---: |
| Software Engineering with LLMs | 99 |
| Machine Learning | 96 |
| Natural Language Processing | 95 |
| Operating Systems | 100 |
| Algorithms | 86 |
| Data Structures | 88 |
| Object-Oriented Programming with .NET and C# | 92 |
| Internet Technologies & Full-Stack Development | 90 |

## Education

**Reichman University - B.Sc. in Computer Science**  
GPA: **92/100**

## Contact

[LinkedIn](https://www.linkedin.com/in/shachar-ben-zur) · [GitHub](https://github.com/shachar-bz) · [shachar.benzur@gmail.com](mailto:shachar.benzur@gmail.com)
