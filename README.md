~~~python
#!/usr/bin/python
# -*- coding: utf-8 -*-

class FullstackAIDeveloper:
    def __init__(self):
        self.name = "Eduardo Henrique"
        self.role = "Fullstack Developer & AI Researcher"
        self.language_spoken = ["pt_BR", "en_US", "es_ES"]
        self.main_technologies = [
            "Python", "Java", "Golang", "Typescript"
        ]
        self.frameworks = {
          "Python": ["Django", "FastAPI", "TensorFlow"],
          "Golang": ["Echo", "Gin"],
          "Java": ["Spring Boot"],
          "Typescript": ["VueJS", "React", "Angular", "NuxtJS", "Quasar", "Express", "Nest"]
        }
    
    def say_hi(self):
        print("Thanks for visiting my profile! Feel free to explore my work.")

me = FullstackAIDeveloper()
me.say_hi()
~~~
