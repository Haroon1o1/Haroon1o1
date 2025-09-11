<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Tab Bar Example</title>
<style>
  body {
    font-family: Arial, sans-serif;
    margin: 50px;
  }
  .tab {
    display: flex;
    border-bottom: 2px solid #ccc;
    cursor: pointer;
  }
  .tab div {
    padding: 10px 20px;
    margin-right: 5px;
    border: 1px solid transparent;
    border-radius: 5px 5px 0 0;
    transition: background 0.3s;
  }
  .tab div.active {
    background: #007bff;
    color: white;
    border-color: #007bff #007bff #fff #007bff;
  }
  .tab-content {
    border: 1px solid #ccc;
    border-top: none;
    height: 400px;
    padding: 20px;
  }
  .tab-content div {
    display: none;
    height: 100%;
  }
  .tab-content div.active {
    display: block;
  }
</style>
</head>
<body>

<div class="tab">
  <div class="tab-item active" data-tab="overview">Overview</div>
  <div class="tab-item" data-tab="projects">Projects</div>
  <div class="tab-item" data-tab="skills">Skills</div>
</div>

<div class="tab-content">
  <div id="overview" class="active">
    <h2>Overview</h2>
    <p>This is the overview content.</p>
  </div>
  <div id="projects">
    <h2>Projects</h2>
    <p>These are your projects.</p>
  </div>
  <div id="skills">
    <h2>Skills</h2>
    <p>These are your skills.</p>
  </div>
</div>

<script>
  const tabs = document.querySelectorAll('.tab-item');
  const contents = document.querySelectorAll('.tab-content div');

  tabs.forEach(tab => {
    tab.addEventListener('click', () => {
      tabs.forEach(t => t.classList.remove('active'));
      tab.classList.add('active');

      contents.forEach(c => c.classList.remove('active'));
      document.getElementById(tab.dataset.tab).classList.add('active');
    });
  });
</script>

</body>
</html>





### 👋 Hi, I'm Haroon

🚀 Flutter Developer | Passionate about UI & mobile performance 
📱 Helping devs build better apps with Flutter  

---

🏢 **Working at**: I'm Self-employed  
🌍 **Based in**: Pakistan | UTC+05:00  
📬 **Reach me at**: ranaharoonwork@gmail.com  

---

### 🌐 Connect with me:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/haroon-naeem-77417025a/)

[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/fahad_961)

---

### Languages and Tools:
[![My Skills](https://skillicons.dev/icons?i=flutter,dart,firebase,github,git,postman)](https://skillicons.dev)
<br><br>

![Haroon's GitHub stats](https://github-readme-stats.vercel.app/api?username=haroon1o1&show_icons=true&theme=dark)



<img align="right" alt="Coding" width="400" src="https://user-images.githubusercontent.com/74038190/229223263-cf2e4b07-2615-4f87-9c38-e37600f8381a.gif">
<br><br>




</p>
<p align="center"> 
 <img src="https://komarev.com/ghpvc/?username=JunaidJameel&label=Profile%20views&color=0e75b6&style=flat" alt="JunaidJameel" /> 

</p>


<img src="https://i.imgur.com/dBaSKWF.gif" height="20" width="100%">




- 🔭 I’m currently working on **Flutter**

- 🌱 I’m currently learning **Back-End Dev**

- 💬 Ask me about **Flutter, Dart, Firebase and API**

- 📫 How to reach me **ranaharoonwork@gmail.com**


