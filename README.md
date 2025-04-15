<div align="center">
  <img src="figs/eltex-logo.png" alt="ELTEX" width="400"/>
  <p>
    <a href="https://arxiv.org/abs/2503.15055"><img src="https://img.shields.io/badge/arXiv-paper-b31b1b.svg" alt="arXiv"></a>
    <a href="https://github.com/Kseymur/eltex-sheets-addon"><img src="https://img.shields.io/badge/Sheets-add--on-0F9D58.svg" alt="Google Sheets Add-on"></a>
  </p>
</div>


This is the official repository for the paper ["ELTEX: A Framework for Domain-Driven Synthetic Data Generation"](https://arxiv.org/abs/2503.15055). ELTEX is a framework that generates high-quality synthetic training data by systematically extracting domain-specific knowledge, enabling resource-efficient models to achieve GPT-4-competitive performance in specialized domains.
## ELTEX Sheets: Build Synthetic Datasets in Google Sheets
We've developed a full-featured Google Sheets add-on that brings our framework directly to users! Currently used internally and coming soon for public release! Stay tuned for updates :shipit:

### Key Features
- No-Code Data Generation: Generate and manage domain-specific datasets directly in Google Sheets
- User-Friendly: Designed for students, teachers, and domain experts with minimal programming experience
- Full Workflow Support: From parameters → indicators → synthetic data → QA → export, all in your spreadsheet

<div align="left">
  <a href="https://github.com/Kseymur/eltex-sheets-addon"><img src="https://img.shields.io/badge/View_Add--on_Repository-4285F4?style=for-the-badge&logo=github&logoColor=white" alt="Add-on Repo"></a>
</div>

## 🤗 Datasets
- [12k Synthetic Social Media Messages for Early Cyberattack Detection on Blockchain](https://huggingface.co/datasets/dn-institute/cyberattack-blockchain-synth)
### Attack Type Distribution

| **Attack Vectors** | **Seed Examples** | 
|-------------------|------------------------|
| Social Engineering & Phishing | Credential theft, wallet phishing | 
| Smart Contract Exploits | Token claim vulnerabilities, flash loans | 
| Exchange Security Breaches | Hot wallet compromises, key theft |
| DeFi Protocol Attacks | Liquidity pool manipulation, bridge exploits | 

For more about Cyberattack Vectors, read [Attack Vectors Wiki by DNI](https://dn.institute/research/cyberattacks/wiki/)

--- 

We're actively working on expanding our research with additional domain-specific datasets!

## Citation
```
@misc{razmyslovich2025eltexframeworkdomaindrivensynthetic,
      title={ELTEX: A Framework for Domain-Driven Synthetic Data Generation}, 
      author={Arina Razmyslovich and Kseniia Murasheva and Sofia Sedlova and Julien Capitaine and Eugene Dmitriev},
      year={2025},
      eprint={2503.15055},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2503.15055}, 
}
```
