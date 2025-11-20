## Hi, I'm Ana!

```python


class AnaDeCordoba:
    def __init__(self):
        self.name = "Ana de Córdoba"
        self.profile = ["Artificial Intelligence Developer", "Data Scientist", "Data Analyst"]
        self.tools = ["Python", "VS Code", "Jupyter"]
        self.MS_certification = "AI-900 Fundamentals and AI-102 Engineer Associate, DP-900 Azure Data Fundamentals, DP-100 Azure Data Scientist Associate"
        self.certifications = "Google AI Essentials, Scrum Fundamentals Certified (SFC)"
        self.linkedin = "https://www.linkedin.com/in/ana-de-cordoba"

    def presentation(self):
        print(f"Hi there! I'm {self.name} and I have the {self.MS_certification} certifications from Microsoft, others like {self.certifications}")
        print(f"My profile includes {self.profile[0]}, {self.profile[1]} and {self.profile[2]}.")
        print("I work with the following tools:")

        for tool in self.tools:
            print(f"- {tool}")

        print(f"You can find me on LinkedIn: {self.linkedin}")

my_profile = AnaDeCordoba()
my_profile.presentation()



```

## Get in touch

- Linkedin: @anadecordoba
