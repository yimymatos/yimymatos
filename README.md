# Yimy Matos

<h2 align="center"> Allow myself to introduce myself </h2>

```golang
package main

import (
	"fmt"
)

type Bio map[string]string

func main() {
	for k, v := range GetBio() {
		fmt.Printf("%+v: %+v\n", k, v)
	}
}

func GetBio() Bio {
	return Bio{
		"- ⚡ Quick bio:":                    "A kind of cyberPunk-amateurMusician-traveler-foodLover-gamer-coder-programmer-sportsAficionado",
		"- 🔭 I’m currently working on":      "Cevaldom as a Software Engineer",
		"- 🌱 I’m currently learning":        "Golang, MongoDB, RabbitMQ, K8s, C# (Tech stack from my company) --- Sharpening my Front End Skills for the MERN stack (Personal goal)",
		"- 👯 I’m looking to collaborate on": "AI, Python, Golang and Docker related projects",
		"- 🤔 I’m looking for help with":     "Anything related to what I am currently learning 😅",
		"- 💬 Ask me about":                  "Python, Java, C#, SQL, Software Design & Architecture, Web-Dev and SEO",
		"- 📫 How to reach me:":              "https://github.com/yimymatos",
	}
}
```
