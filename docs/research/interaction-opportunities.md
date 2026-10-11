# Object-driven interaction opportunities

Interactions should teach how the artifact works, keep historical claims visible, and offer equivalent keyboard, touch, reduced-motion, and non-WebGL paths.

## Stereoscope: two views become one

- Let visitors bring two historically styled photographs into alignment with a slider/keyboard controls; show a depth cue only after the left/right views converge.
- Offer a 2D side-by-side mode and a reduced-motion depth toggle. Avoid requiring cross-eyed viewing or a headset.
- If using a 3D viewer, inspect the actual Smithsonian NMAAHC 2017.111.16 scan. Label it accurately as an A. Mattey French viewer, 1905–1920. Do not imply the model is Holmes’s 1861 viewer.
- Historical cards should be public-domain or specifically cleared, not merely downloaded from a general stereograph archive.

## Zoetrope: frame, slot, motion

- A user-controlled, non-autoplay drum reveals a short sequence through slits; pause mode exposes the individual frames and their order.
- Offer printable/downloadable original artwork created for the site. If animating a museum strip, first clear the exact image and preserve its provenance.
- Make frame stepping and speed available by keyboard and touch. Provide a static contact sheet and reduced-motion setting; motion must not be necessary to understand the sequence.
- A lightweight CSS/canvas cylinder or simple sprite sequence is likely sufficient; no historical 3D mesh is needed.

## Tinfoil phonograph: vibration to groove to sound

- Let the user drag a stylus across a newly made, schematic hill-and-dale groove, changing a simple synthesized tone/noise playback. Make clear it is a teaching simulation, not recovered Edison audio.
- A/B view: embossing versus playback, with the diaphragm and crank parts highlighted. Include a text explanation that early foil wore quickly and the machine was difficult to operate.
- Any archival sound recording requires an identified recording and rights review. Do not present modern voice synthesis as Edison or claim it is authentic foil playback.
- Use SVG/canvas and local generated audio; WebGL is unnecessary.

## Pneumatic postal system: route the carrier

- Let visitors select a documented city route and send a carrier between stations on a simplified, map-based diagram; show pressure/vacuum direction, dispatch time, and the historically specific era.
- Include a small canister cutaway or schematic, not an unverified full network reconstruction. Distinguish NYC dates and routing from Philadelphia or European systems.
- A timeline/map scrubber can show expansion, funding interruptions, restart, and closure. Cite the National Postal Museum/LOC records alongside the interaction.
- No 3D scan is required: a map, animated route line, and canister diagram are more accurate and mobile-friendly. Avoid simulating actual speed as a measured historical fact unless the selected route has evidence.
