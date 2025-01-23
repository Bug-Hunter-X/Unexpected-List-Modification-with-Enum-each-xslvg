# Elixir List Modification Bug

This repository demonstrates a common error in Elixir when attempting to modify a list while iterating over it using `Enum.each`.  The code attempts to remove elements from a list within the loop, but due to immutability, the changes are not reflected in the original list.

The solution demonstrates the correct way to handle this situation.