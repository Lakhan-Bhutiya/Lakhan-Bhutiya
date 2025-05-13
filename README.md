class man:
    def __init__(self, name, age, role, tools, goals):
        self.name = name
        self.age = age
        self.role = role
        self.tools = tools
        self.goals = goals

lakhan = man(
    name="Bhutiya Lakhan",
    age=20,
    role="Machine Learning Enthusiast",
    tools={
        "machine": "Asus vivobook pro 15(16gb ram,512gb storage)",
        "os": "Windows",
        "editor": "VS Code + Jupyter",
        "languages": "Python, SQL",
        "libraries": "NumPy, pandas, scikit-learn, TensorFlow"
    },
    goals=[
        "Contribute to open source",
        "Build an ML project (medical prediction app)",
        "Level up in data visualization",
        "Craft a standout LinkedIn + GitHub presence"
    ]
)

lakhan.introduce()
