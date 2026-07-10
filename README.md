# Guía PALS 2025 · PWA

Aplicación web progresiva educativa para entrenamiento en soporte vital avanzado pediátrico.

## Funciones

- Instalación como PWA en dispositivos compatibles.
- Funcionamiento offline mediante Service Worker.
- Cálculos educativos por peso.
- Algoritmos guiados por escenario.
- Simulador de casos con cronómetro y registro de eventos.
- Dictado por voz en español.
- Guardado automático local.
- Debriefing estructurado con Advocacy–Inquiry.
- Tablas rápidas y checklist post-ROSC.
- Notas exportables.

## Uso local

Abra `index.html` mediante un servidor local. Para probar PWA y Service Worker se requiere HTTPS o `localhost`.

Ejemplo:

```bash
python3 -m http.server 8000
```

Después abra `http://localhost:8000`.

## GitHub Pages

Una vez fusionada la rama en `main`, configure GitHub Pages para publicar desde la rama `main` y la carpeta raíz.

## Aviso

Herramienta exclusivamente educativa para profesionales entrenados. No sustituye fuentes oficiales, protocolos locales, verificación independiente de dosis ni juicio clínico.