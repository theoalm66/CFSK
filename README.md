# CFSK-Protocol V1.0

> **Information Hidden in Plain Noise**
> Ein stochastisches Modulationsverfahren für Low-Energy-Kommunikation, basierend auf Kettenbrüchen (Continued Fractions).
> A stochastic modulation method for low-energy communication, based on continued fractions.

🌐 **Live Demo / Landing Page:** `index.html` (Deutsch / English / Español)

---

## 🇩🇪 Deutsch

### Über CFSK

CFSK ist ein stochastisches Modulationsverfahren für die Low-Energy-Kommunikation. Es nutzt die mathematische Kohärenz von Kettenbruch-Algorithmen (Continued Fractions), um Daten deterministisch unterhalb des Rauschens zu kodieren.

Der Name setzt sich wie folgt zusammen:

| Buchstabe | Bedeutung | Beschreibung |
|---|---|---|
| **C** | Continued Fraction | Mathematische Begründung: logarithmische Kettenbrüche als hochpräzise Filter zur Informationsdarstellung im Chaos. |
| **F** | Fractional / Frequency | Fraktale Einbettung im Frequenzraum, die die Skaleninvarianz des Signals ermöglicht. |
| **SK** | Shift Keying | Übertragung von Information durch gezielte Wechsel der mathematischen Signatur. |

### Mathematisches Fundament

Das Prinzip der logarithmischen Kodierung basiert auf der Übertragung von Zuständen in einen Kettenbruchraum. Diese Transformation ermöglicht es, Daten in scheinbar chaotischen Rauschstrukturen unterzubringen, die zu 100 % deterministisch dekodierbar sind:

```
ln(f/f0) = n0/z + z/(n1 + z/(n2 + ... + z/nk)) = [z, n0; n1, n2, ..., nk]
```

Mit der Einführung mehrdimensionaler Phasen/Kanäle und der **O(1) Turbo-Vektor-Berechnung** wird ein Quantensprung in der Informationsverdichtung erreicht — Berechnungen erfolgen in Echtzeit über vorberechnete Matrizen.

### Aktuelle Implementierungen

- **GS-AUDIO-STEGANOGRAFIE PRO (GUI & Auto-Extension Edition)**
  - 256-QAM (8 Bit pro Sample) Vektor-Turbo
  - AES-256 Verschlüsselung (optional)
  - Automatischer Metadaten-Header zur Endungswiederherstellung
- **GS-AUDIO-STEGANOGRAFIE (5D RAW – Crystal Clear 7-Bit Edition)**
  - 0 fehlende Zustände — 100 % Bit-Genauigkeit, kein Rauschen nach der Dekodierung
  - Automatischer Payload-Header zur Reparatur von Mono/Stereo und Pitch
  - Inklusive O(1) Turbo-Vektor-Berechnung

### Anwendungsgebiete

- **Weltraum & Satellitenkommunikation (Deep Space):** Extrem schwaches SNR (< 0 dB) — das Signal *ist* das Rauschen.
- **IoT & Edge Computing (Ultra-Low-Power):** Millionen Sensoren senden interferenzfrei im selben Band.
- **Steganographische Verschlüsselung:** Plausible Deniability — kein Signal ist erkennbar.
- **LPI Radar & Sonar:** Low Probability of Intercept — das Signal sieht aus wie atmosphärisches Rauschen.
- **Astrophysik:** Analyse kosmischen Rauschens auf extraterrestrische CFSK-Strukturen (SETI).
- **Neuromorphes Computing:** Information liegt bereits in der Rauschstruktur (Stochastic Computing).
- **Post-Quantum Crypto:** Physikalische Zusatzschicht, die nicht gehackt werden kann.
- **Medizin & Finanzen:** Unhörbare Wasserzeichen, strahlungsarme Implantate und Covert-Trading-Signale.

### Repository-Inhalt

| Datei | Beschreibung |
|---|---|
| `index.html` | Mehrsprachige Landing Page (DE/EN/ES) mit interaktiver Visualisierung |
| `diagram_log_coding.png` | Diagramm zur logarithmischen Kodierung |
| `diagram_turbo_matrix.png` | Diagramm zur O(1)-Turbo-Vektor-Matrix |
| `diagram_5d_spheres.png` | Diagramm zur 5D-RAW-Holographie |

### Lokal ansehen

```bash
# Repository klonen
git clone <repo-url>
cd CFSK

# index.html im Browser öffnen
open index.html   # macOS
# oder: xdg-open index.html (Linux) / start index.html (Windows)
```

### Lizenz

© 2026 CFSK Protocol Initiative

---

## 🇬🇧 English

### About CFSK

CFSK is a stochastic modulation method for low-energy communication. It utilizes the mathematical coherence of continued fraction algorithms to deterministically encode data beneath the noise floor.

The name breaks down as follows:

| Letter | Meaning | Description |
|---|---|---|
| **C** | Continued Fraction | The mathematical foundation: logarithmic continued fractions as high-precision filters for information representation within chaos. |
| **F** | Fractional / Frequency | Fractal embedding in the frequency domain, enabling scale invariance of the signal. |
| **SK** | Shift Keying | Transmitting information through targeted shifts of the mathematical signature. |

### Mathematical Foundation

The principle of logarithmic encoding is based on mapping states into a continued fraction space. This transformation allows data to be embedded in seemingly chaotic noise structures that are 100% deterministically decodable:

```
ln(f/f0) = n0/z + z/(n1 + z/(n2 + ... + z/nk)) = [z, n0; n1, n2, ..., nk]
```

With the introduction of multi-dimensional phases/channels and the **O(1) Turbo-Vector Calculation**, a quantum leap in information density is achieved — computations are handled in real time via pre-calculated matrices.

### Current Implementations

- **GS-AUDIO-STEGANOGRAPHY PRO (GUI & Auto-Extension Edition)**
  - 256-QAM (8 bits per sample) Vector-Turbo
  - AES-256 encryption (optional)
  - Automatic metadata header for extension recovery
- **GS-AUDIO-STEGANOGRAPHY (5D RAW – Crystal Clear 7-Bit Edition)**
  - 0 missing states — 100% bit accuracy, absolutely no noise after decoding
  - Automatic payload header repairs mono/stereo and pitch
  - Includes corresponding O(1) Turbo-Vector Calculation

### Applications / Use Cases

- **Space & Satellite Communication (Deep Space):** Extremely weak SNR (< 0 dB) — the signal *is* the noise.
- **IoT & Edge Computing (Ultra-Low-Power):** Millions of sensors transmit interference-free in the same band.
- **Steganographic Encryption:** Provides plausible deniability, as no signal is detectable.
- **LPI Radar & Sonar:** Low Probability of Intercept — the radar signal appears as atmospheric noise.
- **Astrophysics:** Analyzing cosmic noise for extraterrestrial CFSK structures (SETI).
- **Neuromorphic Computing:** Information is native to the noise structure (stochastic computing).
- **Post-Quantum Crypto:** A physical additional layer that resists hacking.
- **Medicine & Finance:** Inaudible watermarks, ultra-low-radiation implants, and covert trading signals.

### Repository Contents

| File | Description |
|---|---|
| `index.html` | Multilingual landing page (DE/EN/ES) with interactive visualization |
| `diagram_log_coding.png` | Diagram of logarithmic coding |
| `diagram_turbo_matrix.png` | Diagram of the O(1) Turbo-Vector matrix |
| `diagram_5d_spheres.png` | Diagram of the 5D RAW holography |

### View Locally

```bash
# Clone the repository
git clone <repo-url>
cd CFSK

# Open index.html in your browser
open index.html   # macOS
# or: xdg-open index.html (Linux) / start index.html (Windows)
```

### License

© 2026 CFSK Protocol Initiative
