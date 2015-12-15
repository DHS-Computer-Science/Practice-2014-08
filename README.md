# Practice 2014 - 08: Gimli’s Gullet

## Background
Legolas and Gimli are packing rations before setting off from the Woodland
Realm, but the kitchen seems to have underestimated the belly of a dwarf! Gimli
absolutely refuses to set off until the matter is settled and his pack is at its
maximal hunger-satisfying potential, lest his Dwarven appetite go unsated.

## Description

### Input
Input consists of several test cases, each over multiple lines. The first line
of every test case contains a single non-negative integer, denoting the
space (in cubic centimeters) remaining in Gimli’s pack. The second line
contains a single non-negative integer, M , describing the number of food
items available. The next M lines each consist of two non-negative integers,
describing the volume (also in cubic centimeters) and caloric content of a food,
respectively. These lines are sorted in increasing order of volume.

A test case starting with 0 cubic centimeters denotes end of input,
and should not produce output.

### Output
For each test case, output a single space-separated line with M entries. Each
entry in the line is the quantity that Gimli should order of the corresponding
food from the kitchen in order to fill his pack with the maximum amount of food.

## Sample
### Input
```
6000
4
230 100
350 500
480 900
1400 2000
760
2
10 180
200 300
0
```

### Output
```
0 2 11 0
76 0
```
