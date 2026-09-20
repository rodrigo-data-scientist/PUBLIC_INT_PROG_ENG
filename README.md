# 🏛️ Introdução à Programação para Engenharias

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Engenharias](https://img.shields.io/badge/Engenharias-Civil%20%7C%20El%C3%A9trica%20%7C%20Computa%C3%A7%C3%A3o-success)](#)
[![Semestre](https://img.shields.io/badge/Semestre-2026.2-blueviolet)](#)

Repositório oficial de materiais didáticos e cadernos computacionais interativos da disciplina **Introdução à Programação para Engenharias**, ministrada para o Núcleo Comum das Engenharias (Civil, Elétrica e da Computação) do **Centro Universitário para o Desenvolvimento Sustentável da Amazônia (UNIFADESA)**.

---

## 👨‍🏫 Informações da Disciplina

- **Instituição:** Centro Universitário para o Desenvolvimento Sustentável da Amazônia — UNIFADESA
- **Área:** Núcleo Comum das Engenharias (Engenharia Civil, Engenharia Elétrica e Engenharia da Computação)
- **Disciplina:** Introdução à Programação para Engenharias
- **Docente:** Prof. Esp. Rodrigo Martins Sousa
- **Semestre Letivo:** 2026.2
- **Linguagem Principal:** Python 3 (com paralelos conceituais em C++, Rust e Portugol)

---

## 🧭 Visão Geral e Objetivos do Repositório

O objetivo deste repositório é fornecer aos estudantes de Engenharia cadernos computacionais executáveis (**Jupyter Notebooks**) focados na aplicação do pensamento algorítmico e programação para resolução de problemas reais de engenharia, incluindo:

1. **Modelagem e Simulação:** Tradução de equações e normas técnicas (como NBRs e formulações físicas) em rotinas computacionais reproduzíveis.
2. **Métodos Numéricos Iterativos:** Resolução de equações transcendentais e sistemas via aproximações sucessivas (Método da Bisseção, Newton-Raphson).
3. **Automação e Tratamento de Dados:** Cálculo estrutural, telemetria de sensores, controle de qualidade de materiais e monitoramento de sistemas de potência.
4. **Preparação para Avaliações:** Prática guiada com testes de mesa, rastreamento de memória, diagnóstico de erros (*debugging*) e baterias com asserções automatizadas (`assert`).

---

## 📂 Estrutura e Conteúdo Programático

```text
PUBLIC_INT_PROG_ENG/
│
├── Aula_04_Estruturas_de_Repeticao.ipynb     # Aula teórica e aplicada sobre laços contados e condicionais
├── Revisao_Pratica_Aulas_01_a_04.ipynb       # Caderno integrador e simulado preparatório para a Avaliação N1
└── README.md                                 # Este documento de apresentação e guia de uso
```

---

### 📘 1. `Aula_04_Estruturas_de_Repeticao.ipynb`
*Caderno dedicado ao domínio completo de laços de repetição e convergência numérica na engenharia.*

- **Paralelo Multi-Linguagem:** Comparativo de sintaxe e desempenho entre Portugol, Python, C++ e Rust.
- **Laços Contados (`for`) & Gerador `range()`:** Variações de início, fim e passo (positivo e regressivo).
- **Padrões Algorítmicos Essenciais:**
  - Padrão **Contador** (ex.: contagem de amostras fora dos limites de tolerância).
  - Padrão **Acumulador / Somatório** (ex.: soma de forças nodais, consumo acumulado de energia).
- **Aplicações Práticas de Engenharia:**
  - *Engenharia Civil/Mecânica:* Cálculo das coordenadas do baricentro/centroide ($\bar{x}, \bar{y}$) de seções transversais compostas.
  - *Engenharia Elétrica:* Geração de tabela técnica de queda de tensão percentual ($\Delta V\%$) ao longo do comprimento de condutores de cobre.
- **Laços Condicionais (`while`) & Validação Robusta:**
  - Prevenção de *loops* infinitos e critérios de parada com sentinelas.
  - Validação interativa de dados de sensores e entradas de operadores.
- **Controle de Fluxo Intermediário:** Uso de `break`, `continue` e cláusula `else` em laços.
- **Métodos Numéricos:** Implementação com convergência e tolerância do **Método de Newton-Raphson** para encontrar raízes de equações não lineares.
- **Laços Aninhados:** Varredura de malhas bidimensionais e discretização espacial de superfícies.
- **Desafios Guiados em Sala:**
  - Aproximação de funções trigonométricas por Série de Taylor (Cosseno).
  - Controle tecnológico de corpos de prova de concreto cilíndricos segundo a **NBR 5739**.

---

### 📙 2. `Revisao_Pratica_Aulas_01_a_04.ipynb`
*Caderno integrador focado na consolidação dos conceitos das 4 primeiras aulas e preparação para a Avaliação Bimestral N1.*

- **O Mapa Conceitual Integrado:**
  $$\text{Aula 01 (I/O \& Algoritmos)} \longrightarrow \text{Aula 02 (Tipos \& Operadores)} \longrightarrow \text{Aula 03 (Decisões)} \longrightarrow \text{Aula 04 (Repetições)} \longrightarrow \mathbf{Avaliação\ N1}$$
- **Pílulas Práticas de Revisão:**
  - *Pílula 1:* I/O padrão, armadilhas do retorno de `input()` e formatação avançada com *f-strings*.
  - *Pílula 2:* Precedência rigorosa de operadores aritméticos e distinção entre `/` (divisão real) e `//` (divisão inteira).
  - *Pílula 3:* Lógica booleana (`and`, `or`, `not`) e lógica de intertravamento de segurança industrial.
  - *Pílula 4:* Tomadas de decisão encadeadas e mutuamente exclusivas com `if / elif / else`.
- **Casos Integradores Multidisciplinares:**
  - **Engenharia Civil:** Controle estatístico e dimensionamento de lote de concreto com cálculo de $f_{ck}$, desvio padrão amostral e verificação de conformidade estrutural.
  - **Engenharia Elétrica:** Telemetria, cálculo de rendimento instantâneo e algoritmo de proteção térmica/sobretensão para usina solar fotovoltaica.
  - **Engenharia da Computação / Métodos Numéricos:** Implementação do **Método da Bisseção** para determinação de raízes de equações transcendentais com tolerância $\epsilon$.
- **Simulado Prático no Padrão da Avaliação N1:**
  - *Questão 1:* Teste de mesa com rastreamento manual de variáveis em iterações.
  - *Questão 2:* Diagnóstico e correção de falhas de lógica e sintaxe (*debugging*).
  - *Questão 3:* Desafio completo de implementação com validação automática por `assert`.
- **Guia de Bolso:** As 6 armadilhas clássicas de código a evitar na prova.

---

## 🚀 Como Executar os Cadernos Localmente

### Pré-requisitos
- Python 3.10 ou superior instalado.
- Gerenciador de pacotes `pip` atualizado.

### 1. Clonar ou Baixar o Repositório
```bash
git clone <URL_DO_REPOSITORIO>
cd PUBLIC_INT_PROG_ENG
```

### 2. Criar e Ativar um Ambiente Virtual (Recomendado)
```bash
# Linux / macOS
python3 -m venv .venv
source .venv/bin/activate

# Windows
python -m venv .venv
.venv\Scripts\activate
```

### 3. Instalar o Jupyter Notebook ou JupyterLab
```bash
pip install notebook jupyterlab
```

### 4. Iniciar o Ambiente
```bash
jupyter lab
# ou
jupyter notebook
```

> 💡 **Dica:** Os cadernos também podem ser executados diretamente no **VS Code** (com as extensões Python e Jupyter instaladas) ou carregados no **Google Colab**.

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

- [Python](https://www.python.org/): Linguagem de programação de alto nível, interpretada e multiplataforma.
- [Jupyter Notebook](https://jupyter.org/): Ambiente interativo para documentação, código e visualização científica.
- Módulos nativos da Standard Library do Python (como `math` e `sys`), dispensando dependências externas complexas para os fundamentos da N1.

---

## 📌 Orientações para os Alunos

1. **Interatividade:** Execute cada célula de código individualmente e altere os parâmetros para analisar o comportamento das variáveis.
2. **Testes de Mesa:** Ao se deparar com os laços e estruturas de decisão, reproduza em papel o valor das variáveis em cada iteração antes de executar o código.
3. **Simulado N1:** Resolva as questões do simulado sem consultar previamente as soluções e execute as células de teste com `assert` para verificar a precisão do seu código.

---

## 📄 Licença e Créditos

Material didático desenvolvido para fins pedagógicos pelo **Prof. Esp. Rodrigo Martins Sousa** no âmbito do **Centro Universitário para o Desenvolvimento Sustentável da Amazônia (UNIFADESA)**.

Distribuído para uso dos acadêmicos do Núcleo Comum das Engenharias.
