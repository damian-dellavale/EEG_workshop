# EEG data analysis workshop
### [Program & Schedule](program/EEG_workshop_v3.pdf)
#### by [Damián Dellavale](https://damian-dellavale.github.io/), [Sebastián Moguilner](https://www.gbhi.org/profiles/sebastian-moguilner), [Carlos Coronel](https://www.gbhi.org/profiles/carlos-coronel), [Jhosmary Cuadros](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Jhosmary+Cuadros&btnG=), [Pavel Prado](https://www.pavelprado.com/), [Agustín Ibáñez](https://www.gbhi.org/profiles/agustin-ibanez)
#### [damian.dellavale [at] atlanticfellows.org](https://damian-dellavale.github.io/)
---

## Module 1 - Oscillations in EEG signals

|Oscillations in EEG signals||
|:---|:---|
|||
| Filtering, Hilbert transform | Theoretical background <br> Analytic examples |
| Coherence measures: Spectral coherence, PLV, wPLV, PPC | Measures description <br> Coding examples |
| Cross-Frequency Coupling (CFC): PAC, PFC, PPC, Mechanistic interpretations (Theta-Gamma code, Gamma-leading Theta interactions) | Measures description and Coding examples |
| Spectral harmonicity (TLI) | Measure description <br> Coding examples |

### Resources

[Shared Resources for module 1](https://drive.google.com/drive/folders/1lYmuekKbw2083DHS0v3Cw-wky0bqZYSO)

[Analyzing the Response of an RLC Circuit (Matlab)](https://www.mathworks.com/help/control/ug/analyzing-the-response-of-an-rlc-circuit.html)\
[Simulating Electrical Circuits (Python)](https://siliconwit.com/education/modeling-and-simulation/simulating-electrical-circuits/)\
[RLC Filter (Python)](https://pyspice.fabrice-salvaire.fr/releases/v1.4/examples/filter/rlc-filter.html)

### Ideas for collaboration

- [CFC directionality](http://dx.doi.org/10.1016/j.neuroimage.2015.05.044)
- [CFC and functional networks](https://doi.org/10.1371/journal.pbio.3000685)
- [CFC and working memory](https://doi.org/10.1038/s41586-024-07309-z)
- [CFC and neuromodulation](https://doi.org/10.34133/cbsystems.0034)
- [Transcranial Temporal Interference Stimulation (tTIS)](https://damian-dellavale.github.io/index.html#projects)
---

## Module 2 - Broadband arrhythmic activity in EEG signals

|Broadband arrhythmic activity in EEG signals||
|:---|:---|
|||
| Neuronal avalanches and criticality, Long-range temporal correlations, Scale-free, Detrended fluctuation analysis | Theoretical background <br> Analytic examples |
| Linking oscillations and transient salient events: Spectral group delay consistency | Analytic examples <br> Coding examples |
| Avalanche-like events in EEG as a biomarker of neurological disorders | Coding examples (Parkinson's disease) |
| Ultradian dynamics of salient events | Examples of data analysis |

### Resources

[Shared Resources for module 2](https://drive.google.com/drive/folders/1xvqX1Z73UU01DlEEpQV6BEUFv9PTK5rM)

### Ideas for collaboration

- [Ultradian dynamics of salient events in brain disorders](https://doi.org/10.1111/epi.17655)
- [Avalanche-like events and neuromodulation](https://tinyurl.com/NIBN4BA)

<img src="arrhythmic/sgdc/designcoding_v14_zero_phase_2.gif" alt="arrhythmic/sgdc/designcoding_v14_zero_phase_2.gif" width="200"/> <img src="arrhythmic/sgdc/designcoding_v14_linear_phase_2.gif" alt="arrhythmic/sgdc/designcoding_v14_linear_phase_2.gif" width="200"/> <img src="arrhythmic/sgdc/designcoding_v14_sgdc_phase_2.gif" alt="arrhythmic/sgdc/designcoding_v14_sgdc_phase_2.gif" width="200"/>

---

## Module 3 - Brain aging models

|Brain aging models||
|:---|:---|
|||
| Normative modeling based on neuroimaging | Conceptual description |
| Brain aging charts: Brain feature ~ Chronological age + Covariates | Conceptual description |
| Brain clock models: Biological brain age ~ Brain feature(s) | Conceptual description |
| Biological age vs. chronological age | Conceptual description |
| Functional connectivity, O-info connectivity | Measures description |
| Regression model for building the clock, Methodological caveats | Measures description |
| Non-invasive biophysical neuromodulation to reduce functional brain aging | Background and rationale <br> Coding examples |

### Resources

[Shared Resources for module 3](https://drive.google.com/drive/folders/1rp-CNfjg_CkrAT9lWLMfv146e2jdYYdU)

### Ideas for collaboration

- [Brain clocks based on arrhythmic activity](https://tinyurl.com/AAIC2026SNE)
- [Brain clocks and neuromodulation](https://tinyurl.com/NIBN4BA)

## References

### Oscillations in EEG signals

Dellavale D, Velarde O, Mato G, Urdapilleta E (2020), *Complex interplay between spectral harmonicity and different types of cross frequency couplings in non linear oscillators and biologically plausible neural network models*, Physical Review E, 102(6), 062401.
DOI: [10.1103/PhysRevE.102.062401](https://doi.org/10.1103/PhysRevE.102.062401)\
Code: [TLI algorithm](https://github.com/damian-dellavale/Time-Locked-Index)

Dellavale D, Urdapilleta E, Cámpora N, Velarde O, Kochen S, Mato G (2020), *Two types of ictal phase-amplitude couplings in epilepsy patients revealed by spectral harmonicity of intracerebral EEG recordings*, Clinical Neurophysiology, 131(8), 1866-1885.
DOI: [10.1016/j.clinph.2020.04.160](https://doi.org/10.1101/2020.03.13.991299)

Velarde O, Urdapilleta E, Mato G, Dellavale D (2019), *Bifurcation structure determines different phase-amplitude coupling patterns in the activity of biologically plausible neural networks*, NeuroImage, 202, 116031.\
DOI: [10.1016/j.neuroimage.2019.116031](https://doi.org/10.1016/j.neuroimage.2019.116031) 
On the cover: https://www.sciencedirect.com/journal/neuroimage/vol/202/

Ueda T, Garnier E, Dellavale D, Bartolomei F, Bénar CG (2025), *Identification of the epileptogenic zone using phase-amplitude coupling on ictal electroencephalography: authentic or spurious PAC?*, Clinical Neurophysiology 174, 151-159.\
DOI: [10.1016/j.clinph.2025.03.029](https://doi.org/10.1016/j.clinph.2025.03.029)

### Broadband arrhythmic activity in EEG signals

Dellavale D, Troisi Lopez E, Romano A, Rabuffo G, Sorrentino P (2026), *Linking local and large-scale salient events with oscillatory and broadband arrhythmic activities in the resting human brain*, Imaging Neuroscience (Cambridge), 4:IMAG.a.1193.
DOI: [10.1162/IMAG.a.1193](https://doi.org/10.1162/IMAG.a.1193)

Dellavale D, et. al (2026), *Decoding the brain's symphony: Oscillations, broadband activity, and paroxysmal salient events in the human encephalographic activity*, 
[Abstract No. 2026-DTA-11965-AAIC](https://tinyurl.com/AAIC2026SNE), Alzheimer's Association International Conference (AAIC), London, UK.

Dellavale D, Bonini F, Pizzo F, Makhalova J, Wendling F, Badier JM, Bartolomei F, Bénar CG (2023), *Spontaneous fast-ultradian dynamics of polymorphic interictal events in drug-resistant focal epilepsy*, Epilepsia 64(8), 2027-2043.\
DOI: [10.1111/epi.17655](https://doi.org/10.1111/epi.17655)\
medRxiv DOI: [10.1101/2023.04.05.23288085](https://doi.org/10.1101/2023.04.05.23288085)\
HAL open science: [hal-04148849](https://hal.science/hal-04148849)\
Researchgate: [Preprint including the discussion with the reviewers](https://www.researchgate.net/publication/370870703_Spontaneous_fast-ultradian_dynamics_of_polymorphic_interictal_events_in_drug-resistant_focal_epilepsy)\
Code: [NODE algorithm](https://github.com/damian-dellavale/node)

### Brain aging models

#### Normative modeling based on structural MRI
Rutherford S & Marquand AF et al. (2022), *The normative modeling framework for computational psychiatry*. Nat Protoc. 17(7):1711-1734.
DOI: [10.1038/s41596-022-00696-5](https://doi.org/10.1038/s41596-022-00696-5)\
Tools: [pcntoolkit.readthedocs.io](https://pcntoolkit.readthedocs.io/en/stable/)

Rutherford S & Marquand AF et al. (2022), *Charting brain growth and aging at high spatial precision*, Elife Feb 1;11:e72904.
DOI: [10.7554/eLife.72904](https://doi.org/10.7554/eLife.72904)

#### Normative modeling based on structural MEG
Zamanzadeh M & Kia SM et al. (2026), *Normative modeling of MEG brain oscillations across the human lifespan*. Commun Biol. Mar 17;9(1):604. 
DOI: [10.1038/s42003-026-09825-2](https://doi.org/10.1038/s42003-026-09825-2)

#### Normative modeling based on structural EEG
Hu S & Valdes-Sosa PA et al. (2025), *GANORM: Lifespan Normative Modeling of EEG Network Topology based on Multinational Cross-Spectra*.
DOI: [10.48550/arXiv.2506.02566](https://doi.org/10.48550/arXiv.2506.02566)

#### Brain clock models

Moguilner S & Ibanez A et al. (2024), *Brain clocks capture diversity and disparities in aging and dementia across geographically diverse populations*, Nature Medicine 30(12):3646-3657. 
DOI: [10.1038/s41591-024-03209-x](https://doi.org/10.1038/s41591-024-03209-x)\
Tools: [osf.io/8zjf4](https://osf.io/8zjf4/)

Dellavale D, et. al (2026), *Non-invasive Biophysical Neuromodulation To Reduce Functional Brain Aging*,<br> 
[Abstract No. 2026-DTA-11908-AAIC](https://tinyurl.com/NIBN4BA), Alzheimer's Association International Conference (AAIC), London, UK.
