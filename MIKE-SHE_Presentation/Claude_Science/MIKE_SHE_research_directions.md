# Research directions in which the MIKE SHE model is used — and where it can go next

*Evidence base: 769 publications (1994–2026) that explicitly name MIKE SHE / MIKE-SHE / MIKESHE in
title or abstract, retrieved from OpenAlex and screened by string match. Theme assignment is by
lexicon matching on title + abstract, so a paper can carry several themes. Counts are indicative of
research effort, not exhaustive.*

---

## 1. What the model is, and why the field list looks the way it does

MIKE SHE (DHI) is a physically based, spatially distributed, fully integrated catchment model. Its
process modules — 2-D overland flow, 1-D unsaturated flow (Richards equation, gravity flow, or a
two-layer water-balance option), 3-D saturated groundwater flow, snowmelt, evapotranspiration, and
channel flow through coupling to MIKE 11 / MIKE HYDRO River / MIKE+ — mean that its research niche
is defined by one property: **problems in which the coupling between compartments is the object of
study**, not a boundary condition. Almost every research direction below is a variation on that
theme, which is why "model coupling and integrated modelling" is the single most common descriptor
in the corpus.

The corpus is dominated by Environmental Science (Water Science and Technology, Environmental
Engineering), with substantial Earth and Planetary Sciences, Engineering, and Agricultural and
Biological Sciences components. Publication volume grew steadily from the mid-1990s and has been
roughly flat at a high level since ~2010; 43% of the corpus is from 2018 or later.

---

## 2. Established research directions (with corpus evidence)

### 2.1 Core hydrological process research

1. **Rainfall–runoff and streamflow simulation** — catchment water balance, runoff generation
   mechanisms, hydrograph partitioning into overland flow, drain flow, interflow and baseflow.
2. **Groundwater recharge, water-table dynamics and aquifer response** — spatially distributed
   recharge estimation, piezometric head simulation, conjunctive-use assessment.
3. **Groundwater–surface water interaction** — stream–aquifer exchange fluxes, gaining/losing reach
   dynamics, riparian and hyporheic exchange. This is MIKE SHE's signature use case even where
   papers do not label it as such.
4. **Unsaturated-zone and soil-moisture dynamics** — vadose-zone flow, soil-moisture spatial
   variability, root-zone storage, comparison of Richards vs. simplified unsaturated formulations.
5. **Evapotranspiration and land–atmosphere exchange** — actual vs. potential ET partitioning,
   vegetation-controlled ET, energy-limited vs. water-limited regimes.
6. **Snow, glacier and permafrost hydrology** — snowmelt-driven regimes, degree-day and
   energy-balance melt, frozen-ground effects, cold-region and high-mountain catchments.

### 2.2 Water resources management and engineering

7. **Flood modelling and inundation mapping** — floodplain inundation, coupled river–floodplain
   1-D/2-D simulation, compound rainfall–river flooding, flood risk under changed land surfaces.
8. **Flood forecasting, real-time operation and early warning** — operational/ensemble forecast
   chains, data-assimilation-driven updating, national warning systems.
9. **Drought, low-flow and baseflow research** — drought propagation from meteorological to
   groundwater drought, minimum-flow assessment, drought adaptation design.
10. **Water supply, abstraction and pumping-impact assessment** — well-field capture zones,
    sustainable yield, drawdown effects on streams and wetlands.
11. **Reservoir, dam, canal and hydropower operation** — regulated systems, sluice/weir control,
    canal–aquifer interaction, operation rules embedded in catchment simulation.
12. **Irrigation and agricultural water management** — irrigation demand and return flow, crop
    water use, conjunctive surface/groundwater irrigation, cropping-pattern change.
13. **Agricultural drainage and tile-drain systems** — drain-flow simulation, drainage design,
    controlled drainage, drainage as a nutrient pathway.
14. **Urban hydrology, stormwater and LID/SUDS** — urban water balance, drainage swales,
    infiltration systems, green infrastructure, polder and combined-sewer interactions.
15. **Mining, quarry and construction dewatering** — dewatering-induced drawdown and its surface
    water and ecological consequences.
16. **Decision support, water policy and IWRM** — model-based DSS, Water Framework Directive
    compliance, stakeholder/participatory modelling, water allocation and multi-criteria frameworks.

### 2.3 Water quality, solutes and biogeochemistry

17. **Nutrient (N and P) transport and catchment water quality** — nitrate leaching and delivery,
    source apportionment, riparian retention, coupling to agronomic models (e.g. DAISY) and to
    MIKE 11 water-quality modules.
18. **Pesticide, contaminant and general solute transport** — leaching to groundwater, plume
    migration, particle tracking, transport in the coupled unsaturated–saturated–surface system.
19. **Salinity and seawater intrusion** — salinisation of coastal and irrigated aquifers.
20. **Isotope, tracer and travel-time / residence-time analysis** — model-based age distributions,
    catchment transit times, isotope-constrained calibration.
21. **Carbon, greenhouse gas and biogeochemical coupling** — water-table-controlled CO₂ and CH₄
    emissions from drained and rewetted organic soils, dissolved organic carbon export.
22. **Sediment and erosion modelling** — soil erosion, sediment yield and delivery, check-dam and
    gully systems (usually via coupling, since MIKE SHE has no native distributed erosion module).

### 2.4 Change, ecosystems and land management

23. **Climate change impact assessment** — GCM/RCM downscaling chains, RCP/SSP/CMIP scenarios,
    multi-model ensembles, climate sensitivity of groundwater as well as streamflow.
24. **Land-use / land-cover change impact and attribution** — urbanisation, deforestation,
    afforestation, cropland conversion; joint attribution of climate vs. land-use signals.
25. **Wetland and peatland hydrology** — wet grassland, fen, bog and tropical peatland water
    tables; drainage and rewetting; peatland subsidence and emission linkages.
26. **Ecohydrology, riparian zones, habitat and environmental flows** — groundwater-dependent
    vegetation, habitat suitability driven by simulated water tables, ecological water allocation.
27. **Forest and vegetation management hydrology** — harvesting, plantation, canopy interception,
    bark-beetle/disturbance-driven runoff change.
28. **Nature-based solutions, restoration and managed aquifer recharge** — re-meandering, wetland
    restoration, retention features, buffer strips, NbS for flood and drought adaptation, MAR.
29. **Sea-level rise and coastal groundwater systems** — coastal aquifer response, tidal boundary
    effects, coastal geo-environmental change.
30. **Karst and fractured-rock systems** — integrated-model representations of conduit-dominated
    catchments (a small but recurring specialist strand).

### 2.5 Model science: MIKE SHE as the research object rather than the tool

31. **Calibration, autocalibration and parameter estimation** — multi-site and multi-variable
    calibration (discharge + heads + ET + soil moisture), automatic calibration with AUTOCAL/PEST,
    inverse methods.
32. **Uncertainty, sensitivity and equifinality analysis** — GLUE-type and Monte Carlo studies,
    parameter identifiability, predictive uncertainty of distributed models.
33. **Scale, discretisation and model-structure research** — grid-resolution effects, appropriate
    complexity, distributed vs. semi-distributed vs. lumped structures, parsimony debates.
34. **Model comparison, benchmarking and intercomparison** — MIKE SHE against SWAT, MODFLOW,
    HYDRUS, APEX, conceptual models; multi-model ensembles; large-sample robustness diagnostics.
35. **Data assimilation and Earth-observation integration** — assimilation of satellite and in-situ
    data, evaluation of satellite precipitation and ET products, GRACE/SAR/MODIS-constrained
    simulation, and (very recently) SWOT surface-water observations.
36. **Machine learning, surrogate and hybrid modelling** — ML emulators of the physical model,
    hybrid physics–ML predictions, AI-assisted calibration.
37. **Computational performance** — parallelisation, run-time reduction, feasibility of large or
    long-horizon integrated simulations.

### 2.6 Cross-disciplinary and applied margins

38. **Water-related public health links** — vector habitat and waterborne exposure pathways (rare).
39. **Archaeo- and palaeo-hydrology** — reconstruction of historical flood protection and
    palaeochannel flow pathways in alluvial landscapes.
40. **Model-based teaching, review and methodological synthesis** — MIKE SHE appears heavily in
    review and comparative-methodology literature, which is where its most-cited mentions sit.

---

## 3. Theme prevalence and recency

Themes whose share of post-2018 papers exceeds the corpus baseline of 43% are growing faster than
the field as a whole; those below it are maturing or declining.

![Theme prevalence and recency in the MIKE SHE literature]({{artifact:art_d6856023-0e54-4463-950a-cc1b57f44336}})

| Research direction | Papers | % of corpus | % published 2018–2026 |
|---|---|---|---|
| Model coupling & integrated modelling frameworks | 304 | 39.5 | 49.3 |
| Model calibration, autocalibration & parameter estimation | 292 | 38.0 | 42.5 |
| Streamflow / rainfall-runoff simulation | 206 | 26.8 | 49.5 |
| Groundwater recharge & aquifer/water-table dynamics | 201 | 26.1 | 45.8 |
| Climate change impact assessment | 185 | 24.1 | 56.2 |
| Evapotranspiration & land–atmosphere coupling | 182 | 23.7 | 47.8 |
| Uncertainty, sensitivity & equifinality analysis | 157 | 20.4 | 35.7 |
| Flood modelling & inundation mapping | 146 | 19.0 | 53.4 |
| Data assimilation & remote sensing integration | 92 | 12.0 | 50.0 |
| Wetland & peatland hydrology | 90 | 11.7 | 42.2 |
| Land-use / land-cover change impacts | 87 | 11.3 | 62.1 |
| Irrigation & agricultural water management | 80 | 10.4 | 45.0 |
| Soil moisture & unsaturated zone | 80 | 10.4 | 48.8 |
| Drought & low-flow analysis | 69 | 9.0 | 55.1 |
| Scale, discretisation & model structure effects | 68 | 8.8 | 41.2 |
| Flood forecasting / real-time & early warning | 66 | 8.6 | 53.0 |
| Decision support, policy & IWRM | 61 | 7.9 | 59.0 |
| Nature-based solutions / restoration & rewetting | 60 | 7.8 | 43.3 |
| Model comparison / benchmarking / intercomparison | 60 | 7.8 | 45.0 |
| Forest & vegetation management hydrology | 57 | 7.4 | 52.6 |
| Water supply / abstraction & pumping impacts | 54 | 7.0 | 48.1 |
| Reservoir, dam & hydropower operation | 54 | 7.0 | 64.8 |
| Ecohydrology / riparian & habitat | 50 | 6.5 | 46.0 |
| Nutrient (N/P) transport & water quality | 49 | 6.4 | 57.1 |
| Urban hydrology, stormwater & LID/SUDS | 44 | 5.7 | 52.3 |
| Agricultural drainage & tile drains | 42 | 5.5 | 66.7 |
| Pesticide / contaminant / solute transport | 39 | 5.1 | 41.0 |
| Groundwater–surface water interaction | 35 | 4.6 | 54.3 |
| Snow, glacier & permafrost hydrology | 34 | 4.4 | 41.2 |
| Sediment & erosion modelling | 33 | 4.3 | 63.6 |
| Isotope & tracer hydrology / travel time | 30 | 3.9 | 73.3 |
| Machine learning / surrogate & hybrid modelling | 27 | 3.5 | 85.2 |
| Carbon, greenhouse gas & biogeochemistry linkage | 26 | 3.4 | 57.7 |
| Mining, dewatering & construction dewatering | 21 | 2.7 | 47.6 |
| Salinity & seawater intrusion | 13 | 1.7 | 38.5 |
| Sea-level rise & coastal groundwater | 9 | 1.2 | 44.4 |
| High-performance / parallel computing & efficiency | 8 | 1.0 | 75.0 |
| Karst & fractured-rock hydrology | 6 | 0.8 | 16.7 |
| Health / vector & waterborne disease linkage | 4 | 0.5 | 50.0 |
| Sustainability of groundwater-dependent ecosystems | 4 | 0.5 | 25.0 |


---

## 4. Currently emerging fronts

Ranked by the share of each theme's literature that is recent, the active growth edges are:

1. **Machine learning / hybrid and surrogate modelling** — the most recency-skewed theme in the
   corpus by a wide margin. Work is still mostly at the "compare or couple" stage: ML emulators,
   AI-assisted calibration, editorial/review framing of physics–ML integration.
2. **Computational performance and parallelisation** — small but almost entirely recent, driven by
   the cost of ensemble, long-horizon and high-resolution integrated runs.
3. **Isotope, tracer and travel-time studies** — recent growth as tracer data are used to constrain
   integrated models beyond discharge fitting.
4. **Agricultural drainage and tile-drain research** — reinvigorated by nutrient regulation and by
   controlled-drainage and drainage-retrofit questions.
5. **Sediment/erosion, reservoir operation, land-use attribution, decision support, nutrient water
   quality, drought and NbS** — all clearly above baseline recency; these are where applied demand
   currently sits.
6. **Nature-based solutions, rewetting and managed aquifer recharge** — a fast-moving applied
   front, with 2024–2026 work explicitly using MIKE SHE to represent NbS in physically based terms
   and to test drought and flood adaptation portfolios.
7. **Peatland carbon–water coupling** — water-table simulation as the driver of emission estimates
   from drained and rewetted organic soils.
8. **New satellite missions as constraints** — 2026 work informing integrated models with SWOT.

Conversely, **uncertainty/equifinality analysis** and **scale/structure research** are the most
mature (lowest recent share): the methodological debates that dominated 2000–2015 have largely
settled into practice.

---

## 5. Directions with clear future potential

These are inferences, framed as opportunity rather than fact. Each is justified either by a growth
trajectory already visible in the corpus, or by a capability the model has that the literature has
barely exploited.

### 5.1 Under-exploited given the model's capabilities

1. **Groundwater-dependent ecosystems (GDEs) as a formal target** — only a handful of papers use
   that framing despite MIKE SHE being one of the few tools that can resolve water-table depth in
   the root zone at catchment scale. Strong potential for GDE mapping, spring-discharge
   sustainability, and ecological-threshold modelling.
2. **Coastal freshwater–saltwater systems under sea-level rise** — very thin coverage (salinity and
   sea-level rise are among the least represented themes) even though coastal groundwater is a
   first-order adaptation problem. Density-dependent coupling (e.g. with FEFLOW/SEAWAT-class
   codes or MIKE SHE's transport module) is an open niche.
3. **Karst and fractured-rock catchments** — a persistent minority strand with almost no recent
   growth; the "how do you make an equivalent-porous-medium integrated model behave like a conduit
   system" question remains unresolved and is now testable with better tracer and spring data.
4. **Water-borne and vector-borne disease hydrology** — near-absent. Simulated ponding duration,
   water-table depth and inundation extent are direct habitat and exposure predictors, making this
   a credible cross-disciplinary extension.
5. **Urban integrated modelling at city scale** — urban work exists but is dominated by local LID
   and swale studies; whole-city coupled surface–sewer–groundwater modelling (including
   groundwater infiltration into sewers, urban baseflow, and subsurface infrastructure) is an
   obvious growth direction, reinforced by 2026 reviews of urban water-balance modelling.
6. **Mine-water and post-closure landscape hydrology** — small existing base, high applied demand
   (tailings, pit-lake recovery, rehabilitation), and a problem structure that requires exactly the
   coupled unsaturated–saturated–surface treatment MIKE SHE provides.

### 5.2 Methodological frontiers

7. **Physics-informed and hybrid ML architectures** — the current ML literature mostly benchmarks
   ML *against* MIKE SHE. The open direction is ML *inside* the workflow: differentiable or
   physics-informed surrogates for the unsaturated and saturated modules, ML-based parameter
   regionalisation, and emulators that make thousands-of-member uncertainty ensembles affordable.
8. **Sequential data assimilation as standard practice** — assimilation appears mainly in
   forecasting studies; routine multi-variable assimilation (heads + soil moisture + ET +
   satellite inundation) into integrated simulation is still rare.
9. **New Earth-observation streams** — SWOT water-surface elevation, high-resolution soil-moisture
   missions, InSAR-derived subsidence, satellite ET products and thermal data as calibration
   constraints on distributed states rather than on outlet discharge.
10. **Large-sample and multi-basin integrated modelling** — the field has moved to large-sample
    hydrology (CAMELS-style) with conceptual models; physically based integrated models are
    largely absent from it. Recent robustness-diagnosis papers point directly at this gap, and it
    depends on the parallelisation/performance work above.
11. **Regional-to-national scale models and digital twins** — national-scale models (the Danish
    DK-model tradition) are the precedent; the direction is continuously updated,
    operationally maintained catchment digital twins with real-time assimilation and scenario
    dashboards.
12. **Model-structure adequacy testing against tracers and residence times** — moving beyond
    hydrograph fitting to falsify internal flow-path representation; the recent isotope growth is
    the leading edge of this.
13. **Uncertainty in the full chain, not the model alone** — climate ensemble × downscaling ×
    land-use scenario × parameter uncertainty, propagated through an expensive integrated model;
    tractable only with surrogates.

### 5.3 Applied and policy-facing frontiers

14. **Nature-based solutions evidence base** — quantifying NbS efficacy (retention, rewetting,
    re-meandering, agroforestry, buffer strips) with a process model instead of empirical
    coefficients, including trade-offs and unintended downstream effects.
15. **Water–energy–food–ecosystem nexus and multi-criteria coupling** — 2026 work already couples
    MIKE SHE to multi-criteria decision layers for allocation; generalising this into optimisation
    under uncertainty is a natural next step.
16. **Compound and cascading hazards** — pluvial + fluvial + groundwater flooding together,
    drought-to-flood transitions, and antecedent-wetness-controlled hazard, which integrated models
    can represent but the corpus rarely tackles jointly.
17. **Managed aquifer recharge and flood–groundwater conjunctive resilience** — explicitly named as
    a reframing target in the newest literature; MIKE SHE is well suited to siting and yield
    assessment for MAR and flood-MAR schemes.
18. **Peatland and wetland carbon accounting for climate policy** — water table as the control
    variable in emission inventories and rewetting-credit verification.
19. **Agricultural adaptation and nutrient regulation design** — crop-switching and
    irrigation-reform scenarios (already appearing for Bangladesh, Xinjiang, the Loess Plateau),
    targeted nutrient measures, and drainage-based mitigation.
20. **Equity and distributional analysis of water interventions** — one 2025 study asks whether
    urban green infrastructure creates equity problems for flood-vulnerable areas; coupling
    distributed hydrological output to social-vulnerability data is an almost untouched direction.
21. **Data-scarce and global-dataset applications** — recent work tests how far globally available
    forcing and parameter data can carry a physically based model; this matters for Africa, Central
    and South Asia, and Latin America, where MIKE SHE applications are growing but data are thin.
22. **Palaeo- and archaeo-hydrology** — reconstruction of historical flood events, palaeochannel
    flow, and past landscape water management; a genuinely novel 2025–2026 strand.

---

## 6. Caveats

- The corpus is limited to records whose OpenAlex title or abstract contains the model name. 141 of
  the 932 phrase-search hits had no abstract available and could not be screened, so recall is
  incomplete — consultancy reports, DHI technical documentation, and many theses are absent.
- Theme detection is lexical. It will over-count generic words (e.g. "coupling", "calibration") and
  under-count papers that describe a topic without the matched vocabulary; treat counts as relative
  effort, not precise tallies.
- Section 5 is interpretation. The growth and gap statistics are computed from the corpus; the
  claim that a gap represents an *opportunity* is a judgement, not a measurement.
