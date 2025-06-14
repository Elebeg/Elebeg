## 🎮 Animações 3D Interativas

<div align="center">

### 🐍 Snake Game das Contribuições
![Snake animation](https://raw.githubusercontent.com/Elebeg/Elebeg/output/github-contribution-grid-snake-neon.svg)

### 🏗️ Gráfico 3D de Contribuições
![3D Contribution Graph](https://raw.githubusercontent.com/Elebeg/Elebeg/main/profile-3d-contrib/profile-night-rainbow.svg)

### 💻 Stack Tecnológico 3D
![Tech Stack 3D](https://raw.githubusercontent.com/Elebeg/Elebeg/output/tech-stack-3d.svg)

### 🌆 GitHub Skyline 2024
<img src="https://skyline.github.com/Elebeg/2024" alt="GitHub Skyline" width="800"/>

</div>

---

## 🔧 Como Implementar

Para replicar essas animações no seu perfil:

1. **Crie um repositório com seu nome de usuário** (ex: `Elebeg/Elebeg`)

2. **Adicione os workflows na pasta `.github/workflows/`**:
   - `3d-contrib.yml` - Para o gráfico 3D de contribuições
   - `developer-3d.yml` - Para animações personalizadas

3. **Configure as permissões**:
   - Vá em Settings > Actions > General
   - Marque "Allow GitHub Actions to create and approve pull requests"

4. **Ative o GitHub Pages**:
   - Settings > Pages
   - Source: "Deploy from a branch"
   - Branch: `output`

5. **Execute os workflows**:
   - Actions > Selecione o workflow > "Run workflow"

### 🎯 Personalização Avançada

```yaml
# Personalize as cores da snake
color_snake: "#00d4ff"
color_dots: "#0d1117,#161b22,#21262d,#30363d,#00d4ff"

# Ajuste o tema do gráfico 3D
SETTING_JSON: |
  {
    "type": "normal",
    "color": "rainbow",
    "background": "night"
  }
```

### 🚀 Dicas Pro

- **Atualizações automáticas**: Os workflows rodam automaticamente
- **Múltiplos temas**: Gere versões light/dark das animações  
- **Performance**: Use cache para builds mais rápidos
- **Monitoramento**: Configure notificações de falha

---

<div align="center">
  
  ### 🌟 "Código é poesia em movimento, e animações são sua dança!" 
  
  **Transforme seu perfil GitHub em uma experiência visual única!** ✨
  
</div>