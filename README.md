# Google Code Jam 2017

This repository contains my solutions to the problems from [Google Code Jam 2017][1] and Distributed Google Code Jam 2017. These solutions are provided "as is" - I give no guarantees that they will work as expected.

## Instructions

You can compile all Google Code Jam problems by issuing the following command:

    $ make

If you want to compile only a specific problem, issue the following command, replacing `<problem_id>` with the section and identifier of the problem you want to compile (see section "Problems Solved" for the list of possible identifiers):

    $ make <problem_id>

Running a compiled problem is just a matter of executing a command similar to the next one, replacing `<problem_id>` with the identifier of the desired problem:

    $ ./<problem_id>

Unless stated otherwise, every problem in this repository reads from the standard input and writes to the standard output.

Distributed Google Code Jam problems should be compiled and run using the local testing tool described in the [guide][2]. An example would be:

    $ dcj test --source <round_name>/<problem_id>.cpp --nodes <number_of_nodes>

You'll need to have an input header file with the name `<problem_id>.h` in the same directory as the source file. You can download sample inputs from each problem's page.

## Problems Solved

The following is the list of the problems solved. Each problem identifier is specified between round brackets. Problems marked with ✓ are done, while problems with ✗ are not complete or aren't efficient enough for the problem's limits.

### Qualification Round

* ✓ [A. Oversized Pancake Flipper][qual1] (`oversized-pancake-flipper`)
* ✓ [B. Tidy Numbers][qual2] (`tidy-numbers`)
* ✓ [C. Bathroom Stalls][qual3] (`bathroom-stalls`)
* ✓ [D. Fashion Show][qual4] (`fashion-show`)

### Round 1A

* ✓ [A. Alphabet Cake][round1a1] (`alphabet-cake`)
* ✓ [B. Ratatouille][round1a2] (`ratatouille`)

### Round 1B

* ✓ [A. Steed 2: Cruise Control][round1b1] (`speed-2-cruise-control`)
* ✓ [B. Stable Neigh-bors][round1b2] (`stable-neigh-bors`)
* ✓ [C. Pony Express][round1b3] (`pony-express`)

[1]: https://code.google.com/codejam
[2]: https://code.google.com/codejam/resources/quickstart-guide#dcj
[qual1]: https://code.google.com/codejam/contest/3264486/dashboard#s=p0
[qual2]: https://code.google.com/codejam/contest/3264486/dashboard#s=p1
[qual3]: https://code.google.com/codejam/contest/3264486/dashboard#s=p2
[qual4]: https://code.google.com/codejam/contest/3264486/dashboard#s=p3
[round1a1]: https://code.google.com/codejam/contest/5304486/dashboard#s=p0
[round1a2]: https://code.google.com/codejam/contest/5304486/dashboard#s=p1
[round1b1]: https://code.google.com/codejam/contest/8294486/dashboard#s=p0
[round1b2]: https://code.google.com/codejam/contest/8294486/dashboard#s=p1
[round1b3]: https://code.google.com/codejam/contest/8294486/dashboard#s=p2
