# Targeted Mass Drug Administration (tMDA) — Southeast Asia

**What this is:**  
This repository documents the targeted mass drug administration (tMDA) component of malaria elimination research in Southeast Asia. While mass drug administration has been widely used for neglected tropical diseases, its use for malaria has been controversial due to past misuse and concerns about drug resistance. This repo curates papers, figures, and notes from tMDA trials and modeling studies I contributed to across Myanmar, Cambodia, Vietnam, and Laos.

**My role:**  
I worked as part of the Mahidol–Oxford Tropical Medicine Research Unit (MORU) team, led by Lorenz von Seidlein and Arjen Dondorp, contributing to field research, data analysis, and modeling. I was based at a field station during this time (the Shoklo Malaria Research Unit), but contributed mapping/GIS and analytics expertise to most of the field sites (except for Vietnam). I documented herd effects, analyzed space-time patterns, and developed models exploring the theoretical limits of tMDA in connected communities. I also linked tMDA work to the infrastructure and surveillance systems built under the [METF-mapping](https://github.com/DMParker1/METF-mapping) program in Karen/Kayin State, Myanmar.

---

## Why this matters
- **Challenge:** Traditional mass drug administration for malaria was often avoided after historical use — for example, adding antimalarials to table salt, which may have contributed to the emergence and/or spread of drug-resistant parasites [NEJM article with interview](https://www.nejm.org/doi/full/10.1056/NEJMp1403340)
- **Hypothesis:** In low-to-moderate transmission settings with ready access to early diagnosis and treatment (EDT), tMDA could rapidly reduce parasite reservoirs, including among asymptomatic carriers who would otherwise remain untreated.
- **Key insight:** Asymptomatic *P. falciparum* infections can be common even in so-called low transmission areas — especially in certain high-risk communities — making targeted interventions valuable.
- **Results:** tMDA can be safe and effective when done with strong community engagement, good diagnostics, and a supportive treatment network, but effects may be temporary if surrounded by high-transmission areas.

---

## Connections
- **Precursor:** [early-dx-tx-borderlands](https://github.com/DMParker1/early-dx-tx-borderlands) — EDT systems in Karen State, Myanmar.
- **Sibling repo:** [METF-mapping](https://github.com/DMParker1/METF-mapping) — mapping and CE groundwork for METF.
- **Downstream:** Modeling work on connectivity and intervention limits.

---

## Selected outputs

### Trial & observational studies
- **Overview of multi-country tMDA program:**  
  **The impact of targeted malaria elimination with mass drug administrations on *Plasmodium falciparum* malaria in Southeast Asia: A cluster randomised trial.**  
  von Seidlein L, Peto TJ, Landier J, Nguyen TN, Tripura R, et al. *PLOS Medicine*. 2019;16(2):e1002745.  
  [https://doi.org/10.1371/journal.pmed.1002745](https://doi.org/10.1371/journal.pmed.1002745)

- **Myanmar (Eastern Karen State):**  
  **Safety and effectiveness of mass drug administration to accelerate elimination of artemisinin-resistant *Plasmodium falciparum* malaria: A pilot trial in four villages of Eastern Myanmar.**  
  Landier J, Kajeechiwa L, Thwin MM, et al. *Wellcome Open Research*. 2017;2:81. [version 1; peer review: 2 approved]  
  [https://doi.org/10.12688/wellcomeopenres.12240.1](https://doi.org/10.12688/wellcomeopenres.12240.1)

- **Vietnam:**  
  **Rapid decline in the susceptibility of *Plasmodium falciparum* to dihydroartemisinin–piperaquine in the south of Vietnam.**  
  Thanh NV, Thuy-Nhien N, Tuyen NTK, et al. *Malaria Journal*. 2017;16:27.  
  [https://doi.org/10.1186/s12936-017-1680-8](https://doi.org/10.1186/s12936-017-1680-8)

- **Cambodia:**  
  **A controlled trial of mass drug administration to interrupt transmission of multidrug-resistant *Plasmodium falciparum* malaria in Cambodian villages.**  
  Tripura R, Peto TJ, Chea N, Chan D, Mukaka M, et al. *Clinical Infectious Diseases*. 2018;67(6):817–826.  
  [https://doi.org/10.1093/cid/ciy196](https://doi.org/10.1093/cid/ciy196)

- **Early asymptomatic prevalence evidence:**  
  **The epidemiology of subclinical malaria infections in South-East Asia: Findings from cross-sectional surveys in Thailand–Myanmar border areas, Cambodia, and Vietnam.**  
  Imwong M, Nguyen TN, Tripura R, et al. *Malaria Journal*. 2015;14:381.  
  [https://doi.org/10.1186/s12936-015-0906-x](https://doi.org/10.1186/s12936-015-0906-x)

---

### Related analyses & modeling
- **Potential herd protection against *Plasmodium falciparum* infections conferred by mass antimalarial drug administrations.**  
  Parker DM, Tun STT, White LJ, Kajeechiwa L, Thwin MM, Landier J, Chaumeau V, Corbel V, Dondorp AM, von Seidlein L, White NJ, Maude RJ, Nosten F. *eLife*. 2019;8:e41023.  
  [https://doi.org/10.7554/eLife.41023](https://doi.org/10.7554/eLife.41023)

- **Space-time patterns (Pailin, Cambodia):**  
  **A multi-level spatial analysis of clinical malaria and subclinical *Plasmodium* infections in Pailin Province, Cambodia.**  
  Parker DM, Tripura R, Peto TJ, Maude RJ, Nguon C, Chalk J, Sirithiranont P, Imwong M, von Seidlein L, White NJ, Dondorp AM. *Heliyon*. 2017;3:e00447.  
  [https://doi.org/10.1016/j.heliyon.2017.e00447](https://doi.org/10.1016/j.heliyon.2017.e00447)

- **Connectivity and theoretical limits of MDA:**  
  **The assembly effect: The connectedness between populations is a double‐edged sword for public health interventions.**  
  Tun STT, Parker DM, Aguas R, et al. *Malaria Journal*. 2021;20:189.  
  [https://doi.org/10.1186/s12936-021-03726-x](https://doi.org/10.1186/s12936-021-03726-x)

- **Transmission model with Shiny app:**  
  **Towards malaria elimination in Savannakhet, Lao PDR: Mathematical modelling driven strategy design.**  
  Tun STT, von Seidlein L, Pongvongsa T, et al. *Malaria Journal*. 2017;16:483.  
  [https://doi.org/10.1186/s12936-017-2130-3](https://doi.org/10.1186/s12936-017-2130-3)  
  *Interactive tool:* [Shiny app](https://moru.shinyapps.io/savannakhet/) — hosted by MORU; availability may change over time.


---

### Commentary & debate
- **Response to Cochrane review limitations on MDA & vivax:**
  There was a Cochrane review paper that, using mostly our papers, [suggested that MDA for vivax malaria would not work](https://www.cochranelibrary.com/cdsr/doi/10.1002/14651858.CD008846.pub3/full)

Since we did tMDA for falciparum malaria, it doesn't make sense to use our results as evidence against tMDA working for vivax malaria. tMDA for vivax would require using some kind of anti-hypnozoite. Our response [here](https://www.cochranelibrary.com/cdsr/doi/10.1002/14651858.CD008846.pub3/detailed-comment/en?messageId=326098774)

---

## Related Repositories

- [METF-mapping](https://github.com/DMParker1/METF-mapping) — Mapping and community engagement groundwork for METF.
- [tMDA-program](https://github.com/DMParker1/tmda-program) — Targeted mass drug administration trials and modeling in Southeast Asia.
- [early-dx-tx-borderlands](https://github.com/DMParker1/early-dx-tx-borderlands) — Early access to malaria diagnosis and treatment in borderland settings.
- [tm-border-mch](https://github.com/DMParker1/tm-border-mch) — Maternal and child health research on the Thailand–Myanmar border.
- [earth-observation-labs](https://github.com/DMParker1/earth-observation-labs) — Remote sensing and Earth observation methods applied to public health.
---

## License & Citation
Text and figures © Daniel M. Parker unless otherwise stated. Licensed under CC BY 4.0.  
See `CITATION.cff` for citation details.

## Notes on Data & Ethics
- Any requests for data from these projects should be directed to [Mahidol–Oxford Tropical Medicine Research Unit (MORU)](https://www.tropmedres.ac/).  
- No sensitive data are included in this repository.  

---


