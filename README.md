<div align="center">

# 👋 Hi, I'm Aaditya Dandge

### 🛡️ Cybersecurity Student | Network Security | Developer

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=00FF9C&center=true&vCenter=true&width=700&lines=Cybersecurity+Student+%F0%9F%94%90;Network+Security+Enthusiast+%F0%9F%8C%90;Learning+Linux+%26+Python+%F0%9F%90%A7;Building+Security+Projects+%F0%9F%9B%A1%EF%B8%8F;Always+Learning.+Always+Building.+%F0%9F%9A%80" />

<br>

<img src="https://komarev.com/ghpvc/?username=aadityadandge&label=PROFILE%20VIEWS&color=00ff9c&style=for-the-badge"/>

</div>

---

# 🛡️ About Me

I'm **Aaditya Dandge**, an engineering student passionate about **Cybersecurity, Network Security, Programming and IoT**.

I enjoy learning how computer systems and networks work, exploring security concepts, and building projects that help me improve my technical skills.

```text
┌─────────────────────────────────────────────┐
│ 👨‍💻 Name       : Aaditya Dandge             │
│ 🎓 Role       : Cybersecurity Student       │
│ 🔐 Focus      : Cybersecurity                │
│ 🌐 Interest   : Network Security             │
│ 🐧 Learning   : Linux                         │
│ 🐍 Learning   : Python                        │
│ 🤖 Exploring  : IoT & Arduino                │
│ 🚀 Goal       : Become a Cybersecurity Pro   │
└─────────────────────────────────────────────┘
🔐 Cybersecurity
🛡️ Security
� � � �
🌐 Networking
� � � �
💻 Tech Stack
🧑‍💻 Programming
� � � �
🌐 Web
� �
🐧 Tools
� � � �
🤖 IoT
�
📊 GitHub Analytics
�

�
￼
�
￼
�

🔥 Contribution Streak
�

�
￼
�

📈 Contribution Activity
�

�
￼
�

🧠 Cybersecurity Learning Journey
Networking          █████████░░░  Learning
Linux               ████████░░░░  Learning
Python              ███████░░░░░  Learning
Web Security        ██████░░░░░░  Learning
Ethical Hacking     █████░░░░░░░  Exploring
Digital Forensics   ███░░░░░░░░░  Exploring
Cloud Security      ██░░░░░░░░░░  Exploring
🚀 Featured Cybersecurity Projects
Project
Description
🛡️ Cybersecurity Projects
Security and network security experiments
🌐 Network Security Lab
Networking and security learning projects
🔎 Security Tools
Python cybersecurity experiments
🤖 Arduino & IoT
Microcontroller and IoT projects
🌐 Web Security
Web development and security projects
🎯 2026 Goals
🔐 Improve Cybersecurity skills
🌐 Master Computer Networking
🐧 Learn Linux deeply
🐍 Improve Python for Cybersecurity
🔎 Learn Web Application Security
🛡️ Build real-world security projects
🧩 Practice CTF challenges
🚀 Contribute to Open Source
📚 Build a strong cybersecurity portfolio
🧠 Cybersecurity Mindset
�

        🔍 OBSERVE
            ↓
        🧠 ANALYZE
            ↓
        🧪 TEST
            ↓
        🛡️ SECURE
            ↓
        🚀 IMPROVE
Think like an attacker. Build like a defender. 🛡️
�

📚 Currently Learning
�

Cybersecurity • Networking • Linux • Python • Web Security • IoT Security
�

🤝 Connect With Me
�

�
￼ 
�

�

🛡️ Security is not just a skill — it's a mindset.
Keep Learning • Keep Building • Keep Securing 🔐
�
```
🐍 Add the contribution snake
After saving the README, create this file:
.github/workflows/snake.yml
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:
  push:
    branches: [main]

jobs:
  generate:
    permissions:
      contents: write

    runs-on: ubuntu-latest

    timeout-minutes: 10

    steps:
      - name: Generate Snake SVGs
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-snake.svg?palette=github-light&color_snake=0891B2&color_dots=#ebedf0,#a5b4fc,#818cf8,#6366f1,#0891B2
            dist/github-snake-dark.svg?palette=github-dark&color_snake=10B981&color_dots=#2d3343,#4b5563,#7C3AED,#A78BFA,#22D3EE

      - name: Push to output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          build_dir: dist
          target_branch: output
          commit_message: "Update snake animation [skip ci]"
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
The workflow follows the setup guide's recommended Platane/snk approach, including scheduled runs, manual runs, and writing to an output branch. �
GitHub-Profile-Setup-Guide.pdf
Don't put the snake code inside README.md. Put it in .github/workflows/snake.yml. After the Action runs successfully, we can add the snake display to your README. The guide specifically recommends waiting until the Action creates the output branch before adding that image. �
GitHub-Profile-Setup-Guide.pdf
