# Projects

## AI Fitness Trainer (CalHacks)
![AI fitness trainer](assets\img\form_friend.png)  
[DevPost](https://devpost.com/software/formfriend-vbw2et)  
AI personal trainer that provides real-time exercise form analysis and generates personalized workout plans.
Integrated TensorFlow's MoveNet model into a ReactJS web app to track 17 key body joints for 12+ exercises, applying pose estimation techniques to deliver visual feedback and posture correction at 30+ frames per second.
Built a conversational AI coach using Vapi and Google Gemini that generates personalized workout plans tailored to user goals, health conditions, and available equipment, achieving less than 1 second latency.

## Stat 20 Tutor
![Stat 20 Tutor](assets\img\stat20_tutor.png)
[GitHub](https://github.com/tangysaurus/stat-20-tutor)  
AI chatbot agent that helps students study for Stat 20 more effectively. 
Implemented using GraphRAG, which involves using an LLM and Neo4j graph database to create a knowledge graph of course material from UC Berkeley's [Stat 20 online textbook](https://stat20.berkeley.edu/summer-2025/notes.html). When a student asks a question, the agent searches through the knowledge graph to retrieve context, which gets fed to an LLM to generate a response. Uses WolramAlpha's API for mathematical tool calling and OpenAI o4-mini for LLM integration.

## DSP Notetaker
![AI notetaker](assets\img\note_generation (2).png)  
[GitHub](https://github.com/tangysaurus/note-creation)  
AI pipeline for generating summarized notes (outlines, glossaries, quizzes, etc.) from raw lecture transcripts. 
Uses semantic chunking to break up transcripts and GPT-5 for summarization. 
Built during my EdTech internship last Summer, where I worked on an AI notetaker that converts lecture recordings into personalized notes for DSP students.
