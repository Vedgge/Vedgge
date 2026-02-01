# Hello, Imperium of Man
## About me 
```python
class SoftwareEngineer:
    def __init__(self):
        self.name = "Facundo Savanco"
        self.role = "Software Engineer"
        self.languages_spoken = ["es_ES", "en_US"]
        self.tech_stack = [
            "PHP (Laravel, Symfony, Lithium, Yii, etc)",
            "Python (Flask, Django, FastAPI)",
            "Java (Spring Boot, Hibernate, JPA, etc)",
            "Go",
            "JavaScript/TypeScript (React, Angular, Vue.js, Next.js, etc)",
            "HTML - CSS (Tailwind, Bootstrap, SASS, etc)",
            "MySQL - PostgreSQL - MongoDB - MariaDB - SQLServer",
            "Git/Github",
            "Docker",
            "Kubernetes",
            "CI/CD (GitLab, GitHub Actions, Jenkins)",
            "API Development (REST, GraphQL, etc)",
            "Cloud-Native Development (AWS, Azure, etc)",
            "Microservices Architecture",
            "Event-Driven Architecture",
            "Domain-Driven Design",
        ]
        self.hobbies = [
            "New Technologies & Frameworks",
            "Chemistry & Other Science Fields",
            "Videogames",
            "Books",
            "Gym",
        ]
        self.job_experience = [
            "Built and maintained insurance management features with PHP, Symfony, and MySQL.",
            "Performed QA testing to improve product reliability and release quality.",
            "Developed decision and financial engines, payment processor integrations, and API maintenance in Angular apps.",
            "Led a team of five to deliver a collections platform with a Python API layer and third-party credit and dialer integrations.",
            "Developed data ingestion and monitoring services for multi-vendor device data pipelines.",
        ]

    def greet(self):
        print(f"Hey! I'm {self.name}, a passionate {self.role}.")
        print("When I'm not coding, you can find me exploring the realms of " + ", ".join(self.hobbies) + ".")
        print("Thanks for visiting my GitHub profile!")

    def show_skills(self):
        print(f"My tech stack includes: {', '.join(self.tech_stack)}")
        print("I'm always eager to learn more, so feel free to share your knowledge!")

    def show_experience(self):
        print("Experience I've gained from my jobs:")
        for item in self.job_experience:
            print(f"- {item}")


facundo = SoftwareEngineer()
facundo.greet()
facundo.show_skills()
facundo.show_experience()
```
