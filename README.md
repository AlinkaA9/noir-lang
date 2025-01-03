<img align="right" width="150" height="150" top="100" src="./assets/readme.png">

# Solidity Circuits

Write zero knowledge proofs in solidity.

Creating an alternative frontend for noir / nargo, developers can write, prove and verify zk circuits that are written in solidity. 

That's it.

## What is in this repo?

This repo contains a `nargo` workspace where the files are written in solidity. Each example demonstrates a different type of circuit, use the run instructions below to test each of them!

### How to run?

1. Make sure you have `noirup` installed - instructions below. 
2. Go and clone this [branch of noir](https://github.com/noir-lang/noir/tree/md/solidity-circuits)
3. Run `noirup -p .` to replace your local nargo binary with the one with solidity support
4. Run `nargo check` to generate prover toml etc
5. Enter the values you want in your generate your proof with in `Prover.toml`
6. `nargo compile`
7. `nargo prove`
8. `nargo verify`


### First time with Noir?

See the official Noir installation [instructions](https://noir-lang.org/getting_started/nargo_installation).

Then, install the [Noir](https://github.com/noir-lang/noir) toolchain installer (`noirup`) with:

```bash
curl -L https://raw.githubusercontent.com/noir-lang/noirup/main/install | bash
```

Now you've installed the `noirup` binary,
Follow the instructions above to install the solidity circuits branch.
