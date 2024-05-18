<div align=center>
  <img align=left src="https://avatars.githubusercontent.com/u/77496597?v=4" width=72>
  <h3>balkenix</h3>
  <h6>the norwegian scottish dev</h6>
</div>

---

```py
class Balkenix:
    def __init__(self) -> None:
        self.IN_DOUBT = False
        self.favourite_color = "\x1b[31;41m"
        self.favourite_languages = ["Python", "Nix"]
        self.favourite_hobbyist_languages = ["C", "Zig", "Rust", "TypeScript"]
        self.distro = "NixOS"
        pass

    def __str__(self):
        return f"""
            Hello, I am Åsmund Balkesen, a developer in training living in Scotland.
            I love {self.favourite_languages[0]} and {self.favourite_languages[1]},
            but I also use {self.favourite_hobbyist_languages[0]} and
            {len(self.favourite_hobbyist_languages) - 1} other languages from time to time.
        """
```
