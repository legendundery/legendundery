<!-- 🌟 Legendundery: Personal GitHub Home -->

<h1 align="center">👋 Welcome to <span style="color:#4FC3F7">Legendundery’s World</span></h1>

<p align="center">
  <em>Code. Create. Chaos. Repeat.</em>  
  <br>
  <img src="https://media.giphy.com/media/Ll22OhMLAlVDb8UQWe/giphy.gif" width="300"/>
</p>

---

### 🧠 About Me
> _“If it looks like magic, it’s probably just a stack overflow post.”_

💡 **Full-stack tinkerer** — exploring AI, creative coding, and weird projects.  
🛠️ Loves building things that are half genius, half accident.  
🎨 Balancing between design and development.  

---

### ⚙️ Tech Stack

`Python` • `JavaScript` • `TypeScript` • `C/C++`  
`Vue` • `Node.js` • `TailwindCSS` • `Vite` • `OpenAI API` • `sora2(???)`

---

### 📈 GitHub Stats

<div align="center">

<!-- ✅ Commit & Activity Stats -->
![Legendundery's GitHub Stats](https://github-readme-stats.vercel.app/api?username=legendundery&show_icons=true&theme=tokyonight&hide_border=true)

<!-- ✅ Code frequency graph -->
![Contribution Graph](https://github-readme-activity-graph.vercel.app/graph?username=legendundery&theme=tokyo-night&bg_color=0d1117&color=70a5fd&line=70a5fd&point=ffffff&hide_border=true)

<!-- ✅ Streak graph -->
![GitHub Streak](https://streak-stats.demolab.com/?user=legendundery&theme=tokyonight&hide_border=true)

</div>

---

### 🌟 Star Showcase

> _Things I love or find inspiring._

<!-- STAR_SHOWCASE_START -->
  ## 🌟 Star Showcase

  <div align="center" style="display:flex; flex-wrap:wrap; justify-content:center;">
      EOF
      
          # 获取数据并生成卡片
          curl -s -H "Authorization: token $GH_TOKEN" \
            "https://api.github.com/users/legendundery/starred?per_page=6" | \
            jq -r '.[] |
            "<div style=\"width:280px; margin:10px; border-radius:12px; box-shadow:0 2px 8px rgba(0,0,0,0.08); padding:15px; background:#fff; text-align:left; transition:transform 0.2s; display:inline-block; vertical-align:top; overflow:hidden;\" onmouseover=\"this.style.transform=\'scale(1.03)\'\" onmouseout=\"this.style.transform=\'scale(1.00)\'\">
              <a href=\"" + .html_url + "\" target=\"_blank\" style=\"text-decoration:none; color:#0969da;\">
                <h3 style=\"margin-top:0; font-size:16px;\">" + .full_name + "</h3>
              </a>
              <p style=\"color:#555; font-size:13px; min-height:40px;\">" + (.description // "No description") + "</p>
              <p style=\"font-size:12px; color:#888;\">⭐ " + (.stargazers_count|tostring) + "</p>
            </div>"' >> star.md
      
          # 文件结尾
          echo '</div>' >> star.md
<!-- STAR_SHOWCASE_END -->


---

### ✍️ Blog & Writing

📰 **Latest Posts**
<!-- Replace with your blog RSS or manual list -->
- [My First Blog Post](https://yourblog.example.com/post1)
- [Thoughts on Creative Coding](https://yourblog.example.com/post2)
- [Building Tiny Tools That Spark Joy](https://yourblog.example.com/post3)

> _Coming soon: RSS auto-updates via GitHub Actions._

---

### 🌐 Other Cool Places

| 🌍 Site | Description |
|---------|--------------|
| [🧩 My Personal Site](https://yourwebsite.example.com) | Experiments, art, and random code |
| [📚 Dev.to](https://dev.to/legendundery) | Technical blogs & snippets |
| [🪩 Are.na](https://www.are.na/) | Inspiration & visual collections |
| [🐦 Twitter/X](https://twitter.com/) | Shitposts and occasional insights |
| [🎧 Spotify](https://open.spotify.com/) | Coding playlist vibes |

---

### 🧭 Fun Fact
> I commit bugs faster than I fix them.  
> But that’s how great stories (and repos) begin.

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=legendundery&color=blueviolet&style=for-the-badge" alt="Profile views"/>
</div>

---

<p align="center">
  <strong>💬 Thanks for visiting! Come back soon — I might’ve broken something new 😆</strong>
</p>
