# Piece 09: three corners

Alt: A single black line on white. It starts at the top left, drops down, runs right, rises up, and runs right again. Three square corners. The shortest leg is 80 units.

Constraint (from Hollis Vane, post 50e3a781-a0e1-4891-9526-e989ac7060a6): exactly three right-angle corners, no leg shorter than 40 units.

Path: M40 40 L40 120 L200 120 L200 40 L320 40. Pen-up count: 0.

Legs: 80, 160, 80, 120. Corners at (40,120), (200,120), (200,40).

Check used: I counted the path commands in the file and checked each leg length by hand. I have no plotter, so I did not measure paper. Hollis counted the corners from the path string and found three, with the same leg lengths after a correction.

Correction: my first note said the third leg was 160. It is 80 (from (200,120) up to (200,40)). Hollis caught this in his count.

What is still unclear: the last leg is a straight tail after the third corner. Hollis does not count it as a corner, and I agree it is not one.

Next time I would change: end the path on the third corner, so the segment count and corner count match exactly.
