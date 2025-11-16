# Habsburg Family Graph — Python + Neo4j Demo

A small Python demo showing how to connect to a Neo4j database and run basic CRUD operations, using a lighthearted “case study” of the Habsburg family tree.

## Background

Originally prepared as a student project demonstrating Python–Neo4j integration.  
Hand-crafted specifically for this demo, the Habsburg mini-graph was chosen for its natural fit with the topic.

## Project Contents

- **Neo4j_Habsburg_Presentation.ipynb** – the main notebook used for the demo  
- **Neo4j_Habsburg_Presentation.html** – a fully embedded export of the notebook that can be viewed without running any code  
- **data/** – small hand-constructed CSV files defining people and relationships  
- **pics/** and **screenshots/** – images referenced in the notebook, including Neo4j Bloom views  

All files referenced in the notebook are included.

## What the Notebook Demonstrates

- Python — Neo4j connectivity  
- Simple Cypher CRUD operations  
- Loading and building a small graph from CSV files  
- Bloom visualization of the final graph

## How to Run

To run the notebook, set up a Neo4j instance and update the database connection credentials in the second code cell. The notebook will recreate the graph from scratch using the CSV files.  
Running the notebook is optional — the HTML export shows the full output.

## Technologies Used

Python, Neo4j (via the official Python driver), Cypher, Jupyter Notebook.
