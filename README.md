# Barcut App creates a schema to cut bars on peaces (details).

It is only one-dimensional (line) cutter.

There are several algorithms to obtain the best schema to cut some bars on given details (parts):
1. **BestCut** - getting all permutations of the details list as non-devided chains, then devide them on bars.
2. **Shuffle** - randomly shuffle the details list as a chain, then devide it on bars - find the best schema.
3. **ShuffleBest** - randomly shuffle the details list and find the best part of the chains as a bar, or several best parts, then take those details from list and continue while done.
4. **BestBar** - get best combination for a detail chain for a bar from ordered details list.
5. **BestBarLongest** - take the longest detail from a bar length, then get the best combination of ordered details list, where details fit to the remain length of the bar.