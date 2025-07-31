Trying to get my head around matrices and how they relate to transforms in Unreal.

Q, W, E - translate incrementally in X, Y, Z
A, S, D - rotate incrementally in X, Y, Z
Z, X, C - scale incrementally in X, Y, Z

Space - reset
Tab - toggle between row/column major

There's also a "manual override" bool exposed on the actor if you want to
switch between transformations without resetting it back to identity

Ben.
