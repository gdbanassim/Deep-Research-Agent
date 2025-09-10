# Deep Research Agent

## Purpose
The Deep Research Agent is a Python-based tool designed to automate comprehensive research on user-specified topics. Leveraging AI language models (e.g., OpenAI), web search capabilities (via Tavily), and tool integration (via Composio), it generates targeted research questions, conducts in-depth web research, synthesizes findings, and produces professional reports in Google Docs. The tool aims to streamline research workflows for domains like Health, Technology, and Finance, making it ideal for researchers, students, and professionals.

## Core Features
- **Question Generation**: Automatically creates three focused research questions based on the user’s topic and chosen domain.
- **Automated Research**: Independently researches each question using AI-driven analysis and web searches powered by Tavily.
- **Report Synthesis**: Compiles findings into a cohesive, well-structured report with proper formatting.
- **Google Docs Integration**: Exports the final report to Google Docs for easy access and sharing.
- **Streamlit Web Interface**: Provides an intuitive UI to input topics, select domains, monitor progress, and review results.
- **Interactive Follow-ups**: Allows users to ask follow-up questions for further clarification or deeper exploration.

## How to Use
1. **Setup**:
   - Clone the repository: `git clone https://github.com/gdbanassim/Deep-Research-Agent.git`
   - Install Python 3.8+ and required dependencies: `pip install -r requirements.txt`
   - Set up API keys for OpenAI, Composio, and Tavily in a `.env` file
   - Configure Composio tools: `composio login`, `composio add tavily`, `composio add googledocs`
2. **Run the Application**:
   - Launch the Streamlit app: `streamlit run app.py`
   - Open `http://localhost:8501` in your browser
3. **Conduct Research**:
   - Enter a research topic (e.g., "AI in healthcare") and select a domain (e.g., Health)
   - Click "Start Research" to initiate the process
4. **Review Results**:
   - Monitor generated research questions and progress in the web interface
   - Access the final report in Google Docs
   - Ask follow-up questions as needed

The Deep Research Agent simplifies complex research tasks, delivering professional-grade reports with minimal user effort.
