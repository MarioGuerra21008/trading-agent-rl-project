# 🤖 Agente de Trading Basado en Aprendizaje por Refuerzo

El propósito del proyecto es aplicar técnicas de **aprendizaje por refuerzo profundo** al ámbito del **trading automatizado**, utilizando distintos modelos de Deep Q-Learning.

---

## 🧠 Descripción del Proyecto

El proyecto consiste en el desarrollo de un **agente de trading** que aprende a **comprar, vender o mantener** un activo financiero dentro de un entorno **simulado de mercado**.  
El agente busca **maximizar las ganancias** mediante la experiencia acumulada, aprendiendo de las recompensas obtenidas a través de sus decisiones.

El entorno fue construido utilizando el modelo **Geometric Brownian Motion (GBM)**, comúnmente empleado en finanzas para representar la evolución aleatoria de los precios.  
De esta forma, el agente enfrenta un escenario **incierto y volátil**, similar al comportamiento de los mercados reales.

---

## ⚙️ Objetivos

- Implementar y comparar distintos **algoritmos de aprendizaje por refuerzo profundo**.  
- Analizar cómo los agentes ajustan su política a partir de la experiencia en un entorno incierto.  
- Evaluar la estabilidad y capacidad de aprendizaje de cada modelo frente a un mercado simulado.  
- Sentar las bases para futuras aplicaciones con **datos financieros reales**.

---

## 🧩 Modelos Implementados

Se desarrollaron tres variantes del algoritmo **Deep Q-Network (DQN)**:

- **DQN:** modelo base que aprende directamente del valor esperado de cada acción.  
- **Double DQN:** mejora que reduce la sobreestimación de valores Q usando dos redes neuronales.  
- **Dueling DQN:** separa el valor del estado y la ventaja de cada acción para un aprendizaje más eficiente.  

Estos modelos se eligieron porque trabajan con **acciones discretas** (comprar, vender o mantener) y permiten comparar su desempeño bajo las mismas condiciones experimentales.

---

## 💻 Tecnologías Utilizadas

- **Python 3.11+**  
- **PyTorch** → construcción y entrenamiento de redes neuronales  
- **NumPy / Pandas** → procesamiento y manipulación de datos  
- **Matplotlib** → visualización de métricas y evolución del agente  
- **Jupyter Notebook** → desarrollo y experimentación interactiva  

---

## 🧾 Metodología General

1. **Diseño del entorno:** se simula un activo financiero usando GBM.  
2. **Definición de acciones:** comprar, vender o mantener posición.  
3. **Entrenamiento del agente:** los modelos aprenden por experiencia, ajustando sus valores Q.  
4. **Comparación de algoritmos:** se analizan estabilidad, velocidad de aprendizaje y consistencia.  
5. **Análisis de comportamiento:** se estudia la frecuencia y tipo de decisiones del agente.  

---

## 👥 Autores

- **Mario Antonio Guerra Morales** – 21008  
- **Diego Alexander Hernández Silvestre** – 21270
- **Linda Inés Jiménez Vides** – 21169 

📅 *Universidad del Valle de Guatemala – Noviembre 2025*

