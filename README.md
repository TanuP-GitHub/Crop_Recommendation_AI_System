# Crop_Recommendation_AI_System
> In the era of internet and google, people are more aware towards searching their views, requirements and go gain some knowledge. from this point of view, as a python developer we are supposed to build a AI based search system using Retreival Augmented Generator(RAG) so that anyone who wants to search about a particular domain can search any question related to it and get correct response

## Table of Contents
* [General Info]
* [Technologies Used]
* [Procedure/Steps]
* [Conclusions]
* [Acknowledgements]

## General Information
- Provide general information about our group project here.
- The main goal of the case study is to build RAG models to generate correct response by building a prompt. By doing this, people can get info about what they actually want.
  
- What is the business problem that your project is trying to solve?
- It is the problem about agriculture, which is the main business in India. so we will build a  crop recommendation AI System for the farmers so that they can search for any problem related to agriculture and crops as per their requirements

- What is the dataset that is being used?
- i have used crop_recommendation dataset here which is taken from kaggle platform and consist of 8 features of crops including climatic conditions, area, temp, wind, soil type, etc

## Technologies Used
- Python - version 3.9

## Procedure/Steps
- Basically we have used RAG to build our project. mainly 3 layers are performed in the whole project-
  1. The Embedding Layer - here documents is processed, cleaned and chunked for embeddings and a model is selected using Huggingface 
  2. The Search Layer - tested the system by generating some queries, embed the queries, searched the chromadb vector db and implemented cache
  3. The Generation Layer - final response system generated, queries asked and received answers for those queries, based on data
     
## Conclusions
- generation of answers when different types of queries are asked and output is recorded and screenshots taken. you can access them through a fle or documentation attached to it.

## Acknowledgements
- This project"s aim was inspired by Upgrad(IIIT Bangalore) and final selection of model was done by me to select crop dataset.
