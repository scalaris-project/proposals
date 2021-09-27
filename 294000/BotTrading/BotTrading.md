## Name: BotTrading

## Link: https://github.com/walkjivefly/proposals/blob/master/294000/BotTrading/BotTrading.md

## Owner: walkjivefly

## Amount: 30000 SCA

## Hash: xxxxx

## Previous Work: 
* https://github.com/walkjivefly
* https://github.com/scalaris-project/proposals/tree/master/84000/Platform-Monitor
* https://github.com/scalaris-project/proposals/tree/master/210000/Platform-Monitor-02

## Overview: 
I propose to deploy some test trading bots on the Scalaris network to generate trades on several pairs of coins. The purpose is to test the bots, exercise the servicenode network, and create some small volume on the exchange. A secondary function is to encourage servicenode creation and operation since the (taker) fees paid by the bots will be distributed across all eligible nodes (ie: those running the wallets of the pairs which are traded).

In this first bot trading proposal the bots will operate only on ScalarisDX and only trade with other ScalarisDX users (primarily themselves). The coins used will be those with the quickest block times and smallest on-chain fees (since the on-chain fees are unrecoverable, real, expenses of operating the bots).

Future proposals may be made to extend the functionality to include CEX order book mirroring or other advanced features.