# Unhandled Throw in Elixir's Enum.each

This repository demonstrates a subtle issue when using `Enum.each` in Elixir and handling exceptions.  The provided code throws an exception within the `Enum.each` function, causing the program to crash instead of gracefully handling or continuing execution.  The solution shows how to properly handle exceptions within `Enum.each`.

## How to Run

1. Clone the repository.
2. Run `iex bug.ex` to see the unexpected termination.
3. Run `iex bugSolution.ex` to observe the correct exception handling.