# LLM-Based-Code-Generation-on-Energy-Dataset
Nidhi Dangar <br/>
LLM Used: Groq llama3-70b-8192 <br/>
<br/>

This project demonstrates how to use Large Language Models (LLMs) to dynamically generate and execute Pandas code from natural language queries. The goal is to create a pipeline that converts plain language questions into executable Python code for data analysis on a CSV dataset.

## Project Structure :

- **llm_query.ipynb**: Main notebook that loads a dataset, generates Pandas code using LLM prompts, and executes it.
- **household_power_consumption.txt**: text file that is read into a Pandas DataFrame.
- **LLM Integration**: Uses an LLM llama3-70b-8192 using groq API to generate query-specific Python code.

  
