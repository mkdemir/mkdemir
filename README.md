# Hello World!

<!--
**mkdemir/mkdemir** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

I'm Mustafa Kaan Demir

## main.go

```go
package main

import "fmt"

type Attributes struct{}

func (a Attributes) Contact() (string, string) {
	twitter := "twitter.com/mkd3mir"
	medium := "medium.com/@mkdemir1"
	return twitter, medium
}

func (a Attributes) Life() (string, string, []string, map[string][]string, []string, []string, []string) {
	company := "Crypttech"
	work := "Cyber Security Engineer"
	langs := []string{"Turkish", "English", "Kazakh"}
	progLangs := map[string][]string{
		"expert":       {"python", "php", "sh", "ps"},
		"intermediate": {"go"},
		"learning":     {"c", "c++", "asm"},
	}
	specialities := []string{"Threat Intelligence", "Incident Response"}
	environment := []string{"vscode", "vim", "visual studio"}
	os := []string{"ubuntu", "windows", "arch linux", "kali linux"}

	return company, work, langs, progLangs, specialities, environment, os
}

func main() {
	attributes := Attributes{}

	twitter, medium := attributes.Contact()
	fmt.Printf("Twitter: %s\nMedium: %s\n", twitter, medium)

	company, work, langs, progLangs, specialities, environment, os := attributes.Life()
	fmt.Printf("Company: %s\nWork: %s\nLanguages: %v\nProgramming Languages: %v\nSpecialities: %v\nEnvironment: %v\nOS: %v\n",
		company, work, langs, progLangs, specialities, environment, os)
}
```

## 👨‍💻 Skills

<p align='center'>
    <a href="https://www.python.org" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40" />
    </a>
    <a href="https://www.php.net" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php" width="40" height="40" />
    </a>
    <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40" />
    </a>
    <a href="https://golang.org" target="_blank" rel="noreferrer"> 
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original.svg" alt="go" width="40" height="40" />
    </a>
    <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40" />
    </a>
    <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40" />
    </a>
    <a href="https://www.elastic.co" target="_blank" rel="noreferrer">
        <img src="https://www.vectorlogo.zone/logos/elastic/elastic-icon.svg" alt="elasticsearch" width="40" height="40" />
    </a>
    <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> 
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40" />
    </a>  
</p>

## 📊 Status

<p align='center'>
    <img src='https://github-readme-stats.vercel.app/api?username=mkdemir&show_icons=true&theme=dark')/>
</p>

<p align="center">
    <img src="https://tryhackme-badges.s3.amazonaws.com/mustafakaandemir.png" alt="TryHackMe">
</p>

<p align='center'>
    <img src='https://github-readme-stats.vercel.app/api/top-langs/?username=mkdemir&layout=compact&theme=dark')/>
</p>
