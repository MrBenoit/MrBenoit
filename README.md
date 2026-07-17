<h1 align="center">Hey, I'm Benoit 👋</h1>

<p align="center">
  <i>I build things for the terminal — and occasionally they escape into production.</i>
</p>

<p align="center">
  <a href="https://github.com/MrBenoit?tab=followers">
    <img src="https://img.shields.io/github/followers/MrBenoit?style=for-the-badge&labelColor=1d1e29&color=7aa2f7&label=Followers&logo=github&logoColor=white" alt="Followers">
  </a>
  <a href="https://github.com/MrBenoit?tab=repositories">
    <img src="https://img.shields.io/github/stars/MrBenoit?style=for-the-badge&affiliations=OWNER&labelColor=1d1e29&color=e0af68&label=Stars&logo=github&logoColor=white" alt="Stars">
  </a>
  <a href="https://github.com/STRRL/serverless-github-badges">
    <img src="https://badges.strrl.dev/years/MrBenoit?style=for-the-badge&labelColor=1d1e29&color=56b6ff&label=Years&logo=github&logoColor=white" alt="Years on GitHub">
  </a>
  <a href="https://github.com/STRRL/serverless-github-badges">
    <img src="https://badges.strrl.dev/contributions/all/MrBenoit?style=for-the-badge&labelColor=1d1e29&color=34d399&label=Contributions&logo=github&logoColor=white" alt="Contributions">
  </a>
</p>

<br>

```go
package main

import (
	"fmt"
	"time"
)

type Developer struct {
	Name     string
	Pronouns []string
	Location string
	Born     time.Time
	Stack    []string
	Hobbies  []string
	Now      string
}

// Age считается от даты рождения, а не хранится числом:
// иначе этот README устаревал бы ровно раз в год.
func (d Developer) Age() int {
	years := time.Now().Year() - d.Born.Year()
	if time.Now().YearDay() < d.Born.YearDay() {
		years-- // день рождения ещё не наступил
	}
	return years
}

func main() {
	me := Developer{
		Name:     "Benoit",
		Pronouns: []string{"he", "him"},
		Location: "Moscow, Russia",
		Born:     time.Date(2004, time.June, 16, 0, 0, 0, 0, time.UTC),
		Stack:    []string{"Go", "Python", "PostgreSQL", "TypeScript"},
		Hobbies:  []string{"Coding", "Gaming", "Anime", "Gym"},
		Now:      "building unissh — a TUI for managing VPS fleets over SSH",
	}

	fmt.Printf("%s, %d — %s\n", me.Name, me.Age(), me.Location)
	fmt.Println("Currently:", me.Now)
}
```

<br>

## 🚀 Featured

<table>
  <tr>
    <td width="80" align="center">
      <a href="https://github.com/MrBenoit/unissh"><b>unissh</b></a>
    </td>
    <td>
      <b>Your whole VPS fleet, one keystroke away.</b><br>
      A fast, colourful terminal UI for SSH: live CPU/RAM/disk right in the server list,
      folders, port forwarding, and automatic first-time setup of a fresh VPS —
      with lockout protection.<br>
      <sub>
        <img src="https://img.shields.io/badge/Go-1.26-00ADD8?style=flat-square&logo=go&logoColor=white&labelColor=1d1e29">
        <img src="https://img.shields.io/github/v/release/MrBenoit/unissh?style=flat-square&labelColor=1d1e29&color=34d399">
        <img src="https://img.shields.io/github/stars/MrBenoit/unissh?style=flat-square&labelColor=1d1e29&color=e0af68">
        <img src="https://img.shields.io/badge/coverage-99%25-34d399?style=flat-square&labelColor=1d1e29">
      </sub>
    </td>
  </tr>
</table>

## 📦 Projects

- **[mrbenoit.ru](https://github.com/MrBenoit/mrbenoit.ru)** &nbsp;·&nbsp; my personal website <sub>`TypeScript`</sub>
- **[MatrixCalculator](https://github.com/MrBenoit/MatrixCalculator)** &nbsp;·&nbsp; a simple matrix calculator, written out of boredom <sub>`Python`</sub>

## 🛠 Stack

<p>
  <img src="https://img.shields.io/badge/-Go-1d1e29?style=for-the-badge&logo=go&logoColor=white&labelColor=00ADD8">
  <img src="https://img.shields.io/badge/-Python-1d1e29?style=for-the-badge&logo=python&logoColor=white&labelColor=3776AB">
  <img src="https://img.shields.io/badge/-PostgreSQL-1d1e29?style=for-the-badge&logo=postgresql&logoColor=white&labelColor=4169E1">
  <img src="https://img.shields.io/badge/-TypeScript-1d1e29?style=for-the-badge&logo=typescript&logoColor=white&labelColor=3178C6">
</p>
<p>
  <img src="https://img.shields.io/badge/-JetBrains-1d1e29?style=for-the-badge&logo=jetbrains&logoColor=white&labelColor=000000">
  <img src="https://img.shields.io/badge/-Zsh-1d1e29?style=for-the-badge&logo=gnubash&logoColor=white&labelColor=4EAA25">
  <img src="https://img.shields.io/badge/-Git-1d1e29?style=for-the-badge&logo=git&logoColor=white&labelColor=F05032">
  <img src="https://img.shields.io/badge/-Linux-1d1e29?style=for-the-badge&logo=linux&logoColor=black&labelColor=FCC624">
</p>

## 💻 Setup

<p>
  <img src="https://img.shields.io/badge/MacBook_Pro-M1_Pro-1d1e29?style=for-the-badge&logo=apple&logoColor=white&labelColor=000000">
  <img src="https://img.shields.io/badge/Desktop-Ryzen_7_7800X3D_·_RTX_5070-1d1e29?style=for-the-badge&logo=amd&logoColor=white&labelColor=ED1C24">
</p>

## 📡 Contact

<p>
  <a href="https://t.me/mrbenoit"><img src="https://img.shields.io/badge/-Telegram-1d1e29?style=for-the-badge&logo=telegram&logoColor=white&labelColor=26A5E4"></a>
  <a href="https://discord.gg/5bb3H73deS"><img src="https://img.shields.io/badge/-Discord-1d1e29?style=for-the-badge&logo=discord&logoColor=white&labelColor=5865F2"></a>
  <a href="https://twitter.com/MrBenoit00"><img src="https://img.shields.io/badge/-@MrBenoit00-1d1e29?style=for-the-badge&logo=x&logoColor=white&labelColor=000000"></a>
  <a href="https://www.reddit.com/user/MrBenoit00"><img src="https://img.shields.io/badge/-u/MrBenoit00-1d1e29?style=for-the-badge&logo=reddit&logoColor=white&labelColor=FF4500"></a>
  <a href="https://www.instagram.com/MrBenoit00"><img src="https://img.shields.io/badge/-@MrBenoit00-1d1e29?style=for-the-badge&logo=instagram&logoColor=white&labelColor=E4405F"></a>
</p>
