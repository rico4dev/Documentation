---
title:  Layer Managers
summary: "Layer managers organize layers and their panels."
sidebar: suite_sidebar
permalink: suite-layer-managers.html
---

{% include /reuse/zoom-levels.md content="yes" extended="no" %}

Layer managers are usually found on the top-left and top-right corners of the screen. A time machine may have more than one timeline chart embedded and each timeline chart features a layer manager.

Layer managers are hidden when the zoom is partially out, to avoid blocking the view of the data in the time machine.

**1. To move a layer manager** to the opposite, top-right corner, left-click on the header and drag it away. Layer managers tend to self-arrange at either of these corners, so you may drop it somewhere next to its destination and let it find its place.

{% include note.html content="The order in which layer managers self-arrange is given by the order of precedence of the embedded timeline charts around the time machine node in the designer." %}

{% include image.html file='interface/layer-managers-01.gif' url='yes' max-width='100' caption='Left-click and drag to move a layer manager to a different corner. Use the wheel of the mouse to roll and scroll layer managers.' %}

**2. To roll a layer manager up or down**, place the mouse pointer on top of the header and turn the wheel. When the layer manager cannot accommodate all layers in its current length, a scrolling bar appears on the right-hand side. To scroll through the layers, place the mouse pointer on top of any of the visible layers and scroll the wheel of the mouse.

**3. To turn layers *on* and *off***, left-click on the layer. 

* When a layer is *loading*, the layer slot in the layers managers shows the progress with an orange dotted line on top of the layer's name.

* When a layer is *on*, the dotted line turns green.

* When a layer is *off*, there is no line.

* When the layer can't load, the dotted line turns red.

Certain layers may feature a <a data-toggle="tooltip" data-original-title="{{site.data.data_mine.plotter_panel}}">panel</a>. Those which do, feature a panel button on the bottom-left corner of the layer slot in the manager.

{% include image.html file='interface/layer-managers-02.gif' url='yes' max-width='100' caption='Left-click and drag to move a layer manager to a different corner. Use the wheel of the mouse to roll and scroll layer managers.' %}

**4. To turn panels *on* and *off***, left-click on the panel button. 

Panels tend to self organize on any of the four corners of the screen.

**5. To move a panel** to a different corner, left-click on the panel label, drag it somewhere near the preferred corner, and let it find its way to its destination.

{% include note.html content="The order in which panels self-arrange is given by the order of precedence of the layer nodes around the layer manager node in the designer." %}

{% include image.html file='interface/layer-managers-03.gif' url='yes' max-width='100' caption='Left-click and drag to move a panel to a different corner.' %}

**6. To minimize a panel** left-click on the small triangle on the right-hand side of the label. To bring it back, left-click the triangle again.

{% include /charting_space/layers-manager.md heading="more" icon="150-" adding="####" configuring="####" charts="" content="yes" definition="bold" table="yes" more="yes"%}

{% include /charting_space/layer.md heading="more" icon="150-" adding="####" configuring="####" charts="" content="yes" definition="bold" table="yes" more="yes"%}