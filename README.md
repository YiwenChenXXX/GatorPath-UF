# GatorPath-UF
Graph-based, risk-aware degree planning web app for University of Florida Computer Science, Data Science, and Statistics students.

GatorPath uses a graph-based model of the UF curriculum to generate personalized, prerequisite-feasible degree paths for UF undergraduates. The system combines (more features are still being developed):

- **Curriculum graph**: UF CS/DS/Stats courses modeled as a directed acyclic graph (DAG) with prerequisite edges and course attributes.
- **Risk modeling**: statistical / ML models that estimate each student's probability of struggling in a candidate course based on their profile and past coursework.
- **Hybrid recommendation**: content-based scoring + risk-aware adjustment + path constraints to suggest courses, multi-semester plans, and external learning resources.

The first version is now UF-specific, but the framework is designed so that the curriculum graph and policies can be swapped out to support other universities in the future.


## Project Timeline

- **Jan–Mar 2025** – Initial idea and problem formulation; survey of course recommendation and curriculum graph literature; early sketches of UF CS/DS/Stats degree structures.
- **Apr–Jun 2025** – Designed the data schema for UF curricula and drafted path-planning and scoring algorithms on paper.
- **Oct 2025–Present** – Implementing the GatorGraph engine, building the GatorPath web UI, and preparing deployment as a public demo web app.
