# Barcelona 1929 AI–3D Reconstruction

## Generative AI Benchmark for the Digital Reconstruction of Vanished Architectural Heritage

**Carles Pàmies**  
Escola Tècnica Superior d'Arquitectura de Barcelona (ETSAB) – Universitat Politècnica de Catalunya (UPC), Barcelona, Spain

### Associated research article

**Reconstructing the Barcelona Exhibition of 1929 through AI-Based Generative 3D Reconstruction**

This repository accompanies the research study evaluating four image-to-3D generative AI systems through three vanished pavilions of the 1929 International Exposition of Barcelona.

### Research question

> To what extent can AI contribute to a deeper, more interactive, and more critical understanding of ephemeral architectural heritage?

### Case studies

| Pavilion | Architect(s) | Historical input |
|---|---|---:|
| Yugoslav Pavilion | Dragiša Brašovan | 4 photographs |
| Romanian Pavilion | Duiliu Marcu | 4 photographs |
| Hungarian Pavilion | Dénes Györgyi and Nikolaus Menyhért | 1 photograph |

### AI systems evaluated

- TripoAI
- Hunyuan 2.5
- Hitem3D
- Meshy

### Evaluation criteria

The study evaluates geometric precision, stylistic fidelity, texture quality, rendering time, polygon density, and applicability in heritage, educational and museographic contexts.

### Main findings

Meshy produced the most consistent overall results for heritage and educational applications, particularly in texture quality, stylistic fidelity and ornamental detail. Hunyuan 2.5 provided a strong balance between geometric quality and efficiency. TripoAI was substantially faster but less geometrically precise. Hitem3D produced high polygon densities and longer processing times without corresponding gains in geometric coherence.

The study also indicates that the richness and diversity of historical documentation strongly affect reconstruction quality.

### Epistemological principle

AI-generated reconstructions should distinguish between:

- **Documented** — directly supported by historical evidence.
- **Inferred** — reconstructed through interpretation of available evidence.
- **Hypothetical** — generated where historical evidence is insufficient.

AI is treated as an instrument for accelerating reconstruction, exploration and hypothesis generation, not as a replacement for expert historical and architectural judgement.

### Benchmark concept

This repository establishes the:

**Barcelona 1929 AI–3D Reconstruction Benchmark — 2026**

The repository is designed so that future studies can repeat comparable experiments with later generations of image-to-3D AI systems.

### 3D resources

The paper identifies a public Sketchfab collection containing the generated renders and meshes:

https://skfb.ly/pCQpW

### Data availability

The historical photographs used as AI inputs are not redistributed here where third-party ownership or usage restrictions apply. Source metadata may be provided without reproducing the protected images.

### Repository structure

```text
paper/                  Research manuscript
methodology/            Experimental and evaluation documentation
results/                Structured quantitative and qualitative results
metadata/               Project and pavilion metadata
supplementary/          Supplementary research material
```

### Citation

Please cite the associated research article as the preferred scientific reference.

**Publisher DOI:** [TO BE ADDED]

**Zenodo DOI:** https://doi.org/10.5281/zenodo.23245446

**ORCID:** (https://orcid.org/0000-0002-0079-0802)

### Keywords

Digital heritage · Generative AI · 3D reconstruction · Architectural heritage · Barcelona 1929 · International Exposition · Image-to-3D · Artificial Intelligence · Cultural heritage · Virtual reconstruction · Museography

### Rights

See `RIGHTS.md` and `LICENSE`.

Third-party historical images are not redistributed unless the applicable rights and permissions allow it.
