# Round-Bottomed Flask: programming with molecules


## Makin stuff

The general process with org chem is to build up molecules through a variety of steps.
An actual program might be like the entire experimental section of my thesis - many reactions & workups.

What operations can we represent so far?

* Concatenation
* Filtering
* Sorting

Could we represent arithmetic? If we stretch the metaphore, we could do 1-bromohexane + 2-bromohexane --> 3-bromohexane.

We could also represent the operation by different reaction types. So have addition reactions model addition.
1-bromobutyl aldehyde + pentan-5-ol --> 6-bromobutyl aldehyde (or, for that matter, pentan-6-ol)

### Subtraction (or decrement?) by elimination reactions
5-bromodecane + base --> 4-bromodecane (the bromine's still there! don't tell anyone!)

### Multiplication by polymerisation reactions

* Amino acid polymerisation
* 5-glycine + 10-leucine + (drying agent?) --> 50-leucine
* This is not very portable to other molecules, though.

* Radical polymerisation
* 5-bromodecane + 10-bromohexadecane + AIBN --> 50-bromohexadecane

### Division by fragmentation?


## What else would we like to be able to represent?

* Loops? Conditionals? ie. control flow
* String processing, eg. splitting, regex, etc.


## Starting materials

### Numbers

Numbers may be represented as haloalkanes, eg. 1-bromohexane.

### Numerical arrays

Numerical arrays may be represented as multihaloalkanes, eg. 1,2,3-tribromohexane.

### Strings

Strings are represented as compounds with some standard functionality, eg. "hello aldehyde" and "world alcohol". Spaces may be encoded with underscores (hello_world) or as ethers (hello world ether).



## Reaction types

### Addition

Addition reactions may occur between an electrophile (eg. an aldehyde) and a nucleophile (eg. an alcohol or an amine) with acid or base catalysis.
eg. hello aldehyde + world alcohol --> hello world ether

### Substitution

### Elimination


## Reaction Conditions

* -78oC
* 0oC
* Room temperature / 18oC
* Refluxing (+ various solvents)
* Sealed tube
* Microwave
* High pressure


## Activation energies


## Workup

* Aqueous - eg. remove salts
* Column - ordering results. Media and solvent system determine ordering.


## Examples

### Hello World

#### Simple version
Commercially available Hello,_world! was distilled under reduced pressure at 150 oC, which set to white, needlelike crystals upon cooling.

#### Preparation from hello aldehyde and world alcohol
A magnetically stirred solution of hello aldehyde (1.00 mmol) and world alcohol (1.00 mmol) in DCM (10 mL) was treated with two drops of concentrated sulfuric acid and the resulting mixture heated under refluxing conditions for 0.5 h. The reaction mixture was poured into sodium bicarbonate (15 mL of a saturated aqueous solution). This mixture was extracted with DCM, and the combined organic phases were dried, filtered and concentrated under reduced pressure.

// Sealed tube == no input? No, but keep procedure here in case needed.
// If sealed tube is not freeze-thawed, it has 10% chance of exploding
//To a sealed tube containing a solution of hello aldehyde (1.00 mmol) and world alcohol (1.00 mmol) in toluene (5 mL) was added two drops of concentrated sulfuric acid. The tube was subjected to three freeze-thaw cycles, sealed, and then heated at 200 oC for 1 h. The reaction mixture was poured into sodium bicarbonate (10 mL of a saturated aqueous solution). This mixture was extracted with DCM, and the combined organic phases were dried, filtered and concentrated under reduced pressure.


### Counter

A solution of 1-bromodecane, 2-bromodecane, 3-bromodecane, 4-bromodecane and 5-bromodecane in DCM (10 mL) was maintained at 18 oC for 0.5 h. The reaction mixture was concentrated under reduced pressure, and the resulting yellow oil subjected to flash column chromatography (silica, ethyl acetate).


### Greeter

* Hi, what's your name?
* Rohan
* Hi, Rohan!

Commercially available Hi,_what's_your_name? was distilled under reduced pressure at 100 oC, affording a light yellow oil.

To a magnetically stirred solution of Hi,_ aldehyde in DCM (10 mL) was added input alcohol (1 mL) and two drops of concentrated sulfuric acid. The resulting mixture was heated under refluxing conditions for 0.5 h. The reaction mixture was poured into sodium bicarbonate (15 mL of a saturated aqueous solution). This mixture was extracted with DCM, and the combined organic phases were dried, filtered and concentrated under reduced pressure.


### Maths test

* What's six times four?
* 12
* You lie!

* What's six times four?
* 24
* Rightyo!

Commercially available What's_six_times_four? was concentrated under reduced pressure.

Equality test. Additions of numbered string compounds will only occur when the numbers are equal.
eg. 24-rightyo aldehyde and hexan-24-ol

When 24 is inputted, we need to somehow destroy a you_lie compound, and enable a rightyo compound.
Let's use a column and play with polarity.

24-rightyo aldehyde
you_lie methyl ketone
input alcohol

// Addition to acid chlorides w/ elimination could be a useful reaction

Competing addition reactions. If input alcohol matches the number of one of the electrophiles, it exclusively reacts with that. Otherwise it reacts
with the next most reactive electrophile (if present). The reaction will form an alcohol.

Then we would have one of:

24-rightyo alcohol
you_lie methyl ketone

24-rightyo aldehyde
1-youlie-1-hydroxy-1-methyl ethyl ester

Then we column with silica (sort by polarity) and take the last (most polar) fraction.
Molecules have a polarity, primarily based on their functional groups, but also based on their attached strings and numbers.
Silica sorts by polarity. Each compound has an Rf, which the programmer must determine experimentally.

Given all that, here's our procedure for the maths test:

Commercially available What's_six_times_four? was distilled under reduced pressure at 175 oC, affording a light yellow oil.

To a magnetically stirred solution of 24-rightyo aldehyde (1 mmol) and you_lie methyl ketone (1 mmol) in DCM (10 mL) was added input alcohol (1 mmol) and two drops of concentrated sulfuric acid. The resulting mixture was heated under refluxing conditions for 0.5 h, concentrated under reduced pressure, and the residue thus obtained was subjected to flash chromatography (silica, ethyl acetate). Concentration of the fraction eluting at Rf = 0.9 resulted in a pale-yellow oil.
