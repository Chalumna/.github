<p align="center">
  <img src="https://github.com/Chalumna/.github/blob/main/profile/logo.png" alt="Chalumna logo" width="220">
</p>

# Chalumna

Open-source machine learning for coelacanth research and conservation.

Chalumna is a small, independent project. The first goal is to find out whether modern computer vision can recognise individual coelacanths from the spot patterns on their bodies, without tagging or touching the animals.

## Why this project

Coelacanths (*Latimeria*) are an endangered species that lives deep, often in caves, and is hard to study. Tagging them is not an option, but each fish carries a pattern of white spots that stays the same for years, so photographs can be used to tell individuals apart. This is what makes it possible to count a population and follow animals over time without disturbing them.

A 2012 study (Thornycroft & Booth) showed this works with semi-automatic software, but an operator had to pick the spots by hand and accuracy dropped quickly as the fish was photographed from a more oblique angle. I would like to see what a learned model can do on the same problem.

The name comes from the Chalumna River, where the first living coelacanth was caught in 1938, and from the species name *Latimeria chalumnae*.

## Current status

Very early stage. There is no code or data published yet.

Planned first steps:

- reproduce the evaluation of the 2012 study (rank-1 accuracy by yaw angle) so results can be compared directly;
- prototype re-identification with metric learning on public datasets of other spotted animals;
- test on coelacanth images only if the data owners agree.

## Projects

| Project | Description | Status |
|---|---|---|
| [.github](https://github.com/Chalumna/.github) | Organization's default community health files, templates, and global workflows | WIP |
| [ReID](https://github.com/Chalumna/ReID) | Individual re-identification of coelacanths from spot patterns | WIP |
| [CoelacanthDataset](https://github.com/Chalumna/CoelacanthDataset) | An openly documented image collection for coelacanth research and conservation. | WIP |

Other machine learning projects related to coelacanths are welcome in this organisation.

## Principles

- **Open code.** Code, experiments and results are public and reproducible whenever possible.
- **Data only with permission.** Datasets, images and videos belong to the people and institutions that collected them. They are shared here only with their explicit agreement, and any conditions they set are followed.
- **No locations.** Exact sites where coelacanths are observed are never published, to protect the animals.
- **Non-invasive methods only.**

## Not affiliated

This is an independent personal project. It is not affiliated with, or endorsed by, any research programme, institution or company mentioned on this page, unless stated otherwise.

## Get involved

Ideas, questions and contributions are welcome. You can open an issue or start a discussion on a repository of this organisation, or contact me directly.

## Contact

Maelig, Master's student in AI at Université du Mans (France), working on this project independently.
maelig.pesco@gmail.com

## References

- Thornycroft R.E. & Booth A.J. (2012). *Computer-aided identification of coelacanths, Latimeria chalumnae, using scale patterns*. Marine Biology Research, 8: 300-306. https://doi.org/10.1080/17451000.2011.628679
- Nulens R., Scott L. & Herbin M. (2011). *An updated inventory of all known specimens of the coelacanth, Latimeria spp.* Smithiana Special Publication 3. South African Institute for Aquatic Biodiversity.

## Logo

The Chalumna logo was generated with ChatGPT and is released under CC0 1.0: no rights reserved, reuse it freely. Code in this organisation’s repositories is licensed separately (see the LICENSE file of each repository).
