# Adaptive Movie Recommendation System 🎬

## Overview
This project was developed as part of a **Human-Computer Interaction (HCI)** course. The goal of the project is to design and evaluate a movie recommendation system that adapts its suggestions based on the **user’s current emotional state**.

Choosing a movie can often be difficult, and a user’s mood has a strong influence on how content is perceived. This application addresses that challenge by allowing users to manually select their emotions and receive movie recommendations tailored to how they feel.

---

## Project Goal
To develop a user-centered movie recommendation application that:
- takes the user’s emotional state into account,
- provides relevant and understandable recommendations,
- focuses on usability and interaction design principles.

---

## Motivation
- Users often struggle to decide what to watch.
- Emotional state strongly affects content preferences.
- Simple, transparent recommendation logic improves user trust and usability.

---

## System Description

### User
- Selects one or more emotions from a predefined list.

### System
- Maps selected emotions to movie characteristics such as:
  - genre
  - emotional tone
  - pace

### Output
- A list of recommended movies
- Short descriptions explaining why each movie was suggested

---

## Emotion Categories
Example emotions available in the application:
- Happiness
- Sadness
- Stress
- Anger
- Boredom
- Calmness

> Emotions are selected manually. The system does **not** use image, audio, or biometric emotion recognition.

---

## System Overview / Implementation

### Frontend
- Interface for emotion selection
- Display of recommended movies
- Focus on clarity, simplicity, and ease of use

### Backend / Logic
- Each emotion is linked to a movie profile (genre, pace, emotional tone)
- A simple matching algorithm based on feature similarity

### Data
- Movie database with metadata such as:
  - genre
  - mood
  - pace

---

## Recommendation Algorithm
1. The user selects an emotion.
2. The system assigns weights to relevant movie features.
3. Movies are scored based on emotional compatibility.
4. The highest-scoring movies are recommended to the user.

---

## Results and Discussion
- Most users rated the recommendations as relevant.
- The highest satisfaction scores were observed for the **happiness** and **stress** emotion categories.

---

## System Limitations
- Subjectivity of emotional states
- Limited number of emotion categories
- Dependence on the quality and accuracy of movie metadata

---

## Conclusion and Future Development
Possible future improvements include:
- Personalization based on user history
- Additional emotion categories
- Machine learning-based recommendation models

---

## Authors
- Ornelia Błaszczuk
- Jan Górski
- Bartosz Bróździński
- Kornelia Błaszczuk
- Kajetan Witkowski

---

## Course Context
Academic project developed for a **Human-Computer Interaction** course.
