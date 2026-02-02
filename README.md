# QuadraMood-P1-
Quadra Mood Journaling App – Technical Project Report
Project Overview
The Quadra Mood Journaling App is an AI-enhanced emotional wellness tool developed as a Grade XII capstone project at The Indian School Bahrain.
 * Objective: Support high school students in monitoring emotional patterns through private, text-based journaling.
 * Core Philosophy: Integrating Natural Language Processing (NLP) with a student-friendly mobile interface to provide emotional insights without compromising user privacy.
AI & Model Architecture
The system utilizes a multi-class text classification model to categorize entries into four emotional quadrants derived from the Circumplex Model of Affect: Energetic, Calm, Tense, and Depressed.
 * Vectorization: Implemented TF-IDF (Term Frequency-Inverse Document Frequency) to capture nuanced linguistic signals.
 * Performance: Achieved a classification accuracy of ~75% on a simulated student-centric dataset.
 * Optimization: Focused on distinguishing "low-arousal" emotions (Calm vs. Depressed) where sentiment overlap is frequent.
Technical Stack
 * Frontend: Developed using MIT App Inventor for a responsive mobile interface.
 * Backend: Powered by Firebase Firestore for secure, authenticated, and private data storage.
 * Visualization: Custom 2D dashboard mapping emotional outputs on a Valence–Arousal grid.
 * Human-in-the-Loop: Features a Manual Override mechanism, allowing users to correct misclassifications and providing a feedback loop for model improvement.
Key Features
 * Insight Engine: Identifies emotional trends (e.g., detecting increased "Tense" entries during exam periods).
 * Pattern Recognition: Links emotional fluctuations to academics, social interactions, or personal stress.
 * Privacy-First Design: Specifically crafted for adolescents who prefer writing thoughts over vocalizing them.
Future Roadmap
 * Named Entity Recognition (NER): Correlating emotional states with specific events, classes, or individuals.
 * Linguistic Nuance: Improving handling of sarcasm and negation, which are common challenges in adolescent journaling.

