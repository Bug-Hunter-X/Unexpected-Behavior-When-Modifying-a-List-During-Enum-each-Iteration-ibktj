# Elixir List Modification During Enum.each Iteration

This example demonstrates an issue with modifying a list while iterating over it using `Enum.each` in Elixir.  The intended behavior is to remove the element '3' from the list, but due to the immutable nature of Elixir lists, the modification within the loop does not affect the original list.

The `bug.ex` file shows the problematic code. The `bugSolution.ex` file provides a corrected approach using `Enum.filter` for a more functional and efficient solution.