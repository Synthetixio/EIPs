---
sccp: 381
network: Base
title: Decrease OI Caps on the FTM Market to zero
author: Kaleb (@kaleb-keny)
status: Implemented
proposal: >-
 https://snapshot.org/#/snxgov.eth/proposal/0x84ca27a9fe1d27bf14c6c9975cf4a7c4d13b1d4a93e33a2015361090bc5a3ba6
type: Governance
---

## Simple Summary

This SCCP proposes to lower the oi caps on the FTM market to zero.

## Abstract

The cap can be lowered by reducing the `maxMarketValue` and `maxMarketSize` to zero.

## Motivation

Given the token swap and rebrand to [sonic](https://www.binance.com/en/support/announcement/binance-will-support-the-fantom-ftm-token-swap-and-rebranding-to-sonic-s-aec6fcbc84b749eeab6690e6bcac2f3d) and as oracle providers switch over to new feeds, it is necessary to deprecate these markets by switching the caps to zero (close only).

## Copyright

Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
