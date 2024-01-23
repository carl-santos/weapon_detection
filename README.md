# weapon_detection
Neste projeto, faremos a detecção de objetos (armas de fogo) em imagens com o uso das técnicas (modelo) YOLO (You Only Look Once) que consiste na utilização de Redes Neurais Convolucionais da área de Deep Learning (redes neurais profundas) com a versão YOLOv8 da Ultralytics. 

### Instalação

Este projeto requer **Python 3.7**, a ferramenta OIDv4_ToolKit, seus requerimentos, e as seguintes bibliotecas Python instaladas:
- ultralytics
- os
- cv2
- matplotlib


Você também precisará ter software instalado para rodar e executar um [iPython Notebook](http://ipython.org/notebook.html)

### Código

O código é fornecido no arquivo notebook `weapon_detection(1).ipynb` e também o arquivo anexo 'converter_annotations.py'.

### Execução

Em um terminal ou janela de comando, navegue até o diretório raiz de projeto 'Projeto_de_dados_de_finanças_Petrobras.ipynb.ipynb'/` (que contém este README) e execute os seguintes comandos:

```bash
ipython notebook weapon_detection(1).ipynb
```  
ou
```bash
jupyter notebook weapon_detection(1).ipynb
```

Isso abrirá o o software e arquivo de projeto iPython Notebook em seu navegador.

### Dados

O conjunto de dados é um conjunto de imagens customizado para fazer o treinamento e a validação com o YOLO e será obtido junto ao repositório Open Images Dataset V7 (https://storage.googleapis.com/openimages/web/index.html)

**Classes**
O objetivo do projeto é fazer a deteccção personalizada de algumas armas de fogo em imagens. Para tanto foram escolhidas as classes alvo: Handgun, Shotgun e Rifle.

Obs. Este projeto foi realizado a partir de uma adaptação de projetos do curso "Detecção de Objetos com YOLO, Darknet, OpenCV e Python" da IA Expert Academy - https://iaexpert.academy/.
