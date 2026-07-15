# Hi, I'm Vivek Raj Singh 👋

**Quantitative researcher & computational modeling engineer** — I build numerical engines where advanced mathematics meets high-performance systems.

My work spans stochastic differential equations, jump-diffusion processes, and Monte Carlo methods applied to derivatives pricing, volatility surface modeling, and risk quantification (VaR/CVaR). I care about code that is *provably correct*: every stochastic solver I ship is cross-validated against an analytical or statistical benchmark.

📫 rajvivek22102004@gmail.com

---

## 🔭 Featured Projects

### [ROCm-Forge](https://github.com/vivekrajsingh04/rocm-forge) — CUDA → AMD ROCm migration copilot
Multi-agent AI system that translates legacy NVIDIA CUDA codebases to AMD ROCm.
- 9-agent pipeline: AST-level static analysis (not regex), hardware-aware scanning (warp→wavefront, Tensor Core→MFMA), deterministic API mapping with confidence scores
- LoRA fine-tuned CodeLlama-7B, trained on AMD Instinct MI300X via ROCm 6.2
- FastAPI backend + web UI, Dockerized · **[Live demo](https://rocm-forge.onrender.com)**
- `Python` `FastAPI` `PyTorch` `QLoRA` `Docker`

### [Heston-SV-Engine](https://github.com/vivekrajsingh04/heston-sv-engine) — Stochastic volatility option pricing
High-fidelity implementation of the Heston (1993) model with a **dual-validation architecture**.
- Analytical pricing via numerical Fourier inversion, cross-validated against a custom Monte Carlo engine (Euler–Maruyama, full truncation)
- Antithetic Variates for ~65% variance reduction; bisection root-finding to extract implied volatility smiles and 3D pricing surfaces
- `Scilab` `Stochastic Calculus` `Monte Carlo` `Numerical Methods`

### [Stochastic-Storage-VaR](https://github.com/vivekrajsingh04/stochastic-storage-var) — Risk engine for storage fleets
End-to-end ML pipeline that models storage hardware degradation as a stochastic process and quantifies operational risk.
- LSTM + ARIMA ensemble forecasting, Isolation Forest anomaly detection, 10k-path Monte Carlo for VaR₉₅/CVaR₉₅
- Built on real-world drive telemetry (Backblaze Drive Stats), with an interactive FastAPI dashboard
- `PyTorch` `scikit-learn` `statsmodels` `FastAPI`

---

## 🧰 Toolbox

| Domain | Tools |
|---|---|
| **Languages** | C++, Python, Scilab |
| **Quant / ML** | NumPy, Pandas, SciPy, PyTorch, scikit-learn, statsmodels |
| **Methods** | Itô calculus, jump-diffusion, Euler–Maruyama, Fourier inversion, variance reduction, VaR/CVaR |
| **Systems** | FastAPI, Docker, Linux, Git |

## 📚 Current Focus

Options pricing (Black–Scholes, volatility surfaces, Greeks) · stochastic calculus (Itô's Lemma, Brownian motion, jump-diffusion) · risk management · algorithmic trading microstructure.

---

<div align="center"><i>Writing robust code for complex markets.</i></div>
