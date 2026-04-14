# YOLOv5 Webcam Detection

Notebook de estudo com deteccao de objetos em tempo real usando YOLOv5 e webcam.

## Conteudo

- `yolo_webcam_detection.ipynb`: notebook principal com instalacao de dependencias, clone do YOLOv5 e inferencia em video.

## Como executar

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook yolo_webcam_detection.ipynb
```

## Observacoes

- O notebook baixa o repositorio `ultralytics/yolov5` em tempo de execucao.
- Este repositorio nao inclui a copia local de `yolov5`, pesos `.pt` ou outros arquivos de terceiros para evitar publicar codigo vendorizado desnecessariamente.
- O uso de webcam requer permissao local do sistema operacional.
