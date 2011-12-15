# RBF (Round-Bottomed Flask)

...

## Makin stuff

The general process with org chem is to build up molecules through a variety of steps.
An actual program might be like the entire experimental section of my thesis - many reactions & workups.

What operations can we represent so far?

Concatenation
Filtering
Sorting

Could we represent arithmetic? If we stretch the metaphore, we could do 1-bromohexane + 2-bromohexane --> 3-bromohexane.

We could also represent the operation by different reaction types. So have addition reactions model addition.
1-bromobutyl aldehyde + pentan-5-ol --> 6-bromobutyl aldehyde (or, for that matter, pentan-6-ol)

Subtraction (or decrement?) by elimination reactions:
5-bromodecane + base --> 4-bromodecane (the bromine's still there! don't tell anyone!)

Multiplication by polymerisation reactions:

Amino acid polymerisation
5-glycine + 10-leucine + (drying agent?) --> 50-leucine
This is not very portable to other molecules, though. 

Radical polymerisation
5-bromodecane + 10-bromohexadecane + AIBN --> 50-bromohexadecane

Division by fragmentation?





## Starting materials

### Numbers

Numbers may be represented as haloalkanes, eg. 1-bromohexane.

### Numerical arrays

Numerical arrays may be represented as multihaloalkanes, eg. 1,2,3-tribromohexane.

### Strings

Strings are represented as compounds with some standard functionality, eg. "hello aldehyde" and "world alcohol". Spaces may be encoded with hyphens (hello-world) or as ethers (hello world ether).



## Reaction types

### Addition

Addition reactions may occur between an electrophile (eg. an aldehyde) and a nucleophile (eg. an alcohol or an amine) with acid or base catalysis.
eg. hello aldehyde + world alcohol --> hello world ether

### Substitution

### Elimination


## Reaction Conditions

-78oC
0oC
Room temperature / 18oC
Refluxing (+ various solvents)
Sealed tube
Microwave
High pressure


## Activation energies


## Workup

Aqueous - eg. remove salts
Column - ordering results. Media and solvent system determine ordering.


## Examples

### Hello World

// If sealed tube is not freeze-thawed, it has 10% chance of exploding

To a sealed tube containing a solution of hello aldehyde (1.00 mmol) and world alcohol (1.00 mmol) in toluene (5 mL) was added two drops of concentrated sulfuric acid. The tube was subjected to three freeze-thaw cycles, sealed, and then heated at 200 oC for 1 h. The reaction mixture was poured into sodium bicarbonate (10 mL of a saturated aqueous solution). This mixture was extracted with DCM, and the combined organic phases were dried, filtered and concentrated under reduced pressure.

// Sealed tube == no input
//A magnetically stirred solution of hello aldehyde (1.00 mmol) and world alcohol (1.00 mmol) in DCM (10 mL) was treated with two drops of concentrated sulfuric acid and the resulting mixture heated under refluxing conditions for 0.5 h. The reaction mixture was poured into sodium bicarbonate (15 mL of a saturated aqueous solution). This mixture was extracted with DCM, and the combined organic phases were dried, filtered and concentrated under reduced pressure.


### Counter

A solution of 1-bromodecane, 2-bromodecane, 3-bromodecane, 4-bromodecane and 5-bromodecane in DCM (10 mL) was maintained at 18 oC for 0.5 h. The reaction mixture was concentrated under reduced pressure, and the resulting yellow oil subjected to flash column chromatography (silica, ethyl acetate).


