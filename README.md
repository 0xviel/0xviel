### About Me

```Python
class Profile:
    def __init__(self):
        self.name = "0xviel"
        self.hobbies = ["Running", "Gym", "Photography"]
        self.age = 20

    def disp_profile(self):
        return {
            "name": self.name,
            "hobbies": self.hobbies,
            "age": self.age,
        }

if __name__ == "__main__":
    profile = Profile()
    print(profile.disp_profile())

```
