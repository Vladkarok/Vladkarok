# Vladyslav Karpenko

Infrastructure engineer in Lombardy, Italy, moving into DevOps and cloud.

I have ten years in IT. I started in networking, with MikroTik and a Cisco CCNA. From 2020 to July 2026, I was the sole systems administrator at KM Trade. I was responsible for Windows and Linux servers, Proxmox, backups, Zabbix monitoring and the underlying networks. My VMware ESXi experience is with standalone hosts.

I learned Terraform and Ansible on AWS and GCP in a mentored DevOps program. I'm learning Kubernetes and Azure hands-on now.

## Recent projects

I build tools and services with AI coding agents. I define requirements, decide priorities, test user workflows and validate the results. Agents implement the code and handle much of the detailed technical analysis and operations. I use automated tests and independent AI reviews alongside hands-on testing.

- [OSKar](https://github.com/Vladkarok/oskar) is a mouse-first on-screen keyboard for Omarchy/Linux, with touch adaptations. It follows the system keyboard layout and works with native Wayland, XWayland and Chromium applications. I initiated the project and define its features and interaction requirements; agents proposed and implemented the Rust helper and QML interface. I test the keyboard in daily use, with automated tests and VM checks supporting development.
- [email-to-telegram](https://github.com/Vladkarok/email-to-telegram) forwards mail sent to email aliases into Telegram. Cloudflare Email Routing and a Worker receive the mail, and a Docker app on a VPS delivers it. Pushes to main deploy to staging, and version tags deploy to production.
- [tg-audio-dl](https://github.com/Vladkarok/tg-audio-dl) is a Telegram bot that downloads audio from YouTube and SoundCloud. It runs as a rootless container with a read-only filesystem. Pushing a version tag builds the image in GitHub Actions and deploys it.
- [discord-translate](https://github.com/Vladkarok/discord-translate) is a Discord bot that translates a message privately for whoever asked.

## Older repos

- [zabbix](https://github.com/Vladkarok/zabbix) has Zabbix templates, including UPS monitoring through NUT and per-core CPU usage on Linux.
- [tutorials](https://github.com/Vladkarok/tutorials) is where I kept sysadmin notes, like ZFS encryption on Proxmox and a Zabbix install.
- [goaccess-auto-report](https://github.com/Vladkarok/goaccess-auto-report) is a Bash script that pulls web server logs over SSH and builds daily and weekly GoAccess reports.
- [terraform-aws-datainfo](https://github.com/Vladkarok/terraform-aws-datainfo) is a small Terraform module from 2022 that looks up AMI IDs and a Route53 zone for Terragrunt.

## What I'm looking for

Infrastructure, Linux, DevOps or automation/tooling roles where I can contribute my systems experience and keep developing cloud skills. Based in Macherio, open to remote work from Italy or a practical commute in Brianza/Milan, as an employee or on a long-term contract.

English B2, Italian A1 and learning. Authorized to work in Italy.

[LinkedIn](https://www.linkedin.com/in/vladkarok/) · vladyslavkarpenko227@gmail.com
