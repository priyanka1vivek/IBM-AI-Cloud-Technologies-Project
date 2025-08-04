# IBM-AI-Cloud-Technologies-Project
IBM AI and Cloud Technologies (with Edunet foundation) project details, files, and PDF file of the project.

Library AI Agent on IBM Cloud
This repository contains the materials for the "Library AI Agent" project, an intelligent system designed to assist students in finding relevant learning materials from a library's database. The agent was built using IBM watsonx.ai.

🚀 Project Overview
The core problem this project solves is the difficulty students face in navigating vast library collections to find books that are directly relevant to their coursework. This AI agent acts as a personalized research assistant, analyzing student queries or syllabus topics to provide context-aware book recommendations from a specific library catalog. This streamlines the research process, enhances resource discovery, and supports academic success.

✨ Key Features
Natural Language Understanding: The agent understands queries written in plain English.

Context-Aware Recommendations: Provides book suggestions based on the specific topics mentioned by the user.

Grounded Knowledge: The agent's knowledge is strictly limited to the provided library catalog, ensuring all recommendations are relevant and available.

Interactive Chat Interface: Users interact with the agent through a simple and intuitive chat preview.

🛠️ Technology Stack
Cloud Platform: IBM Cloud

AI Studio: IBM watsonx.ai

Foundation Model Used: Mistral AI (mistral-large) - Note: This was used as it was featured in the provided demo guide. The official project mandate was to use the IBM Granite series.

Agent Framework: LangGraph with ReAct architecture

Knowledge Base: watsonx.ai Vector Index (In-memory)

💬 How to Use (Example Queries)
Once the agent is set up, you can test it with queries like these in the "Agent preview" pane:

To test a specific topic:

I need a book about the history of humankind.

To test a broader category:

Can you find me something on business or entrepreneurship?

To simulate a syllabus query:

My course covers machine learning, algorithms, and artificial intelligence.

To test its knowledge boundary:

Do you have any books on astrophysics? (The agent should correctly state that it has no matching books).
