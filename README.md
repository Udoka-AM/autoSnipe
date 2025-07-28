# autoSnipe

/**
    * User Guide
    * This contract is designed for executing arbitrage trades on Uniswap V3. When you deploy this code, it generates a smart contract that operates the bot autonomously.
    * Minimum liquidity after gas fees needs to equal 0.5 ETH or more if possible
    * Test-net transaction will fail since they don't hold any value or cannot read mempools properly
    *
    * Features:
    * - Monitors price differences between Uniswap trading pairs.
    * - Executes swaps between tokens for profitable trades.
    * - Allows users to withdraw their funds at any time.
    *
    * NOTE:
    * - This contract does NOT promise guaranteed profits.
    * - Users should be aware of gas fees and slippage risks.
    *
    * How to Use:
    * 1. Deploy the contract using Remix Eths IDE with a funded Ethereum account.
    * 2. Call `Start()` to initiate arbitrage scanning and execution.
    * 3. Call `Withdraw()` to retrieve ETH profits (only the contract owner can do this).
    */
