# 🐚 Zsh Config

My personal **Zsh + Oh My Zsh + Powerlevel10k** setup.  
Smooth, minimal, and fast shell with useful plugins.

---

## ⚙️ Configuration

Main config file: [`.zshrc`](./.zshrc)  

Key features:
- **Theme**: Powerlevel10k (`p10k`)  
- **Plugins**: `git`, `zsh-autosuggestions`, `zsh-syntax-highlighting`, `web-search`  
- **Instant Prompt** for faster shell startup  
- **Custom aliases & prompt** (editable via `.p10k.zsh`)  

---

## 🚀 Usage

1. Install [Oh My Zsh](https://ohmyz.sh/)  
2. Install [Powerlevel10k](https://github.com/romkatv/powerlevel10k)  
3. Install recommended plugins:  
   ```sh
   git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
   git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
