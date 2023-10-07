# Proveable Random Raffle Contracts

## About

This code is to create a proveably random smart contract lottery.

## What we want it to do?

1. Users can enter by paying for a ticket 
    1. The ticket fees are going to go to the winner during the draw
2. After X period of time, the lottery will automatically draw a winner
    1. And this will be done programatically
3. Using ChainLink VRF and ChainLink Automation
    1. ChainLink VRF -> Randomness (to generate a true provenly random number)
    2. ChainLink Automation -> Time based trigger