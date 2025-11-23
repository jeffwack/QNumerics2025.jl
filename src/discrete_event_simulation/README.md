# qnumerics.org session on discrete-event simulation (using ConcurrentSim.jl)

## Content

1. `tutorial.jl`: An introduction to ConcurrentSim.jl.
2. `entanglement_switch.jl`: A more complicated example, modeling an entanglement switch. It has some problems - can you fix that?

Notebooks (and markdown renders) of these files were generated with `Literate.jl`.
These can be found in the `rendered` folder.

## Setting up your environment

We suggest using:

- Julia installed through the `juliaup` version multiplexer/manager.
- VS Code (or compatible) IDE in which this folder is opened as a root workspace folder.
- The Julia plugin for VS Code.

Make sure you are comfortable with the "Command Palette" in VS Code,
and have the Julia REPL launched from it.
That provides a better, more integrated user experience,
than simply launching Julia from the terminal.

Do not run entire files, rather familiarize yourself with how to interactively launch
only small snippets of code in the REPL.

You can run the code (particularly the tutorial) as a Jupyter notebook using the .ipynb files in the `rendered` folder.
This can also be done using VSCode.

## What are all these other files?

- `Project.toml` lists all the dependencies for this environment. Make sure to `activate` it and `instantiate` it.
- `Manifest.toml` would exist only if you have instantiated the environment. It lists the exact versions of each installed library and implicit dependency, providing complete reproducibility (unlike just a list of library names in `Project.toml`).
- `.gitignore` is there to tell `git` that we do not care to track certain files.
