# Materials Expert Persona — VTOL Quadcopter Startup

## Persona Metadata
- **Persona ID**: `materials_expert_vtol_v1`
- **Role**: Materials Expert
- **Domain**: VTOL Quadcopter / Multirotor Hardware Startup
- **Core Objective**: Select and validate optimal materials for airframes, propellers, motor mounts, landing gear, and electronics enclosures — balancing specific strength, stiffness-to-weight ratio, fatigue life, environmental resistance, manufacturability, and cost for a lightweight flying vehicle.

## Demographics
- **Age Range**: 28–55
- **Typical Titles**:
  - Materials Engineer
  - Composites Specialist
  - Metallurgist / Polymer Engineer
  - Failure Analysis Engineer
  - Advanced Manufacturing Engineer
- **Experience Years**: 4+
- **Preferred Industry Background**: Aerospace, Drone manufacturing, Carbon fiber composites, Automotive lightweighting, Consumer electronics enclosures

## Hard Skills
- Material property databases (MatWeb, CES EduPack, ASM Handbook)
- Composite layup design (carbon fiber, fiberglass, Kevlar, flax)
- Polymer selection (nylon, PC, ABS, PETG, TPU, PEEK, ULTEM)
- Metal selection (aluminum 6061/7075, titanium 6Al-4V, magnesium alloys, spring steel)
- Failure mode analysis (fatigue, creep, impact, delamination, stress cracking)
- Environmental degradation (UV, moisture, salt spray, temperature extremes)
- Thermal expansion matching (motor mounts to carbon arms)
- Damping and vibration analysis (material hysteresis for flight stability)
- Weight optimization vs stiffness (specific modulus)
- Cost vs performance trade-offs (e.g., T700 carbon vs T300, forged carbon vs prepreg)

## Soft Skills
- Trade-off communication (engineers want stiffer; sourcing wants cheaper)
- Failure forensics — reading broken parts
- Hands-on prototyping (vacuum bagging, wet layup, 3D printing with exotic filaments)
- Risk assessment for new materials (e.g., magnesium fire hazard)
- Documentation for regulatory certification

## Tools
- MatWeb
- Granta CES EduPack
- Instron universal tester (tensile/compression/flexure)
- Charpy impact tester
- Thermal cycler / environmental chamber
- Microscope for fracture surface analysis
- 3D printers (FDM for nylon/PEEK/ULTEM, SLA for high-temp resins)
- Vacuum bagging and autoclave (for composites)
- Moisture analyzer

## Knowledge Areas
- Aerospace-grade carbon fiber prepreg (e.g., Toray T800, Hexcel IM7) vs standard T300
- Honeycomb core materials (Nomex, aluminum) for sandwich panels
- Additive manufacturing materials for drones (Markforged Onyx with continuous carbon fiber)
- Fastener material compatibility (galvanic corrosion: carbon + aluminum = bad without isolation)
- Propeller materials (polycarbonate, nylon-carbon blends, wood composite, carbon fiber)
- Battery enclosure fire resistance (UL94 V-0 rated plastics, flame retardants)
- Vibration damping materials (Sorbothane, neoprene, silicone for FC mounting)
- Low-outgassing materials for sensor windows (no fogging of optical flow or lidar)
- Recyclability and sustainability (bio-based nylons, flax fiber composites)

## Typical Questions a Materials Expert Asks
- What carbon fiber weave and resin system gives best stiffness-to-weight for 12mm square tube arms?
- Will 6061 aluminum motor mounts fatigue after 500 hours of vibration?
- Which polymer can survive a desert crash (70°C) and an arctic flight (-20°C) without embrittlement?
- How do we prevent galvanic corrosion between carbon fiber arm and aluminum motor mount?
- Is forged carbon fiber strong enough for a landing gear skid, or do we need prepreg?
- What infill pattern and material in 3D printed TPU makes the most impact-absorbing battery bumper?
- How much moisture does nylon-12 absorb, and how does that affect flight performance?

## Constraints & Priorities (in order of importance)
1. Specific stiffness (E/ρ) for airframe rigidity
2. Specific strength (σ/ρ) for crash survival
3. Fatigue resistance (cyclic motor vibrations)
4. Environmental stability (UV, temp, humidity)
5. Manufacturability (can we actually make parts from this?)
6. Cost per kilogram (especially for carbon fiber)
7. Lead time (prepreg often has freezer storage and expiry)
8. Flammability (LiPo fire containment)

## AI Interaction Style
- **Preferred Format**: Property comparison tables (stiffness, strength, density, cost, processability); failure mode lists; pros/cons structured as decision matrices
- **Verbosity**: High on technical data (modulus, yield strength, elongation), low on marketing claims
- **Tone**: Precise, quantitative, failure-aware
- **Decision Framework**: Ashby method (material selection charts) plus real-world manufacturing constraints and supplier availability
- **Dislikes**:
  - "Just use carbon fiber everywhere" without considering cost, anisotropic properties, or galvanic corrosion
  - Ignoring moisture absorption in nylons
  - Suggesting PEEK for a prototype budget
  - Confusing tensile strength with impact resistance
  - No mention of fiber orientation or ply schedule

## Example Prompt for AI

> 
