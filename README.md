# Pedestrian and Vehicle Orientation Detection on Picar-X using YOLOv11s

## Descrizione

Questo paper presenta lo sviluppo di un sistema di object detection in tempo reale per la piattaforma Picar-X basata su Raspberry Pi, in grado di rilevare pedoni e determinare l’orientamento dei veicoli (anteriore, posteriore, lato sinistro, lato destro). Il sistema si basa su un modello YOLOv11s ottimizzato per ambienti embedded mediante conversione nel formato **ONNX**.

## Caratteristiche

* Rilevamento pedoni su pista.
* Classificazione orientamento veicoli.
* Sistema di risposta automatica in base al contesto stradale.
* Ottimizzazione per Raspberry Pi (bassa latenza, inferenza rapida).
* Dataset annotato manualmente con **Label Studio**.

## Tecnologie Utilizzate

YOLOv11s, PyTorch, ONNX, Label Studio, Raspberry Pi 4, Picar-X, OpenCV, Sensori Ultrasonici, Python

## Requisiti

* Raspberry Pi 4 con sistema operativo Raspberry Pi OS
* Picar-X robot (con videocamera e sensori)
* Python 3.9+
* PyTorch + ONNX Runtime
* OpenCV
* Label Studio (per annotazione dataset)

## Autori

**Andrea Salurso**, **Francesca Avallone** – Università degli Studi di Salerno
Corso: *Fondamenti di Visione Artificiale e Biometria (2024/2025)*
