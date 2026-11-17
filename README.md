# Digital Stethoscope — Biomedical Engineering Research

**2024 Master's thesis at Universidad Internacional de Valencia (VIU)**  
**Biomedical audio acquisition | Electronic instrumentation | Cardiac auscultation**

This repository documents the engineering work behind a digital stethoscope developed as part of a **Master's Degree in Biomedical Engineering at VIU in 2024**. The project focused on capturing and processing cardiopulmonary sounds with electronic instrumentation while preserving clinically interpretable acoustic information.

The original study was designed at VIU. **According to the project author, the 2024 prototype was evaluated at Hospital de Clínicas in La Paz, Bolivia, and the recordings were assessed by cardiologists.** The clinical observations reported by the author included **gallop rhythms** and **irregular cardiac rhythms**. The original medical records, individual diagnostic labels, ethics documentation, and quantitative diagnostic-accuracy results have not been supplied for this public repository. Accordingly, this is presented as *clinician-reviewed exploratory research*, not as proof of independent diagnostic accuracy.

> **Scope:** A research and engineering portfolio case study. This is not a certified medical device, a clinical diagnosis service, or an automated arrhythmia diagnostic system.

## Engineering contributions

- Built an approach for **digital acquisition of cardiopulmonary acoustic signals** using an electronic sensing and signal-processing chain.
- Worked on **signal recording, digitization, and playback**, supporting review of cardiac acoustic events.
- Evaluated the usability of recorded heart sounds for **physician-led auscultatory interpretation**, according to the project's 2024 study history.
- Investigated integration of **acoustic sensing, embedded electronics, and digital signal processing** within a biomedical instrumentation prototype.

## Historical development and current research

| Period | Project stage | Status |
| --- | --- | --- |
| **2024 — VIU** | Original digital stethoscope and master's thesis; pilot recordings assessed by cardiologists at Hospital de Clínicas, as reported by the author | Historical study; supporting clinical documents not published here |
| **2026 — UNIVALLE** | Follow-on research towards a modular, reversible stethoscope interface and updated embedded acquisition architecture | Separate redesign in development; **the 2024 clinical observations must not be treated as validation of this new hardware** |

### System overview

```text
Acoustic heart sounds
       │
       ▼
Acoustic coupling / transducer
       │
       ▼
Signal conditioning and digitization
       │
       ▼
Digital audio recording
       │
       ├── Listening / clinical review by a qualified practitioner
       └── Signal visualization and research analysis
```

This is a functional block diagram; it does not disclose the proprietary circuit design or claim a specific hardware configuration for the 2024 device.

## Audio examples

Two demonstration recordings have been provided to the project author but **are not publicly released** because publication permissions and their clinical provenance have not been confirmed. Neither sample has been assigned a clinical diagnosis.

| Material | Publication status |
| --- | --- |
| Two digital cardiac-audio demonstration recordings | Withheld pending permissions and provenance verification |
| Waveforms and spectrograms derived from those recordings | Withheld pending the same review |

**Release gate:** Recordings and derived figures remain excluded until authorized. See the [publication checklist](docs/PUBLICATION_CHECKLIST.md).

## Clinical interpretation and limitations

A **gallop rhythm** is an auscultatory finding often associated with an additional heart sound (S3 or S4); it is not itself a standalone disease diagnosis. An **irregular audible rhythm** can prompt investigation for arrhythmia, but definitive arrhythmia diagnosis generally relies on electrocardiographic assessment. This project does not claim automated pathology classification, diagnostic sensitivity/specificity, or validated performance across clinical populations.

## Documentation

- [2024 clinical research history and evidence status](docs/CLINICAL_BACKGROUND.md)
- [Audio sharing policy](samples/README.md)
- [Publication checklist and permissions](docs/PUBLICATION_CHECKLIST.md)
- [Next-generation research scope](docs/CURRENT_RESEARCH.md)

## Repository boundaries

**Firmware, source code, detailed PCB or circuit designs, raw patient datasets, and unpublished study material are not included.** Technical implementation remains in a restricted development workspace. No code license is provided by this overview. Please contact the author for legitimate scientific or technical collaboration.

## Researcher

**Renan Andres Espinar Saavedra**  
Mechatronics Engineer · Master's Degree in Biomedical Engineering  
[GitHub portfolio](https://github.com/RenanEspinar)
