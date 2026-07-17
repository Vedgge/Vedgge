# Hello, Imperium of Man
## About me 
```cpp
#include <iostream>
#include <string>
#include <vector>

class SoftwareEngineer {
public:
    SoftwareEngineer()
        : name("Facundo Savanco"),
          role("Software Engineer"),
          languages_spoken{"es_ES", "en_US"},
          tech_stack{
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
          },
          hobbies{
              "New Technologies & Frameworks",
              "Gym",
              "D&D",
              "Videogames",
              "Books",
          },
          job_experience{
              "Built and maintained insurance management features with PHP, Symfony, and MySQL.",
              "Performed QA testing to improve product reliability and release quality.",
              "Developed decision and financial engines, payment processor integrations, and API maintenance in Angular apps.",
              "Led a team of five to deliver a collections platform with a Python API layer and third-party credit and dialer integrations.",
              "Developed data ingestion and monitoring services for multi-vendor device data pipelines.",
          } {}

    void greet() const {
        std::cout << "Hey! I'm " << name << ", a passionate " << role << ".\n";
        std::cout << "When I'm not coding, you can find me exploring the realms of "
                  << join(hobbies) << ".\n";
        std::cout << "Thanks for visiting my GitHub profile!\n";
    }

    void show_skills() const {
        std::cout << "My tech stack includes: " << join(tech_stack) << "\n";
        std::cout << "I'm always eager to learn more, so feel free to share your knowledge!\n";
    }

    void show_experience() const {
        std::cout << "Experience I've gained from my jobs:\n";
        for (const auto& item : job_experience) {
            std::cout << "- " << item << "\n";
        }
    }

private:
    std::string name;
    std::string role;
    std::vector<std::string> languages_spoken;
    std::vector<std::string> tech_stack;
    std::vector<std::string> hobbies;
    std::vector<std::string> job_experience;

    static std::string join(const std::vector<std::string>& items) {
        std::string result;
        for (size_t i = 0; i < items.size(); ++i) {
            if (i > 0) {
                result += ", ";
            }
            result += items[i];
        }
        return result;
    }
};

int main() {
    SoftwareEngineer facundo;
    facundo.greet();
    facundo.show_skills();
    facundo.show_experience();
    return 0;
}
```
