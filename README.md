### Algorithms

---

## Bubble Sort

```

n = length(Array)

card = cardValue

tabl = myArrayOfCards

loop: i range: 0, n -1;

    loop: j range: i +1, n;

        if tabl[j] < tabl[i];

            card    = tabl[i]
            tabl[i]  = tabl[j]
            tabl[j]  = card
        
        condition end

    loop end

loop end

```

## Insertion Algorithm

```

n = length(Array)

card = cardValue

tabl = myArrayOfCards

specialCards[
    "As" => 1,
    "Jack" => 11,
    "Queen" => 12,
    "King" => 13
]

loop: i range: 0, n -1;

    card = tabl[i]

    if card is not in specialCards;

        tabl[card -1]  = card

    else if;

        tabl[ specialCards[ card ] ] = card

    condition End

loop end


```