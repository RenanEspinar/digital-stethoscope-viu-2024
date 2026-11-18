
# Digital Stethoscope — Biomedical Engineering Research

**2024 Master's Thesis | Universidad Internacional de Valencia (VIU)**

Biomedical Audio Acquisition · Electronic Instrumentation · Cardiac Auscultation · Digital Signal Processing

**Researcher:** Renan Andres Espinar Saavedra  
**Location:** La Paz, Bolivia  
**Research period:** 2024–Present

---

## Project Overview

This repository documents the research, design and development of a digital stethoscope originally created in 2024 as part of a Master's Degree in Biomedical Engineering at the Universidad Internacional de Valencia (VIU), Spain.

The project investigated the acquisition, digitization, processing and reproduction of cardiopulmonary acoustic signals using electronic instrumentation.

The objective was to preserve clinically relevant acoustic information while enabling digital recording, signal analysis and physician-led auscultation.

According to the project author, the original prototype underwent exploratory clinical evaluation at Hospital de Clínicas in La Paz, Bolivia, with recordings reviewed by cardiologists.

Reported clinical observations included gallop rhythms, irregular cardiac rhythms and other auscultatory findings.

Individual patient records, clinical classifications, ethics documentation and quantitative diagnostic-accuracy results are not included in this public repository.

**Research scope:** This project documents biomedical instrumentation research. It is not a certified medical device or an independently validated automated diagnostic system.

---

## Cardiac Audio Recordings

The following recordings demonstrate the acquisition of cardiac acoustic signals using the research prototype.

Both samples are available directly from this README.

### Recording 01 — Cardiac Auscultation

**Duration:** 15.35 seconds  
**Format:** WAV · 22,050 Hz · Mono

### [▶ LISTEN TO CARDIAC RECORDING 01](https://raw.githubusercontent.com/RenanEspinar/digital-stethoscope-viu-2024/main/samples/audio_output_fine%20%281%29.wav)

[View original WAV file](samples/audio_output_fine%20%281%29.wav)

---

### Recording 02 — Cardiac Auscultation

**Duration:** 24.40 seconds  
**Format:** WAV · 22,050 Hz · Mono

### [▶ LISTEN TO CARDIAC RECORDING 02](https://raw.githubusercontent.com/RenanEspinar/digital-stethoscope-viu-2024/main/samples/audio_output2_fine.wav)

[View original WAV file](samples/audio_output2_fine.wav)

---

### Audio Documentation

These recordings demonstrate the digital capture and reproduction of cardiac acoustic signals.

The recordings are presented without individual diagnostic labels.

Although the original research involved physician-led evaluation, no specific diagnosis is attributed to either published recording without its corresponding clinical documentation.

The recordings should not be interpreted as evidence of independently validated diagnostic sensitivity or specificity.

**Publication note:** The WAV files are publicly accessible. Individual clinical provenance and publication permissions have not been independently verified in this repository. Appropriate patient consent and institutional authorization are required for public dissemination of clinical recordings.

**Playback:** Depending on the browser, selecting a recording will open its audio player or download the WAV file. GitHub does not provide embedded audio playback controls within Markdown READMEs.

---

## Engineering Contributions

The project involved the integration of biomedical sensing, electronic instrumentation and computational signal processing.

Key engineering activities included:

- Development of an electronic system for acquiring cardiopulmonary acoustic signals.
- Integration of acoustic transducers and electronic instrumentation.
- Acquisition and digitization of physiological audio signals.
- Digital recording and reproduction of cardiac sounds.
- Investigation of signal conditioning and noise reduction.
- Visualization and analysis of recorded physiological signals.
- Experimental evaluation of signal acquisition and playback.
- Assessment of the recorded signals for physician-led clinical interpretation.

The research provided a foundation for subsequent development of embedded biomedical acquisition systems.

---

## System Architecture

The original research investigated a signal acquisition and processing architecture consisting of the following functional stages:

```text
          CARDIAC ACOUSTIC SIGNAL
                    |
                    v
          ACOUSTIC TRANSDUCER
                    |
                    v
          SIGNAL CONDITIONING
                    |
                    v
          ANALOG-TO-DIGITAL
               CONVERSION
                    |
                    v
          DIGITAL ACQUISITION
                    |
                    v
          SIGNAL PROCESSING
                    |
           +--------+--------+
           |                 |
           v                 v
      AUDIO RECORDING   SIGNAL ANALYSIS
           |                 |
           v                 v
      AUDIO PLAYBACK     VISUALIZATION
           |                 |
           +--------+--------+
                    |
                    v
          CLINICAL INTERPRETATION
          BY QUALIFIED PHYSICIANS
```

This functional architecture describes the research workflow without disclosing proprietary circuit designs or implementation details.

---

## Research History

### 2024 — Universidad Internacional de Valencia

**Master's Thesis: Digital Stethoscope**

The initial research was developed within the Master's Degree in Biomedical Engineering at VIU.

The project addressed electronic auscultation, biomedical acoustic signal acquisition and digital processing.

According to the project author, exploratory evaluations were performed at Hospital de Clínicas, La Paz, with physician-led interpretation of acquired cardiac recordings.

The reported observations included additional heart sounds consistent with gallop rhythms and irregular cardiac rhythms.

These observations are documented as historical research findings reported by the author, rather than independently verified diagnostic-performance claims.

### 2026 — Universidad del Valle (UNIVALLE)

**Intelligent Digital Stethoscope — Research Continuation**

Subsequent research focuses on developing an updated biomedical acquisition platform using modular electronic instrumentation and embedded processing.

Research directions include:

- Improved acoustic coupling and signal acquisition.
- Embedded hardware integration.
- Digital signal processing.
- Wireless communication.
- Physiological audio recording.
- Signal visualization.
- Experimental validation of updated hardware.

The 2026 development represents a separate hardware research iteration.

Clinical observations from the 2024 study must not be interpreted as validation of the redesigned hardware.

---

## Clinical Research Context

Cardiac auscultation provides information about heart sounds, rhythm, murmurs and additional acoustic events.

Digital acquisition enables physiological sounds to be recorded, reproduced and analyzed.

During the original research, the clinical assessment described by the author involved cardiologists reviewing recorded acoustic signals.

Reported findings included:

- Gallop rhythms and additional heart sounds.
- Irregular audible cardiac rhythms.
- Other clinically relevant auscultatory observations.

A gallop rhythm is an auscultatory finding associated with additional heart sounds, commonly S3 or S4.

An irregular audible cardiac rhythm may indicate the need for further clinical investigation, but definitive diagnosis of an arrhythmia generally requires electrocardiographic assessment.

The project does not claim automatic diagnosis, validated pathology classification or quantified diagnostic accuracy.

---

## Technical Areas

**Biomedical Engineering**
- Electronic auscultation
- Biomedical instrumentation
- Physiological sensing
- Medical-device prototyping

**Signal Acquisition and Processing**
- Acoustic signal acquisition
- Analog-to-digital conversion
- Digital audio recording
- Signal conditioning
- Signal visualization

**Mechatronics and Embedded Systems**
- Sensor integration
- Electronic prototyping
- Embedded system architecture
- Hardware-software integration
- Experimental validation

---

## Repository Structure

```text
digital-stethoscope-viu-2024/
|
|-- README.md
|
|-- samples/
|   |-- audio_output_fine (1).wav
|   |-- audio_output2_fine.wav
|   |-- README.md
|
|-- docs/
|   |-- CLINICAL_BACKGROUND.md
|   |-- CURRENT_RESEARCH.md
|   |-- PUBLICATION_CHECKLIST.md
|
|-- .gitignore
```

The original firmware, detailed electronic schematics, source code and unpublished research materials are not included in this public repository.

---

## Documentation

- [Clinical Research Background](docs/CLINICAL_BACKGROUND.md)
- [Current Research and Development](docs/CURRENT_RESEARCH.md)
- [Publication and Research Documentation Checklist](docs/PUBLICATION_CHECKLIST.md)
- [Audio Samples Directory](samples/)

---

## Research Limitations

This repository documents engineering research and exploratory clinical observations.

The original study's supporting clinical records, individual case descriptions and formal diagnostic-performance metrics have not been published here.

Audio recordings alone cannot establish the presence of a specific cardiac pathology without appropriate clinical interpretation and supporting examination data.

The experimental device should not be used as a replacement for certified diagnostic medical equipment.

---

## Researcher

**Renan Andres Espinar Saavedra**

Mechatronics Engineer  
University Master's Degree in Biomedical Engineering

Research Coordinator for Technology and Computer Science  
Universidad del Valle — UNIVALLE

La Paz, Bolivia

**Research interests:** Biomedical instrumentation, medical-device development, physiological signal processing, embedded systems, intelligent medical technologies and applied engineering research.

**GitHub:** [github.com/RenanEspinar](https://github.com/RenanEspinar)

**ORCID:** [0009-0007-1918-7177](https://orcid.org/0009-0007-1918-7177)

---

*Biomedical engineering research project originally developed at Universidad Internacional de Valencia (2024), with subsequent research activities at Universidad del Valle (2026).*
