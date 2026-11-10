class YoussefErRadouany:
    def __init__(self):
        self.name = "Youssef Er-Radouany"
        self.field = "Networks & Cybersecurity"
        self.specialization = "Cloud Computing"

        self.skills = [
            "Python",
            "HTML",
            "CSS",
            "JavaScript",
            "Linux",
            "Docker",
            "Networking"
        ]

        self.interests = [
            "Cybersecurity",
            "Cloud Computing",
            "Artificial Intelligence"
        ]

    def introduce(self):
        return "Welcome to my GitHub profile!"

me = YoussefErRadouany()
print(me.introduce())
