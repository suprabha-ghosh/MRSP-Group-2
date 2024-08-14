# Perceptual Similarity Analysis of Audio Stimuli

## Overview
This project investigates the perceptual similarity between different audio stimuli using both objective and subjective measures. Our primary objective was to assess the perceptual loss introduced by various audio compression techniques and environments.

## Key Findings

### Objective Analysis: Perceptual Loss
- **Quantization vs. AAC Encoding**:
  - **AAC Encoding**: Demonstrated lower perceptual loss, especially in ambient, instrumental, and piano music.
  - **Quantization**: Preserved perceptual quality better than AAC for poetry.
- **Environmental Impact**:
  - The type of acoustic environment (e.g., Opera Hall, Reverb Hall, Small Office) significantly affected perceived audio quality and influenced perceptual loss values.

### Subjective Analysis: MUSHRA Listening Tests
- **Setup and Methodology**:
  - Conducted MUSHRA tests with 19 participants in a controlled environment to evaluate perceived audio quality across different sound types and acoustic environments.
- **Results**:
  - Subjective listening tests generally aligned with objective analysis, confirming that AAC encoding provided higher perceptual quality for most audio types, except poetry.

### Genre-Specific Observations
- **Poetry**: Quantization was more effective, likely due to the need for clarity and precision in speech.
- **Ambient and Instrumental**: AAC’s advanced algorithms better handled the complexity and variability, resulting in lower perceptual loss.
- **Piano and Drumbeat**: AAC's sophisticated compression preserved rich harmonics and rhythmic elements, making it particularly beneficial for these genres.

## Practical Implications
- **Tailored Processing**: The choice of audio processing method should be tailored to the content type to balance file size reduction and audio quality.
  - **AAC Encoding**: Preferable for complex and rich soundscapes.
  - **Quantization**: More suitable for spoken word content, such as poetry.

## Future Directions
- Further research could focus on refining encoding strategies and optimizing environmental settings to minimize perceptual loss in various audio applications.
- Understanding these factors is crucial for enhancing audio processing workflows, particularly in the media and communication industries.
