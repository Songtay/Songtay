👋 Hi, I'm Songtay

- 🔭 目前正在开发: [https://github.com/dotnet/aspire] 
- 🌱 正在学习: Python/React/AI  
- 📫 联系我: songtao.yu.mail@qq.com  
- 😄 趣事: 我爱咖啡和猫咪！

<img src="https://github-readme-stats.vercel.app/api?username=Songtay&show_icons=true&theme=radical" />



![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### 🛠️ Tech Stack
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

### 📊 GitHub Stats
![GitHub Followers](https://img.shields.io/github/followers/Songtay?style=social)
![GitHub Stars](https://img.shields.io/github/stars/Songtay?style=social)

### 📅 GitHub Contributions
![GitHub Contributions](https://ghchart.rshah.org/Songtay)

### 💬 Random Quote
<!-- QUOTE:START -->
> "The best way to predict the future is to invent it." — Alan Kay
<!-- QUOTE:END -->

## 📝 Blogs
## 📝 最新文章
<div id="hexo-posts">加载中...</div>
<script>
// 封装为立即执行函数避免污染全局
(() => {
  const container = document.getElementById('hexo-posts');
  
  // 创建隐藏的图片元素触发请求
  const trigger = document.createElement('img');
  trigger.style.display = 'none';
  
  // 通过 data: URI 传递函数
  trigger.src = `data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg'>${
    encodeURIComponent(`
      <script>
        (async () => {
          try {
            const res = await fetch('https://songtay.github.io/api/posts.json');
            const posts = await res.json();
            parent.document.getElementById('hexo-posts').innerHTML = posts.map(p => 
              \`<p><a href="\${p.url}" target="_blank">\${p.title}</a><br>
              <small>\${p.date}</small></p>\`
            ).join('');
          } catch(e) {
            parent.document.getElementById('hexo-posts').innerHTML = '加载失败';
          }
        })()
      <\/script>
    `)
  }"></svg>`;

  container.appendChild(trigger);
})();
</script>

