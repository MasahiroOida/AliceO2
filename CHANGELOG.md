# Changes since 2026-06-11

## Changes in Algorithm

- [#15554](https://github.com/AliceO2Group/AliceO2/pull/15554) 2026-06-24: Mergers: fix duplicated header guards by [@knopers8](https://github.com/knopers8)
- [#15555](https://github.com/AliceO2Group/AliceO2/pull/15555) 2026-06-25: Mergers: actually collect only mergeable objects belonging to TCanvas by [@knopers8](https://github.com/knopers8)
## Changes in Analysis

- [#15512](https://github.com/AliceO2Group/AliceO2/pull/15512) 2026-06-11: AOD Writer: correct reserve for cpvClusters by [@ktf](https://github.com/ktf)
## Changes in Common

- [#15511](https://github.com/AliceO2Group/AliceO2/pull/15511) 2026-06-15: Add c-deuteron PDG code in physics constants and add missing Lc* in O2DatabasePDG by [@fgrosa](https://github.com/fgrosa)
- [#15541](https://github.com/AliceO2Group/AliceO2/pull/15541) 2026-06-23: DPL: adapt to FairMQ new API by [@aalkin](https://github.com/aalkin)
## Changes in DataFormats

- [#15511](https://github.com/AliceO2Group/AliceO2/pull/15511) 2026-06-15: Add c-deuteron PDG code in physics constants and add missing Lc* in O2DatabasePDG by [@fgrosa](https://github.com/fgrosa)
- [#15549](https://github.com/AliceO2Group/AliceO2/pull/15549) 2026-06-24: Possibility to globally bias MeanVertex objects via env.var by [@shahor02](https://github.com/shahor02)
## Changes in Detectors

- [#15512](https://github.com/AliceO2Group/AliceO2/pull/15512) 2026-06-11: AOD Writer: correct reserve for cpvClusters by [@ktf](https://github.com/ktf)
- [#15503](https://github.com/AliceO2Group/AliceO2/pull/15503) 2026-06-11: RICH: make local Z the radial axis for radiator and photosensor tiles by [@altsybee](https://github.com/altsybee)
- [#15457](https://github.com/AliceO2Group/AliceO2/pull/15457) 2026-06-12: Ctpdev: cinsistency checker fix by [@lietava](https://github.com/lietava)
- [#15507](https://github.com/AliceO2Group/AliceO2/pull/15507) 2026-06-12: FT3 Staves Minor ambiguity bugfix by [@JustusRudolph](https://github.com/JustusRudolph)
- [#15526](https://github.com/AliceO2Group/AliceO2/pull/15526) 2026-06-15: Add missing parameter instantiation by [@ktf](https://github.com/ktf)
- [#15515](https://github.com/AliceO2Group/AliceO2/pull/15515) 2026-06-15: ITS: optionally restrict CA to a subset of layers + support inactive layers by [@mpuccio](https://github.com/mpuccio)
- [#15524](https://github.com/AliceO2Group/AliceO2/pull/15524) 2026-06-16: Changes in TPC residuals validation by [@shahor02](https://github.com/shahor02)
- [#15519](https://github.com/AliceO2Group/AliceO2/pull/15519) 2026-06-16: TPC: clamp zOut to TPC length by [@matthias-kleiner](https://github.com/matthias-kleiner)
- [#15490](https://github.com/AliceO2Group/AliceO2/pull/15490) 2026-06-17: fix warning final-dtor-non-final-class by [@f3sch](https://github.com/f3sch)
- [#15497](https://github.com/AliceO2Group/AliceO2/pull/15497) 2026-06-17: ITS: add per-stage memory stat by [@f3sch](https://github.com/f3sch)
- [#15527](https://github.com/AliceO2Group/AliceO2/pull/15527) 2026-06-17: ITS: avoid memory shuffeling by accessing tracks via idx by [@f3sch](https://github.com/f3sch)
- [#15498](https://github.com/AliceO2Group/AliceO2/pull/15498) 2026-06-17: ITS: get cluster index only once by [@f3sch](https://github.com/f3sch)
- [#15522](https://github.com/AliceO2Group/AliceO2/pull/15522) 2026-06-17: ITS: GPU: fix perPrimaryVertexProcessing by [@f3sch](https://github.com/f3sch)
- [#15535](https://github.com/AliceO2Group/AliceO2/pull/15535) 2026-06-17: TPC: scale VDrift for every TF with TP by [@matthias-kleiner](https://github.com/matthias-kleiner)
- [#15537](https://github.com/AliceO2Group/AliceO2/pull/15537) 2026-06-18: [ALICE3] TF3: fix labels filling in digitization by [@maciacco](https://github.com/maciacco)
- [#15538](https://github.com/AliceO2Group/AliceO2/pull/15538) 2026-06-19: TPC: fix initialization of FFTW arrays in aggregator-ft by [@ehellbar](https://github.com/ehellbar)
- [#15521](https://github.com/AliceO2Group/AliceO2/pull/15521) 2026-06-24: ALICE3: prepare IOTOF geometry for including TOF in tracking by [@mpuccio](https://github.com/mpuccio)
- [#15552](https://github.com/AliceO2Group/AliceO2/pull/15552) 2026-06-24: ITSMFT: add 13-layer tracking support by [@mpuccio](https://github.com/mpuccio)
- [#15532](https://github.com/AliceO2Group/AliceO2/pull/15532) 2026-06-24: TPC: Add sector edge fluctuation correction infrastructure by [@matthias-kleiner](https://github.com/matthias-kleiner)
- [#15543](https://github.com/AliceO2Group/AliceO2/pull/15543) 2026-06-25: [ALICE3] TF3: add first version of QA macro to check digitization by [@maciacco](https://github.com/maciacco)
## Changes in Framework

- [#15512](https://github.com/AliceO2Group/AliceO2/pull/15512) 2026-06-11: AOD Writer: correct reserve for cpvClusters by [@ktf](https://github.com/ktf)
- [#15517](https://github.com/AliceO2Group/AliceO2/pull/15517) 2026-06-13: DPL: finer grainded timestamps in logs by [@ktf](https://github.com/ktf)
- [#15530](https://github.com/AliceO2Group/AliceO2/pull/15530) 2026-06-16: Allow the MCP to get the wagons of a given train by [@ktf](https://github.com/ktf)
- [#15540](https://github.com/AliceO2Group/AliceO2/pull/15540) 2026-06-18: Add IgProf support to the MCP by [@ktf](https://github.com/ktf)
- [#15550](https://github.com/AliceO2Group/AliceO2/pull/15550) 2026-06-23: DPL MCP: add percentile plots for trains running on the grid by [@ktf](https://github.com/ktf)
- [#15541](https://github.com/AliceO2Group/AliceO2/pull/15541) 2026-06-23: DPL: adapt to FairMQ new API by [@aalkin](https://github.com/aalkin)
## Changes in Steer

- [#15537](https://github.com/AliceO2Group/AliceO2/pull/15537) 2026-06-18: [ALICE3] TF3: fix labels filling in digitization by [@maciacco](https://github.com/maciacco)
## Changes in Utilities

- [#15554](https://github.com/AliceO2Group/AliceO2/pull/15554) 2026-06-24: Mergers: fix duplicated header guards by [@knopers8](https://github.com/knopers8)
- [#15555](https://github.com/AliceO2Group/AliceO2/pull/15555) 2026-06-25: Mergers: actually collect only mergeable objects belonging to TCanvas by [@knopers8](https://github.com/knopers8)
