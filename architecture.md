**Architecture Diagram: News Summarizer AI Agent
**+-------------------+         +-------------------+         +-------------------+
|                   |         |                   |         |                   |
|    User (UI)      +-------->+   Streamlit App   +-------->+   News Sources    |
|                   |         |                   |         | (NewsAPI, SerpAPI)|
+-------------------+         |                   |         +-------------------+
                              |                   |
                              |                   |         +-------------------+
                              |                   +-------->+  Gemini AI Model  |
                              |                   |         +-------------------+
                              |                   |
                              +--------+----------+
                                       |
                                       v
                              +-------------------+
                              |   Summaries,      |
                              |   Key Points,     |
                              |   Insights,       |
                              |   Downloads       |
                              +-------------------+
