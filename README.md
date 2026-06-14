# Adaptive Brain-Stim Laboratory (v3.0)

Welcome to the **Adaptive Brain-Stim Laboratory** — a premium, high-fidelity neuro-hacking and sensory entrainment dashboard. By pairing Web Audio API physical synthesis with local Reinforcement Learning (Q-learning) and simulated Recursive Self-Improvement (RSI), this application explores the intersection of audio DSP, automated cognitive optimization, and closed-loop feedback.

## 🚀 Key Features

### 1. Cyberpunk Dashboard Interface
A premium dark-themed web application styled with glowing neon accents, responsive glassmorphic cards, and high-performance visualizers. Styled using modern vanilla CSS variables for a custom, light-weight look.

### 2. Multi-Module Sound Synthesis Engine (Web Audio API)
Unlike standard media players, all audio in the lab is synthesized in real-time inside your browser using mathematical oscillators and noise generators:
- **Groove Focus Sequencer**: An 8-step sequencer triggering kick, snare, hats, and a detuned FM Bass synthesizer playing pentatonic progressions.
- **Binaural Calm Pad**: Left/right split carrier frequencies that target binaural entrainment, paired with warm detuned sawtooth pads sweeping via a low-frequency oscillator (LFO).
- **Scale Beeps (Generative)**: Generates random melodic tones quantized to chosen scales (Pentatonic, Dorian, Phrygian Dominant, Chromatic) with occasional high-volume pitch-deviants.
- **ASMR & Cat Purr**: Produces randomized micro-noise taps alongside a 25Hz low-frequency sawtooth purr modulated by a slow breathing LFO (inhale/exhale volume sweep).
- **Tibetan Singing Gong**: Uses modal synthesis to model six metallic resonant frequencies decaying at different rates, combined with a 4.2Hz pulsing vibrato.
- **Coffee Machine Simulator**: Synthesizes pink noise coffee grinder hums, rapid high-Q bandpass bubble pops, and steam vent expansion sweeps.

### 3. Neural Wave & Lobe Monitor
- **Spectral Audio FFT**: A real-time canvas visualization of the master synthesizer frequencies.
- **Virtual EEG scrolling monitor**: Simulates and plots Delta ($\Delta$), Theta ($\Theta$), Alpha ($\alpha$), Beta ($\beta$), and Gamma ($\gamma$) wave bands based on playing audio modules.
- **Brain Lobe Map**: A pulsing vector SVG map that illuminates and highlights the lobes (Frontal, Temporal, Parietal, Occipital) corresponding to the dominant brainwave state.

### 4. Reinforcement Q-Learning Engine
- Treatment presets are modeled as discrete actions. Cognitive states are modeled as three states (`calm`, `focus`, `dread`).
- Learns the optimal stimulus mapping by applying the **Bellman Equation** to user session ratings.
- Tracks and displays Q-values in a live 2D grid, alongside a canvas-based reward historical line chart.

### 5. Autonomous Agents
- **Closed-Loop Neuro-Agent**: Evaluates real-time virtual EEG outputs to automatically simulate ratings, update the Q-table, and pick the next stimulus.
- **RSI Genetic Code Mutator**: A retro terminal interface simulation showing Git-style diffs of audio synthesis kernels. When a mutation is triggered, parameters (like carrier frequencies or BPM) are audibly modified in the active sound context.

---

## 🎧 Interactive Presets

- **Active Focus**: Sequences a medium-tempo drum loop and a pentatonic bassline paired with focus beeps to entrain Beta waves.
- **Deep Theta**: Pairs a low-frequency carrier beat ($4.5\text{ Hz}$ difference) and slow ASMR taps to stimulate deep meditation.
- **TikTok Rot (Meme Mode)**: Overstimulates the system at 160 BPM, chromatic beeps, and rapid amplitude modulation bursts to spike Gamma/Beta waves.
- **Zen Gong**: Triggers the resonant Tibetan singing bowl alongside a Schumann resonance binaural beat ($7.8\text{ Hz}$).
- **Bubble Cafe**: Blends the warm, low-frequency purr of a cat with the liquid bubbling and steam vents of a coffee shop.

---

## 🛠 How to Run

1. Make sure you have a modern web browser (Chrome, Edge, Firefox, or Safari).
2. Double-click the [index.html](file:///C:/Users/kai99/Desktop/New%20folder%20(2)/index.html) file, or open it in your browser.
3. Click the **Initialize Audio** button (or click any of the preset buttons) to start the Web Audio API context.
4. *Recommendation*: Use headphones to get the full spatialized effects of the Binaural and ASMR modules.
