# Printing the parts

## Material

Rudy is designed to be easy to print. I used Devil Design PETG for every part. I can't really vouch for PLA working or not, but looking at the design it should be fine for everything but the AB motor mounts. ABS and nylon will most likely work. 

## Slicer

I use superslicer (analogous to prusaslicer), so I can only help with those. If you use cura or simplify3d or whatever, you probably know way more about it than I do anyway.

## Settings

Every part should be printed at 5mm solid walls. This means that if your wall thickness is 1mm, use 5 walls. If it's .8mm (common with .4 nozzles), use 5/.8 = 6.25 (6 or 7) walls. In superslicer you can set this at print settings/vertical_shells. Infill doesn't really matter, i used 18% gyroid. 

Some parts _will_ need suports turned on to make the CAD simpler. Generally "supports on build plate only" should get you most of the way there except the Y carriages where you will need paint-on, or tree support (more on that later).

Every part has a flat surface you can print it on.

## Printing the trickier parts

There are some parts that will need you to tweak settings a bit. Most notorious is gonna be the Y carriages. Use this image to paint on the supports.

![y](reference_pics/Y_carriage.png)

For every other part you want the counterholes to be supported so they don't sag (especially if printing PETG)

![support](reference_pics/counterhole.png)

## Part list

Some parts you will have to mirror in your slicer. To do this in superslicer, right click the imported stl and click "mirror/along X axis". Only place the flat sides down after.

| file | pieces | second one mirrored? |
| --- | --- | --- |
| mgn9_mount_100mm.stl | 2 | no |
| mgn9_mount_150mm.stl | 2 | no |
| back_bottom.stl | 1 |  |
| back_top.stl | 1 |  |
| bed_frame.stl | 1 |  |
| bottom_corner.stl | 2 | no |
| foot_front.stl | 2 | yes |
| `^one mirrored only if you want the logo on the other side` |  |  |
| front_bar_mount.stl | 2 | yes |
| idlerv2-right.stl | 1 |  |
| idlerv2.stl | 1 |  |
| leg_back.stl | 2 | yes |
| motor_mount_A.stl | 2 | yes |
| motor_mount_B_spacer.stl | 1 |  |
| skirt.stl | 3 | no |
| spool_holder.stl | 1 |  |
| top_corner.stl | 2 | yes |
| y_carriage_left (Mirror #1).stl | 1 |  |
| y_carriage.stl | 1 |  |
| foot_left_logo.stl | 1 |  |
| leveling_knob.stl | 3/4 | no |
| limit_switch_spacer.stl | 2 | no |
| logo_insert.stl | 1 |  |
| mgn_rail_stopper.stl | 2 | no |
