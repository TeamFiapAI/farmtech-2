# 🌾 FarmTech Solutions – Sistema de Irrigação Inteligente com ESP32 e Banco SQL

![Arduino](https://img.shields.io/badge/arduino-3670A0?style=for-the-badge&logo=arduino&logoColor=ffdd54)
![C++](https://img.shields.io/badge/c++-3670A0?style=for-the-badge&logo=c%2B%2B&logoColor=ffdd54)
![PlatformIO](https://img.shields.io/badge/platformio-3670A0?style=for-the-badge&logo=platformio&logoColor=ffdd54)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Oracle](https://img.shields.io/badge/Oracle-3670A0?style=for-the-badge&logo=oracle&logoColor=ffdd54)

## 📌 Visão Geral
Este projeto simula um sistema de **irrigação inteligente** utilizando sensores agrícolas, um microcontrolador **ESP32**, e armazenamento em banco **SQL**. A simulação é feita na plataforma **Wokwi**, e os dados coletados são manipulados com **Python**, permitindo análises, visualizações e controle automatizado da irrigação.

## ⚙️ Funcionalidades
✅ Leitura dos sensores simulados  
✅ Armazenamento dos dados em banco SQL  
✅ Operações CRUD implementadas  
🚀 Extras opcionais: Dashboard e integração com API de clima  

## 🗂️ Estrutura do Repositório

```plaintext
📁 /
├── 📄 README.md
├── 📁 /simulador/  → Codigo para utilizar no WokWi on-line
│   ├── 📁 /images/ → Imagens usadas no Readme
│   ├── diagram.json    → Formato JSON, que renderiza o Wokwi
│   ├── libraries.txt   → Bibliotecas utilizadas no projeto
│   ├── main.ino        → Codigo C++ da placa ESP32
├── 📁 /sistema/ → Todas as funcionalidades do nosso sistema
│   ├── 📁 /dashboard/
|   |   ├── 
|   |   ├── 
|   |   ├── 
|   |   ├── 
```
## 🔗 Links Úteis
- 🤖 [Projeto no Wokwi](https://wokwi.com/projects/430970377652249601) – Simulador online de circuitos  
- ▶️ [Demonstração no YouTube](https://www.youtube.com/) – Vídeo demonstrando o funcionamento do projeto

## 👥 Alunos
- Nome: Felipe Balthazar de Almeida
- Nome: Fernando Gomes da Silva
- Nome: Guilherme Urbinatti
- Nome: Vinicius Burchert Vilas Boas

## 📝 ATIVIDADES
### Entrega 1: Sistema de Sensores e Controle com ESP32
├── 📁 /simulador/

<table>
  <tr>
    <td colspan="2" style="text-align: center;">
      <img src="./simulador/images/projeto.png"
           alt="Projeto ESP32 - Wokwi"
           style="width: 80%; max-width: 700px; display: block; margin: 0 auto;">
    </td>
  </tr>
  <tr>
    <td style="width: 50%; vertical-align: top; padding: 5px;">
      <h4>Bomba Ativada - Umidade <= 40%</h4>
      <img src="./simulador/images/log_irrigacao_ativada.png" alt="Texto alternativo Log 1" style="width: 100%;">
    </td>
    <td style="width: 50%; vertical-align: top; padding: 5px;">
      <h4>Log 2 Bomba Desativada - Humidade > 40%</h4>
      <img src="./simulador/images/log_irrigacao_desativada.png" alt="Texto alternativo Log 2" style="width: 100%;">
    </td>
  </tr>
</table>