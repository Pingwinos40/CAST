# CAST Fork Notes

## Fork Rationale

This is a continuation of the [Maasi open-source spin coater](https://github.com/klotzsch-lab/Maasi) project, which became inactive in 2021. The original Maasi design provided an excellent foundation for low-cost precision spin coating, but required updates for:

1. **Reproducibility**: Parts availability, explicit tolerances, and build documentation
2. **DEA-specific workflows**: Precise control for dielectric elastomer actuator fabrication
3. **Soft robotics applications**: Support for high-viscosity elastomers and multi-layer processes
4. **Active maintenance**: Bug fixes, dependency updates, and community support

## Scope & Focus

**Primary Applications:**
- Dielectric elastomer actuator (DEA) fabrication
- PDMS and silicone elastomer thin films
- General microfabrication for soft robotics research

**Out of Scope (for now):**
- Wafer sizes >4 inches
- Automated dispense integration
- Clean room compliance
- Electrode deposition (carbon grease, conductive composites)


## Phases from Upstream

### Phase 1: Reproducibility / Hardware Modernization

### Phase 2: Control Improvements

### Phase 3: DEA-Specific Features

### Phase 4: Characterization

## Technical Scope

**What We're Keeping:**
- Core mechanical design
- Arduino-based control architecture
- General motor / driver selection approach

**What We're Changing:**
- Hardware modernization
- Documentation quality and completeness
- Software UI/UX improvements
- Calibration and metrology procedures

**What We're Adding:**
- Recipe library for common DEA materials
- Validation data and repeatability metrics
- Integration notes for microfab workflows
- Closed-loop control




## Upstream Attribution

This project is derived from Maasi v1.0 (commit `16d2dbce93c17c41b29e9813b1a98a6f61958f19`, dated 2021-12-13). All original design credit goes to the Klotzsch Lab. Changes made in this fork are documented in `CHANGELOG.md`.

**Original Authors:** [Klotzsch Lab](https://www.biologie.hu-berlin.de/en/groupsites/jpexpbp)
- [Dani Carbonell](https://github.com/dani-carbonell)
- Willi Weber
- [Enrico Klotzsch](https://www.biologie.hu-berlin.de/en/groupsites/jpexpbp/members/Enrico_Klotzsch)

**Original License:** GNU GENERAL PUBLIC LICENSE v3.0  
**Fork Maintainer:** Anatol Gogoj, UConn  
**Contact:** https://github.com/Pingwinos40  

## Citation

If you use this fork in research, please cite both the original Maasi project and this fork:

Original Maasi:
DOI: [10.5281/zenodo.5768034](https://zenodo.org/badge/latestdoi/385644588)

CAST:
DOI: Pending


## Contribution Policy

This is an active research tool, not production equipment. Contributions welcome, especially:
- Bug reports with reproducible test cases
- Validated recipes for soft materials
- Calibration data from your builds
- Documentation improvements
