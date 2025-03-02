# Quiz-Application-using-Java
---

# Quiz Application 🎯

A Java-based **Quiz Application** that allows users to participate in a quiz, track scores, and manage quiz rules.

## 📌 Features
- **User Authentication**: Users enter their name before starting the quiz (`Login.java`).
- **Quiz Gameplay**: Interactive quiz interface with multiple-choice questions (`Quiz.java`).
- **Game Rules Display**: Before starting, users can review the quiz rules (`Rules.java`).
- **Score Tracking**: Displays the final score after completing the quiz (`Score.java`).
- **Graphical User Interface (GUI)** using **Swing**.

## 🛠️ Technologies Used
- **Java** (JDK 17)
- **Swing** (for GUI)
- **NetBeans IDE** (recommended)
- **Ant Build System** (via `build.xml`)

## 🚀 How to Run
### 1️⃣ Prerequisites
- Install **Java JDK 17 or later**.
- Install **NetBeans IDE** or any Java-supported IDE.

### 2️⃣ Clone the Repository
```sh
git clone https://github.com/yourusername/quiz-application.git
cd quiz-application
```

### 3️⃣ Open in NetBeans
- Open NetBeans.
- Click **File → Open Project**.
- Select the **Quiz Application** folder.

### 4️⃣ Run the Application
- Click **Run → Run Project** (or press `Shift + F6`).

## 📂 Project Structure
```
📦 Quiz Application
 ┣ 📂 src/quiz/application/
 ┃ ┣ 📜 Login.java         # User login system
 ┃ ┣ 📜 Rules.java         # Quiz rules and guidelines
 ┃ ┣ 📜 Quiz.java          # Main quiz logic
 ┃ ┣ 📜 Score.java         # Score tracking system
 ┣ 📜 build.xml            # Ant build script
 ┣ 📜 manifest.mf          # Manifest file for JAR
 ┣ 📜 project.properties   # NetBeans project properties
 ┣ 📜 README.md            # Project documentation
```

## 🎮 Game Flow
1️⃣ **Login**: Users enter their name before proceeding.  
2️⃣ **Rules Display**: Users can view the rules before starting.  
3️⃣ **Quiz**: Users answer multiple-choice questions with a time limit.  
4️⃣ **Score Display**: The application calculates and displays the user's final score.  
5️⃣ **Play Again Option**: Users can choose to restart the quiz.

## 🏆 Future Enhancements
- Add a **database** to store quiz results.
- Implement multiple **quiz categories**.
- Enhance UI with modern design libraries like **JavaFX**.

## 🤝 Contributing
Feel free to contribute! Fork the repository, make changes, and submit a pull request.

## 📜 License
This project is open-source and free to use.

