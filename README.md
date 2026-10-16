# Generator to Battery Backup

120/240 V battery backup for the ten circuits on the Reliance 310CRK. Those circuits stay on the inverter whether Georgia Power is up or not. The battery charges from Georgia Power or from the Champion generator. 240 V loads stay on the service panel.

The state minimum electrical code is the 2023 National Electrical Code. This is an optional standby system (Article 702) with a listed energy storage system (Article 706). The AHJ inspection is what accepts the installation.

Owner-occupant work is allowed on a house the owner lives in (O.C.G.A. § 43-14-13(d)). The local electrical permit and inspection still apply.

## Existing equipment

- Champion open-frame inverter generator, 7,000 W running and 8,750 W starting, 120/240 V, cord-and-plug to a NEMA L14-30 inlet. It runs on non-ethanol gasoline or propane. Use the lower wattage of the two fuels when setting the charge rate.
- Reliance 310CRK Pro/Tran 2. Indoor 10-circuit, 30 A transfer switch, 7,500 W maximum. The usual breaker set is six 15 A and four 20 A single-pole breakers. Confirm the handles on the installed switch. Combined load is 30 A at 240 V, or 60 A of 120 V load split across the two legs. The neutral is not switched.
- Reliance PB30 outdoor L14-30 inlet and the 10 ft, 10 AWG generator cord.

Each Reliance toggle picks up a breaker that is already in the service panel. On LINE, that breaker feeds the room. On GEN, the room is fed from the switch’s generator bus. Those 15 A and 20 A breakers stay. They are not bought again.

## Backup loads

120 V only, on the Reliance:

- Lights and receptacles in four bedrooms, the kitchen, the dining room, two bathrooms, and the garage.
- One bedroom: desktop computer and two monitors.
- Living room: 55-inch TV and the internet service.
- Refrigerators in the kitchen and the garage.
- Kitchen, one at a time and only occasionally: over-the-stove microwave, air fryer, toaster, or Keurig.
- Main bath: hair dryer, occasionally.

Range, dryer, water heater, and central air stay on the service panel and are off during an outage.

Planning watts below are running watts for these loads, with LED lights and an ordinary office desktop. A refrigerator start is about 1,000 W for a fraction of a second and is not included in the running totals.

| Load on at the same time | Watts |
| --- | ---: |
| Kitchen refrigerator, compressor running | 150 |
| Garage refrigerator, compressor running | 150 |
| Lights in four bedrooms | 160 |
| Kitchen lights | 60 |
| Dining room lights | 40 |
| Lights in two bathrooms | 50 |
| Garage lights | 40 |
| Desktop computer and two monitors | 200 |
| 55-inch TV | 90 |
| Internet | 30 |
| **Evening, both compressors on** | **970** |

Overnight, with the computer, TV, and lights off, the internet plus both compressors is about 330 W. Between compressor cycles the draw is about the internet, near 30 W.

One occasional load is added to the 970 W evening total. Only one of these five is used at a time:

| Occasional load | Watts | Evening total |
| --- | ---: | ---: |
| Toaster | 1,200 | 2,170 |
| Keurig | 1,400 | 2,370 |
| Microwave or hair dryer | 1,500 | 2,470 |
| Air fryer | 1,700 | 2,670 |

Put the kitchen refrigerator and the garage refrigerator on opposite legs. The air-fryer case, about 2,670 W, is the highest running load. If both compressors start during that use, the brief peak is about 4,400 W. Hold each leg near 2,400 W (20 A) so the 30 A bus is not run at its limit for hours.

## How it operates

The inverter load port is the only source on the Reliance generator bus. The ten toggles stay on GEN, so the rooms are on the inverter with the utility up and with the utility down.

- Georgia Power up: the inverter passes utility power through to the load port and charges the battery. Switching time onto the battery is under 15 ms.
- Georgia Power down, generator off: the battery supplies the load port.
- Georgia Power down, generator running: the generator feeds the inverter generator port. The inverter runs the rooms and charges the battery from that port.
- A toggle moved to LINE takes that one circuit off the inverter and puts it back on its service-panel breaker.

The Champion plugs into the existing inlet. That inlet lands on the inverter generator port only. It does not land on the Reliance.

## Parts

Shelf prices checked October 16, 2026. Freight, sales tax, and the local permit fee are extra. Wire and conduit are priced for 25 ft runs. Measure the runs before buying. One-hole straps and EMT couplings are bought with the conduit and are not in this total.

The 60 A breaker below fits a Square D Homeline service panel. If the panel is another brand, buy that brand’s 60 A two-pole instead.

| Qty | Item | Source | Part | Extended |
| --- | --- | --- | --- | --- |
| 1 | EG4 6000XP off-grid inverter, 6,000 W, 120/240 V | Signature Solar | 1511090 | $1,499.99 |
| 1 | EG4 WallMount Indoor battery, 14.3 kWh, 51.2 V, 280 Ah | Signature Solar | 1511092 | $2,700.00 |
| 1 | Indoor conduit box for this battery and the 6000XP | Signature Solar | 1511079 | $92.99 |
| 1 | 42 in. 2/0 battery cables, red and black, Degson connectors | Dragon Off Grid | WallMount OEM set | $49.98 |
| 1 | Emergency-stop button, twist release, 1NO + 1NC | Signature Solar | 1566006 | $26.67 |
| 1 | 25 ft Cat6 cable for the emergency-stop circuit | Home Depot | 345-U6-025BK | $7.99 |
| 1 | 60 A 2-pole breaker, Homeline panels only | Home Depot | HOM260CP | $18.24 |
| 1 | 70 A, 2-space indoor load center for the 30 A breaker | Home Depot | HOM24L70SCP | $25.74 |
| 1 | 30 A 2-pole breaker for that load center | Home Depot | HOM230CP | $18.24 |
| 90 ft | 6 AWG stranded copper THHN, 30 ft each of black, red, and white, at $1.83/ft | Home Depot | 20493399 | $164.70 |
| 228 ft | 10 AWG stranded copper THHN at $0.78/ft | Home Depot | 22973299 | $177.84 |
| 3 | 1 in. x 10 ft EMT | Home Depot | 550210000 | $55.02 |
| 5 | 3/4 in. x 10 ft EMT | Home Depot | 0550110000 | $52.40 |
| 4 | 1 in. EMT set-screw connectors | Home Depot | Halex 82710 | $12.88 |
| 1 | 3/4 in. EMT set-screw connectors, 25-pack | Home Depot | Halex 12301B | $15.98 |
|  | **Parts total** |  |  | **$4,918.66** |

The 6 AWG covers the 25 ft grid feeder (L1, L2, and neutral) and a 3 ft whip from the inverter load terminals to the 30 A breaker. The 10 AWG covers the grid equipment ground, the whip ground, the 25 ft load feeder, and the 25 ft run from the inlet to the generator port. Buy 10 AWG in black, red, white, and green. The $0.78 price is the black by-the-foot price.

About 11 kWh is usable if the battery is kept above a 20 percent reserve. That is about 11 hours at the 970 W evening load, and about 4 hours at the 2,670 W air-fryer case. Start the generator at that point. A second module can be added later on the same inverter.

## Alternative inverter and battery

Sol-Ark 5K-2P-N with three Pytes V5 modules. Same wiring: utility on the grid port, Champion on the generator port, load port through the 30 A breaker to the Reliance. Prices checked October 16, 2026.

| Qty | Item | Source | Part | Extended |
| --- | --- | --- | --- | --- |
| 1 | Sol-Ark 5K-2P-N, 5,000 W, 120/240 V | RES Supply | 5K-2P | $4,699.00 |
| 3 | Pytes V5, 5.12 kWh, 51.2 V, 100 Ah each | Current Connected | V5 | $4,350.00 |
|  | **Inverter and batteries** |  |  | **$9,049.00** |

The 5K-2P continuous output is 20.8 A, under the 30 A Reliance bus. Its 10-second surge is 16,000 VA, which covers the 4,400 W refrigerator-start peak. Transfer to battery is 4 ms. It is listed UL 1741 SB. Pytes lists the 5K with these batteries as a UL 9540 system. Three modules are 15.36 kWh, about 12.3 kWh above a 20 percent reserve: about 13 hours at 970 W and about 4.5 hours at 2,670 W. Two modules can supply the inverter’s 120 A battery current, and the runtime drops to about 8 hours at 970 W.

The grid and generator passthrough breaker inside the Sol-Ark is 63 A. The external 30 A breaker stays, because the Reliance is 30 A. The breakers, THHN, and EMT in the parts list above stay. The EG4 conduit box, Degson cable set, and EG4 stop button do not. Battery cables are the ones specified for the Pytes-to-Sol-Ark connection. Bond neutral to ground only once, at the service panel, and leave the generator neutral floating.

Some dealers listed the 5K-2P sold out on October 16, 2026. The Pytes modules were temporarily out of stock at Current Connected. Georgia Power still asks for a separate mechanically interlocked transfer switch. This inverter’s transfer is internal, the same class of device as the 6000XP relay.

## Conductors

Terminals on breakers and on this inverter are used at the 75°C column.

- Grid feeder: 60 A breaker, 6 AWG copper for L1, L2, and neutral, 10 AWG copper equipment ground, in 1 in. EMT. The grid port can draw up to 50 A. Set the inverter so charging plus the backup load stays at or below 48 A, which is the continuous-load limit of a 60 A breaker.
- Load feeder: 30 A breaker, 10 AWG copper for L1, L2, neutral, and equipment ground, in 3/4 in. EMT. The 6000XP can pass 50 A from the grid relay. The Reliance cannot. The 30 A breaker is what enforces the switch rating.
- Generator: the existing L14-30 inlet, 10 AWG cord, and 10 AWG copper from the inlet to the generator port. The generator’s 30 A receptacle breaker protects that circuit.

Hold a continuous backup load to 24 A (about 5,760 W). That is 80 percent of the 30 A switch. The inverter’s 25 A output is inside that bus rating. A refrigerator start or a short surge may exceed 30 A for a few seconds. The breaker allows that. A continuous oven-sized load does not belong on this switch.

## Connections

- Service-panel 60 A breaker to the inverter grid port only.
- Existing outdoor inlet to the inverter generator port only.
- Inverter load port, through the 30 A breaker, to the Reliance generator bus only.
- Battery positive and negative to the inverter on the 2/0 cable set, inside the conduit box. No extra DC disconnect between the battery and the inverter. EG4’s UL 9540 listing is violated by a disconnect inserted in those cables, and the cables can stay energized after shutdown.
- Emergency-shutdown initiator on the battery communications circuit, mounted where firefighters can reach it, labeled as the ESS emergency shutdown.

## Neutral and ground

There is one neutral-to-ground bond, in the service panel.

- The 310CRK does not switch the neutral. Its white lead stays on the service neutral bar. Its green lead stays on the service ground bar.
- On the 6000XP, turn the internal neutral-ground bond off (setting 26, disabled). The inverter neutral is common from the grid port to the load port and is not a second bond.
- The Champion that matches this wattage, model 100520, ships with the neutral bonded to the frame. Lift that bond with Champion’s floating-neutral procedure for the model on the nameplate before the cord is used on this inlet. A bonded generator on this switch would be a second neutral-ground bond.

## Inverter settings

- 120/240 V, 60 Hz output.
- Grid charging on. This inverter has no sell-to-grid mode.
- Generator charging on. Set it near 2,500 W on gasoline so the generator can carry the rooms and still charge. Set it lower on propane, from the wattage that fuel actually produces.
- Closed-loop communication with the EG4 battery. Low-battery cutoff at 20 percent state of charge.
- Confirm setting 26 shows the internal bond disabled before the load breaker is turned on.

## Georgia Power

The grid port takes power from the utility and does not send power back. Georgia Power’s standby-battery checklist (residential behind-the-meter summary, Part 4) also asks for a UL 1741 SB inverter and a separate open-transition automatic transfer switch with a mechanical interlock. The 6000XP is UL 1741, not UL 1741 SB, and its transfer is the internal break-before-make relay.

Send Georgia Power form DB 18-23, the 6000XP specification sheet, and the one-line in `SCHEMATIC.md` before buying the equipment. The internal transfer is what keeps the rooms up in under 15 ms. If Georgia Power requires the separate mechanical switch, stop and revise this drawing. That switch would replace the fast transfer.

## Before the feeder breaker is turned on

1. Pull the electrical permit. Do not energize ahead of the inspection.
2. Mount the inverter and battery indoors, in a dry location, with the working space in NEC 110.26 and the clearances in both manuals.
3. Land the grid feeder, the relocated inlet, and the load feeder. Leave every new breaker off.
4. Set the generator neutral floating, and set inverter bond setting 26 disabled.
5. Pass inspection.
6. Turn on the battery, then the grid breaker. Confirm the battery charges and the rooms are live with the toggles on GEN.
7. Open the 60 A breaker. The rooms should stay live from the battery.
8. Plug in the Champion and confirm the rooms stay live and the battery charges. Stop the test if a neutral-ground fault appears.
9. Leave the ten toggles on GEN.
