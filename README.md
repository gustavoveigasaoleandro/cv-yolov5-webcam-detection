# cv-yolov5-webcam-detection

Laboratorio de visao computacional para detecao de objetos em tempo real usando YOLOv5 e webcam.

## Conteudo

- `yolo_webcam_detection.ipynb`: notebook demonstrando o uso de YOLOv5 para inferencia em frames da camera.
- `requirements.txt`: dependencias diretas do experimento.

## Objetivo

O repositorio demonstra:

- configuracao de ambiente para YOLOv5;
- uso de modelo pre-treinado;
- captura de frames da webcam;
- inferencia visual em tempo real;
- separacao entre codigo proprio e repositorio de terceiros.

## Dependencias Externas

O codigo pode clonar ou usar o projeto oficial `ultralytics/yolov5` em tempo de execucao. A copia local completa do YOLOv5 nao foi versionada aqui para evitar republicar codigo de terceiros e artefatos desnecessarios.

## Como Executar

Instale dependencias basicas:

```bash
pip install -r requirements.txt
```

Abra o notebook:

```bash
jupyter notebook yolo_webcam_detection.ipynb
```

## Cuidados

O acesso a webcam depende do sistema operacional, permissoes locais e ambiente de execucao. Este repositorio e um lab de estudo, nao uma aplicacao empacotada para distribuicao.
