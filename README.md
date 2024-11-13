# **AI-Powered Adaptive Quiz and Flashcard System**

## **Overview**
This project is a personal endeavor to learn the programming language **Elixir** and the basics of **AI/ML implementation** by creating a practical and educational application. The app allows users to upload text-based content (e.g., textbooks, notes, or articles) to generate quizzes and flashcards automatically. It also incorporates adaptive learning features, such as spaced repetition for flashcards and dynamic quiz difficulty adjustment.

## **Goals**
The primary goal of this project is to:
- Learn the **fundamentals of AI/ML integration** in web applications.
- Explore **Elixir and Phoenix** for building scalable, fault-tolerant, and real-time systems.
- Gain experience working with **external AI APIs** (e.g., OpenAI, Hugging Face).
- Practice implementing **adaptive algorithms** like spaced repetition and performance-based question adjustments.
- Build a functional MVP to apply both AI/ML and full-stack development skills.

## **Features (Planned)**
### **MVP Features**
- **Content Upload**: Upload files (e.g., text, PDFs) and extract meaningful data.
- **AI-Generated Quizzes**:
  - Multiple-choice, true/false, and short-answer questions.
  - Immediate feedback on quiz responses.
- **Flashcard System**:
  - Generate flashcards from uploaded content.
  - Spaced repetition for optimized review schedules.
- **Progress Tracking**:
  - Record quiz scores and flashcard review progress.

### **Future Features**
- Advanced analytics dashboard with personalized insights.
- Gamification (badges, streaks, and leaderboards).
- Mobile responsiveness for on-the-go learning.
- Collaboration features for group study sessions.

## **Tech Stack**
### **Core Technologies**
- **Backend**: [Elixir](https://elixir-lang.org/) with [Phoenix Framework](https://www.phoenixframework.org/).
- **Frontend**: Phoenix LiveView (or React, if necessary for complex UI needs).
- **Database**: PostgreSQL for storing user data, quiz/flashcard progress, and uploaded content.
- **AI/ML Integration**: 
  - External APIs (e.g., OpenAI, Hugging Face) for natural language processing and question generation.
  - Spaced repetition algorithms for adaptive flashcards.

### **Other Tools**
- **Testing**: ExUnit for backend tests, Cypress for end-to-end tests.
- **Deployment**: Fly.io or Heroku for hosting the application.

## **How to Run the Project**
> Note: This section will be updated as the project progresses.

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/quiz-flashcard-ai.git
   cd quiz-flashcard-ai
2. Install dependencies:
    ```bash
    mix deps.get
3. Set up the database:
   ```bash
   mix ecto.create
   mix ecto.migrate
4. Start the Phoenix server:
   ```bash
   mix phx.server
6. Open your browser and navigate to http://localhost:4000.


## **Learning Outcomes**
By the end of this project, I aim to:
- Understand how to use external APIs for AI/ML tasks.
- Build real-time features in Elixir using **Phoenix Channels** and **LiveView**.
- Implement basic ML concepts (e.g., spaced repetition, data analysis).
- Gain hands-on experience in designing and deploying full-stack applications.

## **Project Roadmap**
### **Phase I: Planning and Setup**
- Set up the development environment.
- Test integration with AI APIs (e.g., OpenAI).
- Design initial database schema and wireframes.

### **Phase II: MVP Development**
- Implement file upload and parsing.
- Generate quizzes and flashcards using AI.
- Create a simple frontend for quiz and flashcard interactions.

### **Phase III: Advanced Features**
- Add spaced repetition for flashcards.
- Integrate adaptive quiz difficulty.
- Build a user-friendly dashboard for tracking progress.

### **Phase IV: Testing and Deployment**
- Write unit and integration tests.
- Deploy the app to a live environment.
- Collect user feedback for improvements.

## **Contributing**
This is a personal learning project and is not open for contributions at this time. However, feedback and suggestions are always welcome!

## **License**
This project is licensed under the [MIT License](LICENSE).

