# Token Contract

**Overview:**
- ERC-20 token: DEGEN
- Symbol: DGN
- Decimals: 18
- Total Supply: Dynamic (minted by owner)

**Functions:**
1. **Minting:**
   - Owner can create and assign tokens.
   - Function: `mint(address to, uint256 amount)`

2. **Burning:**
   - Users can destroy tokens, reducing total supply.
   - Function: `burn(address from, uint256 amount)`

3. **Transferring:**
   - Transfer tokens from sender to another address.
   - Function: `transfer(address to, uint256 amount)`

4. **Redeeming:**
   - Exchange tokens for in-game items.
   - Function: `redeem(address to, uint256 amount, uint256 gameItem)`

**Usage:**
1. Deploy contract.
2. Mint initial tokens if needed.
3. Interact with contract functions.

**Important Notes:**
- Only owner can mint tokens.
- Check balances before burning or transferring.
- Minimum token balances for in-game item redemption.

**License:**
MIT License
