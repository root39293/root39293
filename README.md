
```python
class Readme:
    def __init__(self, name, website, bio):
        self.name = name
        self.website = website
        self.bio = bio
        self.tech_stack = []
        self.current_focus = {}

    def add_tech_stack(self, tech):
        self.tech_stack.append(tech)

    def set_current_focus(self, learning, exploring):
        self.current_focus = {
            "learning": learning,
            "exploring": exploring
        }

    def introduce(self):
        print(f"Hello, I'm {self.name}.")

    def display_info(self):
        self.introduce()
        print(f"\nAbout Me:")
        print(f"Website: {self.website}")
        print(f"bio: {self.bio}")
        print(f"\nTech Stack: {', '.join(self.tech_stack)}")
        print(f"\nCurrent Focus:")
        for key, value in self.current_focus.items():
            print(f"{key.capitalize()}: {value}")

if __name__ == "__main__":
    faith6 = Readme(
        name="Faith6",
        website="https://faith6.me",
        bio="less code != less bug"
    )

    faith6.add_tech_stack("Python")
    faith6.add_tech_stack("Node.js")
    faith6.add_tech_stack("...")

    faith6.set_current_focus(
        learning="LLM",
        exploring="DevOps"
    )

    faith6.display_info()
```


![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=root39293&show_icons=true&hide_rank=true&include_all_commits=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=root39293&hide=jupyter%20notebook)


