# Awesome-Drilling-Operations

# Top Drilling Operations Management Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Well Planning, Drilling Reporting & Real-Time Operations Monitoring*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Drilling Operations Management**. These tools manage well planning, drilling reporting, real-time monitoring, non-productive time (NPT) analysis, and operational performance review for oil & gas operators, drilling contractors, and service companies.

**Examples** include WellPlan, Pason Live, RigER, Peloton WellView, OpenWells, DrillOps, Wellsite Report, FieldCap, WellEz, and Drillnet (the category leaders).

**Open-source emphasis**: This section is expanded with active projects for self-hosting, custom well trajectory planning, and transparent drilling data management — ideal for petroleum engineers, drilling contractors, and developers building vendor-independent drilling solutions. The open-source ecosystem is anchored by **welleng** (well trajectory planning), **Witsml Explorer** (WITSML data management), and the **Open Source Drilling Community** microservice architecture, with strong coverage in directional drilling calculations and drilling data analytics.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[WellPlan](https://www.landmark.solutions/WellPlan)**  
  Halliburton Landmark's comprehensive well planning and drilling engineering software covering trajectory design, casing design, hydraulics, torque and drag, and wellbore stability.

- **[Pason Live](https://www.pason.com/)**  
  Real-time drilling data monitoring and reporting platform providing rig instrumentation, electronic drilling recorder (EDR) data, and operational dashboards.

- **[RigER](https://www.riger.com/)**  
  Cloud-based drilling and well servicing management software with scheduling, reporting, and invoicing for drilling contractors.

- **[Peloton WellView](https://www.peloton.com/)**  
  Industry-standard well data management and drilling reporting software covering the full well lifecycle from planning through completion. Tracks daily drilling reports, NPT, and operational performance .

- **[OpenWells](https://www.landmark.solutions/OpenWells)**  
  Halliburton Landmark's drilling and completions reporting software for capturing and analyzing well operations data.

- **[DrillOps](https://www.slb.com/)**  
  Schlumberger's drilling operations optimization platform with automated drilling control, real-time performance monitoring, and NPT reduction.

- **[Wellsite Report](https://www.wellsitereport.com/)**  
  Daily drilling reporting and well data management platform for operators and drilling contractors.

- **[FieldCap](https://www.fieldcap.com/)**  
  Oilfield operations management platform with drilling reporting, field ticketing, and production data capture.

- **[WellEz](https://www.wellez.com/)**  
  Cloud-based drilling and well operations reporting software with daily reports, NPT tracking, and performance analytics.

- **[Drillnet](https://www.drillnet.net/)**  
  Drilling information management system providing real-time data aggregation, reporting, and operational intelligence.

## Open-Source GitHub Projects

- **[welleng](https://github.com/jonnymaserati/welleng)**  
  The most widely adopted open-source collection of well engineering tools, focused on well trajectory planning and anti-collision analysis. Python-based with 110+ stars on GitHub . Features survey management, well trajectory calculation, ISCWSA standard well paths, collision detection using exact Mahalanobis separation factor, kick-tolerance engine, and tortuosity index calculation. Includes a curve-hold-curve point-to-target solver using analytical methods. Supports 3D visualization for well trajectory rendering. MIT-licensed with extensive academic citations and validation against published methods .

- **[Witsml Explorer](https://github.com/equinor/witsml-explorer)**  
  Open-source data management tool from Equinor for browsing and editing data directly on WITSML servers. Runs in the browser or as a local desktop application with a simple installer. Connects to any WITSML server running version 1.4.1.1. Supports comprehensive WITSML objects including wells, wellbores, bharuns, changelogs, fluidsreports, formation markers, log objects, curves, messages, mudlogs, geology intervals, rigs, risks, trajectories, tubulars, and wbgeometries . Features copy objects between different servers, URL deep linking, WITSML query editor, and QA/QC jobs on logs and curves (edit, splice, compare, analyze gaps, trim, offset). Apache-2.0 licensed .

- **[Open Source Drilling Community](https://github.com/open-source-drilling-community)**  
  A repository of open-source drilling models, test cases, and benchmarks for deep drilling problems, distributed under MIT license. The community provides a microservice architecture where each component runs independently and communicates through APIs . Key microservices include: **Trajectory** (drilling trajectory handling), **Well** (well management), **WellBore** (wellbore management), **WellBoreArchitecture** (wellbore architecture), **DrillString** (drill-string/BHA management), **DrillingFluid** (drilling fluid calculations), **YPLCalibrationFromRheometer** (rheology calibration using Herschel-Bulkley model), **GeologicalProperties** (geological properties along wellbore), **Simulator4nDOF** (near real-time 4n degree of freedom transient torque and drag simulations), **Cluster** (clusters or templates management), and **Field** (field management) . These microservices provide a modular foundation for building custom drilling operations platforms.

- **[witskit](https://github.com/Critlist/witskit)**  
  Comprehensive Python SDK for processing WITS (Wellsite Information Transfer Standard) data in the oil & gas drilling industry. Parses raw WITS frames into structured, validated Python objects with 724 symbols across 20+ record types auto-parsed from the spec . Features CLI tools for symbol search, frame decoding, and validation. Production-ready SQL storage for SQLite, PostgreSQL, or MySQL databases. Time-series analysis for querying historical drilling data with time-based filtering. Modular architecture with plug-and-play transports (serial, TCP) and outputs (SQL, JSON). Type-checked with pydantic for data integrity .

- **[well_profile](https://github.com/pro-well-plan/well_profile)**  
  Python tool for well trajectory calculation with 82+ stars on GitHub . Part of the pro-well-plan organization providing open-source well engineering tools. Includes related repositories for torque and drag calculations (torque_drag) and temperature analysis (pwptemp) .

- **[directional_drilling](https://github.com/faridrafati/directional_drilling)**  
  Web-based directional drilling application built with TypeScript, React, Three.js, Fastify, and Prisma. Ported from ~19k lines of Delphi/Pascal trajectory math and UI . Features 30+ profile types including CH→D3DS chained profiles with min-DLS hints on failure. 3D wellbore viewer with tubular mesh rendering, field scene with grid visualization, and compass markers. Field map support with `.grd` parser (Petrel ASCII grid format), coloured raster display, marching-squares contours, and volume calculator. Reports export to PDF (multi-page A4 via pdfmake) and XLSX (via SheetJS) with columns for MD, Incl, Azm, TVD, VSEC, NS, EW, DLS, TF, BR, TR, DMD . Undo/redo with 50-deep history, debounced autosave, and CSV import for bulk data loading .

- **[OpenGeoPlotter](https://github.com/bsomps/OpenGeoPlotter)**  
  PyQt5 application for visualizing geologic drill hole data, catered to the exploration industry. Features cross-sections, simple 3D views, strip logs, scatter plots, and downhole line plots. Includes data transformation techniques like factor analysis, desurveying, and alpha-beta conversion .

- **[WellTrajectoryCalculator](https://github.com/aliakseis/WellTrajectoryCalculator)**  
  C++ implementation for directional well trajectory calculation, referenced from drillingmanual.com. Includes profile design and planning algorithms .

- **[sag_correction_quality_control](https://github.com/scottkerstetter/sag_correction_quality_control)**  
  Python tool for processing corrected survey sheets from MagVar (Saphira). Loops through files, extracts data, loads into dataframe, and exports to CSV for quality control workflows .

- **[target_line_plot](https://github.com/scottkerstetter/target_line_plot)**  
  Python utility for plotting target lines for geosteering and directional drilling applications .

### Additional Strong Open-Source Options

- **Drilling Rate of Penetration Prediction** — Random forest and particle swarm optimization for ROP prediction and optimization in drilling processes. Chinese-language project with recent commits (November 2024) .
- **Drilling NPT Ledger** — Python tool that turns daily drilling reports into a non-productive-time ledger. Measures why drilling-NPT models do not transfer between operators and how little local data fixes it. Updated August 2026 .
- **Physics-based Rig Simulator** — Surface-to-surface drilling rig simulator for generating synthetic EDR telemetry and directional well data. Updated August 2026 .
- **DDR Intelligence Pipeline** — Data pipeline for the public Utah FORGE geothermal well archive (FORGE 16A(78)-32). Updated July 2026 .
- **Volve Field Drilling Monitor** — Watches live drilling data, flags trouble before it becomes an incident, and answers plain-English questions about the well — built entirely on Equinor's real Volve field data. Updated June 2026 .
- **welltrajconvert** — Calculate directional survey metadata points along the wellbore. Python-based .
- **Interactive Well Trajectory Plot** — Python implementation for generating interactive well trajectory plots using Plotly. Focused on visualizing Well 15/9-F-5 from the Volve dataset. Updated June 2026 .

**Frameworks for building custom drilling operations solutions**: Combine **welleng** for well trajectory planning and anti-collision analysis . Use **Witsml Explorer** for WITSML data management and QA/QC . Deploy the **Open Source Drilling Community** microservices for modular drilling calculations including torque/drag, hydraulics, and trajectory . Integrate **witskit** for WITS data decoding and time-series storage . Use **directional_drilling** for a complete web-based directional drilling application with 3D visualization . Note that true enterprise drilling operations platforms with real-time rig instrumentation, automated drilling control, and integrated NPT analytics remain primarily commercial territory; open-source stacks provide strong trajectory planning, data management, and calculation foundations that require integration for complete operations management.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Drilling operations tools must comply with industry standards (IADC, API), safety regulations, and environmental requirements.
- Self-hosted open-source solutions require proper infrastructure, petroleum engineering expertise, and ongoing maintenance. Well trajectory calculations and anti-collision analysis should be validated against industry-standard methods before field deployment.
- The open-source ecosystem provides strong trajectory planning, WITSML data management, and drilling calculation foundations, but real-time rig instrumentation, automated drilling control, and enterprise NPT analytics remain primarily a commercial offering.

---

**Made for drilling engineers, well planners, drilling contractors, and petroleum technologists.**  
Let's make drilling operations management more open, transparent, and data-driven.
