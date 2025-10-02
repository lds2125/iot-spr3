# 🚦 Simulação de Estacionamento de Motocicletas

Este projeto implementa uma **simulação visual** em Python utilizando **OpenCV** e **NumPy**, onde motocicletas se movimentam até vagas predefinidas e estacionam.  
O código foi desenvolvido inicialmente no Google Colab, mas pode ser executado localmente.

---

## 📌 Funcionalidades
- Geração de um ambiente 2D com vagas de estacionamento.
- Motos virtuais entrando na cena e ocupando vagas.
- Máquina de estados para as motos (`approach → align → park → parked`).
- Vagas livres em **verde**, vagas ocupadas em **vermelho**.
- HUD mostrando quantidade de vagas livres e FPS em tempo real.

---

## 🛠 Tecnologias Utilizadas
- [Python 3]
- [OpenCV]
- [NumPy] 
- [PIL (Pillow) 
- [Ultralytics YOLOv8]

---

## ▶️ Como Executar

### Rodando no Google Colab
1. Abra o notebook `motorcycle_detection_parking.ipynb` no Colab.
2. Execute o **Bloco 1** (instalação de dependências).
3. Execute o **Bloco 2** (simulação das vagas e motos estacionando).  
   - A simulação aparecerá direto no output do notebook.


