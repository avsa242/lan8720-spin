# lan8720-spin
--------------

This is a P2X8C4M64P/Propeller 2 driver object for the LAN8720 Ethernet PHY

**IMPORTANT**: This software is meant to be used with the ~~[spin-standard-library](https://github.com/avsa242/spin-standard-library) (P8X32A) or~~ [p2-spin-standard-library](https://github.com/avsa242/p2-spin-standard-library) (P2X8C4M64P). Please install the applicable library first before attempting to use this code, otherwise you will be missing several files required to build the project.

## Salient Features

* TBD

## Requirements

P2/SPIN2:
* p2-spin-standard-library
* network-spin

## Compiler Compatibility

| Processor | Language | Compiler               | Backend     | Status                |
|-----------|----------|------------------------|-------------|-----------------------|
| P1	    | SPIN1    | FlexSpin (5.9.25-beta)	| Bytecode    | Not yet implemented   |
| P1	    | SPIN1    | FlexSpin (5.9.25-beta) | Native code | Not yet implemented   |
| P1        | SPIN1    | OpenSpin (1.00.81)     | Bytecode    | Not yet implemented   |
| P2	    | SPIN2    | FlexSpin (5.9.25-beta) | NuCode      | FTBFS                 |
| P2        | SPIN2    | FlexSpin (5.9.25-beta) | Native code | OK                    |
| P1        | SPIN1    | Brad's Spin Tool (any) | Bytecode    | Unsupported           |
| P1, P2    | SPIN1, 2 | Propeller Tool (any)   | Bytecode    | Unsupported           |
| P1, P2    | SPIN1, 2 | PNut (any)             | Bytecode    | Unsupported           |

## Limitations

* Very early in development - may malfunction, or outright fail to build
* No spin1/P1 support (future plans undecided)

