![](https://github.com/Alver-Lin/Alver-Lin/blob/main/Assets/pictures/background.png)


```python
#!/usr/bin/python
# -*- coding: utf-8 -*-

class SoftwareEngineer:
    def __init__(self):
        self.name = "Alver-Lin"
        self.role = "Software Engineer"
        self.language_spoken = ["zh_CN", "en_US"]

        self.current_project = "seeUtoken"
        self.currently_learning = "agenttest"
        self.interests = [
            "Test Development",
            "Artificial Intelligence",
            "Open Source Tools",
            "AI Agent Evaluation",
        ]
        self.open_to_discuss = "AI Agent Evaluation"

    def say_hi(self):
        print("Thanks for dropping by!")
        print("Hope you find some of my work interesting.")

    def now_doing(self):
        print(f"🔭 Working on: {self.current_project}")
        print(f"🌱 Learning: {self.currently_learning}")
        print(f"💡 Interests: {' / '.join(self.interests)}")
        print(f"🤝 Let's talk about: {self.open_to_discuss}")


me = SoftwareEngineer()
me.say_hi()
me.now_doing()
```


