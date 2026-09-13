# 👋 Hey, I'm Will Hall

🐳 Container wrangler · ⚙️ Automation enthusiast · 📦 Maintainer of far too many Docker images

I spend my days making machines do the boring stuff so humans don't have to — mostly with **Docker**, **Ansible**, **Terraform** and a healthy dose of CI/CD pipelines.

## 🚢 docker-ansible

My flagship project: [**docker-ansible**](https://github.com/willhallonline/docker-ansible) — Ansible inside Docker containers, so you can run your playbooks anywhere Docker runs. ⭐ 470+ stars and counting!

- 🐧 Multiple base images: **Alpine, Ubuntu, Rocky Linux & Debian**
- 📌 Ansible Core **2.16 through 2.21** (older versions still supported)
- 🔄 Regularly rebuilt and published to [Docker Hub](https://hub.docker.com/u/willhallonline/)

Friends of the family:

- 🤖 [docker-ansible-github-action](https://github.com/willhallonline/docker-ansible-github-action) — run Ansible in your GitHub Actions workflows
- 🧪 [docker-ansible-test](https://github.com/willhallonline/docker-ansible-test) — systemd-enabled images for testing roles and playbooks
- ✅ [docker-ansible-github-action-test](https://github.com/willhallonline/docker-ansible-github-action-test) — integration tests for the GitHub Action across the image matrix
- 🔐 [ansible-role-acme_sh](https://github.com/willhallonline/ansible-role-acme_sh) — install acme.sh and issue Let's Encrypt certificates
- 🛠️ [docker-devtools-aliases](https://github.com/willhallonline/docker-devtools-aliases) — shell aliases that swap locally-installed tools for Docker containers ([docs here](https://docker-devtools.gitlab.io))

## 🔭 What I'm working on

- 🐳 Keeping the **docker-ansible** image matrix fresh across distros and Ansible releases, including Alpine 3.23/3.24, Debian Trixie, Rocky Linux 10 and Ubuntu 26.04
- 🩺 Adding healthchecks and keeping the companion test images aligned with the main Ansible releases
- 🤖 Building and testing a GitHub Action that runs playbooks inside the same Docker images locally and in CI
- 🔐 Maintaining Ansible roles for practical infrastructure tasks, including automated TLS certificates with acme.sh
- 🧰 **Docker DevTools** — never install a dev tool locally again

## 🌍 Find me around the web

| | |
|---|---|
| ✍️ Blog | [willhallonline.co.uk/blog](https://www.willhallonline.co.uk/blog) |
| 🐳 Docker Hub | [hub.docker.com/u/willhallonline](https://hub.docker.com/u/willhallonline/) |
| 🐙 GitHub | [github.com/willhallonline](https://github.com/willhallonline) |
| 🦊 GitLab | [gitlab.com/willhallonline](https://gitlab.com/willhallonline) |
| 💼 LinkedIn | [linkedin.com/in/willhallonline](https://www.linkedin.com/in/willhallonline/) |
| 🧰 Docker DevTools | [docker-devtools.gitlab.io](https://docker-devtools.gitlab.io) |

## 📝 Latest from the blog

- 🚀 [Docker Ansible 6.4.8 and the Projects Around It](https://www.willhallonline.co.uk/blog/2026-09-12-docker-ansible-6-4-8-and-the-projects-around-it/)
- 📚 [Documentation in a Post-AI-Agent World](https://www.willhallonline.co.uk/blog/2026-09-12-documentation-in-a-post-ai-agent-world/)
- 📶 [Improving home Wi-Fi: what the tests revealed](https://www.willhallonline.co.uk/blog/2026-08-23-improving-home-wifi-what-the-tests-revealed/)
- 🤖 [Running Docker Ansible with a GitHub Action](https://www.willhallonline.co.uk/blog/2026-08-12-docker-ansible-github-action-and-test-repo/)
- 🧠 [My AI Process, or Am I Hallucinating?](https://www.willhallonline.co.uk/blog/2026-07-28-my-ai-process-or-am-i-hallucinating/)
- 🔥 [Melting Point: What a UK Heatwave Taught Me About My Homelab](https://www.willhallonline.co.uk/blog/2026-07-13-melting-point-the-heatwave-and-my-homelab/)

---

> 💡 *"Why install it locally when you can `docker run` it?"*
