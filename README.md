# zero-day-fundamentals
This repository is a collection of projects to build the necessary skills in the evolving world of networking and software engineering with the rise of AI and other technological advances. You will use AI as a force multipler for your production and to speed up your learning.

It provides a comprehensive 16-week plan is divided into four phases, each focusing on hands-on projects in networking, operating systems, infrastructure, and cyber operations. The projects assumes use with a MacBook (with Parallels for VMs) and emphasize terminal-based workflows. Each week’s project includes a title, summary, tools/concepts, step-by-step instructions, theory explanations, example commands, documentation guidance, and optional extensions. The goal is to spend about 6–12 hours per week on each project (adjustable by depth) and document everything in a GitHub repository (including code, scripts, markdown notes, and screenshots).

This repository documents the steps for each project as well as a review of key learnings along the way.

## Plan Overview

### Phase 1: Core Systems Weeks 1–4
**OS fundamentals, environment setup, scripting, VMs, basic services**

**Focus:** Build a strong foundation in operating system usage, command-line tools, and local virtualization. These projects will ensure your environment is set up for productivity and that you understand core system concepts. You’ll use Parallels to run Linux VMs on your Mac and practice shell scripting and basic service setup. By the end of Phase 1, you will have a customized terminal environment, an Ubuntu server VM, experience with containers, and automation scripts – all documented on GitHub.


### Phase 2: Infrastructure & Networking Weeks 5–8
**Network engineering, cloud infrastructure, IaC, monitoring**

**Focus:** Building on the OS and tooling fundamentals, Phase 2 transitions into designing and managing infrastructure. You will handle networking both locally (between VMs or devices) and in the cloud, use Infrastructure as Code (IaC) tools to provision resources, set up monitoring on a larger scale, and implement automation in deployment pipelines. The projects simulate real-world scenarios like setting up a small network, deploying servers on AWS/GCP, configuring a monitoring stack (Prometheus/Grafana), and practicing automation with CI/CD or configuration management. By tying into your Cosmos work, these could include setting up infrastructure that a validator might use (like sentry nodes, monitoring dashboards for chain metrics, or an automated deployment of node upgrades). Each week continues the pattern of hands-on project with documentation.


### Phase 3: Cyber Operations & Security Weeks 9–12
**System hardening, penetration testing, incident response, security tools**

**Focus:** This phase shifts to security – both defending systems and understanding offensive techniques, as well as incident response. You’ll leverage the robust infrastructure and automation skills from earlier phases to secure and test your environment. Projects include hardening a system (locking it down and scanning for vulnerabilities), simulating a penetration test on a target system, performing incident response on logs or memory from a compromised machine, and implementing security automation tools like an IDS or fail2ban. These weeks will likely use platforms like TryHackMe for guided scenarios or use intentionally vulnerable setups to practice. The outputs will be in-depth reports (with commands and findings) much like a security assessment or incident report, along with scripts or configs for any tools deployed (like fail2ban rules or Snort config). Documentation and clear explanation of each step remain crucial.


### Phase 4: AI-Augmented Systems Weeks 13–16
**Integrating AI into ops, AI-assisted scripting, anomaly detection, AI for infra**

**Focus:** In the final phase, you will explore how artificial intelligence and machine learning can assist in systems administration, infrastructure management, and cyber operations. This is a forward-looking set of projects to experiment with AI tools that can automate tasks, analyze complex data (like logs and metrics) for insights, and even interact with your systems via natural language. You will integrate AI APIs (such as OpenAI’s GPT) for scripting and troubleshooting, implement a basic anomaly detection on system metrics using machine learning, use AI to generate or validate infrastructure as code, and build a conversational assistant that can summarize system status or recommend actions. These projects are a bit more exploratory, aiming to demonstrate what’s possible as AI becomes part of DevOps (“AIOps”). By the end, you’ll have a taste of how AI can augment your workflow — for example, a chatbot that can answer “Is my validator healthy?” by aggregating data, or scripts that auto-tune or fix issues based on AI suggestions.

