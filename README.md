# AI-Powered Travel Itinerary Assistant

## Overview
This project is an AI-based travel planning system that creates a complete and organised itinerary for the user. Instead of simply listing activities, the system reads the travel details, checks for mistakes like overlapping timings or unrealistic schedules, and then fixes them automatically. The goal is to build something that feels like a small travel-planning team working together to create a clean and conflict-free itinerary.

The project uses LangChain, structured outputs, and a step-by-step workflow to manage how the travel plan is processed. Each part of the notebook adds a new piece of logic, starting from setting up the environment, defining the data structures, generating the itinerary, resolving conflicts, and finally presenting a proper breakdown.

## Reason for picking up this project
I chose this project because I wanted to learn how AI can solve real problems that people face while planning trips. It also helped me understand structured outputs, prompt design, and how to build a complete working system from start to finish. My reasons were:
- To learn how to manage a full workflow where each step builds on the previous one  
- To understand how AI detects and fixes mistakes logically  
- To explore how LangChain handles structured data  
- To create something simple, practical, and easy for anyone to use  
- To get hands-on experience with organising code into meaningful stages  

## Video Summary Link
https://drive.google.com/drive/folders/1e5cdSPml8jYzQlQyLjRC424z12veEUtU?usp=sharing

## Plan
I plan to execute these steps to complete my project:

[DONE] Step 1: Project Initialization & Environment Setup    
This step prepares the notebook, installs dependencies, and sets up the environment needed for the system to run.

[DONE] Step 2: Secure API Configuration & System Access   
This step adds the API key configuration so the AI model can be used safely inside the notebook.

[DONE] Step 3: Defining Structured Data Models for Itinerary Planning    
This step introduces the Pydantic models that control and validate the format of the itinerary data.

[DONE] Step 4: Initialising the AI Model for Travel Reasoning    
This step loads and configures the AI model that will analyse and generate the trip itinerary.

[DONE] Step 5: Utility Logic for Checking and Cleaning Travel Data    
This step adds helper functions that support conflict detection, formatting, and reasoning.

[DONE] Step 6: Core Itinerary Planning Engine    
This step contains the main logic that creates the structured travel itinerary using the AI model.

[DONE] Step 7: User Input Layer & Itinerary Generation Interface    
This step allows the user to enter their trip details and receive a generated itinerary.

[DONE] Step 8: Conflict Resolution & Final Cost Breakdown Output    
This step displays how conflicts were fixed and shows the final cost breakdown for clarity.

## Conclusion
My aim in this project was to build a travel assistant that understands a user’s trip details and produces a clear and corrected itinerary. After working through each step, I feel the project successfully shows how AI can improve planning by checking for errors and presenting information in a structured way.

Overall, this project helped me understand how to divide a task into stages, how AI models can support real-life use cases, and how to make a complete system starting from setup and ending with a final polished output.