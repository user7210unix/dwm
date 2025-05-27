# dwm

<img src="image.jpg" align="center" alt=" Preview" width="1050" style="display: block; margin: 32px auto; border: 2px solid #555; border-radius: 12px; box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);">


**Wget** all the above fonts (and extract if archived). Then, put them as instructed into the `~/.fonts` directory.

```bash
mkdir -pv ~/.fonts/
```

---

```bash
wget --no-hsts -cNP ~/.fonts/ https://github.com/ryanoasis/nerd-fonts/releases/download/v3.4.0/LiberationMono.zip && cd ~/.fonts && unzip LiberationMono.zip && fc-cache -vf && cd && clear  
```
