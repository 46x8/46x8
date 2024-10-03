<div align="center">
  <h1>Welcome to 6cod's Profile! 👋</h1>
  <h2 id="current-time"></h2>

  <h3>Languages & Tools</h3>
  <p>
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white&logoWidth=20" />
    <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white&logoWidth=20" />
    <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white&logoWidth=20" />
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black&logoWidth=20" />
    <img src="https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white&logoWidth=20" />
    <img src="https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white&logoWidth=20" />
    <img src="https://img.shields.io/badge/Lua-2C2D72?style=for-the-badge&logo=lua&logoColor=white&logoWidth=20" />
  </p>
</div>

<script>
  function updateTime() {
    const options = { timeZone: 'America/New_York', hour: '2-digit', minute: '2-digit', second: '2-digit' };
    const easternTime = new Date().toLocaleTimeString('en-US', options);
    document.getElementById('current-time').innerText = `Current Time: ${easternTime} EST`;
  }
  setInterval(updateTime, 1000);
  updateTime();
</script>
