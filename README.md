# ✍️ Luft-Zeichnen & 🍉 Luft-Ninja

Zwei Browser-Anwendungen, die per Webcam die Hand erkennen und mit dem Zeigefinger gesteuert werden.

**[▶ Live ausprobieren](https://stanislavgrd.github.io/luft-zeichnen/)** (Webcam erforderlich)

## Luft-Zeichnen

Mit dem Zeigefinger in die Luft malen – die Linie erscheint auf dem Bildschirm.

- Rückgängig, Löschen und Speichern des Bildes
- Einstellbare Strichdicke
- Tafel-Modus (Kamerabild ausblenden)
- Tastenkürzel: Z, C, B, S

## Luft-Ninja

Ein Fruit-Ninja-Klon: Früchte mit schnellen Fingerbewegungen zerschneiden und den Bomben ausweichen.

## Technik

- HTML, CSS, JavaScript – ohne Framework, jeweils eine einzige Datei
- Handerkennung mit [MediaPipe Hand Landmarker](https://ai.google.dev/edge/mediapipe/solutions/vision/hand_landmarker)
- Das Kamerabild wird ausschließlich lokal im Browser ausgewertet
