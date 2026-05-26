# 🔬 Agile V™ Framework

### *Verifiable AI-Augmented Engineering - Stop AI Hallucinations with Formal Traceability*

[![Website](https://img.shields.io/badge/Website-agile--v.org-blue)](https://agile-v.org/)
[![Email](https://img.shields.io/badge/Email-info%40agile--v.org-green)](mailto:info@agile-v.org)
[![License](https://img.shields.io/badge/License-CC--BY--SA--4.0-lightgrey)](https://creativecommons.org/licenses/by-sa/4.0/)
[![Stars](https://img.shields.io/github/stars/Agile-V?style=social)](https://github.com/Agile-V)

---

## 🎯 **The Problem**

**AI agents hallucinate.** They generate code without requirements, skip testing, make silent assumptions about hardware, and deploy to production without approval. Great for demos. **Catastrophic for real products.**

## ✨ **The Solution**

The **Agile V™ Framework** transforms unreliable AI agents into **Verifiable Engineering Systems** through:

- ✅ **Formal Traceability** — Every line of code links to `REQ-XXXX` → `ART-XXXX` → `TC-XXXX`
- ✅ **Independent Verification** — Red Team Verifier tests what Build Agent creates (no self-grading)
- ✅ **Hardware Awareness** — Agents validate RAM/CPU/GPU constraints before optimizing
- ✅ **Human Gates** — Evidence Summaries before production deployments (no autonomous releases)
- ✅ **Halt on Ambiguity** — Agents stop and ask when requirements are unclear
- ✅ **Compliance-Ready** — Auto-generates ISO 9001, ISO 27001, GxP artifacts from day 1

---

## 📦 **Core Projects**

### [agile_v_skills](https://github.com/Agile-V/agile_v_skills) ⭐ 38 stars
**Agent Skills Library** - The official collection of 20+ Agent Skills for the Agile V™ framework. Works with Claude Code, Cursor, VS Code, GitHub Copilot.

- 🎯 **20+ specialized skills** covering full product lifecycle
- 🔬 **Formal traceability** (REQ→ART→TC) prevents AI hallucinations
- 🛡️ **Red Team verification** catches what Build Agent misses
- 📋 **Compliance-ready** (ISO 9001, ISO 27001, GxP)
- 🚀 **Multi-platform** (Claude Code plugin, Cursor rules, VS Code skills)

**[→ Explore Agent Skills](https://github.com/Agile-V/agile_v_skills)**

---

### [agentic_agile_v](https://github.com/Agile-V/agentic_agile_v) ⭐ 1 star
**Production-Ready Scaffold** - Template for building verifiable AI-augmented engineering systems with structured briefs, evidence bundles, and CI gates.

- 🏗️ **Project scaffold** with automated traceability
- 📝 **Structured briefs** for requirements engineering
- 📊 **Evidence bundles** for verification
- 🔄 **CI/CD integration** with quality gates
- 🎯 **TypeScript/Node.js** template

**[→ Get Started with Template](https://github.com/Agile-V/agentic_agile_v)**

---

### [local-llm-proxy](https://github.com/Agile-V/local-llm-proxy) ⭐ 1 star
**Local LLM Integration** - HTTPS-to-HTTP proxy for using local/network LLM backends (Ollama, LocalAI, LM Studio) with Agile V Studio.

- 🔌 **Local LLM support** for air-gapped environments
- 🔒 **Privacy-first** (no cloud dependencies)
- ⚡ **Zero-config** proxy setup
- 🛠️ **Works with** Ollama, LocalAI, LM Studio, custom endpoints

**[→ Use Local LLMs](https://github.com/Agile-V/local-llm-proxy)**

---

## 🌟 **Why Agile V?**

| Feature | Typical AI Agents | Agile V Framework |
|---------|------------------|-------------------|
| **Traceability** | ❌ Code without requirements | ✅ Every artifact links to REQ-XXXX |
| **Verification** | ❌ Self-tests (confirmation bias) | ✅ Independent Red Team Verifier |
| **Hardware** | ❌ Assumes unlimited resources | ✅ Validates RAM/CPU/GPU constraints |
| **Deployment** | ❌ Autonomous production pushes | ✅ Human Gates with Evidence Summaries |
| **Ambiguity** | ❌ Silent assumptions | ✅ Halts and asks clarifying questions |
| **Compliance** | ❌ Manual audit prep (weeks) | ✅ Auto-generated ISO/GxP artifacts |

---

## 🚀 **Quick Start**

### 1. Install Agent Skills

**Claude Code:**
```bash
/plugin install agile-v-skills
```

**Cursor:**
```bash
cp -r .cursor/rules/ /path/to/your/project/.cursor/
```

**VS Code / GitHub Copilot:**
```bash
cp -r agile-v-core/ ~/.copilot/skills/
```

### 2. Start Your First Verified Build

```
You: "Add user authentication"

Agent: ⚠️ HALT CONDITION: No requirement specification found
Invoking: requirement-architect

[Requirement Architect creates REQ-0001, REQ-0002...]

Build Agent: ✓ Implementation complete (ART-0001 → REQ-0001)
Red Team Verifier: Found 2 security issues
Build Agent: ✓ Issues fixed
Red Team Verifier: ✓ All tests pass

Agent: Ready for Human Gate approval
```

**[→ Full Documentation](https://github.com/Agile-V/agile_v_skills#readme)**

---

## 📚 **Documentation**

- 📖 **[Official Website](https://agile-v.org)** — Framework overview and philosophy
- 📘 **[Agent Skills Guide](https://github.com/Agile-V/agile_v_skills/blob/main/README.md)** — Complete skills documentation
- 📙 **[Examples](https://github.com/Agile-V/agile_v_skills/blob/main/EXAMPLES.md)** — Before/after scenarios
- 📗 **[Skill Routing Guide](https://github.com/Agile-V/agile_v_skills/blob/main/SKILL_ROUTING_GUIDE.md)** — When to use which skill
- 📕 **[Compliance Matrices](https://github.com/Agile-V/agile_v_skills/tree/main/docs/compliance)** — ISO 9001, ISO 27001, GxP mappings

---

## 🏢 **Who Uses Agile V?**

**Ideal for:**
- 🏭 **Enterprise teams** needing verifiable AI-augmented engineering
- 🏥 **Regulated industries** (medical devices, aerospace, pharma, finance)
- 🔬 **R&D teams** building mission-critical systems
- 🎓 **Academic researchers** studying AI safety and verifiability
- 🛡️ **Security-conscious organizations** requiring audit trails

**Industry Coverage:**
- Medical Devices (ISO 13485, 21 CFR Part 11)
- Aerospace (AS9100D)
- Pharmaceuticals (GxP, GAMP 5)
- Financial Services (SOC 2, GDPR)
- General Manufacturing (ISO 9001)

---

## 🤝 **Contributing**

We welcome contributions! The Agile V™ Framework is open source (CC-BY-SA-4.0).

**Ways to contribute:**
- ⭐ **Star our repos** to show support
- 🐛 **Report issues** or suggest improvements
- 💡 **Share use cases** from your industry
- 🔧 **Contribute new skills** following our guidelines
- 📚 **Improve documentation** (especially examples)
- 🌍 **Translate** to other languages

**[→ Contribution Guidelines](https://github.com/Agile-V/agile_v_skills#contributing)**

---

## 📬 **Connect With Us**

- 🌐 **Website**: [agile-v.org](https://agile-v.org)
- 📧 **Email**: [info@agile-v.org](mailto:info@agile-v.org)
- 🐦 **Twitter**: [@AgileVFramework](https://twitter.com/AgileVFramework)
- 💼 **LinkedIn**: [Agile V Framework](https://linkedin.com/company/agile-v)
- 📖 **GitHub**: [github.com/Agile-V](https://github.com/Agile-V)

---

## 📊 **Project Stats**

![GitHub Org's stars](https://img.shields.io/github/stars/Agile-V?style=social)
![Total Repos](https://img.shields.io/badge/Total_Repos-13-blue)
![Public Repos](https://img.shields.io/badge/Public_Repos-3-green)
![Contributors](https://img.shields.io/github/contributors/Agile-V/agile_v_skills)
![License](https://img.shields.io/badge/License-CC--BY--SA--4.0-lightgrey)

---

## 🎯 **Our Mission**

> **To make AI-augmented engineering verifiable, traceable, and trustworthy for mission-critical systems.**

We believe AI agents should be **powerful tools**, not **uncontrolled wildcards**. The Agile V™ Framework provides the rigor and structure needed to build real products with AI assistance while maintaining the quality, traceability, and compliance requirements of enterprise and regulated environments.

---

## 📄 **License**

All public Agile V™ projects are licensed under **[CC-BY-SA-4.0](https://creativecommons.org/licenses/by-sa/4.0/)** (Creative Commons Attribution-ShareAlike 4.0 International).

**This means:**
- ✅ Free to use for commercial and personal projects
- ✅ Modify and adapt for your needs
- ✅ Share with attribution
- ⚠️ Derivatives must use the same license (ShareAlike)

---

<div align="center">

**Built with ❤️ by the Agile V™ Team**

[⭐ Star us on GitHub](https://github.com/Agile-V/agile_v_skills) • [🌐 Visit agile-v.org](https://agile-v.org) • [📧 Get in touch](mailto:info@agile-v.org)

</div>
