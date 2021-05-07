# Adversary Emulation Planner Data

This repository contains data used by [Adversary Emulation Planner](https://github.com/mnemonic-no/aep).

This tool can be used to automatically build an ordered set of attack stages
with [MITRE ATT&CK](https://attack.mitre.org/) techniques executed during each stage.

The output is a set of attack stages that show all possible techniques that an
adversary might execute during each stage.

To decide when the different techniques are to be found in such a set, `promises` are used as access tokens for execution of techniques. Each technique defines the set of promises required to execute it (think pre-conditions) and the set of promises it provides upon execution (think post-conditions).

## Installation

Clone this repository:

```bash
git clone https://github.com/mnemonic-no/aep-data
```

Install [Adversary Emulation Planner](https://github.com/mnemonic-no/aep) with pip:

```bash
pip install aep
```

See [Adversary Emulation Planner](https://github.com/mnemonic-no/aep) for detailed usage of the tools.
