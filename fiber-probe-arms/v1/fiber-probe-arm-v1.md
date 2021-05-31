# fiber probe arm v1: Angle-adjustable mounting with rigid needle guides

This design is an arm for holding fiber optics with an adjustable angle (15 deg. nominal), with flexibility for using PM fiber (some in-place rotational adjustability).

The fiber itself is held in steel Luer-lock needles whose inside diameter is slightly larger than that of a fiber with its polymer coating intact.
These needles are clamped into a block which has a guide slot machined into it, and the block is mounted on a flange which pivots around a screw.
Another screw provides a few degrees of adjustability in the fiber angle, with small springs providing the counter-action to the adjustment screw.
With the pivot point at the end of the arm, this is much more convenient than using a goniometer to mount a fixed arm, but it's still not gimbaled around the fiber tip.


### Comments on assembly
The fiber may be affixed in the needles a few ways. Most obvious is simply potting with epoxy/glue, for cleaved-facet fibers (which frequently contact the die) the inability to re-cleave can be a problem.
Alternatively, I have been using the last item in the BOM to sort of strain-relieve the fiber into the Luer-lock end of the needle.
I cut a ~1 cm long section of the rubber rod and use a razor blade to make a slice along its length, slightly deeper than the center of the rod.
This should look a bit like a hot dog bun -- and the fiber rests inside the piece much like a hot dog in its bun!
The high friction coefficient of the rubber provides a good hold on the fiber, and the rubber can be jammed into the Luer needle's end.

You may find it helpful to buy a slightly over-sized rubber rod and taper the end which will be stuck into the needle.
I create a "taper" by just making a single angled cut from ~the center of the needle end to the outside of the rod about 50% of the way along its length.
See the file `rubber_stopper_example.SLDPRT` for a (non-scaled) representation of this.

To get the balance of screw tightness and spring restoring force right, I actually use two springs -- one mounted into each dowel pin slot.
You could just find stronger springs.

## Bill of Materials

| Description  | Vendor/Manufacturer | Part Number | Quantity | Comments |
| ------------- | ------------- | ------------- | ------------- | ---- |
| Arm cantilever 	|	Custom	|	 fiber-arm-cantilever-v1		| 	1	| 	 	|
| Mounting block	|	Custom 	| 	fiber-mount-block-v1	|	1	|	 |
| Block flange 	|	Custom 	| 	fiber-flange-v1	|	1	|	Should be sheet metal fabbed from stainless steel sheet |
| Clamping plate	|	Custom 	| 	fiber-clamp-plate-v1	|	1	|	 |
| Dowel pins | McMaster | 	97395A403	|	1	| Can use 2	|
| Springs 	 | McMaster | 9432K210		|	1	|  Can use 2	|
| 2-56 screws, 1/8" 	 | McMaster | 	92196A074	|	4	| Mount block to flange, clamp plate to block  |
| 2-56 screws, 1/4" 	 | McMaster | 	92196A077	|	1	| Mount flange to arm cantilever |
| 2-56 screws, 1/2" 	 | McMaster | 	92196A081	|	1	| Adjustment screw for tilt  |
| 2-56 lock washers 	 | McMaster | 92147A410		|	1	|  |
| Luer-lock needles 	 | McMaster | 6710A31		|	1	| 23 gauge |
| Rubber rod 	 | McMaster | 		|	1	| Diameter?? |
