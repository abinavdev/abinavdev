class AbinavDev:
    def __init__(self):
        self.name        = "Abinavdev A D"
        self.location    = "Ernakulam, Kerala, India"
        self.degree      = "B.Tech Information Technology @ CUSAT (2023–2027)"
        self.email       = "abinavdevabinav@gmail.com"

        self.stack = [
            "React.js", "Node.js", "Express.js",
            "MySQL", "Python", "JavaScript",
            "HTML", "CSS", "REST APIs"
        ]

        self.currently_learning = [
            "Machine Learning (Supervised Algorithms)",
            "Docker & CI/CD Pipelines",
            "Flutter Mobile Development"
        ]

        self.fun_fact   = "I built a Lost & Found platform — because I kept misplacing things 😄"

    def motto(self):
        return "Build. Break. Learn. Repeat."

me = AbinavDev()
print(me.motto())