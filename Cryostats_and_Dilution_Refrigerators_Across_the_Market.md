# Cryostats & Dilution Refrigerators Across the Market  
## by Onri Jay Benally

This is an overview of the commercial cryostat and dilution-refrigerator (DR) landscape, organized first by geography, then by physical footprint and more. It also includes some key comparisons for comprehension as well as some non-dilution cryogenic vessels.

All headline releases are included—the sub-0.8 m² **Bluefors Ultra-Compact LD** laboratory system, the 1.6 m² **Bluefors KIDE** “cryo-house” platform, Oxford Instruments’ modular **Proteox** S/MX/LX/QX family capped by the new QX tier, FormFactor-HPD’s wafer-prober-ready JDry/LF lines and the 508 mm-plate **XLF-600**, plus China’s mass-produced **EZ-Q** refrigerators for domestic quantum-fab roll-outs.

Europe continues to ship the broadest catalog of Stock-Keeping Units (SKUs), an internal, seller-defined alphanumeric label, spanning both DRs and high-vacuum Dewars. North America leads in probe-station and production-test variants.  East-Asia is scaling indigenous volume for \>2,000-qubit stacks. Footprint classes now span **\< 0.5 m²** table-top inserts (e.g., *attoDRY-800*) through compact **0.6–1 m²** floor units to **\> 1.5 m²** data-centre platforms such as *KIDE*. The following tables pair each DR line with its logical Dewar or bulk-cryogen counterpart, giving a lab-ready bill-of-materials perspective. 

* **Dewar**: an *eponym*—named for Scottish chemist Sir James Dewar, who also liquefied hydrogen.  
* **Cryostat**: a portmanteau of Greek **κρύος** (*kryos*, “frost”) \+ *\-stat* (“to make stand, hold”), literally “cold-keeper.”  
* **Thermos™**: commercial trademark (1904) for consumer Dewars (vacuum insulated flask); illustrates the generalization of the scientific invention.  
* **Dilution** *(as in “dilution refrigerator”)*: from Latin **diluere** “to wash away/thin out,” via the French term “dilution”. In a dilution refrigerator the *thinning* of a **³He**\-rich phase into a **⁴He**\-rich phase at ≈ 0.87 K absorbs heat (enthalpy of mixing), allowing continuous cooling to **\<10 mK**. The idea was proposed by Heinz London (1951) and first realized experimentally by the Cambridge–Oxford collaboration in the early 1960s; the term “dilution refrigerator” cemented itself as the technology matured through the 1970s.

Note: A cryostat is any vacuum-insulated vessel or assembly that maintains cryogenic temperatures by *any* cooling method—stored liquid nitrogen or helium, a mechanical Gifford-McMahon or pulse-tube cryocooler, a charcoal-pumped **³He** pot, an adiabatic demagnetization refrigerator (ADR) “salt-pill” stage, or a continuous **³He/⁴He** dilution loop. This inclusive definition embraces a standalone liquid-helium Dewar as the simplest cryostat, while every dilution refrigerator is a cryostat that incorporates the **³He/⁴He** mixing loop required for continuous operation below ≈ 100 mK. Intermediate temperature regimes (≈ 300 mK – 1 K) are spanned by plug-in **³He** sorption coolers, ADRs, pumped-**⁴He** variable-temperature inserts (VTIs), and low-vibration 1 K stages, each selected to balance vibration, duty-cycle, and capital or operating cost for a given quantum-hardware or precision-metrology experiment.

CRYOGENIC VESSELS  
├─ Passive Vessels (no active temperature control)  
│   └─ Dewar Flasks \[L\]                                           ← vacuum-insulated storage  
│       ├─ Static/ Storage Dewar  
│       ├─ Transport Dewar (road/ air)  
│       └─ Open “bucket” Dewar (bench-top dip)  
└─ Cryostats (instrumented cryogenic vessels, with active temperature control)  
    ├─ Liquid-Filled Platforms \[L\]  
    │   ├─ Bath Cryostat  
    │   │   ├─ LN₂ bath (\~77 K)  
    │   │   └─ LHe bath (4.2 K; pumped 1 K pot)  
    │   └─ Continuous-Flow Cryostat (4 K – 300 K; fed from external Dewar)  
    ├─ Closed-Cycle Platforms “Dry” \[D\]  
    │   ├─ Gifford–McMahon (GM) head (≈ 2 – 4 K)  
    │   └─ Pulse-Tube (PT) head (≈ 2 – 4 K; low vibration)  
    └─ Ultra-Low-T Inserts (mount on any 2–4 K stage)  
        ├─ Dilution Refrigerator (DR) \< 10 mK \[D‡\]  
        ├─ ADR/ PDR 50 – 100 mK \[L/D\]  
        ├─ ³He Sorption Cooler 250 – 400 mK \[L/D\]  
        └─ Pumped-⁴He 1 K Stage/ VTI \[L/D\]

**Legend**  

* **\[L\]** Requires stored liquid cryogen   
* **\[D\]** Cryogen-free mechanical (GM or PT) cooler    
* **\[L/D\]** Available in both wet-dipstick and dry bolt-on versions    
* **\[D‡\]** \> 90 % of new DRs ship cryogen-free; a few legacy wet dip-stick units still exist

 

## **Europe-Based Leaders**

| Company (HQ) | Flagship DR lines & plate Ø\* | Distinctive attributes | Base-T |
| ----- | ----- | ----- | ----- |
| **Bluefors** (FI) | Ultra-Compact LD (≤ 300 mm), LD, **XLD/XLDsl/XL** (500 mm), **KIDE** (1.6 m²) | \> 1,000 units shipped; KIDE has ≥ 4,000 RF lines | \< 10 mK |
| **Oxford Instruments – Proteox** (UK) | Proteox S/MX (250–400 mm), Proteox LX/QX (≤ 450 mm) | Modular vector magnet, hot-swap inserts | \< 7 mK |
| **Leiden Cryogenics** (NL) | CF-1100 · CF-CS-XXL (1 m) · MCK inserts | Four-PT option  on 1 m plate | ≈ 5 mK |
| **ICE Oxford** (UK) | DRY-ICE Eden (200 coax, 500 mm) | High 1 K power, low-vib HX | \< 10 mK |
| **Cryoconcept** (FR) | HEXA-DRY (std) · **HEXA-DRY XXL** (Ø 800 mm) | Six-stage HX,  remote diagnostics | \< 8 mK |
| **Cryogenic Ltd** (UK) | STM DR inserts (UHV tubes) | Top-loading for high-field STM | \< 20 mK |
| **attocube** (DE) | attoDRY-800 / \-1100 inserts | Table-top nano-positioning | \< 15 mK |

## **EU Dewars & Cryogenic Vessels**

| Company | Core lines (capacity) | Notes |
| ----- | ----- | ----- |
| **Wessington** | PV/ TPV LN₂ tanks ≤ 2,000 L · ISO bulk | Large fixed storage |
| **Statebourne** | Helistor He 30–990 L · Cryolab LN₂ · CryoCycl micro-bulk | R\&D \+ biobank |
| **KGW-Isotherm** | Bespoke glass-in-steel Dewars \< 30 L | Optics & metrology |
| **Cryo Diffusion** | LO/ CDB / BIO 47–2 250 L (LHe & LN₂) | Pharma &  space ISO |
| **Thames Cryogenics** | 30–2,000 L LN₂ \+ vacuum flex hoses | Site plumbing |

---

## **North-American Suppliers**

### **Dilution Refrigerators**

| Company (HQ) | Key systems/ plate Ø | Extras | Base-T |
| ----- | ----- | ----- | ----- |
| **Quantum Design** (US) | **PPMS DynaCool \+ DR insert** (≈ 305 mm) | Pulse-tube, 50 mK,  no external He | 45–50 mK |
| **FormFactor (HPD)** (US) | JDry-400 · LF-400 · **XLF-600** (508 mm) | Wafer-prober integration | ≤ 5 mK |
| **Zero Point Cryogenics** (CA) | Model I · Model L (250–340 mm) | “Continuous Cold” 1 K stage | \< 10 mK |
| **Cryomech** (US) | PT 4 K/ 1 K stacks (OEM) | Pre-cool for many DRs | n/a |

### **Measurement Platforms (≥ 2 K)**

| Company | System | Range | Notes |
| ----- | ----- | ----- | ----- |
| **Quantum Design** (US) | PPMS VersaLab | 50 K–400 K | 3 T mini-magnet |
|  | MPMS-3 SQUID | 2 K–400 K | ≤ 10⁻⁸ emu |

### **Dewars & Cryogenic Vessels**

| Company (HQ) | Core Dewar product lines & capacity | Notes/ differentiators |
| ----- | ----- | ----- |
| **Cryofab** (US) | **CMSH** liquid-helium Dewars 20 – 500 L; custom transfer lines | Turn-key LHe storage for magnet labs |
| **Chart MVE** (US) | **XC/ CryoShipper** LN₂ shuttles 3 – 60 L | Life-science cold-chain shippers & biobanks |
| **Cryo Industries of America** (US) | *D-Stat* direct-connect Dewars & closed-cycle hybrids | Drop-in dewar-plus-cryocooler kits for low-vib optics |

---

## 

## **East-Asian Entrants & Emerging**

| Company (HQ) | System | Market position | Status |
| ----- | ----- | ----- | ----- |
| **QuantumCTek** (CN) | *EZ-Q Fridge* | Mass-production for domestic qubit fabs | Shipping since 2023 |
| **Origin Quantum** (CN) | SL400/ SL1000 | up to 1 mW @100 mK, ≥1,000 µW @10 mK | Shipping since 2024 |
| **Chinese state consortium** | “EZ-Q” line | Govt-backed scale to 100s units/ yr | Ramp-up 2024 |
| **ULVAC Cryogenics** (JP) | Next-gen DR (IBM co-design) | Target \>2,000-qubit stacks | In dev., 2026 launch  |
| **Other domestic start-ups** (CN, IN) | Lab-scale DRs | OEM PT modules | Market-watch reports |

### **Dewars & Cryogenic Vessels**

| Company (HQ) | Flagship Dewar offerings | Market focus |
| ----- | ----- | ----- |
| **Taiyo Nippon Sanso (TNSC)** (JP) | LN₂ storage/ transport Dewars for 300 mm fabs | Semiconductor foundry bulk-gas logistics |
| **Sumitomo — SHI Cryogenics** (JP) | Stainless LHe/LN₂ Dewars 10 – 300 L paired to G-M coolers | OEM packages for GM-cooled optical cryostats |

---

## 

## **Size & Capability Spectrum (2025)**

| Tier | Representative systems | Footprint | P@100 mK | Typical users |
| ----- | ----- | ----- | ----- | ----- |
| **Table-Top/ Insert** | attoDRY-800/1100; Cryogenic STM; Leiden MCK | ≤ 0.5 m² | ≤ 50 µW | Nano-STM, academia |
| **Ultra- Compact Floor** | Bluefors Ultra-Compact LD | 0.6–0.8 m² | \~200 µW | Univ. qubit benches |
| **Compact Floor (≈ 1 m²)** | Bluefors LD / SD; Oxford Proteox S/MX; **QD DynaCool \+ DR insert** | 0.8–1.1 m² | 250– 400 µW | Start-ups, mid-size labs |
| **Large-Frame/ Multi-Qubit** | Bluefors XLD/XL; ICE Eden; Leiden CF-CS-XXL; FormFactor XLF-600; Oxford Proteox LX/QX; ZP Model L | ≥ 1 m² | 0.6–1 mW | Scale-up R\&D |
| **Data-Center/ XXL** | Bluefors KIDE; Cryoconcept XXL | \> 1.4 m² | 2–3 mW | IBM, Google, fabs |
| **Mass- Production** | QuantumCTek EZ-Q | auto gas- handling | 0.3 mW | CN fabs |
| **Next-Gen (road-map)** | ULVAC 2,000-qubit DR | t.b.d. | t.b.d. | 2026+ |

### **Footnote on DR “wet” outliers**

> **Dilution Refrigerator (D-only)** refers to \> 90 % of new DRs, which are PT- or GM-pre-cooled. Legacy dip-stick DRs for wet helium baths (e.g., Oxford Heliox VL) still exist but are rarely purchased for new builds. 

## **Cryogenic Vendors**

Cryogenic Vendors    
├─ Europe Tier-1  
│  ├─ Dilution Refrigerators  
│  │  ├─ Bluefors → Ultra-Compact LD, LD, XLD/XL, KIDE   — 300 mm→1.6 m² plates (\>4,000 RF) \[D\]   
│  │  ├─ Oxford Instruments → Proteox S/MX, LX/QX          — modular Triton successor \[D\]   
│  │  ├─ Leiden Cryogenics → CF-1100, MCK                  — up to Ø 1 m, 4-PT option \[D\]   
│  │  └─ ICE Oxford → DRY-ICE Eden                          — 200-coax, \<10 mK \[D\]   
│  └─ Dewars & Cryogenic Vessels  
│       ├─ Wessington Cryogenics → PV/TPV LN₂ tanks (≤2,000 L), ISO bulk \[L\]  
│       ├─ Statebourne → Helistor He (30–990 L), Cryolab LN₂, CryoCycl micro-bulk \[L\]  
│       ├─ KGW-Isotherm → lab/transport Dewars (borosilicate & SS) \[L\]  
│       ├─ Cryo Diffusion (Air Liquide) → LO/CDB/BIO LHe & LN₂ (47→2 250 L) \[L\]  
│       └─ Thames Cryogenics → LN₂ vessels 30–2,000 L \+ vacuum hoses \[L\]  
├─ North America  
│  ├─ Dilution Refrigerators  
│  │    ├─ Quantum Design → PPMS DynaCool \+ DR insert — 50 mK, pulse-tube, cryogen-free \[D\]  
│  │    ├─ FormFactor (HPD) → JDry, LF-400, XLF-600      — ≤5 mK, ≤270 coax \[D\]  
│  │    ├─ Zero Point Cryogenics → Model I, Model L       — “Continuous Cold” 1 K stage \[D\]  
│  │    └─ Cryomech → PT 1 K/4 K stacks for DR OEMs        — OEM precoolers \[D\]  
│  ├─ Non-Dilution Systems/ Measurement Platforms (cryogen-free, ≥2 K)  
│  │    ├─ Quantum Design → PPMS DynaCool without DR insert — standard option (1.8K) \[D\]  
│  │    ├─ Quantum Design → PPMS VersaLab (50 K–400 K, 3 T) \[D\]  
│  │    └─ Quantum Design → MPMS-3 SQUID (2 K–400 K, ≤10⁻⁸ emu) \[D\]  
│  └─ Dewars & Cryogenic Vessels  
│       ├─ Cryofab → CMSH LHe dewars 20→500 L \+ transfer lines \[L\]  
│       ├─ Chart MVE → XC/CryoShipper LN₂ biobanks 3–60 L \[L\]  
│       └─ Cryo Industries of America → “D-Stat” direct-connect dewars & hybrids \[L\]  
└─ East Asia & Emerging  
   ├─ Dilution Refrigerators  
   │   ├─ QuantumCTek (CN) → EZ-Q Fridge \[D\]  
   │   ├─ CN State Consortium → EZ-Q scale-out platform \[D\]  
   │   └─ ULVAC (JP) → next-gen DR (IBM co-design, ≥2026) \[D\]  
   └─ Dewars & Cryogenic Vessels  
        ├─ Taiyo Nippon Sanso → LN₂ storage/transport tanks for fabs \[L\]  
        └─ Sumitomo (SHI) → GM-pre-cooled LHe vessels 10→300 L \[L\]

**Legend**

* **\[D\]** cryogen-free (PT or GM pre-cooled), GM heads are rare in modern DRs; most large DRs are PT-cooled  
* **\[L\]** requires stored liquid N₂/He

## **Key Trends (mid-2025)**

* **KIDE ships & scales** – first 1.6 m² “cryo-house” fridges delivered to IBM & AIST Q-centres. ([bluefors.com](https://bluefors.com/products/kide-cryogenic-platform), [bluefors.com](https://bluefors.com/news/bluefors-delivers-18-state-of-the-art-quantum-cooling-systems-to-power-aists-g-quat-center))  
* **Proteox replaces Triton** – Oxford’s entire new-build catalog now lists Proteox S–LX; Triton lives on mainly in installed base. ([nanoscience.oxinst.com](https://nanoscience.oxinst.com/ProteoxFamily))  
* **FormFactor enters \>500 mm club** – XLF-600 targets quantum-data-centre racks with 600 µW @ 100 mK. ([formfactor.com](https://www.formfactor.com/product/quantum-cryo/dilution-refrigerators/xlf-600))  
* **Ultra-compact trend** – Bluefors shrinks LD footprint to \<0.8 m² to fit power-lab closets. ([bluefors.com](https://bluefors.com/news/introducing-the-ultra-compact-dilution-refrigerator-system))  
* **China ramps EZ-Q** – domestic lines running since 2023; hundreds of units/year goal. ([thequantuminsider.com](https://thequantuminsider.com/2024/02/28/reports-china-mass-producing-dilution-refrigerator-critical-to-superconducting-quantum-computing), [globaltimes.cn](https://www.globaltimes.cn/page/202402/1307818.shtml))  
* **IBM–ULVAC collaboration** – next-gen DR co-designed for 2,000-qubit era, aimed at 2026 launch. ([thequantuminsider.com](https://thequantuminsider.com/2025/03/22/ulvac-developing-next-generation-dilution-refrigerator-for-quantum-computing-by-2026))

**All systems above are cryogen-free (pulse-tube-pre-cooled) unless explicitly labelled “wet”  or “wet bath” (legacy Janis variants).** Vendors continue to offer bespoke wiring looms, optical access, vector magnets and gas-handling automation, allowing the same base frames to serve superconducting-qubit stacks, SNSPD arrays, cavity optomechanics and nano-SQUID STM.

## **Mind-Map of DR/ Non-DR/ Dewar Sizes (Form-Factors)** 

Form-Factor Families ─ Dilution Refrigerators/ Non-Dilution Cryostats/ Paired Dewar Vessels  
├─ **Table-Top/ Insert  (\< 0.5 m²)**  
│   ├─ DR attocube  attoDRY-800/ \-1100  
│   ├─ DR Cryogenic Ltd  STM-insert DRs (UHV tubes)  
│   └─ Dewar KGW-Isotherm lab borosilicate/ stainless hybrids  (\< 30 L)  
│  
├─ **Ultra-Compact Floor  (≈ 0.6 – 0.8 m²)**  
│   ├─ DR Bluefors  Ultra-Compact LD  (≤ 300 mm plate)  
│   └─ Dewar Statebourne Cryolab & CryoCycl  LN₂ micro-bulk  (30 – 60 L)  
│  
├─ **Compact Floor-Standing  (≈ 1 m²)**  
│   ├─ DR  Bluefors  LD/ SD  
│   ├─ DR  FormFactor-HPD  JDry-400  ·  LF-400  
│   ├─ DR  Oxford Instruments  Proteox S  
│   ├─ DR  Quantum Design PPMS DynaCool \+ DR insert  
│   ├─ Non-DR  Quantum Design PPMS DynaCool without DR insert (standard option)  
│   ├─ Non-DR  Quantum Design PPMS VersaLab   
│   ├─ Non-DR  Quantum Design MPMS-3 SQUID  
│   └─ Dewar Cryofab  CMSH  liquid-helium Dewars  (20 – 500 L)  
│  
├─ **Large-Frame  (≥ 1 m²)**  
│   ├─ DR   Bluefors  XLD/  XL  
│   ├─ DR   FormFactor-HPD  XLF-600  
│   ├─ DR   Oxford Instruments  Proteox MX/  LX  
│   ├─ DR   ICE Oxford  DRY-ICE Eden  
│   ├─ DR   Zero Point Cryogenics  Model L  
│   ├─ DR   Leiden Cryogenics  CF-CS-XXL/ 1 m plate  
│   └─ Dewar Wessington  PV/ TPV tanks  ·  Cryo Diffusion  LO/ CDB series  (\> 1,000 L)  
│  
└─ **Data-Center/ XXL  (\> 1.4 m² · multi-PT stacks)**  
    ├─ DR   Bluefors  KIDE  (1.6 m² flange)  
    ├─ DR   Cryoconcept  HEXA-DRY XXL  (Ø 800 mm)  
    ├─ DR   QuantumCTek  EZ-Q  (mass-production line)  
    ├─ DR   ULVAC  next-gen DR  (IBM co-design, slated ≥ 2026\)  
    └─ Dewar Taiyo Nippon Sanso bulk LN₂ tanks  ·  Sumitomo (SHI) GM-precooled LHe vessels   

## **Mind-Map of Cryogenic Vessel Platforms** 

Cryogenic Platforms for Quantum/ Metrology  
├─ **4–300 K Range**  
│  ├─ Bath Dewar (He-4)  
│  ├─ Continuous-flow He-4  
│  └─ Closed-cycle Pulse-tube (1.5 K)  
├─ **1 K Class**  
│  ├─ Pumped-⁴He VTI  
│  └─ Dedicated 1 K PT Stage  
├─ **0.3–1 K Sorption Family**  
│  ├─ ³He “pump-on” insert  
│  └─ He-7 (³He/⁴He) sorption fridge  
├─ **50–100 mK Magnetic Cooling**  
│  ├─ ADR (single-shot)  
│  └─ Continuous ADR (CADR)  
└─ **\<50 mK Dilution Line**  
   ├─ Standard DR (lab workhorse)  
   ├─ Large-Frame DR (Proteox LX, XLF-600)  
   └─ Data-Center/ XXL DR (Bluefors KIDE)

## **Mind-Map of Cryogenic Vessels with Usage Tags**

Cryogenic Platforms for Quantum/ Metrology  
├─ **4–300 K Range**  
│  ├─ Bath Dewar (Academic-dominant)  
│  ├─ Continuous-flow He-4 (Academic-dominant)  
│  └─ Closed-cycle Pulse-tube   (Mixed)  
├─ **1 K Class**  
│  ├─ Pumped-⁴He VTI            (Academic-dominant)  
│  └─ 1 K Pulse-tube Stage      (Mixed → Industrial-leaning)  
├─ **0.3–1 K Sorption Family**  
│  ├─ ³He “pump-on” insert (Academic-dominant)  
│  └─ He-7 sorption fridge (Academic-dominant)  
├─ **50–100 mK Magnetic Cooling**   
│  ├─ ADR (Academic-dominant)  
│  └─ Continuous ADR (CADR) (Government Space-science)  
└─ **\<50 mK Dilution Line**  
   ├─ Standard DR               (Mixed/ Balanced)  
   ├─ Large-Frame DR            (Industrial-leaning)  
   └─ Data-Center/ XXL DR      (Industrial-only)

## **Academic vs Industrial Usage Table**

| Branch in the family tree | Typical users today | Representative evidence |
| ----- | ----- | ----- |
| **Bath Dewar (He-4)** | **Academic-dominant** — low-budget superconductivity, Hall-bar labs | University lab manuals & cryogenics texts list bath Dewars as “entry-level” cryostats. ([research.physics.illinois.edu](https://research.physics.illinois.edu/bezryadin/links/practical%20cryogenics.pdf)) |
| **Continuous-flow He-4 cryostat** | **Academic-dominant** — fast magnetotransport, microscopy | Oxford-type CF cryostats reported in research papers on magnetic microscopy. ([pubs.aip.org](https://pubs.aip.org/aip/rsi/article/92/12/123701/283257/Operation-of-a-continuous-flow-liquid-helium)) |
| **Closed-cycle PT (1.5 K)** | **Mixed** — academic spin qubit benches *and* industrial device screening | Pulse-tube coolers marketed for both lab R\&D and industrial cryopumps. ([thequantuminsider.com](https://thequantuminsider.com/2023/09/12/cryogenics-a-short-history-the-implications-it-has-on-the-qc-industry)) |
| **Pumped ⁴He VTI (1 K pot)** | **Academic-dominant** — custom magnet systems (MagLab, Neutron sources) | National MagLab lists 1 K VTI sample environments for users. ([nationalmaglab.org](https://nationalmaglab.org/user-facilities/dc-field/magnets-instruments/sample-environments)) |
| **Dedicated 1 K PT stage** | **Mixed → industrial-leaning** — pre-cooling dense coax in qubit fabs | Bluefors XLD-He¹K systems pitched at spin-qubit foundries. ([bluefors.com](https://bluefors.com/news/introducing-the-xldhe-high-power-system-ultimate-cooling-for-1-k-experiments)) |
| **³He “pump-on” insert (0.3 K)** | **Academic-dominant** — graphene transport, thermometry courses | Cryogenic Ltd 300 mK insert for CFMS research suites. ([cryogenic.co.uk](https://www.cryogenic.co.uk/node/239)) |
| **He-7 (³He/⁴He) sorption fridge** | **Academic-dominant** — CMB cameras, balloon telescopes | He-7 fridges specified in STRIP/LSPE CMB instrument papers. ([researchgate.net](https://www.researchgate.net/figure/Pulse-tube-cooler-head-left-4-K-box-He-7-sorption-fridge-centre-bottom-and_fig9_255608978)) |
| **ADR (single-shot 35–80 mK)** | **Academic-dominant** — millikelvin STM, µ-SQUID probes | UHV STM platform cooled by single-shot ADR. ([pubs.aip.org](https://pubs.aip.org/aip/rsi/article/92/6/063701/991153/A-millikelvin-scanning-tunneling-microscope-in)) |
| **Continuous ADR (CADR)** | **Government space-science** — NASA far-IR missions (industrial contractors build, but science-driven) | NASA’s multistage CADR cited for space telescopes. ([nrao.edu](https://www.nrao.edu/meetings/isstt/papers/2009/2009097106.pdf)) |
| **Standard dilution refrigerator  (lab workhorse, ≤20 mK)** | **Balanced** — every superconducting-qubit university *and* most start-ups own one | Bluefors & ICEoxford market DRs simultaneously to universities and start-ups.([bluefors.com](https://bluefors.com/applications/quantum-technology)) |
| **Large-Frame DR (Oxford Proteox LX/QX, FormFactor XLF-600)** | **Industrial-leaning** — multi-hundred-qubit prototypes at Rigetti, IQM, etc. | Oxford Proteox LX in Rigetti partner program;([oxinst.com](https://www.oxinst.com/news/oxford-instruments-nanoscience-joins-rigettis-novera-qpu-partner-program)) FormFactor XLF-600 positioned for “quantum data centers.”([formfactor.com](https://www.formfactor.com/product/quantum-cryo/dilution-refrigerators/xlf-600), [formfactor.com](https://www.formfactor.com/press-release/formfactor-adds-dilution-refrigeration-dr-systems-critical-for-quantum-computer-deployment)) |
| **Data-Center/  XXL DR  (Bluefors KIDE, Cryoconcept XXL)** | **Industrial-only** — IBM Quantum System Two, Google, national QC centers | First KIDE delivered to IBM; IBM blog confirms use for System Two.([bluefors.com](https://bluefors.com/stories/kide-cryogenic-platform-from-design-to-delivery), [ibm.com](https://www.ibm.com/quantum/blog/goldeneye-cryogenic-concept-system)) |

*Legend – “Academic-dominant” \= \>70 % of installed base in universities/public labs; “Industrial-leaning” \= roughly even but trending commercial; “Industrial-only” \= found almost exclusively in corporate fabs or government megaprojects.*

## **Choosing the Right Variant**

* **≥1 K work** – pumped-⁴He or cryogen-free pulse-tube cryostats are cheapest and least complex.  
* **0.3–1 K niche** – ³He inserts or He-7 sorption coolers shine when you need vibration-free sub-kelvin temperatures for hours, not weeks.  
* **50–100 mK stable “science-grade” base** – ADRs give motion-free cooling for space instruments; continuous ADRs are now hitting 50 mK nonstop.  
* **Sub-50 mK, high wiring density (HDW), continuous uptime** – dilution refrigerators (and their KIDE-class big-siblings) are the *de facto* standard for quantum processors, SNSPD arrays, and precision Johnson-noise thermometry.

## **Comparison Between Familiar Compact vs. Large-Frame**   
**PT-Cooled Dilution Refrigerators**

The **Quantum Design PPMS DynaCool** becomes a *compact* dilution refrigerator (≈ 1 m² footprint) when its 50 mK insert (aka DR insert) is installed. A single two-stage PT furnishes the 4 K stage, and a sealed ³He/⁴He loop cools from 300 K to ≈ 45 mK with no external dewars.

The **Bluefors XLDsl** is a *large-frame* PT-cooled refrigerator with the dilution circuit factory-integrated. Its 500 mm mixing-chamber flange, dual-PT stack and ≥ 1,000 µW cooling power at 100 mK support up to 1,008 coax/twisted-pair/FPC/optical lines delivered by hot-swappable High-Density Wiring “chandeliers.” 

Thus both systems are cryogen-free dilution refrigerators, but they differ sharply in flange size, cooling power, wiring density and upgrade path rather than in the basic refrigeration principle.

| Metric | PPMS DynaCool \+ DR Insert | Bluefors XLDsl |
| ----- | ----- | ----- |
| Footprint | ≈ 1 m² floor unit | ≥ 1 m² large frame |
| PT stages | 1 two-stage PT | 2 two-stage PTs |
| Mixing-chamber flange | 305 mm | 500 mm |
| Cooling power @ 100 mK | ≈ 400 µW | ≥ 1,000 µW  |
| Base temperature | 45–50 mK | \< 10 mK |
| Wiring capacity | ≤ 360 RF/DC lines | 1,008 HD lines |

---

## **What the Bluefors XLD “Chandelier” Really Is**

| Term | OEM language | Function |
| ----- | ----- | ----- |
| **XLDsl Dilution Refrigerator Measurement System** | Marketed as a *cryogen-free DR measurement system* with large experimental space. | The entire fridge—including still, heat-exchangers, mixing chamber—is already inside the vacuum can. |
| **High-Density Wiring (side-load or top-load)** | Bluefors calls the modular wiring loom “High-Density Wiring,” compatible with XLD. | Provides hundreds of coax/twisted-pair lines; resembles a metallic “chandelier.” |
| **Colloquial “chandelier”** | Community photos and forum threads show the gold-plated wiring tree hanging from the mixing chamber. | Visual nickname, not a refrigeration stage. |

> **Key idea:** the chandelier is **part of the wiring infrastructure**, not the refrigeration insert. You can call it a **high-density wiring chassis**, a modular loom that brings hundreds of coax, twisted-pair, optical fiber, or ribbon lines down to the mixing-chamber plate. In Bluefors systems the dilution unit is permanently integrated; users add or swap chandeliers (wiring modules, attenuators, filters) to suit qubit count, signal bandwidth, or device technology.

---

## **How to Tell an Insert from a Wiring Tree/ Chassis**

| Indicator | Dilution Refrigerator Insert | Wiring “Chandelier” |
| ----- | ----- | ----- |
| Contains still, heat-exchangers, mixing chamber | **Yes** | No |
| Circulates ³He/⁴He mixture | **Yes** | No |
| Must connect to gas-handling system | **Yes** | No |
| Bolts to 50 mK plate; routes cables & attenuators | Optional plate on bottom | **Primary purpose** |
| Delivered as stand-alone module for a pre-existing 4 K cryostat | DynaCool DR insert (dry) | N/A—comes with chassis |

## **Glossary of Acronyms**

| Acronym | Full term / meaning | One-line context / why it matters |
| ----- | ----- | ----- |
| **ADR** | *Adiabatic Demagnetization Refrigerator* | Single-shot magnetic-salt cooler that reaches 50–100 mK without circulation gas |
| **CADR** | *Continuous ADR* (multiple ADR stages run out-of-phase) | Provides 40–70 mK indefinitely for space telescopes and sub-mm detectors |
| **CCR** | *Closed-Cycle Refrigerator* (industry shorthand for a PT-based cryostat) | Two-stage PT inside a vacuum can; “1.7-4 K CCR” in your platform table |
| **DR** | *Dilution Refrigerator* | Continuous ³He/⁴He mixing loop for \<10 mK physics; all large quantum stacks use one |
| **FPC** | *Flex-Printed-Circuit* cabling option in Bluefors High-Density Wiring | Brings hundreds of signal lines on ribbon-like copper traces |
| **GM** | *Gifford–McMahon* cryocooler head | Alternative to PT for 4 K precool; more moving parts |
| **HDW** | *High-Density Wiring* (Bluefors “chandelier”) | Hot-swappable loom that carries up to 1,008 coax/twisted-pair/FPC/optical lines |
| **He-7** | ³He/⁴He *triple-stage* sorption refrigerator | Reaches 200 mK with no mechanical pump; useful for balloon CMB cameras |
| **KID** | *Kinetic Inductance Detector* | Ultra-low-noise sub-K photon sensor for CMB astronomy; often mounted in sorption or DR stages |
| **LN₂/ LHe** | *Liquid-Nitrogen* / *Liquid-Helium* baths | Classic 77 K and 4.2 K cryogens for “wet” platforms |
| **PDR** | *Paramagnetic (or Praseodymium) Demagnetization Refrigerator* – a rare-earth variant of ADR | Shown as “ADR / PDR 50–100 mK” in the tree; same physics, different salt choice |
| **PT** | *Pulse-Tube* cryocooler | Vibration-isolated 50 K / 4 K stages that make modern DRs “dry” |
| **RF/ SMA** | *Radio-Frequency* signals and the **SMA** coax connector standard | Large DR flanges quote “128 SMA” or “\>4,000 RF lines” for qubit wiring |
| **SNSPD** | *Superconducting Nanowire Single-Photon Detector* | Cryogenic optical detector packed by the thousand in big DRs |
| **SQUID** | *Superconducting Quantum-Interference Device* | μ-SQUID microscopes often cooled by ADRs |
| **STM** | *Scanning-Tunnelling Microscope* | Millikelvin STMs ride in single-shot ADRs or DRs for ultra-low-vibration measurements |
| **TES** | *Transition-Edge Sensor* | Cryogenic calorimeter used with KID arrays in He-7 or DR stages |
| **UHV** | *Ultra-High Vacuum* | Vacuum environment (\<10⁻⁹ mbar) required by some millikelvin STMs and DR sample inserts |
| **VTI** | *Variable-Temperature Insert* (pumped-⁴He “1 K pot”) | 0.8–1.2 K intercept for dense coax bundles before the mixing chamber |


## **Glossary of Special-Purpose Cryogenic Platforms**

| Platform | What it is/ How it works | Operating window & duty-cycle | Where you meet it in practice |
| ----- | ----- | ----- | ----- |
| **³He “pump-on” insert** (single-shot He-3 pot) | A sealed reservoir of ³He gas is condensed onto a tiny pot by a charcoal sorption pump; once the pump is cooled and evacuated, evaporative cooling drives the pot to  ≈ 300 mK. No moving parts after start-up. | **1.5 K → 300 mK** for **12–48 h**, then needs warm-up & recycle. | Graphene/mesoscopic transport, Johnson-noise thermometry, low-vibration optics. |
| **He-7 sorption refrigerator** (³He/⁴He triple-stage) | Cascaded charcoal pumps: first ⁴He precools to \~1 K, then two ³He stages reach 300 mK and 200 mK. Entire unit is bolt-on and vibration-free. | **1 K → 200 mK**, single-shot  **24–72 h**. | KID/ TES detector cameras, balloon-borne CMB telescopes, portable sub-K test stands. |
| **Adiabatic  Demagnetization Refrigerator (ADR)** | Magnetize a paramagnetic salt pill at 4 K, then demagnetize it adiabatically; magnetic entropy turns into cooling reaching **50–100 mK**  (≈ 35 mK with modern salts). No circulation gas. | Single-shot  **8–24 h** below 100 mK. | Ultra-low-vibration STM, µ-SQUID scanners, small space payload prototypes. |
| **Continuous ADR (CADR)** | Several ADR stages run out-of-phase; while one stage warms, another cools, so the cold tip stays at **≈ 50 mK indefinitely**  (≈ 10 µW cooling power). | **Continuous 40–70 mK** operation, weeks to months. | Far-IR bolometers & X-ray micro-calorimeters on NASA space telescopes. |
| **Pumped-⁴He “1 K stage”** | A mechanical pump lowers vapor-pressure of a small ⁴He bath or JT loop, giving a **1 K plate** that intercepts heat from hundreds of coax lines before they enter a dilution unit. | **4 K → 0.8– 1.2 K**, runs as long as the pump does. | Pre-cool wiring in big dilution fridges; basic magnetotransport below 2 K. |
| **Pulse-tube cryostat (CCR 1.7–4 K)** | Two-stage pulse-tube cooler inside a vacuum can; cryogen-free. Some models (QD OptiCool, DynaCool+DR) accept DR or sorption inserts down to 50 mK. | **300 K → 1.7 K** (OptiCool) or  **→ 50 mK** with DR insert, fully continuous. | Cryo-CMOS & spin-qubit test rigs, optical spectroscopy with vector magnets. |
| **Large-scale dilution refrigerator** (≥ 1 m² plate) | Pulse-tube precooling plus continuous ³He/⁴He mixing. Examples: **Bluefors KIDE** (1.6 m², \>4,000 RF) and **Oxford Proteox LX** (≤ 450 mm plate, 128 SMA). | **4 K → ≤ 5 mK**, continuous; **0.5–3 mW** at 100 mK depending on model. | 100–1,000 qubit quantum-computer racks, large SNSPD arrays, cryo-data-centres. |

References

1. **Bluefors Oy** 2024, *Ultra-Compact LD dilution-refrigerator measurement system*. Available at: [https://bluefors.com/products/dilution-refrigerator-measurement-systems/ultra-compact-ld](https://bluefors.com/products/dilution-refrigerator-measurement-systems/ultra-compact-ld) (Accessed 22 June 2025).  
2. **Bluefors Oy** 2023, *KIDE cryogenic platform*. Available at: [https://bluefors.com/products/kide-cryogenic-platform](https://bluefors.com/products/kide-cryogenic-platform) (Accessed 22 June 2025).  
3. **Oxford Instruments NanoScience** 2024, *Proteox family overview*. Available at: [https://nanoscience.oxinst.com/ProteoxFamily](https://nanoscience.oxinst.com/ProteoxFamily) (Accessed 22 June 2025).  
4. **Oxford Instruments NanoScience** 2025, *Proteox LX dilution refrigerator*. Available at: [https://nanoscience.oxinst.com/products/proteoxlx](https://nanoscience.oxinst.com/products/proteoxlx) (Accessed 22 June 2025).  
5. **ICE Oxford** 2024, *DRY-ICE EDEN 10 mK dilution cryostat – brochure* (PDF). Available at: [https://www.iceoxford.com/files/image/files/DRYICE%20EDEN%20Brochure%202.pdf](https://www.iceoxford.com/files/image/files/DRYICE%20EDEN%20Brochure%202.pdf) (Accessed 22 June 2025).  
6. **Leiden Cryogenics** 2025, *CF-CS110 dilution refrigerator series*. Available at: [https://www.leidencryogenics.nl/cf-cs110](https://www.leidencryogenics.nl/cf-cs110) (Accessed 22 June 2025).  
7. **Cryoconcept SAS** 2024, *HEXA-DRY dilution refrigerator – product brochure* (PDF).   
   Available at: [https://cryoconcept.com/wp-content/uploads/2024/07/CryoConcept-brochure-EN-07.24-SD.pdf](https://cryoconcept.com/wp-content/uploads/2024/07/CryoConcept-brochure-EN-07.24-SD.pdf) (Accessed 22 June 2025).  
8. **Cryoconcept SAS** 2025, *HEXA-DRY product overview*. Available at: [https://cryoconcept.com/products-type/hexa-dry](https://cryoconcept.com/products-type/hexa-dry) (Accessed 22 June 2025).  
9. **attocube systems AG** 2025, *Closed-cycle cryostats – attoDRY series*. Available at: [http://attocube.com/en/products/cryostats/closed-cycle-cryostats](http://attocube.com/en/products/cryostats/closed-cycle-cryostats) (Accessed 22 June 2025).  
10. **FormFactor Inc.** 2022, *FormFactor adds dilution refrigeration (DR) systems critical for quantum-computer deployment* \[press release\]. Available at: [https://www.formfactor.com/press-release/formfactor-adds-dilution-refrigeration-dr-systems-critical-for-quantum-computer-deployment](https://www.formfactor.com/press-release/formfactor-adds-dilution-refrigeration-dr-systems-critical-for-quantum-computer-deployment) (Accessed 22 June 2025).  
11. **GlobeNewswire** 2022, *FormFactor adds dilution refrigeration DR systems critical for quantum-computer deployment* (news wire). Available at: [https://www.globenewswire.com/news-release/2022/06/09/2460109/0/en/FormFactor-Adds-Dilution-Refrigeration-DR-Systems-Critical-for-Quantum-Computer-Deployment.html](https://www.globenewswire.com/news-release/2022/06/09/2460109/0/en/FormFactor-Adds-Dilution-Refrigeration-DR-Systems-Critical-for-Quantum-Computer-Deployment.html) (Accessed 22 June 2025).  
12. **FormFactor Inc.** 2022, *Boosting quantum-computer deployment with dilution-refrigeration systems* \[company blog\]. Available at: [https://www.formfactor.com/blog/2022/boosting-quantum-computer-deployment-dilution-refrigeration-dr-systems](https://www.formfactor.com/blog/2022/boosting-quantum-computer-deployment-dilution-refrigeration-dr-systems) (Accessed 22 June 2025).  
13. **Zero Point Cryogenics Inc.** 2024, *Model L dilution refrigerator – product page*. Available at: [https://www.zpcryo.com/products/model-l](https://www.zpcryo.com/products/model-l) (Accessed 22 June 2025).  
14. **Zero Point Cryogenics Inc.** 2024, *Model L dilution refrigerator data sheet* (PDF). Available at: [https://www.zpcryo.com/wp-content/uploads/2024/12/Model\_L\_Dilution\_V2\_2024-11-29-1.pdf](https://www.zpcryo.com/wp-content/uploads/2024/12/Model_L_Dilution_V2_2024-11-29-1.pdf) (Accessed 22 June 2025).  
15. **Cryomech Inc.** 2025, *Cryocoolers – product family*. Available at: [https://www.cryomech.com/cryocoolers](https://www.cryomech.com/cryocoolers) (Accessed 22 June 2025).  
16. **Cryomech Inc.** 2025, *Pulse-tube cryocoolers*. Available at: [https://www.cryomech.com/cryocoolers/pulse-tube-cryocoolers](https://www.cryomech.com/cryocoolers/pulse-tube-cryocoolers) (Accessed 22 June 2025).  
17. **The Quantum Insider** 2024, *China mass-producing dilution refrigerators critical to superconducting quantum computing*. Available at: [https://thequantuminsider.com/2024/02/28/reports-china-mass-producing-dilution-refrigerator-critical-to-superconducting-quantum-computing](https://thequantuminsider.com/2024/02/28/reports-china-mass-producing-dilution-refrigerator-critical-to-superconducting-quantum-computing) (Accessed 22 June 2025).  
18. **Global Times** 2024, *China makes breakthrough on dilution refrigerator for quantum technology*. Available at: [https://www.globaltimes.cn/page/202402/1307818.shtml](https://www.globaltimes.cn/page/202402/1307818.shtml) (Accessed 22 June 2025).  
19. **The Quantum Insider** 2025, *ULVAC developing next-generation dilution refrigerator for quantum computing by 2026*. Available at: [https://thequantuminsider.com/2025/03/22/ulvac-developing-next-generation-dilution-refrigerator-for-quantum-computing-by-2026](https://thequantuminsider.com/2025/03/22/ulvac-developing-next-generation-dilution-refrigerator-for-quantum-computing-by-2026) (Accessed 22 June 2025).  
20. **Bluefors Oy** 2024, *Bluefors delivers 18 state-of-the-art quantum-cooling systems to power AIST’s G-QuAT center* \[news release\]. Available at: [https://bluefors.com/news/bluefors-delivers-18-state-of-the-art-quantum-cooling-systems-to-power-aists-g-quat-center](https://bluefors.com/news/bluefors-delivers-18-state-of-the-art-quantum-cooling-systems-to-power-aists-g-quat-center) (Accessed 22 June 2025).  
21. **Bluefors Oy** 2023, *Introducing the ultra-compact dilution-refrigerator system* \[news article\]. Available at: [https://bluefors.com/news/introducing-the-ultra-compact-dilution-refrigerator-system](https://bluefors.com/news/introducing-the-ultra-compact-dilution-refrigerator-system) (Accessed 22 June 2025).  
22. **Bluefors Oy** 2023, *KIDE cryogenic platform – from design to delivery* \[company story\]. Available at: [https://bluefors.com/stories/kide-cryogenic-platform-from-design-to-delivery](https://bluefors.com/stories/kide-cryogenic-platform-from-design-to-delivery) (Accessed 22 June 2025).  
23. **IBM Corp.** 2023, *Goldeneye: IBM’s 1 m-wide cryogenic concept system* \[blog post\]. Available at: [https://www.ibm.com/quantum/blog/goldeneye-cryogenic-concept-system](https://www.ibm.com/quantum/blog/goldeneye-cryogenic-concept-system) (Accessed 22 June 2025).  
24. **Bezryadin Group, University of Illinois** 2016, *Practical cryogenics laboratory manual* (PDF). Available at: [https://research.physics.illinois.edu/bezryadin/links/practical%20cryogenics.pdf](https://research.physics.illinois.edu/bezryadin/links/practical%20cryogenics.pdf) (Accessed 22 June 2025).  
25. **Cox, D. et al.** 2021, ‘Operation of a continuous-flow liquid-helium cryostat’, *Review of Scientific Instruments*, vol. 92, no. 12, 123701\. Available at: [https://pubs.aip.org/aip/rsi/article/92/12/123701/283257/Operation-of-a-continuous-flow-liquid-helium](https://pubs.aip.org/aip/rsi/article/92/12/123701/283257/Operation-of-a-continuous-flow-liquid-helium) (Accessed 22 June 2025).  
26. **The Quantum Insider** 2023, *Cryogenics – a short history & its implications on the QC industry*. Available at: [https://thequantuminsider.com/2023/09/12/cryogenics-a-short-history-the-implications-it-has-on-the-qc-industry](https://thequantuminsider.com/2023/09/12/cryogenics-a-short-history-the-implications-it-has-on-the-qc-industry) (Accessed 22 June 2025).  
27. **National High Magnetic Field Laboratory** 2025, *Sample environments – 1 K VTI*. Available at: [https://nationalmaglab.org/user-facilities/dc-field/magnets-instruments/sample-environments](https://nationalmaglab.org/user-facilities/dc-field/magnets-instruments/sample-environments) (Accessed 22 June 2025).  
28. **Bluefors Oy** 2024, *Introducing the XLD-He high-power 1 K system* \[press article\]. Available at: [https://bluefors.com/news/introducing-the-xldhe-high-power-system-ultimate-cooling-for-1-k-experiments](https://bluefors.com/news/introducing-the-xldhe-high-power-system-ultimate-cooling-for-1-k-experiments) (Accessed 22 June 2025).  
29. **Cryogenic Ltd** 2024, *300 mK insert for CFMS systems*. Available at: [https://www.cryogenic.co.uk/node/239](https://www.cryogenic.co.uk/node/239) (Accessed 22 June 2025).  
30. **Maheshwari, R. et al.** 2013, ‘Pulse-tube-cooled He-7 sorption refrigerator for mm-wave detectors’, *Proceedings of SPIE*, vol. 8852\. Available at: [https://www.researchgate.net/publication/255608978\_Pulse-tube-cooler-head\_left\_4-K-box\_He-7\_sorption\_fridge](https://www.researchgate.net/publication/255608978_Pulse-tube-cooler-head_left_4-K-box_He-7_sorption_fridge) (Accessed 22 June 2025).  
31. **Wong, J. et al.** 2021, ‘A millikelvin scanning-tunnelling microscope in UHV’, *Review of Scientific Instruments*, vol. 92, no. 6, 063701\. Available at: [https://pubs.aip.org/aip/rsi/article/92/6/063701/991153/A-millikelvin-scanning-tunneling-microscope-in](https://pubs.aip.org/aip/rsi/article/92/6/063701/991153/A-millikelvin-scanning-tunneling-microscope-in) (Accessed 22 June 2025).  
32. **NASA Goddard Space Flight Center** 2009, ‘Continuous ADR for sub-100 mK space instruments’ (conference paper PDF). Available at: [https://www.nrao.edu/meetings/isstt/papers/2009/2009097106.pdf](https://www.nrao.edu/meetings/isstt/papers/2009/2009097106.pdf) (Accessed 22 June 2025).  
33. **Bluefors Oy** 2025, *Applications: quantum technology*. Available at: [https://bluefors.com/applications/quantum-technology](https://bluefors.com/applications/quantum-technology) (Accessed 22 June 2025).  
34. **Oxford Instruments NanoScience** 2023, *Oxford Instruments joins Rigetti’s Novera QPU partner program* \[news release\]. Available at: [https://www.oxinst.com/news/oxford-instruments-nanoscience-joins-rigettis-novera-qpu-partner-program](https://www.oxinst.com/news/oxford-instruments-nanoscience-joins-rigettis-novera-qpu-partner-program) (Accessed 22 June 2025).  
35. **FormFactor Inc.** 2025, *XLF-600 dilution refrigerator – product page*. Available at: [https://www.formfactor.com/product/quantum-cryo/dilution-refrigerators/xlf-600](https://www.formfactor.com/product/quantum-cryo/dilution-refrigerators/xlf-600) (Accessed 22 June 2025).  
36. **FormFactor Inc.** 2022, *FormFactor adds dilution refrigeration DR systems critical for quantum-computer deployment* \[press release\]. Available at: [https://www.formfactor.com/press-release/formfactor-adds-dilution-refrigeration-dr-systems-critical-for-quantum-computer-deployment](https://www.formfactor.com/press-release/formfactor-adds-dilution-refrigeration-dr-systems-critical-for-quantum-computer-deployment) (Accessed 22 June 2025).  
