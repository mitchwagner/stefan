# S.T.E.F.A.N.

The Sack Toss Engine Furnishing Analysis and Notation (S.T.E.F.A.N.)
is, as titularly denotated, a collection of tools for the consummate 
cornhole obsessive. 

## S.T.E.F.A.N. Cornhole Notation (SCN)
S.T.E.F.A.N. Cornhole Notation (SCN) is a generic notation for
specifying toss results in a frame, distinguishing between three
discrete toss outcomes (miss, woody, cornhole). The specification
allows for additional annotations denoting whether or not a bag is
"dirty", viz., did it touch the ground, as well as for recording the
interaction between bags.

In the following example, assuming a single player and a four-bag
frame, the SCN specifies that
- the first bag was a woody
- the second bag was a miss, and made the first bag a miss
- the third bag was a dirty cornhole
- the fourth bag was a woody and knocked the third bag in for a
  cornhole

```
w
m; 1m
wd
w; 3c
```

Note that whether or not a bag was dirty or not is specified
only on the line corresponding to its initial toss.

## Planned Features
- S.T.E.F.A.N. Cornhole Notation (SCN): a flexible shorthand
  notation/markup language for frame-by-frame records of games.

- S.T.E.F.A.N. will track:
    - Player Statistics (across a selection of stored games)

    - Per-Toss Bag Characteristics:
      - Woody/Cornhole/Miss/Dirty
      - Bag interactions (knock in/knock off)

    - Game Parameters:
      - Number of players / teams
      - Bags per frame
      - Points per woody/cornhole
      - Whether or not dirty bags count
      - Toss rotation strategy
      - "Bust" penalty, if any
      - Other house rules/scoring variations
