<!-- contents of title.svg is from github.com/aeneasr/aeneasr -->
![BraKistad](title.svg)

<div align="center">
    <img src="https://img.shields.io/badge/Open%20Source%20Stats-blueviolet?style=for-the-badge&logo=github" alt="Open Source Stats" />
</div>

<div align="center" style="display: flex; justify-content: center; gap: 30px; margin-top: 20px;">
    <div> 
        <img 
            width="350px" 
            src="https://github-readme-stats.vercel.app/api/top-langs/?username=brakistad&layout=compact&count_weight=0.5&size_weight=0.5&langs_count=9&theme=radical"
        />
    </div>
    <div>
        <img 
            width="450px" 
            src="https://github-readme-stats.vercel.app/api?username=brakistad&show_icons=true&include_all_commits=true&count_private=true&&hide=issues&theme=radical"
        />
    </div>
</div>

<div align="center">
    
⚡ **Creating value in the digital space** ⚡
    
🚀 **Working on large-scale enterprise CloudOps solutions**
    
🎯 **Learning about product development, bringing quality of life to customers**
    
💬 **Ask me about anything. I love to meet people with interests in the digital space**
    
📊 **Passionate about big data and visualizations**
    
</div>

<details>
  <summary>
          Show source...
  </summary>

```bash
cd ~/mind/core/values/
conn_str=$(grep "conn_str" config.env | cut -d '=' -f2)
if [ -z "$conn_str" ]; then
  echo "No VALUES, RUN!"
else
  psql "$conn_str" -c "SELECT * FROM shared_values ORDER BY created_at DESC LIMIT 5;"
fi
```

</details>

