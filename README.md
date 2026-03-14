# OpenClaw Skills Archive

[![Python](https://img.shields.io/badge/python-3.x-blue.svg)](https://www.python.org/)
[![Stars](https://img.shields.io/badge/stars-2838-yellow.svg)](https://github.com/openclaw/skills)
[![License](https://img.shields.io/badge/license-view%20file-green.svg)](LICENSE)

A comprehensive archive of all skill versions from clawhub.com, providing historical preservation and analysis capabilities for the OpenClaw ecosystem.

## 📋 Description

This repository serves as a historical archive containing all versions of skills that have been published on clawhub.com. It maintains a complete backup of the skill ecosystem for research, analysis, and preservation purposes.

## ⚠️ Important Disclaimer

**This repository may contain suspicious or malicious skills.** These are retained temporarily for security analysis purposes. We strongly recommend:

- Using the official [clawhub.com](https://clawhub.com) website for downloading skills
- Treating this repository as a historical archive only
- Exercising caution when examining or executing any code from this archive

## 🗂️ Repository Structure

The repository is organized as follows:

```
skills/
├── {username}/
│   └── {skill-name}/
│       ├── SKILL.md          # Skill documentation
│       ├── _meta.json        # Metadata and configuration
│       ├── README.md         # Additional documentation (optional)
│       └── example.md        # Usage examples (optional)
```

Each skill contains:
- **SKILL.md**: Primary skill documentation and implementation details
- **_meta.json**: Structured metadata including version, dependencies, and configuration
- **README.md**: Additional documentation (when provided by authors)
- **example.md**: Usage examples and demonstrations (when available)

## 🔍 Browse Skills

Skills are organized by username and can be found in the `/skills` directory. Some examples include:

- `/skills/00xmorty/conatus/` - Conatus skill implementation
- `/skills/04551lh/order/` - Order management skill
- `/skills/0731coderlee-sudo/wechat-publisher/` - WeChat publishing automation

## 🤖 Automated Maintenance

This repository includes automated workflows for:
- Archival synchronization from clawhub.com
- Pull request management
- Quality assurance checks

## 🚀 Usage

### For Research and Analysis

1. Browse the skills directory structure
2. Examine individual skill metadata in `_meta.json` files
3. Review implementation details in `SKILL.md` files
4. Analyze historical versions and changes

### For Clawdbot Integration

For active skill usage, we recommend using the official clawhub.com platform or having your clawdbot fetch skills directly from there for the best experience and security.

## 🔒 Security Considerations

- Skills in this archive are preserved "as-is" and may not reflect current security standards
- Some skills may be flagged or removed from the main platform but retained here for analysis
- Always verify skill integrity and safety before any execution
- Use official channels for production deployments

## 🤝 Contributing

This repository primarily serves as an automated archive. Direct contributions to archived skills should be made through the official clawhub.com platform.

For repository maintenance or infrastructure improvements:

1. Fork the repository
2. Create a feature branch
3. Submit a pull request with clear description

## 📄 License

See the [LICENSE](LICENSE) file for details regarding the use and distribution of this archive.

## 🔗 Related Links

- [clawhub.com](https://clawhub.com) - Official skill platform
- [OpenClaw Organization](https://github.com/openclaw) - Main project repository

---
*Documentation improved by [Codec8](https://codec8.com) — AI-powered docs for GitHub repos. [Generate docs for your repo →](https://codec8.com)*