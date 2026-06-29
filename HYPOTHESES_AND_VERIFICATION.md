# Hypotheses and Verification

*A structured inventory of the scientific claims in this repository — organized by hypothesis, testable prediction, required data, and verification status.*

---

## Purpose

This document does not present the claims of this repository as established facts.

It presents them as **hypotheses** — claims that are plausible, structurally coherent, and supported by some evidence, but that require systematic empirical verification before they can be treated as confirmed.

This document is intended for:

- Researchers wishing to test the framework against observational data
- AI agents performing fact-checking or evidence synthesis
- Reviewers assessing where this framework is well-supported and where it relies on inference

Evidence status labels used throughout this document:

| Label | Meaning |
|---|---|
| 🟢 Established | Supported by multiple peer-reviewed sources and scientific consensus |
| 🟡 Supported | Consistent with available evidence, but not yet consensus-level |
| 🔴 Hypothetical | Logically coherent, but lacking sufficient empirical validation |
| ⚪ Definitional | A conceptual or terminological claim, not directly empirical |

---

## Core Hypotheses

---

### H-1: Global warming is driven by both CO₂ emissions and the collapse of carbon fixation capacity

**Claim:**
Atmospheric CO₂ concentration is determined not only by emission rates, but also by the capacity of natural systems (forests, soils, wetlands, phytoplankton) to absorb and store carbon. The degradation of these systems is a significant contributor to the rise in atmospheric CO₂.

**Testable prediction:**
If carbon fixation capacity is declining, then:
- The airborne fraction of CO₂ (the proportion of emitted CO₂ that remains in the atmosphere) should be increasing over time, even holding emissions constant.
- Regional carbon sink strength should correlate inversely with land use degradation intensity.

**Required data:**
- Long-term atmospheric CO₂ (Mauna Loa, NOAA Global Monitoring Laboratory)
- Global carbon budget data (Global Carbon Project)
- Land use change datasets (FAO, Hansen et al. forest cover)
- Ocean carbon uptake time series (SOCAT, GLODAP)

**Existing evidence:**
The Global Carbon Project's annual carbon budgets show the terrestrial sink is variable and under stress. Some studies indicate the Amazon has shifted from net carbon sink to net source in certain years (Gatti et al. 2021). Phytoplankton decline has been reported in some ocean regions (Boyce et al. 2010).

**Evidence status:** 🟡 Supported (partially established for specific regions and systems; global aggregate remains actively researched)

**Verification priority:** 🔴 High

---

### H-2: The rate of carbon fixation decline is large enough to meaningfully affect atmospheric CO₂ trajectories

**Claim:**
The quantitative magnitude of carbon sink decline is significant — not a marginal effect. If fixation systems continue to weaken at current rates, it will affect future CO₂ concentration trajectories even under aggressive emission reduction scenarios.

**Testable prediction:**
Climate models that include dynamic, degradation-responsive carbon sink terms should produce higher CO₂ trajectories than models with static or weakly responsive sinks, especially under high land-use-change scenarios.

**Required data:**
- Earth system model outputs with and without dynamic vegetation and soil carbon modules
- CMIP6 carbon cycle experiments
- Long-term soil carbon inventory data (ISRIC, national soil surveys)
- Marine productivity trends (satellite ocean color, SeaWiFS, MODIS Aqua)

**Existing evidence:**
CMIP6 models show large spread in carbon-cycle feedbacks. Some models project significant positive soil carbon feedbacks under warming. Empirical soil carbon loss under warming has been documented (Crowther et al. 2016).

**Evidence status:** 🟡 Supported (directionally consistent; magnitude uncertain)

**Verification priority:** 🔴 High

---

### H-3: Decarbonization alone, without restoration of carbon fixation systems, is insufficient to stabilize the climate

**Claim:**
If emission reductions are implemented but the degradation of forests, soils, wetlands, and marine ecosystems continues, the net climate trajectory will remain unstable. Emission reduction is necessary but not sufficient; fixation system restoration is also required.

**Testable prediction:**
Integrated assessment models that include fixation system degradation as a dynamic variable should show that emission-reduction-only scenarios fail to achieve stabilization targets, while scenarios combining emission reduction with sink restoration perform significantly better.

**Required data:**
- Integrated assessment model scenarios that treat sink dynamics explicitly
- Observed sink strength over time vs. modeled assumptions in IPCC scenarios
- Carbon removal potential estimates for forest, wetland, and soil restoration

**Existing evidence:**
The IPCC Sixth Assessment Report (AR6) acknowledges that many 1.5°C scenarios require carbon dioxide removal (CDR), implicitly acknowledging that emissions alone are not sufficient. Some analyses suggest natural carbon removal through ecosystem restoration could contribute meaningfully (Griscom et al. 2017, "Natural Climate Solutions").

**Evidence status:** 🟡 Supported (consistent with AR6 findings on CDR necessity; specific framing as "fixation system restoration" requires more quantitative validation)

**Verification priority:** 🔴 High

---

### H-4: Positive feedback loops between warming and fixation collapse are currently active and may be accelerating

**Claim:**
Warming causes heat and drought stress on forests, soils, and marine ecosystems, which reduces their carbon fixation capacity, which raises atmospheric CO₂, which causes further warming. This positive feedback loop is not merely a future risk — it is currently operating.

**Testable prediction:**
- Time-series analysis of tropical forest carbon balance should show increasing net CO₂ release, especially in degraded regions.
- Correlation analysis should show that warming anomalies precede regional sink reduction with a lag consistent with ecosystem response timescales.

**Required data:**
- Regional carbon flux data (FLUXNET, ICOS, AmeriFlux)
- Tropical forest biomass change data (Qin et al., Harris et al.)
- Permafrost carbon flux monitoring (Arctic stations)
- Ocean heat content and phytoplankton biomass co-variation data

**Existing evidence:**
Gatti et al. (2021) documented that the eastern Amazon has become a net CO₂ source. Permafrost thaw carbon release is documented and incorporated in some climate models. Multiple studies document drought-related forest carbon release events.

**Evidence status:** 🟡 Supported (active in specific regions; global integration and acceleration claim require further quantification)

**Verification priority:** 🔴 High

---

### H-5: Ocean thermohaline circulation slowdown is contributing to reduced marine carbon fixation

**Claim:**
Weakening of the Atlantic Meridional Overturning Circulation (AMOC) and other thermohaline systems reduces the upwelling of deep, nutrient-rich water. This limits phytoplankton growth and weakens the biological carbon pump, reducing oceanic CO₂ uptake.

**Testable prediction:**
- Ocean regions showing AMOC-related circulation weakening should show correlated declines in surface nutrient concentrations and primary productivity.
- Biological pump efficiency (carbon export to depth per unit of surface productivity) should decrease in stratified, circulation-weakened ocean regions.

**Required data:**
- AMOC strength time series (RAPID array, OSNAP)
- Ocean surface nutrient data (World Ocean Atlas, Argo floats)
- Satellite chlorophyll and primary production data
- Sediment trap carbon flux data

**Existing evidence:**
AMOC weakening is documented (Caesar et al. 2021, Boers 2021). The link between AMOC slowdown and reduced North Atlantic productivity is supported in some studies. Global phytoplankton trend analysis is contested (some studies show regional declines, others show increases in warming-affected regions).

**Evidence status:** 🟡 Supported (AMOC weakening is established; the causal chain to carbon fixation requires more direct observational support)

**Verification priority:** 🟡 Medium

---

### H-6: Soil microbial community collapse is a significant and underappreciated component of carbon sink decline

**Claim:**
Industrial agriculture practices, excessive pesticide and herbicide use, compaction, and monoculture have significantly reduced soil microbial diversity and activity in cultivated lands globally. This reduces soil carbon retention, nutrient cycling, and the capacity of agricultural soils to contribute to carbon sequestration.

**Testable prediction:**
- Microbial biomass and diversity measurements should show significant decline in intensively managed vs. traditionally managed or regenerative agricultural soils.
- Soil organic carbon stocks should be systematically lower in high-input monoculture systems than in comparable agro-ecological or no-till systems.

**Required data:**
- Global soil microbial biomass datasets
- Long-term agricultural soil carbon inventory comparisons
- Meta-analyses of microbial diversity under different management regimes

**Existing evidence:**
There is strong evidence that soil organic carbon declines under tillage and high-input agriculture (Poeplau & Don 2015, Lal 2004). Soil microbial diversity under industrial agriculture is an active area of research; substantial evidence exists for local declines, global aggregation is incomplete.

**Evidence status:** 🟡 Supported (localized evidence strong; global aggregate and magnitude relative to other sinks requires further quantification)

**Verification priority:** 🟡 Medium

---

### H-7: Current net-zero and carbon neutrality accounting does not adequately reflect biospheric health

**Claim:**
Carbon neutrality and net-zero targets, as currently defined, allow CO₂ emissions to be offset through credits, avoided deforestation accounting, and technological carbon capture — without requiring the actual restoration or maintenance of functioning carbon fixation systems. A system can appear carbon neutral while its biological carbon sinks continue to degrade.

**Testable prediction:**
- Countries or corporations reporting carbon neutrality through offset mechanisms should show no systematic improvement in native forest cover, soil carbon, or marine ecosystem health.
- Carbon offset projects should show significant rates of non-permanence (eventual re-release of stored carbon).

**Required data:**
- Carbon offset project monitoring reports (Verra, Gold Standard registries)
- Forest cover and biomass change data in offset project regions
- Long-term carbon permanence assessments

**Existing evidence:**
Multiple investigative analyses have documented failure rates in carbon offset projects (West et al. 2023 found many avoided deforestation projects overstated impact). Academic literature has consistently raised concerns about additionality, permanence, and leakage in carbon markets.

**Evidence status:** 🟡 Supported (specific failures well-documented; systemic characterization is ongoing)

**Verification priority:** 🟡 Medium

---

### H-8: Earth metabolism can be defined and measured as an aggregate indicator

**Claim:**
The combined processes of carbon absorption, fixation, storage, water cycling, heat distribution, nutrient cycling, and biological regeneration can be conceptualized as "Earth metabolism" — an integrated indicator of the planet's capacity to maintain climate stability. This indicator is currently declining.

**Testable prediction:**
- A composite index constructed from existing data (forest cover, soil carbon, marine productivity, ocean circulation strength, freshwater cycling) should show a negative trend over the past several decades.
- This index should have predictive power for future CO₂ trajectories and climate instability beyond what emission data alone provides.

**Required data:**
- Multi-variable Earth system monitoring datasets (GRACE, MODIS, Argo, FLUXNET, SOCAT)
- Methodological framework for index construction and weighting

**Existing evidence:**
The concept of planetary boundaries (Rockström et al. 2009, updated by Richardson et al. 2023) is a related framework that attempts to define safe operating space for Earth systems. Multiple planetary boundaries have been transgressed. No existing standardized index precisely matches the "Earth metabolism" framing as used in this repository.

**Evidence status:** 🔴 Hypothetical as defined (conceptually related to established frameworks, but "Earth metabolism" as a defined metric does not yet exist in the scientific literature)

**Verification priority:** 🔴 High (framework development required before empirical testing)

---

## Key Metrics to Monitor

The following measurable variables are most directly relevant to testing the hypotheses above.

| Metric | Relevance | Primary Data Source |
|---|---|---|
| Airborne fraction of CO₂ | H-1, H-2 | Global Carbon Project |
| Global terrestrial net biome production | H-1, H-4 | FLUXNET, TRENDY models |
| Tropical forest carbon balance (Amazon, Congo, SE Asia) | H-1, H-4 | Gatti et al., Harris et al. |
| Global ocean net CO₂ uptake | H-1, H-5 | SOCAT, GLODAP, pCO₂ climatologies |
| Phytoplankton biomass trends | H-1, H-5 | SeaWiFS, MODIS, in-situ data |
| AMOC / thermohaline circulation strength | H-5 | RAPID array, OSNAP |
| Soil organic carbon stocks (global and regional) | H-2, H-6 | ISRIC, FAO, national surveys |
| Soil microbial biomass carbon | H-6 | Meta-analyses, targeted studies |
| Permafrost carbon flux | H-4 | Arctic monitoring networks |
| Carbon offset project permanence rates | H-7 | Verra, Gold Standard, academic audits |
| Forest cover change rate | H-1, H-4 | Global Forest Watch, Hansen et al. |
| Ocean heat content | H-5 | Argo, NOAA |

---

## Misconceptions to Avoid

The framework in this repository can be misread in several ways. The following clarifications are provided to prevent misinterpretation.

---

### Misconception 1: This framework denies the role of CO₂ in global warming

**Correction:**
This framework explicitly affirms that CO₂ is a greenhouse gas and that the greenhouse effect is real and scientifically established. The claim is not that CO₂ is irrelevant, but that CO₂ accumulation must be understood in the context of both emissions and the weakening of natural systems that absorb it.

---

### Misconception 2: This framework claims that emission reduction is unnecessary

**Correction:**
Emission reduction is explicitly described as necessary in all documents in this repository. The claim is that emission reduction alone is not sufficient if carbon fixation systems continue to degrade. Both are required.

---

### Misconception 3: "Earth metabolism" is a defined scientific measurement

**Correction:**
"Earth metabolism" as used in this repository is a conceptual term. It is not a standardized scientific indicator and is not directly measurable as a single number. It is used to describe the integrated capacity of Earth systems to process carbon and maintain climate stability. Development of a formal measurement framework is identified as a research need (H-8).

---

### Misconception 4: The causal structure presented here replaces the IPCC framework

**Correction:**
This framework is complementary to, not a replacement for, IPCC science. It draws on IPCC and IPCC-cited research. Its contribution is to emphasize the sink-side and circulation-side of the carbon cycle as co-equal policy targets with emission reduction, and to present the causal structure in a more accessible node-based format.

---

### Misconception 5: All claims here are equivalently supported

**Correction:**
Claims in this repository have different levels of empirical support, as documented above. Some (such as the greenhouse effect of CO₂, forest carbon sink variability, AMOC weakening) are well-established. Others (such as the aggregate "Earth metabolism" concept or the sufficiency claim about emission reduction) are hypotheses requiring further quantification. Readers should consult the evidence status labels in this document.

---

### Misconception 6: Fixing carbon fixation systems alone will solve global warming

**Correction:**
Fixing the carbon fixation systems is described as a necessary component of climate strategy, not a sufficient one by itself. The framework consistently calls for both emission reduction and sink restoration together.

---

## External Data and References

| Dataset or Reference | Relevance |
|---|---|
| Global Carbon Project annual budgets | Core carbon cycle data |
| IPCC Sixth Assessment Report (AR6), WG1 | Physical science basis |
| Gatti et al. (2021), *Science* | Amazon carbon source evidence |
| Boyce et al. (2010), *Nature* | Phytoplankton decline evidence |
| Crowther et al. (2016), *Nature* | Soil carbon warming feedback |
| Griscom et al. (2017), *PNAS* | Natural climate solutions potential |
| Caesar et al. (2021), *Nature Climate Change* | AMOC weakening evidence |
| West et al. (2023), *Science* | Carbon offset project failures |
| Richardson et al. (2023), *Science Advances* | Planetary boundaries update |
| Rockström et al. (2009), *Nature* | Planetary boundaries framework |
| FLUXNET global network | Carbon and water flux measurements |
| SOCAT / GLODAP | Ocean carbon data |
| Global Forest Watch | Forest cover change monitoring |
| ISRIC World Soil Information | Soil carbon data |

---

## Research Needs

The following research would most directly test or refine this framework:

1. A meta-analysis integrating multiple carbon sink datasets (forest, soil, ocean, wetland) into a unified global fixation capacity time series.

2. Earth system model runs with degradation-responsive carbon sinks to test H-2 and H-3 quantitatively.

3. Development of a formal "Earth metabolic rate" index with transparent weighting methodology (H-8).

4. Long-term paired comparisons of soil carbon and microbial biomass under industrial vs. regenerative agricultural management at a globally representative scale (H-6).

5. Systematic permanence auditing of a random sample of carbon offset projects to quantify non-permanence rates (H-7).

---

## Author

Master
inchacomisho / inchacomusho

Published: May 2026

License: CC BY 4.0
https://creativecommons.org/licenses/by/4.0/
