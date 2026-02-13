<!-- contents of title.svg is from github.com/aeneasr/aeneasr -->
![BraKistad](title.svg)
    
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

