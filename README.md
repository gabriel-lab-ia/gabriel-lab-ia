<p align="center">
  <img src="assets/banner.svg" alt="Banner do projeto NeuroSync-RL" />
</p>

<p align="center">
  <a href="https://github.com/gabriel-lab-ia/gabriel-lab-ia/stargazers">
    <img src="https://img.shields.io/github/stars/gabriel-lab-ia/gabriel-lab-ia?style=for-the-badge" alt="GitHub Stars" />
  </a>
  <a href="https://github.com/gabriel-lab-ia/gabriel-lab-ia/commits">
    <img src="https://img.shields.io/github/last-commit/gabriel-lab-ia/gabriel-lab-ia?style=for-the-badge" alt="Ultimo commit" />
  </a>
  <a href="https://github.com/gabriel-lab-ia/gabriel-lab-ia">
    <img src="https://img.shields.io/github/repo-size/gabriel-lab-ia/gabriel-lab-ia?style=for-the-badge" alt="Tamanho do repositorio" />
  </a>
  <a href="https://github.com/gabriel-lab-ia/gabriel-lab-ia">
    <img src="https://img.shields.io/github/languages/top/gabriel-lab-ia/gabriel-lab-ia?style=for-the-badge" alt="Linguagem principal" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.12-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python 3.12" />
  <img src="https://img.shields.io/badge/C%2B%2B-High%20Performance-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/PyTorch-Tensors%20%26%20Autograd-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/NVIDIA-CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="NVIDIA CUDA" />
  <img src="https://img.shields.io/badge/Matplotlib-Analise%20de%20Sinais-11557C?style=for-the-badge&logo=plotly&logoColor=white" alt="Matplotlib" />
  <img src="https://img.shields.io/badge/Linux-Environment-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/Jupyter-VS%20Code%20%7C%20Pop!_OS-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter" />
  <img src="https://img.shields.io/badge/AWS-Cloud-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS" />
  <img src="https://img.shields.io/badge/DRL-Deep%20Reinforcement%20Learning-0F172A?style=for-the-badge" alt="Deep Reinforcement Learning" />
</p>

# NeuroSync-RL: Interface Cérebro-Máquina de Malha Fechada

Este projeto implementa uma simulação avançada de **Deep Reinforcement Learning (DRL)** focada na simbiose entre Inteligência Artificial e o Cérebro Humano. O sistema modela a co-adaptação entre tensores artificiais e plasticidade biológica, respeitando as leis fundamentais da termodinâmica e do metabolismo cerebral.

## Arquitetura do Projeto

O motor principal utiliza uma arquitetura inspirada no **Córtex Pré-Frontal** e no **Corpo Estriado**, implementada via **PyTorch**. O modelo evoluiu através de diversas fases:

1. **TD-Learning Basal:** Modelagem do Erro de Previsão de Recompensa (Dopamina).
2. **Transformer & Geometria Analítica:** Detecção de patologias em imagens de RM utilizando mecanismos de *Self-Attention* (GPT-2 Style) e coordenadas cartesianas.
3. **Monte Carlo & Softmax:** Otimização de política baseada em episódios para seleção de protótipos de hardware.
4. **Simulação Termodinâmica:** Filtro de viabilidade física baseado no Efeito Joule, Consumo de ATP e Frequências Cerebrais (Alpha, Beta, Gamma).

## Protótipos Avaliados

| Protótipo | Tecnologia | Viabilidade (Softmax) | Notas de Engenharia |
| :--- | :--- | :--- | :--- |
| **A** | Microeletrodos | 0.00% | Falha crítica: Superaquecimento (175°C). |
| **B** | EEG | ~49.6% | Seguro, mas baixa largura de banda (ruído alto). |
| **C** | ECoG | 0.00% | Inviável: Estresse térmico acima de 1.5°C. |
| **D** | **Neuromórfico** | **~50.3%** | **Vencedor: Alta eficiência energética e Sincronia.** |

## Tecnologias Utilizadas

- **Linguagem:** Python 3.12
- **Deep Learning:** PyTorch (Tensors & Autograd)
- **Visualização:** Matplotlib (Análise de Sinais e Calor)
- **Ambiente:** Pop!_OS / VS Code (Jupyter)
- **Conceitos:** Deep Q-Learning, REINFORCE, Computação Neuromórfica, Geometria Analítica.

## Como Executar

1. **Ativar o Ambiente:**
   ```bash
   source ~/meu-projeto-ml/bin/activate
   ```

2. **Instalar Dependências:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Executar a Simulação:**
   ```bash
   python neuro_sync_rl.py
   ```

4. **Visualizar Resultados:**
   Abra o notebook `analysis.ipynb` no Jupyter para gráficos e análises.

## Contribuição

Contribuições são bem-vindas! Abra uma issue ou pull request no repositório.

## Licença

Este projeto está sob a licença MIT.
