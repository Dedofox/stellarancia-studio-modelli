# Stellarancia Studio — risorse facoltative della Webapp

File scaricati dalla Webapp di Stellarancia Studio (https://stellarancia.com/studio-app/) solo quando l'utente installa
OCR, traduzione offline o protezione dei PDF. La Webapp li verifica con SHA-256 prima di conservarli sul dispositivo.
Pubblicati con GitHub Pages; stellarancia.com li inoltra da `/studio-app/optional/`.

Contenuto e licenze (testi completi e provenienza in `avvisi/`):
- `translation-it-en`, `translation-en-it`: modelli OPUS-MT (Helsinki-NLP), CC BY 4.0, convertiti in ONNX.
- `runtime`: ONNX Runtime Web (MIT) e Transformers.js (Apache 2.0).
- `ocr`: Tesseract.js (Apache 2.0) e modelli tessdata (Apache 2.0).
- `qpdf`: qpdf compilato in WebAssembly (Apache 2.0).

Non modificare i file a mano: l'elenco con le impronte sta in `models-manifest.json` della Webapp.
