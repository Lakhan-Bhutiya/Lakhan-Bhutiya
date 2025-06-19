### 🧠 About Me

class Human:
     def __init__(self, name, age, role, tools, goals):
     
        self.name = name
        self.age = age
        self.role = role
        self.tools = tools
        self.goals = goals


lakhan = Human(

    name="Bhutiya Lakhan",
    age=20,
    role="Machine Learning Enthusiast",
    tools={
        "Machine": "Asus Vivobook Pro 15 (16GB RAM, 512GB SSD)",
        "OS": "Windows 11",
        "Editor": "VS Code + Jupyter",
        "Languages": "Python, SQL",
        "Libraries": "NumPy, Pandas, Scikit-learn, TensorFlow"
    },
   
)

lakhan.introduce()
