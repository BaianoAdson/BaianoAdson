## Olá me chamo Adson, mas todos me chamam de Baiano. 🙂

- 🔭 ...
- 🌱 Estudando C e HTML.
- 🔗 Contato: adsonsouzameireles731@gmail.com.
- 😄 Pronomes: Ele/Dele.
- ⚡ Fato engraçado: Sou gêmeo(não é signo).

 <div align="center">
  <a href="https://github.com/BaianoAdson">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=BaianoAdson&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=BaianoAdson&layout=compact&langs_count=7&theme=tokyonight"/>
</div>

<div style="display: inline_block"><br>
  <img align="center" alt="HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="C" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg">
  <img align="right" alt="baianogif" height="150em"  src="https://i.pinimg.com/originals/43/ed/fe/43edfe34a6e73a19fb0a03b5e73a7d79.gif">

         # Snake Animation
  - uses: Platane/snk@master
    id: snake-gif
    with:
      github_user_name:BaianoAdson
      svg_out_path: dist/github-contribution-grid-snake.svg
  - uses: crazy-max/ghaction-github-pages@v2.1.3
    with:
      target_branch: output
      build_dir: dist
    env:
      GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
