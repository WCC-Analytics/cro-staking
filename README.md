# Codex Protocol | ERC 900 Contracts
[![Build Status](https://travis-ci.org/codex-protocol/contract.erc-900.svg?branch=master)](https://travis-ci.org/codex-protocol/contract.erc-900)

## Background
For background on ERC-900 itself, view the issue in the EIP repo here: https://github.com/ethereum/EIPs/issues/900

This repo has a few different takes on staking. The main principle that these contracts follow is that staking is used as a discount mechanism using an ERC-20 token for operations on a protocol.

For example, at Codex Protocol we're using this concept so that users can stake CodexCoin (CODX) to receive discounts when creating Codex Records. See the repo here for a live example: https://github.com/codex-protocol/contract.codex-registry.

## Contracts
- ERC900.sol - ERC-900 interface
- ERC900BasicStakeContract.sol - A basic implementation of the ERC-900 interface following the principle outlined above.
