# Introdução à Visão Computacional com OpenCV e Detecção Facial

## Descrição
Este repositório reúne exemplos práticos de Visão Computacional com OpenCV, organizados em um único notebook consolidado.  
O material é voltado para fins educacionais e demonstra diferentes técnicas de detecção de faces:

1. Fundamentos do OpenCV: carregamento e manipulação de imagens.  
2. HaarCascades: método clássico de detecção de faces com classificadores pré-treinados.  
3. HOG (Histogram of Oriented Gradients): técnica baseada em gradientes para localizar rostos.  
4. CNN (Redes Neurais Convolucionais): abordagem mais robusta para detecção facial.  

O notebook inclui observações e boas práticas sobre carregamento de imagens, organização dos arquivos e uso de modelos pré-treinados.  

---

## Estrutura do Repositório
```
vision-opencv-basics/
│
├── notebooks/
│   └── 001_OpenCV_Face_Detection.ipynb
│
├── datasets/        
│   ├── images/      # imagens de teste utilizadas nos notebooks
│   ├── models/      # arquivos de modelos pré-treinados do OpenCV (ex.: Haarcascades)
│
└── README.md
```

---

## Como usar

1. Clonar este repositório:
   ```bash
   git clone https://github.com/prof-atritiack/vision-opencv-basics.git
   cd vision-opencv-basics
   ```

2. Criar ambiente virtual (opcional, mas recomendado):
   ```bash
   python -m venv venv
   source venv/bin/activate   # Linux/Mac
   venv\Scripts\activate      # Windows
   ```

3. Abrir o notebook em ambiente local:
   ```bash
   jupyter notebook notebooks/001_OpenCV_Face_Detection.ipynb
   ```

4. Alternativamente, abrir o notebook no Google Colab:
   - Acesse o [Google Colab](https://colab.research.google.com/).  
   - Carregue o arquivo `001_OpenCV_Face_Detection.ipynb` da pasta `notebooks/`.  
   - Habilite a GPU em: Ambiente de execução > Alterar tipo de ambiente de execução > Acelerador de hardware > GPU.  

---

## Referências e Fontes de Pesquisa
- [Documentação OpenCV](https://docs.opencv.org/)  
- [Tutorial OpenCV-Python](https://opencv-python-tutroals.readthedocs.io/)  
- [Haarcascades disponíveis](https://github.com/opencv/opencv/tree/master/data/haarcascades)  
- Material do Prof. Arnaldo Viana  
- Conteúdos da IA Expert Academy  
- Organização do material com apoio do ChatGPT  

---

## Sobre o repositório
Este repositório foi criado como material de apoio didático para aulas de Visão Computacional.  
Ele integra diferentes técnicas de detecção facial em um único notebook, com foco em aprendizado progressivo e prática guiada.
