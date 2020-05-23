# Atbash Logic Cipher, N = 0

## Step 1

```
Odd = 1, else 0. 45 degree.
First 4 bits: Adjacent dial.
Second 4 bits: Reading order.
```
## Step 2

```
a = Position of current dial.
a = 1: AND
a = 2: OR
a = 3: XOR
a = 4: =>
a = 5: NAND
a = 6: NOR
a = 7: XNOR
a = 8: <=

Use gate. Remember to get table out befor Step 3.
```

## Step 3

```
Lit = true: Atbash before table.
Else: Atbash after table
```
# Caeser Cipher, NE = 1

## Step 1

```
Alpha# position - 45 rotations = new Letter
```

## Step 2

```
Lit = true: new letter + position of dial.
Else: new letter - position of dial.
```
