# 🕸️ Simulation de l'Algorithme PageRank via la Méthode Monte-Carlo
> **Progetto Bilingue: Italiano & English**

---

## 🇮🇹 Versione Italiana

### 📝 Presentazione del Progetto
Questo progetto, realizzato in collaborazione con @Belvindev, consiste nel modellare e simulare l'algoritmo **PageRank** di Google. Il PageRank misura l'importanza di una pagina web analizzando la quantità e la qualità dei link che puntano ad essa.

Per stimare la popolarità delle pagine, abbiamo implementato un modello probabilistico basato sul concetto del **"Random Surfer"** (il navigatore casuale) utilizzando le simulazioni di **Monte-Carlo**.

### 🧠 Concetti Chiave & Approccio Matematico
*   **Modellazione a Grafi:** Il web è rappresentato come un grafo orientato in cui i nodi sono le pagine e gli archi sono i link ipertestuali.
*   **Catene di Markov:** Gli spostamenti del navigatore da una pagina all'altra sono modellati tramite una matrice di transizione di probabilità.
*   **Simulazione Monte-Carlo:** Invece di risolvere complessi sistemi di equazioni matriciali, simuliamo migliaia di percorsi casuali per far convergere le frequenze di visita verso il punteggio reale del PageRank.
*   **Damping Factor (Fattore di smorzamento):** Consideriamo la probabilità (solitamente fissata a 0.85) che un utente si stanchi e digiti un nuovo URL a caso.

### 🛠️ Tecnologie Utilizzate
*   **Ambiente:** Google Colab / Jupyter Notebook
*   **Linguaggio:** Python
*   **Librerie:** `NumPy` (calcolo matriciale), `Matplotlib` / `Seaborn` (visualizzazione della convergenza).

---

## 🇬🇧 English Version

### 📝 Project Overview
This project, developed in collaboration with @Belvindev, models and simulates Google's famous **PageRank** algorithm. PageRank measures the importance of a webpage by analyzing the quantity and quality of links pointing to it.

To estimate page popularity, we implemented a probabilistic model based on the **"Random Surfer"** concept using **Monte-Carlo** simulations.

### 🧠 Key Concepts & Mathematical Approach
*   **Graph Modeling:** The web is represented as a directed graph where nodes are pages and edges are hyperlinks.
*   **Markov Chains:** The surfer's movement from one page to another is modeled using a probability transition matrix.
*   **Monte-Carlo Simulation:** Instead of solving heavy matrix equations, we simulate thousands of random walks to let the visit frequencies converge toward the true PageRank score.
*   **Damping Factor:** We account for the probability (usually set to 0.85) that a user stops clicking links and types a new random URL.

### 🛠️ Technologies Used
*   **Environment:** Google Colab / Jupyter Notebook
*   **Language:** Python
*   **Libraries:** `NumPy` (matrix operations), `Matplotlib` / `Seaborn` (convergence visualization).

---

## 🚀 Come eseguire il progetto / How to run

Puoi aprire direttamente il notebook in Google Colab cliccando sul pulsante qui sotto / You can open the notebook directly in Google Colab by clicking the button below:

[![Open In Colab](https://colab.research.google.com/drive/1hAoTq4NZyUG5UitLwopHPre98CHTKZTc)
