# SAR-NET: Scene-Appearance Registration Network

**Real-time Bidirectional Artifact Correction for High-Speed OR-PAM via Scene-Appearance Disentanglement**

---

## Status

This repository contains the official implementation of SAR-NET.

**The paper is currently under peer review.** Code and pre-trained models will be released upon acceptance.

## Abstract

High-speed optical-resolution photoacoustic microscopy (OR-PAM) using bidirectional raster scanning suffers from misalignment artifacts between odd and even columns due to differences in scanning dynamics. We propose SAR-NET, a scene-appearance disentanglement framework that models this as a domain adaptation problem rather than a traditional registration task. By separating domain-invariant anatomical structure from domain-specific acquisition parameters, our method achieves real-time correction while maintaining vascular continuity.

## Dataset

The **HSVC-PAM** (High-Speed Voice-Coil PAM) dataset used in this work will be made publicly available via cloud storage upon paper acceptance.

The dataset includes:
- Multi-frame OR-PAM brain vasculature images from multiple mouse samples
- Bidirectional scanning data with odd/even column pairs
- Ground truth annotations for evaluation

**Dataset link:** *Coming soon*

## Code Release

The following will be released:
- [ ] Training code
- [ ] Inference code
- [ ] Pre-trained models
- [ ] Evaluation scripts

## Citation

If you find this work useful, please cite:

```bibtex
@article{sarnet2025,
  title={Real-time Bidirectional Artifact Correction for High-Speed OR-PAM via Scene-Appearance Disentanglement},
  author={...},
  journal={IEEE Transactions on Medical Imaging},
  year={2025},
  note={Under Review}
}
```

## Contact

For questions, please open an issue or contact the authors.

## License

This project will be released under the MIT License.
