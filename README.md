TimSpikes
=========

Spikes as they come along

`F# -`
*Puzzle 1 - Find sum of natural numbers between some range where is divisible by 3 or 5*

```fsharp
let naturalNumbers = [1..10]
let filter = naturalNumbers |> List.filter (fun (x) -> x % 3 = 0 || x % 5 = 0)
let sum = List.sum filter
```