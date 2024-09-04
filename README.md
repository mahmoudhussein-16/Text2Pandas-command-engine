## Overview

The **Text2Pandas Command Engine** is an AI-driven tool designed to transform natural language commands into executable pandas code, making data analysis more accessible. It allows users to interact with datasets through plain English queries, eliminating the need to write complex code.

This project leverages the power of the **LLaMA2 model**, fine-tuned to understand data analysis tasks and convert natural language inputs into equivalent pandas operations. Whether you are a data enthusiast, a beginner, or a professional, this tool simplifies the process of working with data, empowering you to derive insights with minimal coding expertise.

## Key Features

- **Natural Language to Code**: Enter commands in natural language, and the engine converts them to pandas code.
- **Automated Data Manipulation**: Perform filtering, sorting, grouping, and aggregations with ease.
- **Data Exploration**: Query and explore your data without writing code.
- **Visualization Support**: Generate visualizations based on your queries.
- **Seamless Workflow Integration**: Integrate the tool with existing data analysis workflows.

## How It Works

1. **Input**: Users type a query in plain English, such as "Show me the top 10 rows sorted by revenue."
2. **Processing**: The engine uses the LLaMA2 model to process the query and translate it into a pandas command.
3. **Output**: The corresponding pandas code is executed, and the result (e.g., filtered data or visualization) is displayed.

## Technical Details

- **Model**: LLaMA2 7B, fine-tuned for natural language understanding of data analysis tasks.
- **Backend**: Powered by pandas for efficient data manipulation.
- **Languages**: Python, using pandas for data analysis.
