# Hi Imperium of Man 👋 I'm Facu
## About me 🙋🏻‍♂️
```python
# -*- coding: utf-8 -*-

class FullStackDeveloper:
    def __init__(self):
        self.name = "Facundo Savanco"
        self.role = "Full Stack Developer"
        self.languages_spoken = ["es_ES", "en_US"]
        self.tech_stack = ["Python", "Flask", "Django", "JavaScript/Typescript", "React", "Next.js", "HTML", "CSS/Tailwind"]
        self.hobbies = ["New Technologies & Frameworks", "Chemistry & Other Science Fields", "Videogames", "Books", "Gym"]

    def greet(self):
        print(f"Hello there! I'm {self.name}, a passionate {self.role}.")
        print("When I'm not coding, you can find me exploring the realms of " + ", ".join(self.hobbies) + ".")
        print("Thanks for visiting my GitHub profile. Check out my pinned repos to see some of my recent experimental projects!")

    def show_skills(self):
        print(f"My tech stack includes: {', '.join(self.tech_stack)}")
        print("I'm always eager to learn more, so feel free to share your knowledge!")

facundo = FullStackDeveloper()
facundo.greet()
facundo.show_skills()
```
