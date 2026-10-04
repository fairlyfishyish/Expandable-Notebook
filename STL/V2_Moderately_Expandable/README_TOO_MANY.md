Alr so this is a version which is being worked on seperately as a much more detailed version.

# V2.1
I updated export_stl.sh to find OpenSCAD on that disk image as well as in the usual places. From now on ./export_stl.sh runs as-is, and it takes about a minute for all parts.

The bounding boxes match the design:

Part	Size (mm)
front_cover	163.2 × 220 × 6.4
back_cover	170.4 × 220 × 6.4
spine_plate	34.8 × 220 × 6.4
band_insert	18.4 × 60 × 2.4
pen_holder	14.4 × 130 × 9.8
latch_clip	85.9 × 40 × 6.4

Both covers are 220 mm in Y, so you need a bed of about 230 mm or more.

I haven't verified the 45° overhang rule or the hinge clearances. The latch-clip bounding box matches the intended 85.9 × 40 mm flat strap and plate, but the pen holder, bridge arms and hinge fit still need a physical check. Print one hinge section and the latch first, and tell me what fits badly.
