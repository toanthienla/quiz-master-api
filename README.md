# Quiz Master API

A fake RESTful API built for the **FER202** course, designed to support the development of quiz-related applications. This project uses **[JSON Server](https://github.com/typicode/json-server)** to simulate API operations for users, contacts, and quizzes.

```json
{
    "users": [
        {
            "id": "user-01",
            "fullName": "User 01",
            "email": "user@example.com",
            "studentId": "STU00001",
            "username": "username123",
            "password": "password123",
            "img": "https://ui-avatars.com/api/?name=User&background=0069ff&color=fff"
        }
    ],
    "contacts": [
        {
            "id": "contact-01",
            "name": "User 01",
            "email": "contact@example.com",
            "message": "This is a placeholder message."
        }
    ],
    "quizzes": [
        {
            "id": "quiz-001",
            "title": "Sample Quiz Title",
            "description": "This is a sample quiz description for placeholder purposes.",
            "number_of_questions": 2,
            "type": "sample-category",
            "questions": [
                {
                    "question": "Sample question 1?",
                    "options": {
                        "A": "Option A",
                        "B": "Option B",
                        "C": "Option C",
                        "D": "Option D"
                    },
                    "correct_answer": "C"
                },
                {
                    "question": "Sample question 2?",
                    "options": {
                        "A": "Option A",
                        "B": "Option B",
                        "C": "Option C",
                        "D": "Option D"
                    },
                    "correct_answer": "A"
                }
                // 👇 Add more questions here
            ]
        }

        // 👇 Add more quizzes here
    ]
}
```
