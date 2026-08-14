# Arch Linux GitHub Profile Design

## Goal

Turn the GitHub profile README into a compact terminal-style developer profile that feels personal, technically credible, and recognizably retro without looking like Windows.

## Visual Direction

- Use an Arch Linux-inspired shell prompt such as `carsten@arch:~$`.
- Use monospace code blocks as the primary visual device.
- Reference the Atari 800 XL as a personal retro detail.
- Keep humor subtle and relevant to development.
- Avoid Windows prompts, excessive badges, and decorative animation.

## README Structure

1. Terminal-style boot or `fastfetch`-inspired introduction.
2. `cat ~/about.txt` section with a concise personal description.
3. `ls -la ~/projects` section containing three selected repositories and short explanations.
4. `cat ~/status.txt` section for current focus, technologies, and learning goals.
5. `./connect.sh` section for the website and social links.
6. Optional GitHub language or activity statistics at the end, kept visually secondary.

## Content Direction

The profile should communicate that Carsten is a web developer who builds practical web-based solutions and is currently exploring agentic engineering. Existing personal details such as photography, voluntary club work, and Spencer the Sheltie can remain, but should support the profile rather than dominate it.

Example terminal details:

```text
OS:       Arch Linux
Host:     Atari 800 XL -> modern workstation
Shell:    bash
Mission:  Agentic Engineering
Status:   compiling useful ideas
```

Possible jokes include `AUR packages installed: too many`, `System uptime: since the Atari 800 XL`, and `It works on my machine: still investigating`. Use only a few so the README remains readable.

## Constraints

- Preserve the README's existing external links unless they are intentionally changed later.
- Do not rely on JavaScript, custom rendering, or assets that GitHub README rendering may block.
- Keep the page readable on mobile and accessible as plain Markdown.
- Correct obvious content errors while editing, including `GitHub Copilot`.
- Do not make unrelated repository changes.

## Success Criteria

- The first screen immediately presents a Linux-terminal identity.
- The profile has a clear path from introduction to projects to contact links.
- The visual style is Arch/Linux-based with restrained Atari-era humor.
- Featured projects are understandable without opening every repository.
- The README remains useful and readable if terminal styling is ignored.
