### Hi there 👋


# Abdulsamad Yusuf

<h2 align="center">About me</h2>

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
		"- ⚡ Quick bio:":                    "Student and a full stack web developer eager to learn new thimgs.",
		"- 🔭 I’m currently working on":      "",
		"- 🌱 I’m currently learning":        "Django, javascript, Nodejs --- Sharpening my backend End Skills ",
		"- 👯 I’m looking to collaborate on": "javascript and python(Django)",
		"- 🤔 I’m looking for help with":     "Anything related to what I am currently learning 😅",
		"- 💬 Ask me about":                  "Python, javascript, html and css",
		"- 📫 How to reach me:":              "https://twitter.com/seermad21",
	}
}
```
