# 🎓 DS-GA-1006 Capstone Takeaways

A concise summary of concepts and tools from the **NYU Data Science Capstone Bootcamp**, focusing on workflow, reproducibility, software tools, and high-performance computing (HPC).

---

## 📑 Table of Contents
- [What I Learned](#-what-i-learned)
- [Core Topics](#-core-topics)
  - [Data Science Stack](#-data-science-stack)
  - [Git & Version Control](#-git--version-control)
  - [Python Environments](#-python-environments)
  - [Remote Development](#-remote-development)
  - [NYU Greene HPC & GCP Bursting](#️-nyu-greene-hpc--gcp-bursting)
  - [Singularity Containers](#-singularity-containers)
- [References & Resources](#-references--resources)
- [Author](#-author)

---

## 🧾 What I Learned

This bootcamp provided hands-on experience with the end-to-end data science workflow — from code collaboration and automation to scalable computation on HPC and cloud systems.  

**Key takeaways:**
- Building reproducible ML environments using Conda, Docker, and Singularity  
- Leveraging GitHub and testing workflows for collaboration  
- Developing and debugging efficiently with VSCode and CLI tools  
- Utilizing NYU Greene HPC and Google Cloud Platform (GCP) for large-scale computation  
- Managing containers and GPU jobs with Slurm and Singularity  

---

## 💻 Core Topics

### 🧠 Data Science Stack
- CLI & Shell Scripting for automation  
- Environment Management with Conda, Mamba, and Docker  
- IDE Mastery: VSCode remote debugging and notebook integration  

### 🧩 Git & Version Control
- Version tracking, branching, and collaborative workflows  
- Resource: [MIT Missing Semester – Version Control](https://missing.csail.mit.edu/2020/version-control/)

### 🐍 Python Environments
- Created isolated dependencies using `environment.yml`  
- Shared and reproduced consistent environments across systems  

### 🌐 Remote Development
- Configured SSH key authentication and ProxyJump  
- Connected VSCode and Jupyter to remote HPC or GCP instances  
- Used `tmux`, `htop`, and `nvidia-smi` for performance monitoring  

### ☁️ NYU Greene HPC & GCP Bursting
- Accessed 550+ CPU and 60+ GPU nodes via Slurm  
- Deployed GPU workloads on GCP burst instances  
- Transferred data securely between Greene and GCP using `scp`  

### 🧱 Singularity Containers
- Built HPC-compatible containers without root privileges  
- Reused NVIDIA PyTorch / TensorFlow Docker images  
- Ensured consistent environments across HPC and cloud systems  

---

## 📚 References & Resources
- [MIT Missing Semester (CSAIL)](https://missing.csail.mit.edu/)  
- [Practical Bootcamp Examples – Wenda Zhou](https://github.com/wendazhou/cds-bootcamp)  
- [VSCode Python Tutorial](https://code.visualstudio.com/docs/python/python-tutorial)  
- [AWS Machine Learning Documentation](https://aws.amazon.com/machine-learning/)  

---

## ✍️ Author
**Wenxin Zhang**  
*NYU DS-GA-1006 Capstone Notes (Condensed Edition)*
