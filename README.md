# The Arxivist: AI Research Assistant

This project is a Streamlit web application that acts as an AI research assistant. It uses a CrewAI-powered-agent team to scrape research papers from arXiv based on a user's topic, sort preference, and desired number of results.

The app displays the paper's title, authors, summary, keywords, and citation, and saves the results to a local `scraped_papers.json` file.

---

## 🚀 Features

* **Search:** Find papers on any topic using the arXiv API.
* **Filter & Sort:** Choose the number of results (1-10) and sort by "Relevance" or "Latest".
* **Agent-Based:** Uses CrewAI with two agents: a `Scraper` agent and a `Data Manager` agent.
* **LLM-Free Logic:** Cleverly uses a `NullLLM` to run CrewAI's agentic workflow without requiring an LLM or API key.
* **Display Results:** Shows the title, authors, summary, keywords, and a "Read More" link.
* **Save Data:** Automatically saves the scraped paper data to `scraped_papers.json`.

---

## 🛠️ Tech Stack

* **Python**
* **Streamlit:** For the web app interface.
* **CrewAI:** For the agent-based workflow.
* **Requests:** For making API calls to arXiv.
* **BeautifulSoup4:** For parsing the XML response from arXiv.
* **lxml:** As the XML parser for BeautifulSoup.

---

## 🏁 How to Run

Follow these steps to get the project running on your local machine.

### 1. Clone the Repository

```bash
git clone [https://github.com/Aakashbisht01/The-Arxivist.git](https://github.com/Aakashbisht01/The-Arxivist.git)
cd The-Arxivist
