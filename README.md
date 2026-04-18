# Guilherme de Sena Hughes

**Computational Modeling (MSc) · ML & Scientific Computing · PINNs · PyTorch**

I'm an electrical engineer turned computational scientist, currently pursuing a PhD in Computational Modeling at UESC (Brazil). My work sits at the intersection of **physics-informed machine learning**, **numerical simulation**, and **data-driven operations**. I like building things that connect mathematical rigor to real-world impact.

## What I'm working on

🔬 **Research** - Physics-Informed Neural Networks (PINNs) for solving differential equations, coupled neutron-thermohydraulic simulations of nuclear reactor pins (Serpent + ANSYS Fluent), and multi-objective optimization with evolutionary algorithms.

⚙️ **Industry** - Leading data operations at scale (400-500 insurance certificates/week, zero-error SLA), building Python & Apps Script automation pipelines that eliminated hours of manual work, and developing demand forecasting models used for capacity planning.

## Highlight: NeuTherm-PINN

[![NeuTherm-PINN](https://img.shields.io/badge/NeuTherm--PINN-Physics--Informed%20ML%20for%20Nuclear%20Reactors-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)](https://github.com/carcaraa/neutherm-pinn)

End-to-end ML project solving the **coupled neutron diffusion + heat conduction** problem in a PWR fuel pin using PyTorch. Compares a data-driven surrogate (FNN) against a physics-informed neural network (PINN) that learns directly from the governing PDEs via automatic differentiation.

| Component | Description |
|-----------|-------------|
| **Solver** | 2-group finite-difference diffusion + Picard-coupled heat conduction ($k_{\text{eff}}$ = 1.30, converges in 6 iterations) |
| **Surrogate** | FNN with residual blocks trained on 5000 LHS samples — **< 0.003% error** on all fields |
| **PINN** | Learns $\phi_1(r), \phi_2(r), T(r)$ and $k_{\text{eff}}$ from PDEs alone, no labeled data needed |

Built from scratch: numerical solvers, cross-section models (Doppler feedback), dataset generation (Latin Hypercube), training pipelines, and comparison benchmarks. **[See the repo →](https://github.com/carcaraa/neutherm-pinn)**

## Featured projects

| Project | What it does | Stack |
|---------|-------------|-------|
| [**neutherm-pinn**](https://github.com/carcaraa/neutherm-pinn) | PINNs for coupled neutronics–thermal hydraulics in nuclear fuel elements | PyTorch · NumPy · SciPy |
| [**redes-neurais**](https://github.com/carcaraa/redes-neurais) | PINNs for solving ODEs/PDEs — full ML pipeline from linear regression to deep learning | PyTorch · NumPy · Matplotlib |
| [**article-multi-small-candu-th**](https://github.com/carcaraa/article-multi-small-candu-th) | Multiphysics simulation of a small supercritical CANDU reactor with thorium fuel | Serpent · ANSYS Fluent · Python |
| [**alocacao-dlccs**](https://github.com/carcaraa/alocacao-dlccs) | Multi-objective genetic algorithm (NSGA-II) for optimal placement of fault current limiters in power systems | Python · Optimization |

## Tech & tools

```text
Languages        Python · C · R · JavaScript · SQL
ML / DS          PyTorch · Scikit-learn · Pandas · NumPy · SciPy · Matplotlib · Seaborn
Methods          PINNs · Regression · Classification · MLE · SGD · SVM · NSGA-II · Causal Inference
Simulation       ANSYS Fluent (CFD) · Serpent (Monte Carlo) · Numerical methods for ODEs/PDEs
DevOps           Docker · Git · Google Apps Script · ETL pipelines
```

## Education

- 🎓 **PhD in Computational Modeling** - UESC *(in progress)*
- 📜 **MSc in Computational Modeling** - UESC *(2025)*
- 📜 **Postgrad in DevOps Engineering** - IFMT *(in progress)*
- ⚡ **BEng in Electrical Engineering** - UESC *(2020)*

## Let's connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/guilhermehughes/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:guilhermehughes@gmail.com)

---

<details>
<summary>🇧🇷 Versão em Português</summary>

### Sobre mim

Engenheiro eletricista, mestre em Modelagem Matemática e Computacional e doutorado em andamento em Modelagem Matemática e Computacional (UESC). Trabalho na interseção entre **machine learning informado por física**, **simulação numérica** e **operações orientadas a dados**. Experiência liderando equipes, construindo pipelines de automação em Python e desenvolvendo modelos de previsão para planejamento de capacidade.

Busco aplicar minha base quantitativa forte e experiência com modelagem e ML em problemas reais de escala industrial.

</details>