# cv-yolov5-webcam-detection

Laboratório de visão computacional para detecao de objetos em tempo real usando YOLOv5 e webcam.

## Conteúdo

- `yolo_webcam_detection.ipynb`: notebook demonstrando o uso de YOLOv5 para inferência em frames da câmera.
- `requirements.txt`: dependências diretas do experimento.

## Objetivo

O repositório demonstra:

- configuração de ambiente para YOLOv5;
- uso de modelo pre-treinado;
- captura de frames da webcam;
- inferência visual em tempo real;
- separação entre código próprio e repositório de terceiros.

## Dependências Externas

O código pode clonar ou usar o projeto oficial `ultralytics/yolov5` em tempo de execução. A cópia local completa do YOLOv5 não foi versionada aqui para evitar republicar código de terceiros e artefatos desnecessarios.

## Como Executar

Instale dependências básicas:

```bash
pip install -r requirements.txt
```

Abra o notebook:

```bash
jupyter notebook yolo_webcam_detection.ipynb
```

## Cuidados

O acesso a webcam depende do sistema operacional, permissões locais e ambiente de execução. Este repositório e um lab de estudo, não uma aplicação empacotada para distribuição.
