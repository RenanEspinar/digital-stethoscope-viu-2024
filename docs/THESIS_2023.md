# VIU Master's Thesis — technical record (2023)

**Full title:** *Diseño de un prototipo de sistema de estetoscopio electrónico para digitalizar y procesar sonidos cardíacos.*\
**Author:** Renán Andrés Espinar Saavedra\
**Program:** Máster Universitario en Ingeniería Biomédica, Universidad Internacional de Valencia (VIU)\
**Academic period:** 2022–2023\
**Defense period appearing on cover:** 20–24 November 2023\
**Director:** Aldo Eleazar Pérez Ramos\
**Source:** "21MIBI E2 ESPINAR SAAVEDRA RENAN.pdf", 60 pages. The original research manuscript and supporting medical documentation are retained by the researcher.

## Problem and objectives

The master's thesis sought to capture cardiac sounds, digitize them, filter noise, enable portable transmission, and make recordings available for review. The specific objectives (p. 10) address signal acquisition and transmission, DSP, and feedback from medical personnel.

## Engineering implementation

1. **Input and analog gain (pp. 18–20):** a microphone coupled to a conventional stethoscope head; comparison of MAX9814, MAX9812/13 and MAX4465-family options; selection of **MAX9814** in the reported design.
2. **Wi-Fi/embedded platform (pp. 20–24):** ESP32-family hardware and the Arduino audio tools / AudioWAVServer approach, with firmware printed in Annex A.
3. **Python receiver (pp. 25–26):** desktop reception, local audio reproduction, streaming interruption, and WAV recording.
4. **DSP (pp. 25–28, 33–34):** FFT spectral inspection, configurable real-time frequency processing and an offline FIR band-pass filter for WAV data. The thesis includes time-domain and frequency-domain plots.
5. **GUI (pp. 31–34):** Tkinter interface showing the device URL, recording controls, WAV selection, spectrum visualization, cutoff settings and fields for documenting an auscultation session.
6. **Mechanical design (pp. 29–30, 58–59):** enclosure CAD, drawing details and a photograph of the assembled prototype; the thesis states that SLS printing was used.

## Experimental evidence

The research documented five cardiac sound recordings acquired at Hospital de Clínicas (La Paz) and reviewed by medical specialists (pp. 35–39, Table 4.1). The researcher maintains signed medical diagnostic certificates supporting the documented clinical findings, together with signed hospital authorization expressly permitting publication of the research recordings. These records document the medical assessment and publication authorization; the exploratory study was not designed to estimate statistical sensitivity or specificity.

## Reproducibility limitations

Although code listings are present in Annexes A, B and F, the extracted text is not a verified, deployable project. A fresh implementation requires pinout/circuit review, no hard-coded network credentials, dependency versions, verification of sample rate and byte order, calibration, noise measurement and signal-processing unit tests. The original filtering routines should be evaluated before describing their mathematical response as validated.

## Image provenance

- pp. 27–28: signal figures and software controls;
- p. 29: enclosure CAD drawings;
- p. 30: prototype CAD assembly and **real-device photograph**;
- pp. 31–34: graphical interface captures;
- p. 35: **patient photographs (excluded from this public engineering repository)**;
- pp. 36–38: plots from clinical recordings — treated as patient-derived research material;
- pp. 58–59: mechanical construction drawings.

The source PDF is not included because it contains clinical photographs and historical network configuration. The signed hospital authorization and medical diagnostic certificates are retained privately.
