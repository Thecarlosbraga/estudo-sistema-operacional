# 🖥️ Processador de Registradores

```mermaid
flowchart TD
    REG[📥 Registradores] --> STACK[📚 Pilha de Execução]
    STACK --> SP[📌 Ponteiro da Pilha]
    REG --> PSW[📊 Palavra de Estado da CPU]
    
    REG --> ULA[🧮 Unidade Lógica e Aritmética]
    REG --> UC[🎛️ Unidade de Controle]
    REG --> MEM[🧠 Memória Principal]
    
    ULA --> REG
    UC --> REG
    MEM --> REG
