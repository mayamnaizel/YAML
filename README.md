# 🧠 YAML Complete Guide – From Basics to Advanced 🧩

Welcome to this **YAML Learning Repository** — a practical, beginner-friendly, and slightly opinionated guide created as part of my DevOps learning journey. Whether you're configuring containers, defining Kubernetes manifests, or automating workflows, **YAML is everywhere** — and this guide will help you master it.

---

## 📘 What This Guide Covers

This repo contains a **complete walkthrough of YAML**, starting from basic syntax and progressing to advanced features used in real-world DevOps workflows.

### ✅ Topics Included:

- 🔤 YAML Syntax 101  
  - Indentation  
  - Comments  
  - Scalars (strings, numbers, booleans)

- 📦 Data Structures  
  - Lists (Sequences)  
  - Dictionaries (Mappings)  
  - Nested structures

- 🔗 Anchors & Aliases  
  - `&` Anchors  
  - `*` Aliases  
  - `<<` Merge key

- 🔁 Overriding Values  
  - How to reuse and modify structures without rewriting everything

- 📄 Multiple Documents in One File  
  - Using `---` to separate resources  
  - Practical use in Kubernetes & CI/CD

- 🔧 Real-World Examples  
  - Docker Compose configs  
  - Kubernetes manifests  
  - CI/CD YAML snippets

---

## 📂 Repository Structure

.
├── YAML_Guide.md # Main guide document
├── examples/
│ ├── docker-compose.yml # Service inheritance example
│ ├── k8s-multi-resource.yaml # Multi-document Kubernetes file
│ └── simple.yaml # Basic YAML syntax examples
└── README.md # You're here!

