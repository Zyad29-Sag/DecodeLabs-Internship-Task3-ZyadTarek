# AI Career & Tech Stack Recommendation System

## Overview

This project is an AI-powered recommendation system that suggests suitable career paths and technology stacks based on a user's skills, interests, and career goals. The system uses content-based recommendation techniques to analyze user input and rank the most relevant career options.

Developed as part of the DecodeLabs AI Internship Program.

---

## Features

- Interactive user interface
- Skill and interest-based recommendations
- Content-based filtering approach
- TF-IDF vectorization
- Cosine similarity scoring
- Jaccard similarity comparison
- Top-N ranked recommendations
- Match percentage calculation
- Skill gap analysis
- Career guidance suggestions

---

## How It Works

### 1. User Input
The user enters:
- Current skills
- Interests
- Career goals

### 2. Data Processing
The system:
- Cleans and preprocesses text
- Converts skill profiles into vectors using TF-IDF
- Computes similarity scores between user profiles and career profiles

### 3. Recommendation Engine
The recommendation engine uses:

#### TF-IDF (Term Frequency-Inverse Document Frequency)
Converts text data into numerical vectors representing the importance of skills and technologies.

#### Cosine Similarity
Measures the similarity between the user's profile and available career paths.

#### Jaccard Similarity
Provides an additional similarity measure based on shared skills.

### 4. Results
The system ranks careers based on similarity scores and displays:
- Recommended careers
- Match percentages
- Matching skills
- Missing skills
- Suggested learning paths

---

## Technologies Used

### Frontend
- HTML5
- CSS3
- JavaScript

### AI & Recommendation Techniques
- Content-Based Filtering
- TF-IDF Vectorization
- Cosine Similarity
- Jaccard Similarity

---

## Project Structure

```text
project/
│
├── tech_stack_recommender_v2.html
├── README.md
└── assets/
```

---

## Example Use Case

### Input

Skills:
- Python
- SQL
- Machine Learning

Interests:
- Artificial Intelligence
- Data Science

### Output

Recommended Careers:
1. Machine Learning Engineer
2. Data Scientist
3. AI Engineer

Along with:
- Match percentage
- Skill gaps
- Learning recommendations

---

## Future Improvements

- User authentication
- Recommendation history
- Collaborative filtering
- Deep learning-based recommendations
- Real-time labor market analysis
- Resume-based recommendations
- Integration with job portals

---

## Learning Outcomes

This project demonstrates:

- Recommendation Systems
- Information Retrieval
- Similarity Metrics
- Feature Engineering
- Content-Based Filtering
- Frontend Development
- AI-Powered Decision Support Systems

---

## Author

**Ziad Tarek**

Computer and Communication Engineering Student  
Alexandria University

---

## DecodeLabs AI Internship

This project was developed as part of the DecodeLabs AI Internship Program to demonstrate the implementation of recommendation system concepts using AI and similarity-based ranking techniques.
