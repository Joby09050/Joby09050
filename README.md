import pypandoc

markdown = r'''<div align="center">

# Hey there, I'm Joby! 👋

### Full-Stack Developer | JavaScript Enthusiast | Lifelong Learner

Building useful things for the web, one line of code at a time.

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=36BCF7&center=true&vCenter=true&width=600&lines=Welcome+to+my+GitHub+profile!;I+love+building+for+the+web;Always+learning+something+new;Turning+ideas+into+code+%F0%9F%9A%80)](https://git.io/typing-svg)

[![GitHub followers](https://img.shields.io/github/followers/YOUR_USERNAME?style=for-the-badge&logo=github&label=Followers)](https://github.com/YOUR_USERNAME)
[![Profile views](https://komarev.com/ghpvc/?username=YOUR_USERNAME&style=for-the-badge&color=blueviolet)](https://github.com/YOUR_USERNAME)

</div>

---

## 🚀 About Me

- 💻 I'm interested in **full-stack web development**.
- 🌱 Currently improving my skills in **React, TypeScript, and C#**.
- 🧠 Exploring **Machine Learning and Artificial Intelligence**.
- 🔧 I enjoy turning ideas into practical projects.
- 📷 Outside coding, I enjoy photography and exploring nature.
- 🎯 My goal: keep learning, keep building, and create technology that helps people.

---

## 🛠️ Tech Stack

### Languages
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=000)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=fff)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=fff)
![C%23](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=fff)

### Frontend
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=fff)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=fff)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

### Backend & Database
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=fff)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=fff)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=fff)

### Tools
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=fff)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=fff)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=fff)

---

## 📌 Featured Projects

> Replace these examples with your own repositories.

<table>
  <tr>
    <td width="50%">
      <h3>📚 Project One</h3>
      <p>A short description of what this project does and the problem it solves.</p>
      <a href="https://github.com/Joby09050">View repository →</a>
    </td>
    <td width="50%">
      <h3>🌐 Project Two</h3>
      <p>A short description of another project, including its most interesting feature.</p>
      <a href="https://github.com/YOUR_USERNAME/PROJECT_TWO">View repository →</a>
    </td>
  </tr>
</table>

---

## 📊 GitHub Dashboard

<div align="center">

<a href="https://github.com/Joby09050">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true" alt="GitHub statistics" />
</a>
<a href="https://github.com/Joby09050">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=tokyonight&hide_border=true" alt="Most used languages" />
</a>

[![GitHub Streak](https://streak-stats.demolab.com?user=YOUR_USERNAME&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

</div>

---

## 🐍 Contribution Activity

<div align="center">

<!-- This animation requires the GitHub Actions workflow described below. -->
![Contribution snake](https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_USERNAME/output/github-contribution-grid-snake.svg)

</div>

---

## 🎯 Currently Learning

- [ ] Strengthening React and TypeScript skills
- [ ] Building full-stack applications
- [ ] Learning Machine Learning fundamentals
- [ ] Exploring practical AI projects

---

## 🤝 Let's Connect

I'm always happy to connect with developers, exchange ideas, and learn together.

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Joby09050)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](YOUR_LINKEDIN_URL)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:YOUR_EMAIL)

<div align="center">

### 💬 A little reminder

**"Great things are done by a series of small things brought together."**

⭐ If you find something useful here, feel free to explore my repositories!

</div>
'''

output_path = "/mnt/data/GitHub_Profile_README.md"
pypandoc.convert_text(markdown, "md", format="md", outputfile=output_path, extra_args=["--standalone"])
print(f"Created: {output_path}")
