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

Plan on about 1,000 W with both refrigerators, the lights, the computer, the TV, and the internet. A kitchen appliance or the hair dryer adds about 1,200 to 1,800 W, so the total is about 2,200 to 2,800 W while one of those is on. Use only one of those five at a time. Put the kitchen refrigerator and the garage refrigerator on opposite legs. Hold each leg near 2,400 W (20 A) so the 30 A bus is not run at its limit for hours.

## How it operates

The inverter load port is the only source on the Reliance generator bus. The ten toggles stay on GEN, so the rooms are on the inverter with the utility up and with the utility down.

- Georgia Power up: the inverter passes utility power through to the load port and charges the battery. Switching time onto the battery is under 15 ms.
- Georgia Power down, generator off: the battery supplies the load port.
- Georgia Power down, generator running: the generator feeds the inverter generator port. The inverter runs the rooms and charges the battery from that port.
- A toggle moved to LINE takes that one circuit off the inverter and puts it back on its service-panel breaker.

The Champion plugs into the existing inlet. That inlet lands on the inverter generator port only. It does not land on the Reliance.

## Equipment

| Qty | Item | Role |
| --- | --- | --- |
| 1 | EG4 6000XP off-grid inverter | 6,000 W, 120/240 V. Grid port, generator port, and load port. UL 1741. Listed with the battery below as a UL 9540 system. Switching time under 15 ms. Continuous output 25 A at 240 V. Grid and generator bypass relay 50 A. No export to the utility. |
| 1 | EG4 WallMount Indoor battery, 14.3 kWh, 51.2 V, 280 Ah | UL 1973 battery. 200 A BMS, so one module can supply the 6000XP. Indoor listing. |
| 1 | EG4 ESS emergency-shutdown initiator for this battery | One-button shutdown for the dwelling, NEC 706.15. |
| 1 | 60 A two-pole breaker, same brand as the service panel | Feeder to the inverter grid port. |
| 1 | 30 A two-pole breaker in a listed disconnect enclosure | Protects the load-port feeder and the 30 A Reliance bus. |
| — | 6 AWG and 10 AWG stranded copper THHN, EMT, fittings | Measured to the run. |

About 11 kWh is usable if the battery is kept above a 20 percent reserve. That is about 11 hours at 1,000 W, and about 4 hours if a kitchen appliance or the hair dryer runs the whole time. Start the generator at that point. A second module can be added later on the same inverter.

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
- Battery positive and negative to the inverter with the cables supplied for this UL 9540 pair, in the battery conduit box. No extra DC disconnect between the battery and the inverter. EG4’s UL 9540 listing is violated by a disconnect inserted in those cables, and the cables can stay energized after shutdown.
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
