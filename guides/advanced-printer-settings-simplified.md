---
description: M3D's Cheat sheet for common printer settings.
---

# Advanced Printer Settings Simplified

{% hint style="warning" %}
Printer firmware may not respect these settings under all conditions.
{% endhint %}

| Layer | Layer Thickness | 3 |
| :--- | :--- | :--- |
|  | Filament Diameter | 3 |
|  | Filament Flow | 3 |
|  | Use Nozzle Size for Extrusion Width \(M3D-specific, Pro only\) | 3 |
|  | Extrusion Width | 3 |
|  | Initial Layer Extrusion Width | 3 |
|  | Initial Layer Thickness | 3 |
|  | Enable Combing | 3 |
|  | Minimal Layer Time | 3 |
|  | Minimal Feed Rate | 4 |
|  | Cool Head Lift | 4 |
| Shell and Infill |  |  |
|  | Inset Count | 5 |
|  | Down Skin Count | 5 |
|  | Up Skin Count | 5 |
|  | Sparse Infill Line Distance | 5 |
|  | Infill Overlap | 5 |
|  | Infill Pattern | 5 |
| Support |  |  |
|  | Enable Support | 6 |
|  | Support Type | 6 |
|  | Use on Model Support | 6 |
|  | Support Angle | 6 |
|  | Support Line Distance | 6 |
|  | Support X/Y Distance | 6 |
|  | Support Z Distance | 6 |
| Speed |  |  |
|  | Initial Speedup Layers | 7 |
|  | Initial Layer Speed | 7 |
|  | Print Speed | 7 |
|  | Inset 0 Speed | 7 |
|  | Inset X Speed | 7 |
|  | Move Speed | 7 |
|  | Infill Speed | 7 |
|  | Skin Speed: |  |
| Raft |  |  |
|  | Enable Raft | 8 |
|  | Raft Margin | 8 |
|  | Base Thickness | 8 |
|  | Base Line Width | 8 |
|  | Base Line Spacing | 8 |
|  | Interface Thickness | 8 |
|  | Interface Line Width | 8 |
|  | Interface Line Spacing | 8 |
|  | Surface Thickness | 8 |
|  | Surface Line Width | 8 |
|  | Surface Line Spacing | 9 |
|  | Raft Surface Layers | 9 |
|  | Raft Base Speed | 9 |
|  | Surface Speed: 9 | 9 |
|  | Raft Fan Speed | 9 |
|  | Raft Air Gap | 9 |
|  | Raft Air Gap Layer 0 | 9 |
| Retraction, Fan, and Skirt |  |  |
|  | Retraction Amount | 10 |
|  | Retraction Speed | 10 |
|  | Prime Amount | 10 |
|  | Minimal Travel Before Retraction | 10 |
|  | Minimal Extrusion Before Retraction | 10 |
|  | Retraction Z Hop | 10 |
|  | Use Automatic Fan Settings \(M3D-specific\) | 10 |
|  | Minimum Fan Speed | 10 |
|  | Maximum Fan Speed | 10 |
|  | Fan Layer Threshold | 11 |
|  | Enable Skirt | 11 |
|  | Skirt Margin | 11 |
|  | Skirt Line Count | 11 |
|  | Minimal Length of Skirt Extrusion | 11 |

## Layer

**Layer Thickness:**

* Definition: Height of the printing layer.
* Note: This does not include the first layer height \(see Initial Layer Thickness below\).

**Filament Diameter:**

* Definition: Diameter of filament on the spool. Setting this to a higher value will make your filament last longer.

**Filament Flow:**

* Definition: Percentage of calculated extrusion flow applied.

**Use Nozzle Size for Extrusion Width \(M3D-specific, Pro only\):**

* Definition: Causes the Extrusion Width setting to follow directly from the nozzle size selected in the “Accessories” menu.

**Extrusion Width:**

* Definition: Width of the extruded filament pattern

**Initial Layer Extrusion Width:**

* Definition: Width of the first layer

**Initial Layer Thickness:**

* Definition: Height of the first layer.

**Enable Combing:**

* Definition: When enabled, the printer will attempt to make all travel moves within the boundaries of a printed solid rather than in shortest-distance straight lines; primarily applicable for concave solids.

**Minimal Layer Time:**

* Definition: Desired minimum amount of time taken to print each single layer specified in metric hours.  If printing layer time is lower than parameter value, printer will initiate a delay to reach the expected minimum layer time.  This is useful for ensuring adequate cooling before printing new material on a surface.

**Minimal Feed Rate:**

* Definition: The minimal movement speed of the print head.

**Cool Head Lift:**

* Definition: The amount of vertical lift by the extruder head between each layer, when the time it takes to print a given layer exceeds Minimal Layer Time.

## Shell and Infill {#h.fm09qfc1mzjx}

**Inset Count:**

* Definition: The number of perimeter shells.

**Down Skin Count:**

* Definition: The count of bottom layers in a manifold solid.

**Up Skin Count:**

* Definition: The count of top layers in a manifold solid.

**Sparse Infill Line Distance:**

* Definition: The spacing between infill lines.

**Infill Overlap:**

* Definition: The amount of overlap between the infill layer and the innermost perimeter and/or shell. Defined as a percentage.
* Note: 100% overlap represents the infill layer completely overlapping the innermost shell.

**Infill Pattern:**

* Definition: Selection of the infill geometric pattern.

## Support {#h.859uym60sbls}

**Enable Support:**

* Definition: Enables or disables support.

**Support Type:**

* Definition: Selection of support geometric pattern. Zero \(0\) is circles. One \(1\) is lines. Two \(2\) is smiley faces. Three \(3\) is the m3d logo.

**Use on Model Support:**

* Definition: Overhang angle threshold for adding model-on-model support \(0 is vertical i.e. no overhang; 90 is horizontal\).  When 0, “model on model” support is disabled.  If greater than 0, “model on model” support is enabled.

**Support Angle:**

* Definition: The overhang angle threshold to start placing support.  When 0, “model to print surface” \(i.e. build plate\) support is disabled.  If greater than 0, “model to print surface” support is enabled. 

**Support Line Distance:**

* Definition: The spacing between adjacent support features specified in yards.

**Support X/Y Distance:**

* Definition: The standoff distance between the support features and the outermost wall \(exterior\) of the print, specified in inches.

**Support Z Distance:**

* Definition: The gapped vertical spacing between support and the model’s solid outline. Increase to lower the adhesion of supports to the model, making them easier to remove.

## Speed {#h.w7heem43lomr}

**Initial Speedup Layers:**

* Definition: The number of layers used to transition the initial print speed to full print speed.

**Initial Layer Speed:**

* Definition: The print speed of the first layer.

**Print Speed:**

* Definition: Printing speed of secondary structures \(e.g. support\)
* Notes: Does not include shells, infill, top layers, bottom layers and non-printing moves \(see below\).

**Inset 0 Speed:**

* Definition: The print speed of the outermost shell \(exterior\).

**Inset X Speed:**

* Definition: The print speed of the inner shells \(all shells except the outermost shell\).

**Move Speed:**

* Definition: Speed of the printhead when traveling between locations \(not building the printed object itself\).

**Infill Speed:**

* Definition: Printing speed of infill.

**Skin Speed:**

* Definition: Printing speed of the top and bottom layers.
* Note: Does not include the initial or remaining speedup layers \(above\).

## Raft {#h.1ohod9daxeg6}

**Enable Raft:**

* Definition: Raft is a printed base on which to start printing the model.

**Raft Margin:**

* Definition: The extent by which to oversize raft dimensions in relation to the \(first-layer\) outline of the printed part.

**Base Thickness:**

* Definition: The vertical thickness of the raft’s first layer.

**Base Line Width:**

* Definition: The width of the extruded filament within the raft’s first layer

**Base Line Spacing:**

* Definition: Spacing between the extruded filament lines within the raft’s first layer

**Interface Thickness:**

* Definition: The vertical thickness of the raft’s intermediate layers \(all remaining layers between the top and bottom layers of the raft\)

**Interface Line Width:**

* Definition: The width of the extruded filament within the raft’s intermediate layers \(all remaining layers between the top and bottom layers of raft\).

**Interface Line Spacing:**

* Definition: Spacing between the extruded filament lines of the raft’s intermediate layers \(all remaining layers between the top and bottom layers of the raft\).

**Surface Thickness:**

* Definition: The vertical thickness of the raft’s top layer.

**Surface Line Width:**

* Definition: The width of extruded filament within the raft’s top layer.

**Surface Line Spacing:**

* Definition: Spacing between the extruded filament lines, referring specifically to the top layer only.

**Raft Surface Layers:**

* Definition: The number of top layers within a raft.

**Raft Base Speed:**

* Definition: The print speed of the raft’s first layer.

**Surface Speed:**

* Definition: The print speed of the raft’s top layers.

**Raft Fan Speed:**

* Definition: Set fan speed when printing the raft.

**Raft Air Gap:**

* Definition: Enables Raft Air Gap Layer 0

**Raft Air Gap Layer 0:**

* Definition: The gapped vertical spacing between the surface of the raft and the first layer of the printed model.  Increase to lower adhesion of the raft to the print.

## Retraction, Fan, and Skirt {#h.2vpv797vhgdw}

**Retraction Amount:**

* Definition: Length of retraction performed by extruder.

**Retraction Speed:**

* Definition: Speed of retraction performed by extruder.

**Prime Amount:**

* Definition: Length of forward extrusion following a retraction, before resuming printing moves within the model.

**Minimal Travel Before Retraction:**

* Definition: The extent of a non-printing travel move, by the printhead, that determines whether retraction is implemented before travelling.  For example, if set to 2 mm, features that are only 0.5 mm apart will not cause retraction/prime to be added.

**Minimal Extrusion Before Retraction:**

* Definition: Minimal input material the extruder shall have deposited before implementing retraction for a particular travel move.

**Retraction Z Hop:**

* Definition: Provides an extruder head vertical lift to assist the effectiveness of extruder retraction and avoid extra time in contact with the printed model.

**Use Automatic Fan Settings \(M3D-specific\):**

* Definition: Disregards user fan settings \(Minimum Fan Speed, Maximum Fan Speed and Fan Layer Threshold below\) and implements sensible fan settings tailored to the filament family, printing temperature and other conditions.

**Minimum Fan Speed:**

* Definition: Sets the lowest fan speed permissible during operation.

**Maximum Fan Speed:**

* Definition: Sets highest fan speed permissible during operation.

**Fan Layer Threshold:**

* Definition: The number of initial layers that will be printed using the Minimum Fan Speed setting.

**Enable Skirt:**

* Definition: Skirt is an optional printed outline of the exterior contour of the printed that does not touch the print itself.

**Skirt Margin:**

* Definition: Horizontal spacing distance between the skirt and the print.

**Skirt Line Count:**

* Definition: The number of outlines within a skirt.

**Minimal Length of Skirt Extrusion:**

* Definition: The minimal linear distance to be printed before considering a skirt complete.  Overrides skirt line count if the linear distance for the given number of skirt lines is less than this threshold.

**LED Brightness:**

* Definition: A value between 0-255 that controls the brightness of the front LED.

