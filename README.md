<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Haroon's Profile</title>
<style>
  body {
    font-family: Arial, sans-serif;
    margin: 20px;
    background: #f5f5f5;
  }

  /* Tab styles */
  .tab {
    display: flex;
    border-bottom: 2px solid #ccc;
    cursor: pointer;
    margin-bottom: 20px;
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
    background: white;
    overflow-y: auto;
  }
  .tab-content div {
    display: none;
  }
  .tab-content div.active {
    display: block;
  }

  /* Profile styling */
  .profile img.right {
    float: right;
    margin-left: 20px;
  }
  .profile h1 {
    margin-bottom: 0;
  }
  .profile p {
    margin-top: 5px;
  }
</style>
</head>
<body>

<div class="profile">
  <img class="right" src="https://user-images.githubusercontent.com/74038190/229223263-cf2e4b07-2615-4f87-9c38-e37600f8381a.gif" width="200" alt="Coding">
  <h1>👋 Hi, I'm Haroon</h1>
  <p>🚀 Flutter Developer | Passionate about UI & mobile performance</p>
  <p>📱 Helping devs build better apps with Flutter</p>
  <p>🏢 Working at: Self-employed | 🌍 Based in: Pakistan | UTC+05:00</p>
  <p>📬 Reach me at: ranaharoonwork@gmail.com</p>
</div>

<hr>

<!-- Tab Bar -->
<div class="tab">
  <div class="tab-item active" data-tab="overview">Overview</div>
  <div class="tab-item" data-tab="projects">Projects</div>
  <div class="tab-item" data-tab="skills">Skills</div>
</div>

<div class="tab-content">
  <div id="overview" class="active">
    <h2>Overview</h2>
    <p>Here’s a little about me, my journey as a Flutter Developer, and what I love building.</p>
    <p>Languages & Tools:</p>
    <img src="https://skillicons.dev/icons?i=flutter,dart,firebase,github,git,postman" alt="Skills">
  </div>
  <div id="projects">
    <h2>Projects</h2>
    <p>Some of my recent projects include Flutter apps, API integrations, and mobile UI experiments.</p>
  </div>
  <div id="skills">
    <h2>Skills</h2>
    <ul>
      <li>Flutter & Dart</li>
      <li>Firebase & APIs</li>
      <li>UI/UX Design</li>
      <li>Git & Version Control</li>
    </ul>
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
