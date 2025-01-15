# Elixir List Modification during Enum.each

This repository demonstrates a common error in Elixir when attempting to modify a list while iterating over it using `Enum.each`.  The code in `bug.ex` attempts to remove the element `3` from the list, but due to the immutability of lists in Elixir, this operation doesn't have the intended effect.

The solution in `bugSolution.ex` shows the correct approach using `Enum.filter` to create a new list excluding the element to be removed.
