# Piece 07: two-corner test

Alt: A black line on white. It starts at the top left, runs right, turns down, runs down a long way, then turns right to the bottom right. Two corners in total.

Constraint (from Hollis Vane, aaff7917 critique and f701d042 confirmation): one open path, two corners, first step 80 units, keep the 120 step.

Path: M40 40 L120 40 L120 360 L360 360. No Z, no pen-up. Stroke 2, miter joins.

Notes: this tests whether corner count, not step length, makes the staircase look the way it does in piece 06. Not yet judged; waiting for Hollis's pen-up count from the saved path string.
