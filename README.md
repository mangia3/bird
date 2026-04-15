# F22 Raptor — 3D Print Build Guide

| | Version | Date | Notes |
|---|---|---|---|
| Created | V1 | July 2021 | Original issue |
| Current Revision | V3 | 13th October 2022 | Scale shaping, tail reinforcements, sacrificial stab tips |

This document covers print, assembly, and setup instructions for the 50mm EDF F22 Raptor. The model is intended for intermediate to advanced RC pilots with a low part count (29 parts) and a print time of approximately one week on a well-tuned printer.

---

## Materials

1. PLA, LW-PLA (Colorfab, 3DLabPrint etc.) is preferred. A 1.75mm direct drive extruder printer is ideal
2. 50mm EDF. FMS 50mm, XRP-50mm, XFly-Model 4600kV or similar
3. 4s 1300mAh 25C or above battery
4. 350mm 0.87–1mm piano wire pushrod x 2
5. RC gear, quick pushrod linkages x 2
6. 250mm 3x1mm carbon main spar pultruded strip (x2) + 55mm (x2) for rear sub spars (optional)
7. 60mm OD3mm carbon taileron axle rod (x2) (or filled tube)
8. Adhesive Velcro j/o
9. 40A ESC or above to suit EDF
10. 2x 9g servos (+2x 8mm thick servos if using flaperons)
11. Servo extension leads
12. Optional: 10mm dia. magnets for nose (x2)
13. Thin CA type hinges (optional)
14. 3x small servo mount type screws for fan hatch
15. Twist wire (from $2 shop or similar) or 1mm sharpened carbon fibre skewers to pin control surfaces

## Tools

1. Step drill bits (fine increment)
2. Hand twist drill or Dremel
3. Coarse round file or rasp to clean stringing
4. Sandpaper
5. Z bend pliers or needle nose pliers
6. Needle files
7. Hobby knife, hot knife
8. Side cutters
9. Metal ruler

## Adhesives

1. Acrifix™ 0192 to glue PLA main assemblies and foamie Welder's Glue™ or UHU-Por™ for spars etc.
2. Alternatively, medium CA plus accelerator as a rule throughout
3. Thin CA for wicking joints

---

## Print Overview & Part Weights

**Part Count = 29**

| # | Part | Weight |
|---|------|--------|
| 1 | Nose | 18g |
| 2 | Canopy | 7g |
| 3 | Fuse1 | 56g |
| 4 | Fuse2 | 64g |
| 5 | Fuse3 | 41g |
| 6 | Fuse4 | 51g |
| 7 | Taileron / Horizontal Stab | 12g |
| 8 | Wing 1lf | 17g |
| 9 | Wing 1b no servo | 20g |
| 10 | Wingtip | 9g |
| 11 | 1 whole wing panel (updated with 250mm carbon and PLA spars, P2) | 51g |
| 12 | Vstab 1 side 2 pieces | 17g (9, 8g) |
| 13 | Tail fairing | 3g |
| 14 | Fan hatch | 10g |
| 15 | Wing servos (x2) | 10g |
| 16 | Tail servos (x2) | 22g |
| 17 | V3: 4 Fuse lamination pieces (not shown) | — |

---

## FAQs

**Q: There are fine gaps in the parts when I load into the slicer. Is this normal? Will the parts be compromised?**

A: It is the design intent to have slices. They merge/close up during printing and form structural ribbing. If your extrusion is low, they will be more noticeable in the print. LW-PLA yields the best, strongest and lightest result as it foams, expands and merges during print. If unavoidable through print settings, run some thin CA glue in the gap and it will be even stronger.

**Q: Your parts look solid and un-usable.**

A: Slice with 0% infill (unless stated).

**Q: The nose is a very tight fit.**

A: It is designed on the tight side in case some printers extrude differently and end up way too loose, so you might have to sand the corners slightly to achieve a snug fit. The material may relax a bit with use too, so the intent was to start off snug.

**Q: Which orientation to print the parts?**

A: Refer to the table in the printing section below.

---

## Configuration

There are 2 wing versions:

1. **Mandatory** — 2 servos (i.e.: taileron/elevon control)
2. **Optional** — flaps + taileron 4 servos version. Flap to elevator mixing is in the radio control setup and throws section.

### Scaling to 130%

If you want a slightly larger model, this model scales up to 910mm wingspan, 1110g + battery weight:

1. 130% size in slicer program
2. 64mm EDF
3. 4S 2200 mAh Lipo
4. 4mm carbons in lieu of 3mm (solid rod is preferred over tube as handling damage can over-torque and split the carbon tubing)
5. 17g servos (30mm L) + 9g 8mm thick flap servos
6. 2% infill for wing 1f, horizontal stabs, wingtip, vstabs
7. Files from regular PLA version for wing 1r, horizontal stabs
8. Run fibre string through fuselage parts prior to joining to route servo cable extensions

---

## Printing

1. Print the parts with your best settings for LW-PLA/PLA. LW-PLA is a foaming PLA material which is less than half the weight of standard PLA when printed properly. It has good layer adhesion due to expansion and foaming.
2. Unless stated, print orientation for the parts is intended to be rear bulkheads/wing root to build plate where possible. Look for any scribe lines which show where to cut after printing and align that surface to build plate.

### Print Orientation Table

| Part | Orientation (face) on print bed | Bottom Layers | Top Layers |
|------|----------------------------------|:---:|:---:|
| Sawtooth Nose | Rear | N | Y |
| Nose | Rear | N | Y |
| Fuse1 | Rear | Y | N |
| Fuse2 | Rear | Y | N |
| Fuse3 | Rear | Y | N |
| Fuse4 | Front | Y | Y |
| Wings | Root | Y | Y |
| Hatch | Front | Y | Y |
| Fairings | Inboard | Y | N |
| Tailerons | Root | Y | Y |
| Vertical Stabs | Rear and front | Y | Y |
| Flaps / Ailerons | Control horn | Y | Y |
| Hstab main | Root | Y | Y |
| HStab Front | Rear (rear, engraving down) | Y | Y |

### Additional Print Notes

3. 2 walls of foaming LW-PLA. It is more expensive but worth using as the parts are more resilient. You will get better results, less transport damage and "tin canning" thanks to the extra wall.
4. Narrow gaps.
5. If using regular non-foaming PLA, 1 wall is recommended as 2 walls will be too heavy.
6. Good idea to start with the fan hatch print first to check if your fan unit will need any cutting or wrapping with tape to fit in the bay.
7. Print the rest of the parts starting with the nose, fuse1, fuse2, left wing, right wing etc.
8. The wing sections are very thin. Use an adhesive product such as Dimafix™ on the print bed or a brim to ensure they don't get knocked over. The aileron CAD has been supplied with adhesion tabs to help. Trim these off with side cutters after printing.
9. 0.4mm 'Z hop when retracted' to allow expansion flow and avoid knocking parts over.
10. 0% infill unless essential or printing the 64mm version.
11. Clean any stringing as much as possible with a rasp or long metal ruler edge.
12. Parts that need knifing/hot wire cutting afterward have the paths scribed/indented. They are important for cable routing. Heat a wire and use it to cut the excess panel out, or use several careful light cuts with a scalpel. Don't forget — it is a pain to do this afterwards.
13. The taileron horns require a slightly cooler printing temp (if using LW-PLA) to have less foaming effect and greater hardness/precision. Use 220–225°C as opposed to 230°C for the airframe.

---

## Assembly

Start the fuselage assembly whilst the wings are printing.

1. Starting with the Fan hatch and Fuse3, cut open the motor wire and servo openings with a hot knife. Check your EDF fan unit fits. Wrap with masking tape/cut plastic if needed. Install the unit with UHU Por or Welders glue.
2. Plug in the ESC, route the cables and ESC forward and make sure the fan spins in the correct direction when powered up (it should also be balanced for best results). Screw down the fan hatch. That's the engine installation done!
3. Cut the marked cable routing panels for Fuse2 out of the bottom and have the part ready.
4. Cut 2x 250mm of the 0.81mm piano pushrod wire and thread it through the pushrod guides of Fuse2 and Fuse3. Make sure it slides freely. Use it as an alignment aid to help glue the fuse together (Medium CA or Acrifix). Don't use excessive glue, and **don't glue the fan hatch to Fuse2!**
5. Glue Fuse4 using the same method.
6. Cut routing holes and glue Fuse1.
7. Paint and attach the canopy to the nose or set painted canopy aside for later. Friction fit to Fuse1 should be enough but install the optional magnets if needed. Tape can also be used to retain the nose. File the corners of Fuse1 neck if needed.

The taileron/horizontal stabilizer assembly starts from the pushrod and works its way out to the control surface:

8. Make a "Z" or "L" bend on the pushrod wire ends exiting Fuse4.
10. Glue the horn lamination onto the taileron horn. Once dry, clean the pushrod holes with a step drill bit and assemble the Z bend into the outermost hole of the horn.
11. **New V3:** Glue the lamination plates to the cantilever tail forks. This will reduce the chance of the bearings shattering if your elevons get caught on grass.
12. Check that the 3mm carbon torque tubes pivot freely in the bearings of Fuse4 with no slop. Some filing or drilling might be needed.
13. With the torque tube in the bearing of Fuse4, press fit the laminated horn assembly (with wire pushrod attached) onto the end of the torque tube. The horn lamination top surface should be flush with the end of the carbon tube.
14. Use a sharp micro step drill to drill across the horn and carbon torque tube. Push some lock wire or 1mm carbon skewer through the hole to lock the assembly. When satisfied, back the whole torque rod assembly out of the bearing slightly and carefully apply 2 small drops of thin CA to fix. Hit with accelerator to make sure it is all cured overnight and won't accidentally be glued to the bearing. It's important to have a smooth and slop-free linkage here, so start over if it goes badly.
15. Press fit the horizontal stab onto the axle. Use a sharp drill bit and drill through the stab guide holes and axle, and use 1mm carbon skewer and thin CA to lock in.
16. **Wing:** Glue Wing 1f to 1b. Let dry. Cut 250mm of the 3x1 carbon strip and sharpen one end. Use it to clear the spar hole and then glue the wing tip. Check spar final fit and repeat for right wing. Wings are done!
17. Once the control surfaces are done and working smoothly, glue the fairings to cover up the linkages and strengthen the tail. UHU Por the fairing or tack glue in case it needs to be serviced later.
18. Glue the fin halves.
19. Glue the spars into the wings with Welder's or UHU glue; inject some into the spar holes first.
20. Glue wings to fuselage (note there are positions for rear spars) and the airframe is done.
21. Install all the RC gear with servo lead extensions.
    - If you use quick links with grub screws on the servo end, ensure they have adequate Loctite on the pushrod and grub screw tip. More is better. The taileron pushrods can experience strong pull force in dives and landing mishaps have occurred (catching grass). They can pull out of your servos if not secure and cause a loss of control. A Z-bend is better if you can form one at the servo end.
22. Stick self-adhesive Velcro on the battery bay tray.

---

## Mandatory CG Check and Pre-Flight

1. The CG is located at **22.6% of the wing chord from the wing leading edge (87mm from the leading edge)**. This coincides with the front edge of the servo hole openings. CG is also at the front edge of servo openings for the 130% version.
2. You will need a **Delta mix** in your radio to mix the control surface inputs.
3. Check that the control surfaces respond smoothly and correctly:
   - Trailing edge of the tailerons should go **up** when up elevator is applied; **down** when down is applied.
   - Right roll should have right trailing edge go up and the left one go down. Opposite for left.

---

## Control Setup and Throws

1. 25mm up and down measured from the front tip of the horizontal stab
2. 25–30% expo aileron and elevator, 10% differential
3. Level the stabs
4. Adjust to suit preferences
5. 5% up elevator mix with flaps down

---

## Flying Tips

1. Do your pre-flight checks! Make sure the linkages are tight and working smoothly.
2. Finger grips have been designed near the CG to help grip the model. The centre hole is a cut-out to allow hanging the model up on the wall easily.
3. The model is meant to be **hand-launched**. As with most jet models, a good level throw is needed, slightly nose up (no more than 10 degrees).
4. **Landing:** Relax up elevator upon touchdown. The elevator tips can catch rutty terrain if you hold the flare like a taildragger, resulting in torn up elevators, linkages, or servos. The throws are less than the fuselage extremities, but grass can get stuck in the gaps. Relax the elevator to be safe. Sacrificial elevator tips are on the cards if beneficial.

