# Hi there 👋, I'm Sree Hari P  

💻 **Electronics & Communication Engineer | Software Developer | Antenna Researcher**  
🔹 Passionate about **5G antennas, Machine Learning, and Compiler/Parser Development**  
🔹 Currently an **Intern @ McLaren Strategic Solutions** – building a **Sybase Stored Procedure Parser (AST Generator)**  
🔹 Experienced with **Python, ANTLR, SQL, ANSYS HFSS, Arduino, Raspberry Pi**  

---

## 🚀 Featured Projects  

### 🛠️ Sybase Stored Procedure Parser (Internship)  
Enterprise-grade **AST Generator** for Sybase stored procedures using **Python + ANTLR**, supporting control flows, cursors, and transformations.  
➡️ [Repository Link](#)  

### 📡 MIMO Antenna Design for Sub-6GHz 5G  
Designed & optimized **MIMO patch antennas** with **hybrid ML models (ANN, CNN, RF, HGNN, KBNN)** to improve gain, S11, and isolation.  
➡️ [Repository Link](#)  

### 🛰️ Raspberry Pi Based Small Satellite  
Built a low-cost **weather & atmosphere data collection satellite** using Raspberry Pi, sensors, and telemetry.  

### 🤖 Arduino Robot Car for Military Applications  
Developed a **multipurpose robotic car** for military use with **Arduino Uno**, equipped with wireless control and automation.  

---

## 📊 Tech Stack  

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![ANTLR](https://img.shields.io/badge/ANTLR-DC322F?logo=java&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-003B57?logo=database&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?logo=c&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?logo=arduino&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?logo=raspberrypi&logoColor=white)
![ANSYS HFSS](https://img.shields.io/badge/ANSYS%20HFSS-FFB71B?logo=ansys&logoColor=black)
![MATLAB](https://img.shields.io/badge/MATLAB-FF8800?logo=mathworks&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)

---

## 🔄 Integration Flow (Internship Project)  

```mermaid
flowchart LR
    A["Sybase .sql Files"]

    subgraph Pipeline["Modernization Pipeline"]
        B["Tool 1: Indexer"]
        C["Tool 2: Parser (This Tool)"]
        D["Tool 3: Documentation Generator"]
        E["Tool 4: Lineage Analyzer"]
        F["Tool 5: SP Transformer"]
        G["Tool 6: Validator & Report"]
    end

    H["Postgres .sql Files"]

    A --> B
    A --> C
    B --> D
    C --> D
    B --> E
    C --> E
    C --> F
    F --> G
    E --> G
    D --> G
    G --> H
