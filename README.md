# Bio

## About Me
```python
class Bio:
    def __init__(self):
        self.name = "Jesse laRue"
        self.title = "Aspiring Data analyst"
        self.location = "Nampa, USA"
        self.interests = ["Coding", "Collaboration", "Dog Person", "Video Games"]

    def describe(self):
        return f"I'm {self.name}, a {self.title} based in {self.location}. I'm passionate about {', '.join(self.interests)}."

my_bio = Bio()
print(my_bio.describe())


