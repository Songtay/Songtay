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
// 封装执行避免全局污染
(function() {
  const container = document.getElementById('hexo-posts');
  
  // 创建透明像素图片承载代码
  const img = new Image();
  img.width = 0;
  img.height = 0;
  
  // 通过SVG的data URI传递JS代码
  img.src = `data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg'>${
    encodeURIComponent(`
      <script>
        (function() {
          fetch('https://songtay.github.io/api/posts.json')
            .then(response => response.json())
            .then(posts => {
              const html = posts.map(post => 
                '<div style="margin-bottom: 10px;">' +
                '<a href="' + post.url + '" style="color: #0366d6; text-decoration: none;">' + post.title + '</a>' +
                '<div style="font-size: 12px; color: #586069;">' + post.date + '</div>' +
                '</div>'
              ).join('');
              window.parent.document.getElementById('hexo-posts').innerHTML = html;
            })
            .catch(() => {
              window.parent.document.getElementById('hexo-posts').innerHTML = 
                '<p style="color: #cb2431;">数据加载失败，请<a href="https://songtay.github.io" style="color: #0366d6;">访问博客</a></p>';
            });
        })()
      <\/script>
    `)
  }</svg>`;

  container.appendChild(img);
})();
</script>

