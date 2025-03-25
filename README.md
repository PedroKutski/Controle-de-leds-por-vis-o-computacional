# 🚀 Controle de LEDs com Reconhecimento de Mãos

Este projeto apresenta um sistema interativo que utiliza **reconhecimento de mãos** para acionar LEDs de forma dinâmica! Utilizando **Python (OpenCV e MediaPipe)** para detectar gestos e um código **C++ para Arduino Uno**, os LEDs acendem ou apagam conforme os dedos são levantados. 🤖💡

---

## 🎯 Como Funciona?

🔹 **Dois códigos conectados**: 
   - **C++ (Arduino Uno)** → Controla os LEDs (pinos 2, 3, 4, 5, 6 e 7).
   - **Python (VS Code)** → Processa os gestos com a câmera do notebook e envia comandos ao Arduino.

🔹 **Configuração da Porta Serial**:
   - No **Arduino**, verifique a porta de conexão.
   - No **código Python**, configure a porta correta para comunicação serial.

🔹 **Detecção de Mãos** 🖐️:
   - O sistema usa **MediaPipe Hands** para identificar dedos levantados.
   - Cada dedo levantado aciona um LED correspondente.
   - Os LEDs servem para ilustrar o funcionamento, podendo ser substituídos por outros acionamentos!

---

## 🛠️ Instalação e Uso

1️⃣ **Configurar o Arduino**
   - Carregar o código **C++** no Arduino Uno.
   - Verificar a porta de conexão.

2️⃣ **Rodar o Código Python**
   - Instalar dependências (**OpenCV**, **MediaPipe**, **pyserial**).
   - Configurar a porta serial do Arduino no código.
   - Executar o script Python no **VS Code**.

3️⃣ **Testar os Gestos**
   - Levantar os dedos para acender os LEDs. 💡✨
   - Baixar os dedos para apagá-los.

4️⃣ **Finalizar**
   - Para encerrar o programa, basta pressionar **ESC**.

---

## 🚀 Expansões Futuras

🔹 **Adicionar novas funcionalidades**: Substituir LEDs por motores, sons ou outros dispositivos.

🔹 **Melhorar a precisão**: Ajustes no algoritmo de reconhecimento de mãos para maior confiabilidade.

🔹 **Explorar integração com IoT**: Conectar o sistema a dispositivos inteligentes para automação residencial! 🏠

---

## 📜 Licença
Este projeto é de código aberto e está licenciado sob a **MIT License**. Sinta-se à vontade para explorar, modificar e aprimorar! 🎉
