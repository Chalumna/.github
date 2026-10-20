 <p align="center">
  <img src="https://github.com/Chalumna/.github/blob/main/profile/logo.png" alt="Chalumna logo" width="220">
</p>

# Chalumna

**Open-source machine learning for coelacanth research and conservation.**

[Website](https://chalumna.github.io/) · [GitHub organisation](https://github.com/Chalumna) · [Contact](mailto:maelig.pesco@gmail.com)

Chalumna is a small, independent project exploring whether modern computer vision can help identify individual coelacanths from the distinctive white spot patterns on their bodies — without tagging, touching, or otherwise disturbing the animals.

## Website

Visit **[chalumna.github.io](https://chalumna.github.io/)** to learn more about the project, its scientific motivation, current work, and guiding principles.

## Why this project

Coelacanths (*Latimeria*) are endangered deep-sea fish that are difficult to study in their natural environment. Their distinctive white spot patterns may allow researchers to recognise individuals across photographs and over time, supporting population monitoring without physical tagging.

A 2012 study by Thornycroft and Booth explored computer-assisted identification using scale patterns. Their approach required an operator to select spots manually, and performance decreased as the viewing angle became more oblique. Chalumna aims to investigate what modern learned computer-vision methods could contribute to this problem.

The name comes from the Chalumna River, where the first living coelacanth known to science was caught in 1938, and from the species name *Latimeria chalumnae*.

## Current status

Chalumna is at an early research and development stage. The projects below are exploratory and should not be interpreted as validated tools for scientific monitoring.

Planned research directions include:

- Reproducing the evaluation framework from the 2012 study, including rank-1 identification accuracy across yaw angles, to establish a comparable baseline.
- Prototyping re-identification using metric learning and public datasets of other spotted animals.
- Investigating coelacanth imagery only where the relevant rights holders have authorised its use.

## Projects

| Project | Description | Status |
|---|---|---|
| [Website](https://chalumna.github.io/) | Public overview of Chalumna's goals, principles, and research directions. | Online |
| [.github](https://github.com/Chalumna/.github) | Organisation profile, community health files, templates, and shared workflows. | In progress |
| [ReID](https://github.com/Chalumna/ReID) | Research into individual coelacanth re-identification from body spot patterns. | In progress |
| [CoelacanthDataset](https://github.com/Chalumna/CoelacanthDataset) | An openly documented image collection for coelacanth research and conservation, subject to individual image rights and permissions. | In progress |

Other machine-learning projects related to coelacanth research and conservation are welcome in this organisation.

## Principles

- **Open code.** Code, experiments, and results should be public and reproducible whenever possible.
- **Data only with permission.** Images and videos remain subject to the rights and conditions set by their creators, collectors, and institutions. Materials are redistributed only when the applicable permissions and licences allow it.
- **Protect sensitive locations.** Exact coelacanth observation locations are not published, to help protect the animals.
- **Non-invasive methods only.** Research should not require tagging, touching, or disturbing wild coelacanths.

## Independence

Chalumna is an independent personal project. It is not affiliated with, endorsed by, or officially connected to any research programme, institution, or company mentioned here unless explicitly stated otherwise.

## Get involved

Ideas, questions, and contributions are welcome. Open an issue or start a discussion in one of the organisation's repositories, or get in touch by email.

## Contact

Maelig — Master's student in AI at Université du Mans, France, working on this project independently.

[maelig.pesco@gmail.com](mailto:maelig.pesco@gmail.com)

## References

- Thornycroft, R. E. & Booth, A. J. (2012). *Computer-aided identification of coelacanths, Latimeria chalumnae, using scale patterns*. Marine Biology Research, 8, 300–306. [https://doi.org/10.1080/17451000.2011.628679](https://doi.org/10.1080/17451000.2011.628679)
- Nulens, R., Scott, L. & Herbin, M. (2011). *An updated inventory of all known specimens of the coelacanth, Latimeria spp.* Smithiana Special Publication 3. South African Institute for Aquatic Biodiversity.

## Logo and licensing

The Chalumna logo was generated with ChatGPT and is released under **CC0 1.0**, as stated by the project. Code in each repository is licensed separately; consult the relevant `LICENSE` file. Image and video datasets may have separate rights and licence conditions.
