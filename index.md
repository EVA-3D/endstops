---
title: X Endstop
badges:
    - Official
---

## Standard

EVA 1 had a endstop mount that I never really liked. This changes with EVA 2. A standard is now defined that will allow to adapt different, on-carriage endstops with one part. Also, the X position of the endstop is not possible.

By default every `top` part comes with a "blank" endstop plug, which could be used for sensorless homing, this EVA 2 Addon will contain different X endstop options.

<figure>
  <img src="assets/x_endstop.gif" width="640" />
  <figcaption>Endstop position adjustments</figcaption>
</figure>

## Spec

{{ eva_link("endstops") }}

{{ onshape_link("endstops") }}

### Endstops

=== "Angled MGN12"

    ![](assets/angled_mgn12.png)

{{ bom("addons/x_endstop/bom/angled_mgn12.csv", 4) }}

=== "Angled MGN15"

    ![](assets/angled_mgn15.png)

{{ bom("addons/x_endstop/bom/angled_mgn15.csv", 4) }}

=== "Openbuilds MGN12"

    ![](assets/[Endstop] Openbuilds Endstop.png)

{{ bom("addons/x_endstop/bom/openbuilds_mgn12.csv", 4) }}

=== "Openbuilds MGN15"

    ![](assets/[Endstop] Openbuilds Endstop MGN15.png)

{{ bom("addons/x_endstop/bom/openbuilds_mgn15.csv", 4) }}
