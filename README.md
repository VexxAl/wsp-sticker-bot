# wsp-sticker-bot

Bot de WhatsApp que convierte cualquier imagen recibida en un sticker (.webp) y responde con ella en ese formato.

## Motivación

La función nativa de WhatsApp para crear stickers tiene dos limitaciones:

1. Agrega un borde blanco no deseado al adaptar la imagen a cuadrado.
2. Requiere tener la imagen guardada en la galería del dispositivo.

Este proyecto resuelve ambas: procesa la imagen con relleno transparente en vez de blanco, y funciona con cualquier imagen que le llegue al bot (pegada, reenviada, etc.), sin pasos intermedios.

## Stack

- **WhatsApp Business Cloud API** (Meta) — recepción y envío de mensajes
- **n8n** (self-hosted) — orquestación del flujo
- **[procesamiento de imagen — a definir]**

## Arquitectura

_(diagrama y explicación — pendiente)_

## Estado del proyecto

En desarrollo — Hito 1: setup base

## Setup

_(instrucciones de instalación/despliegue — pendiente)_

## Licencia

_(a definir)_
