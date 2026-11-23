# MIS Report Agent

An AI agent that automates repetitive sales analysis tasks: it reads sales data,
calculates stats, creates charts, writes an AI summary, and answers questions
in Marathi using tool-calling.

## Features
- Sales analysis with Pandas (by product, region, month)
- Auto-generated HTML report with charts and AI summary
- Chat agent: the LLM decides which tool to run (tool-calling loop)

## Tech stack
Python, Pandas, Matplotlib, Groq API (openai/gpt-oss-20b), Google Colab

## How to run
1. Open `mis_agent.ipynb` in Google Colab
2. Add your Groq API key in Colab Secrets with the name `GROQ_API_KEY`
   (free key: console.groq.com)
3. Run the cells from top to bottom

## Example questions
- "Total sales kiti zali?"
- "Konta product sarvat jast chalto?"
- "Region-wise chart bana"

## Author
Sarthak Chougale, Final-year CSE (Data Science)
