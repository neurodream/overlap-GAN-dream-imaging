# overlap-GAN-dream-imaging
**quick simulation whether (fuzzy) video readout from EEG sensors is feasible**   

---

- if there is a way to have some spatial resolution from EEG in the visual field (via beamforming maybe), then maybe a video’s semantics might be decipherable from very few locations of overlapping greyscales
- Inspired by: Zhang, X. et al. Multi-task Generative Adversarial Learning on Geometrical Shape Reconstruction from EEG Brain Signals. arXiv preprint arXiv (2019).
- also check out preprint [Natural image reconstruction from brain waves: a novel visual BCI system with native feedback](https://www.biorxiv.org/content/10.1101/787101v3)
- also check out [4D gaussian splatting](https://guanjunwu.github.io/4dgs/)

---

- necessary resolution can be very easily simulated
	- read in video in Python
	- adjust number of greyscale levels and overlapping “pixels”
	- add noise
	- see if people can identify the video’s semantics
