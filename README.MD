# Auto Rebass

# Interface

<img width="1216" height="2405" alt="1000378953" src="https://github.com/user-attachments/assets/3ef0d08b-22e5-4d81-89fd-92cbe92ae6b3" />

**Look At All These Effects!**

<img width="1216" height="7729" alt="1000378957" src="https://github.com/user-attachments/assets/0da33842-dbd4-48a6-9f41-f8cd9e708490" />

Auto Rebass is a real-time audio processing application designed for system-wide audio rebassing and subharmonic frequency division. It captures system audio output, applies real-time DSP to synthesize subharmonic content based on the detected fundamental frequency, and mixes it back into the audio stream.

## Core Features

**Using Cast and a Pop-Over**

<img width="1216" height="2688" alt="1000378960" src="https://github.com/user-attachments/assets/2da46204-0bd9-4438-be73-1dd16e095d6d" />
<img width="1216" height="2688" alt="1000378959" src="https://github.com/user-attachments/assets/4a042111-cf5e-465d-8f91-999b9d865a7c" />
<img width="1216" height="2688" alt="1000378958" src="https://github.com/user-attachments/assets/cd51c03b-01d2-4cb7-8546-144c41f2da3e" />


- **System Audio Capture**: Captures audio output from other applications using Android MediaProjection.
- **Subharmonic Synthesis**: Detects fundamental frequencies in real-time and synthesizes subharmonic content to reinforce low-end frequencies.
- **DSP Pipeline**:
  - **Parametric Equalization**: 12-band equalizer for precise frequency shaping.
  - **Dynamics Processing**: Auto-clipping, compression, and sidechain ducking.
  - **Filter Bank**: State-variable and analog ladder filters for sound design.
  - **Effects**: Huge list of effects. Reverb, stereo imaging, and saturation.
- **Auto-Retiming**: Advanced algorithm to maintain phase correlation and timing alignment between processed audio streams.

## Themes!

<img width="1216" height="2688" alt="1000378942" src="https://github.com/user-attachments/assets/f9d6f154-a521-43a2-bf52-440f978b2c6b" />


<img width="1216" height="2688" alt="1000378943" src="https://github.com/user-attachments/assets/f973bcdc-bab4-4632-a217-fff42b72e7c7" />

<img width="1216" height="2688" alt="1000378967" src="https://github.com/user-attachments/assets/901ac6cc-a9ed-402e-965c-984c4a693f5c" />
<img width="1216" height="2688" alt="1000378966" src="https://github.com/user-attachments/assets/95143bad-6552-4b88-8909-169ab7f21c39" />
<img width="1216" height="2688" alt="1000378965" src="https://github.com/user-attachments/assets/935017d2-0b6e-4a82-9d1b-b357e30a399b" />
<img width="1216" height="2688" alt="1000378961" src="https://github.com/user-attachments/assets/321d0995-bffc-42e0-ac46-96b792a90fb2" />
<img width="1216" height="2688" alt="1000378962" src="https://github.com/user-attachments/assets/48005f13-807a-4953-bb9e-45c711046c40" />
<img width="1216" height="2688" alt="1000378964" src="https://github.com/user-attachments/assets/612e98f6-6cb7-475c-95bd-d5e60c1d8399" />
<img width="1216" height="2688" alt="1000378963" src="https://github.com/user-attachments/assets/ba8fba0b-3804-4bfc-ac3e-9bba083764c2" />

## Technical Implementation

- **Language**: Kotlin
- **Framework**: Jetpack Compose (Material 3)
- **Audio Engine**: Custom DSP implementation utilizing AudioRecord and AudioTrack for low-latency processing.
- **Persistence**: Database for managing audio settings and graph configurations.
- **Concurrency**: Kotlin Coroutines and StateFlow for managing heavy audio processing tasks on background threads.

## Default Settings

- **Input Gain**: 0.0 dB
- **Sub Mix Gain**: 0.5
- **Crossover Cutoff**: 80 Hz
- **Bass Delay**: 0.0 ms
- **Music Delay**: 25.0 ms
- **Noise Gate**: -60.0 dB
- **Wet/Dry Mix**: 0.5
- **Auto-Clipping**: Enabled
- **Bass Replacement**: Enabled
- **Bass Tune**: Enabled
- **BPM Quantization**: Enabled
- **Pure Note Mode**: Enabled
- **Native EQ Mode**: Enabled
- **Invert Phase**: Disabled
- **Auto-Retime**: Disabled
