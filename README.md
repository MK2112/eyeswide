# eyeswide: Deepfake Detection and Ethical Watermarking

eyeswide aims to address the concern of deepfakes and media authenticity. I want to beat the problem by utilizing its cause: AI. Also I felt inspired by what [DARPA](https://govciomedia.com/darpa-launches-new-programs-to-detect-falsified-media/) has been doing in this field.<br>
Processing a piece of media should explainably yield a quantitative scalar value of certainty for integrity, which then can enable prioritization and/or filtering of authentic media on a broader scale.
Also, because I never worked with it (and hope the weird hype died down around it), I want to integrate a blockchain-based media-score watermarking system for transparency.

By definition, such a system has to be:

- built in the open and has to be kept there,
- be privacy-preserving through data protection,
- scalable to handle variable volumes of media inputs,
- understandable in its derivation of the certainty for integrity,
- transparent with its own limitations.

## Roadmap

### Foundation
- [ ] Conduct literature review on deepfake detection (capture the SOTA)
- [ ] Analyze DARPA's MediFor and SemaFor programs for insights
- [ ] View diverse datasets of authentic and manipulated media, investigate synthetic generation options

### Core Development
- [ ] Develop multi-headed/multi-modal core analysis system (visual, audio, text)
- [ ] Implement first iteration of quantitative integrity scoring algorithm
- [ ] Integrate xAI for detection reasoning (interpret attention layer? etc.)
- [ ] Performance and Efficiency Optimization

### Blockchain Drafting
- [ ] Test blockchain architecture for secure score storage
- [ ] Implement ethical watermarking system to be verifiable via blockchain (3301 did this with GPG e.g.)

### Integration and UI
- [ ] Build APIs for AI models, blockchain, and front-end interaction
- [ ] Make UI for media upload and analysis
- [ ] Implement back-to-back privacy-preserving data protection measures
