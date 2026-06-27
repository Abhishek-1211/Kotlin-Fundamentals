# Kotlin Learning Repository

This repository contains my notes, code snippets, and practice programs while learning **Kotlin**. The initial setup uses **Jupyter Notebook** with the Kotlin kernel for interactive coding, along with **IntelliJ IDEA** for building full-fledged Kotlin applications.

---

# Prerequisites

* Miniconda
* Jupyter Notebook
* Kotlin Jupyter Kernel
* IntelliJ IDEA (Optional, for project-based development)

---

# Installation & Setup

## 1. Install Miniconda

Install **Miniconda** on your system.

You can verify the installation by checking the installation directory:

```bash
/opt/miniconda3
```

> **Note:** The default installation location on macOS/Linux may vary depending on your setup.

---

## 2. Install Jupyter Notebook

Open a terminal and run:

```bash
conda install jupyter
```

---

## 3. Install the Kotlin Jupyter Kernel

Run:

```bash
conda install -c jetbrains kotlin-jupyter-kernel
```

---

## 4. Start Jupyter Notebook

Launch Jupyter using:

```bash
jupyter notebook
```

---

## 5. Create a Kotlin Notebook

Inside Jupyter:

```
File
    └── New Notebook
            └── Kotlin
```

Now you're ready to write and execute Kotlin code interactively.

---

## 6. Opening Jupyter in the Future

Whenever you want to work again:

### Activate the Conda environment

```bash
conda activate
```

Then launch Jupyter:

```bash
jupyter notebook
```

---

# IntelliJ IDEA Setup (Optional)

If you want to build Kotlin applications instead of notebooks:

## 1. Install IntelliJ IDEA

Download and install IntelliJ IDEA Community Edition.

---

## 2. Create a New Project

While creating the project:

* Use **PascalCase** for the project name.
* Avoid spaces in the project name.

Example:

```
HelloWorld
```

---

## 3. Select the SDK

Choose the appropriate **JDK (Java SDK)** during project creation.

---

# Useful Resources

* Kotlin Jupyter Playground Guide:
  https://www.kodeco.com/27470305-create-your-own-kotlin-playground-and-get-a-data-science-head-start-with-jupyter-notebook

---

# Repository Structure

```
.
├── notebooks/      # Kotlin Jupyter notebooks
├── examples/       # Sample Kotlin programs
├── notes/          # Learning notes
└── README.md
```

---

# Goals

* Learn Kotlin fundamentals
* Practice Kotlin syntax
* Explore object-oriented programming
* Learn collections and functional programming
* Build small Kotlin applications
* Prepare for Android and Backend development

---

Happy Learning! 🚀
