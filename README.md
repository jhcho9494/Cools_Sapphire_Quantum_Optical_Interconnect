# Cools Sapphire Quantum Optical Interconnect

## One crystal. One alignment frame. One through-thickness quantum optical channel.

> **Do not connect a single-photon source and a superconducting detector with separate fibers, alignment stages and cryogenic interfaces.**  
> **Integrate them on opposite faces of one single-crystal sapphire handler and let the photon travel directly through the crystal.**

[한국어](README_KR.md) · [中文](README_ZH.md)

---

## The strategic proposition

Quantum optical systems are still assembled as separate subsystems:

```text
single-photon source
→ fiber pigtail or free-space optics
→ alignment hardware
→ cryogenic interface
→ superconducting detector
```

This creates a chain of loss, alignment drift, vibration sensitivity, thermal-contraction mismatch and packaging complexity.

Cools proposes a different architecture:

```text
single-photon emitter on sapphire face A
↓ through-thickness quantum optical channel
single-crystal sapphire handler
↓
SNSPD on sapphire face B
```

> **The photon source, optical medium, detector substrate, alignment reference and cryogenic heat path become one package.**

---

## Why sapphire

Single-crystal sapphire provides a rare combination of properties required by quantum optical packaging:

- broadband optical transparency across visible, near-infrared and telecom wavelengths;
- electrically insulating single-crystal body;
- low magnetic disturbance compared with magnetic package materials;
- high mechanical stiffness and dimensional stability;
- atomically smooth surfaces suitable for direct bonding and thin-film growth;
- compatibility with GaN-family epitaxy;
- compatibility with superconducting thin films; and
- very high cryogenic thermal conductivity along a selected crystal axis.

> **Sapphire is not merely a window. It is the optical, electrical, mechanical and cryogenic integration medium.**

---

# 1. Dual-side quantum package

A single-photon emitter is positioned on one face of the sapphire handler. A Superconducting Nanowire Single-Photon Detector (SNSPD) is positioned on the opposite face.

The emitted photon travels through the thickness of the sapphire to the detector.

```text
Single-Photon Emitter (SPE)
↓
quantum optical path through sapphire
↓
Superconducting Nanowire Single-Photon Detector (SNSPD)
```

The source and detector are referenced to the same single-crystal body, reducing the number of independent mechanical elements that can drift during cool-down.

---

# 2. The sapphire performs multiple functions simultaneously

The same sapphire body can serve as:

1. substrate or bonding medium for the single-photon emitter;
2. coherence-preserving through-thickness optical medium;
3. substrate for SNSPD thin-film growth or detector-die bonding;
4. front-to-back optical alignment frame;
5. electrical insulation body for Through-Sapphire Vias (TSaVs); and
6. cryogenic heat-spreading handler.

> **One crystal replaces the separate optical bench, detector substrate, alignment frame and part of the cryogenic thermal stack.**

---

# 3. Single-photon source options

The platform can support multiple source families, including:

- III–V semiconductor quantum dots;
- GaN / InGaN quantum dots directly integrated on sapphire;
- diamond color centers such as NV, SiV or related defects;
- hexagonal boron nitride and other two-dimensional defect emitters;
- thin-film SiC defect emitters;
- spontaneous parametric down-conversion sources; and
- telecom-band quantum-dot emitters.

The source may be integrated by epitaxial growth, direct bonding, low-temperature bonding, micro-transfer or another source-specific assembly process.

Optical cavities, Distributed Bragg Reflectors (DBRs), photonic crystals or directional structures can be used to direct emission toward the sapphire thickness axis.

---

# 4. SNSPD integration on the opposite face

The detector side can include superconducting materials such as:

- niobium nitride (NbN);
- niobium titanium nitride (NbTiN);
- tungsten silicide (WSi);
- molybdenum silicide (MoSi); and
- related superconducting thin-film stacks.

The superconducting film may be formed directly on sapphire and patterned into:

- meander nanowires;
- Superconducting Nanowire Avalanche Photodetectors (SNAPs); or
- Superconducting Nanowire Single-Photon Imagers (SNSPIs).

Alternatively, a separately manufactured detector die may be bonded to the sapphire.

The sapphire crystal surface can support either preferred-texture growth for crystalline superconducting films or uniform amorphous / nanocrystalline films, depending on the detector material.

---

# 5. Through-thickness quantum optical alignment

The optical path can be implemented by one or more of:

- direct propagation through the sapphire body;
- micro-lens arrays aligned to the emitter and detector;
- refractive-index-modified vertical optical channels written inside sapphire;
- optical shielding walls or absorptive partitions; and
- optical-cavity or mirror structures around the detector.

These structures suppress beam divergence, optical leakage and adjacent-channel crosstalk while maintaining the source-to-detector alignment inside a single body.

> **Alignment is no longer maintained by an external optical bench. It is embedded in the crystal geometry.**

---

# 6. Cryogenic thermal architecture

SNSPDs operate below their superconducting critical temperature and generate localized transient heating during photon detection.

The sapphire handler provides a short heat path from the detector to the cryogenic cooling interface.

The crystal axis can be oriented along the package thickness so that the strong cryogenic thermal conduction of sapphire is used directly for detector recovery and thermal stabilization.

This architecture targets:

- faster removal of detector hot-spot energy;
- stable superconducting reset behavior;
- lower thermal accumulation in detector arrays;
- reduced dark-count contribution from local heating; and
- common mechanical and thermal behavior of source and detector during cool-down.

> **The same crystal that carries the photon also removes the detector heat.**

---

# 7. Liner-free through-sapphire electrical vias

Electrical connections for source pumping, detector bias, detector output and control signals can pass through TSaVs.

Because sapphire is electrically insulating, the via sidewall does not require the oxide or nitride electrical liner normally required in silicon.

Representative cryogenic-compatible via conductors include tungsten and molybdenum, with optional non-insulating adhesion, seed or diffusion-barrier layers.

This enables separate through-thickness paths for:

- emitter pump current or pump-control signals;
- SNSPD bias current;
- photon-detection pulse output;
- ground return; and
- cryogenic interface control.

---

# 8. Monotonically decreasing thermal budget

The manufacturing sequence is arranged so that later integration steps do not damage earlier quantum or superconducting structures.

```text
higher-temperature thin-film or epitaxial process
→ lower-temperature source or detector integration
→ cryogenic-compatible final assembly
```

The source-side and detector-side processes can be ordered so that the later bonding temperature remains below the thermal limit of the previously formed superconducting film or emitter structure.

---

## Conventional architecture versus Cools

| Quantum optical packaging axis | Conventional separated approach | Cools sapphire dual-side architecture |
|---|---|---|
| Source and detector | Separate modules | Opposite faces of one crystal |
| Optical path | Fiber, free-space optics or separate waveguide | Through sapphire thickness |
| Alignment | External stages and multiple interfaces | Single-crystal front-to-back reference |
| Cryogenic contraction | Multiple materials and joints | Common handler body |
| Detector substrate | Separate chip or substrate | Sapphire face or bonded detector |
| Heat removal | Separate detector mount | Sapphire cryogenic heat path |
| Electrical feedthrough | Separate wiring and substrate | Liner-free TSaVs |
| Package size | Multiple optical and mechanical parts | Integrated dual-side package |

---

## Target applications

The platform is applicable to:

- Quantum Key Distribution (QKD);
- Measurement-Device-Independent QKD (MDI-QKD);
- photonic quantum computing;
- quantum-repeater nodes;
- quantum-memory–photon interfaces;
- quantum internet nodes;
- single-photon imaging and sensing; and
- cryogenic quantum interconnects.

---

## Core declaration

> **Quantum optical packaging should not be a collection of aligned modules.**  
> **It should be one crystal that generates, carries, detects and thermally stabilizes the photon path.**

---

## Patent protection and transaction options

The technologies and architectures described in this repository are protected by pending patent applications and associated proprietary know-how of Cools Inc.

The patent-pending portfolio includes concepts covering:

- dual-side sapphire integration of a single-photon emitter and SNSPD;
- through-thickness quantum optical coupling;
- sapphire-mediated coherence and polarization preservation;
- superconducting-film growth or detector bonding on sapphire;
- cryogenic sapphire heat spreading;
- liner-free cryogenic TSaVs;
- micro-lens, vertical waveguide and optical-shielding reinforcement; and
- monotonically decreasing thermal-budget integration.

Cools is open to structured discussions with quantum-computing, quantum-communication, detector, cryogenic-packaging and strategic investment partners. Potential structures may include:

- exclusive or non-exclusive patent licensing;
- application-, wavelength-, device- or territory-limited rights;
- joint package and process development;
- detector, emitter and cryogenic-system integration;
- manufacturing collaboration;
- strategic investment or technology-business transfer; and
- where commercially appropriate, assignment or transfer of the relevant patent applications and patent rights themselves.

**Negotiations are not limited to a licence. Where the strategic purpose and conditions are appropriate, the relevant patent portfolio itself may be included in the transaction.**

Publication of this repository does not constitute a licence, waiver or permission to practise the disclosed technology. Detailed optical stacks, superconducting processes, alignment tolerances, cryogenic interfaces and claim charts are reserved for controlled technical and legal discussions.

---

## Related Cools platform

- [Cools Sapphire Single-Optical-Domain Computing](https://github.com/jhcho9494/Cools_Sapphire_Single_Optical_Domain_Computing)

---

## Contact

**Cools Inc.**  
Jinhyun Cho  
Former Samsung Electronics Master-level semiconductor engineer  
Ph.D., Mechanical Engineering, University of Michigan

Email: jhcho@cools.co.kr  
Email: jhcho9494@naver.com  
Mobile: +82-10-2280-9414
