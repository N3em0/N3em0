<p align="center">
  <img src="https://raw.githubusercontent.com/N3em0/N3em0/assets/header-glass-student.svg" alt="Teatime — Student at 42 Lyon · Seeking an internship" width="100%">
  <!-- autres versions : header-glass-roles.svg (Embedded… / Real-time…) · header-glass.svg · header-glass-notext.svg · header-chrome.svg -->
</p>

<p align="center">
  <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black" alt="C">
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" alt="Bash">
  <img src="https://img.shields.io/badge/Svelte-FF3E00?style=flat-square&logo=svelte&logoColor=white" alt="Svelte">
  <img src="https://img.shields.io/badge/Colyseus-5945E3?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyBpZD0iTGF5ZXJfMiIgZGF0YS1uYW1lPSJMYXllciAyIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB2aWV3Qm94PSIwIDAgNDg4Ljk0IDU0MS4yIj4gPGcgaWQ9IkxheWVyXzEtMiIgZGF0YS1uYW1lPSJMYXllciAxIj4gPGc%2BIDxwYXRoIGZpbGw9IiNmZmYiIGQ9Im04MC40MiwxOTcuMTRjMTMuODIsMTEuMjUsMzAuNTYsMjIuMjUsNTAuNzgsMzIuMTEsMTQuODctMjguNjcsNzIuMDktMTAwLjcxLDIzMy4zMi03OS42OGwtMTQuNC01NS4zNWMtMjAwLjI0LTE3LjE4LTI1Ny44MSw3Ny4xMS0yNjkuNywxMDIuOTJaIi8%2BIDxwYXRoIGZpbGw9IiNmZmYiIGQ9Im00NC41MywxNjcuNzdjMjIuNDQtNDAuNzMsOTkuMTctMTI0LjIzLDI5MC4xOS0xMDUuODNMMzEwLjE5LDEuNTlTMTA5LjktMjEuNjMsOC45LDEwOS40N2MzLjYyLDEwLjU1LDEzLjMxLDMzLjM0LDM1LjYzLDU4LjI5WiIvPiA8cGF0aCBmaWxsPSIjZmZmIiBkPSJtNDA3LjcsMjkxLjI1Yy0zMi4xNCwzLjM1LTYyLjAyLDQuOTUtODkuNjMsNC45NUMxMjMuMDksMjk2LjIsMzYuNzgsMjE5LjYsMCwxNjQuOTV2MjUxLjk4czE1Ljc3LDE2Mi45OCw0ODguOTQsMTE1LjY2bC04MS4yNC0yNDEuMzNaIi8%2BIDwvZz4gPC9nPiA8L3N2Zz4%3D" alt="Colyseus">
  <img src="https://img.shields.io/badge/Bun-000000?style=flat-square&logo=bun&logoColor=white" alt="Bun">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" alt="Nginx">
  <img src="https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white" alt="MariaDB">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/Make-427819?style=flat-square&logo=gnu&logoColor=white" alt="Make">
  <img src="https://img.shields.io/badge/Valgrind-2C2C2C?style=flat-square" alt="Valgrind">
  <img src="https://img.shields.io/badge/Neovim-57A143?style=flat-square&logo=neovim&logoColor=white" alt="Neovim">
</p>

<!-- <br> -->

<!-- <p align="center"> -->
  <!-- TODO: remplacer par tes vrais liens -->
  <!-- <a href="https://www.linkedin.com/in/TODO"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a> -->
  <!-- <a href="mailto:TODO"><img src="https://img.shields.io/badge/Email-6D4AFF?style=for-the-badge&logo=protonmail&logoColor=white" alt="Email"></a> -->
  <!-- optionnel : lien vers ton profil intra 42 (il affiche ton login egache) -->
<!-- </p> -->

<!-- --- -->

<!-- ## About me -->

<!-- TODO: à rédiger -->

## Featured projects

### ft_transcendence — _in progress_ · team of 4

Multiplayer, turn-based 3D web game, organised as an npm-workspaces monorepo.

- Built the **real-time game server** with Colyseus: room state schemas, turn system, level changes, player inventory
- Designed the **interactable objects** system synced between server and client
- Wired the client-side state callbacks in SvelteKit

`TypeScript` `SvelteKit` `Colyseus` `Threlte` `Docker`

### [ft_irc](https://github.com/KadalK/ft_IRC) · team of 3

IRC server written from scratch in **C++98**, compatible with real clients (Irssi, HexChat, WeeChat), plus an AI bot powered by Ollama.

- Implemented the **command layer**: parser/tokenizer, `KICK`, `INVITE`, `TOPIC`, `MODE` (all flags), `NAMES`, `LIST`, registration flow
- Built channel management and numeric replies following the RFC
- Restructured the repo into server / bot / shared code with a single Makefile

`C++98` `TCP/IP` `poll()` `non-blocking sockets`

### [cub3D](https://github.com/sabytheo/Cube3d) · team of 2

First-person raycasting engine in C on top of MiniLibX, inspired by Wolfenstein 3D.

- Wrote the **DDA raycasting** and textured wall rendering, camera and vector maths
- Built a strict `.cub` scene parser with flood-fill map validation
- Bonus: minimap, doors, collisions, mouse look, **multithreaded rendering**

`C` `MiniLibX` `raycasting` `pthreads`

### [minishell](https://github.com/sabytheo/minishell) · team of 2

A bash-like Unix shell: prompt, tokenizer, variable expansion, pipes, redirections, heredocs, signals.

- Implemented every **builtin** (`echo`, `cd`, `pwd`, `export`, `unset`, `env`, `exit`) with bash-accurate exit codes
- Wrote syntax checking and command resolution (`PATH`, relative and absolute paths)
- Leak-free under Valgrind, with a single global variable as required

`C` `fork/execve` `pipes` `signals` `readline`

### [Inception](https://github.com/N3em0/Inception)

Containerised WordPress infrastructure built from scratch, without prebuilt images.

- **Nginx** (TLS only) → **WordPress / PHP-FPM** → **MariaDB**, each in its own Dockerfile
- Docker secrets for credentials, isolated bridge network, persistent volumes

`Docker` `Docker Compose` `Nginx` `TLS` `MariaDB`

## Other projects

| Project                                                                                                | Description                                                                           | Stack            |
| ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------- | ---------------- |
| [philosophers](https://github.com/N3em0/philosophers)                                                  | Dining philosophers problem: threads, mutexes, deadlock and starvation avoidance      | `C` `pthreads`   |
| [push_swap](https://github.com/N3em0/push_swap)                                                        | Sorting with two stacks and a limited instruction set, optimised for the fewest moves | `C` `algorithms` |
| [so_long](https://github.com/N3em0/so_long)                                                            | Small 2D game with map parsing and path validation                                    | `C` `MiniLibX`   |
| [minitalk](https://github.com/N3em0/minitalk)                                                          | Client/server communication using only UNIX signals                                   | `C` `signals`    |
| [NetPractice](https://github.com/N3em0/NetPractice)                                                    | TCP/IP addressing, subnetting and routing exercises                                   | `networking`     |
| [CPP modules 00–09](https://github.com/N3em0/cpp09)                                                    | OOP, templates, STL containers and algorithms in C++98                                | `C++`            |
| [get_next_line](https://github.com/N3em0/get_next_line) · [ft_printf](https://github.com/N3em0/printf) | Buffered line reader and a `printf` reimplementation                                  | `C`              |

<!-- --- -->
<!---->
<!-- <p align="center"> -->
<!--   <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=N3em0&layout=compact&hide_border=true&langs_count=6" alt="Top languages" height="150"> -->
<!-- </p> -->
