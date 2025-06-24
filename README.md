# Satistizer
A **Satis**factory Op**ti**mi**zer** written in Elixir.
I am learning Elixir at the same time as writing this program, so it may be a while! And most definitely will not be the best written code ever

## Features:

- To start: Provide input resources and output desired.
  - Algorithm will calculate intermediary steps
  - Start slow - do basic recipes to get a feel for the language and understand what data structures i will use. Likely composite pattern.
  - Algorithm:
    - likely a sort of search tree where it pieces together the recipe from end to back, calculating all possible routes and adding them to a list.
    - It will then select valid entries from that list (what alternate recipes enabled, starting resources, etc.)
    - Then calculate maximum amount of output for given input.
      - This will then have to be broken down into steps with overclocking/under clocking percentages.
- Add support for calculating intermediary steps
- Eventually increase complexity to allow for more input and more outputs
- 