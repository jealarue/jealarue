# Bio

## About Me
```python
class Bio:
    def __init__(self):
        self.name = "Jesse LaRue"
        self.title = "Aspiring Data analyst"
        self.location = "Nampa, USA"
        self.interests = ["Coding", "Collaboration", "Dog Person", "Video Games"]
        self.sql_certification = "[SQL Certification]([link_to_sql_cert](https://www.freecodecamp.org/certification/JesseRyan81/relational-database-v8))"
        self.d3_certification = "[D3 Certification]([link_to_d3_cert](https://www.freecodecamp.org/certification/JesseRyan81/data-visualization))"


    def describe(self):
        return f"I'm {self.name}, a {self.title} based in {self.location}. I'm passionate about {', '.join(self.interests)}."

my_bio = Bio()
print(my_bio.describe())


