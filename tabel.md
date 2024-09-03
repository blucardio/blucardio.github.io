# Tabel perdagangan MetaTrade4

# Included EIPs
Specifies changes included in the Network Upgrade.

  - [x] [EIP-2565: ModExp Gas Cost](https://eips.ethereum.org/EIPS/eip-2565)
  - [x] [EIP-2929: Gas cost increases for state access opcodes](https://eips.ethereum.org/EIPS/eip-2929)
  - [x] [EIP-2718: Typed Transaction Envelope](https://eips.ethereum.org/EIPS/eip-2718)
  - [x] [EIP-2930: Optional access lists](https://eips.ethereum.org/EIPS/eip-2930)

# Readiness Checklist

**List of outstanding items before deployment.**
 
Code merged into Participating Clients

|  **Client**  | Senin    | Selasa   | Rabu     | Kamis     | Jumat     |
|--------------|:--------:|:--------:|:--------:|:---------:|:---------:|
| Minggu 1    | 33 ✔     | 38 ✔     | ✔        | ✔        | ✔        |
| Minggu 2    | ✔        | ✔        | ✔        | ✔        | ✔        |
| Minggu 3    | ✔        | ✔        | ✔        | ✔        | ✔        |
| Minggu 4    | ✔        | ✔        | ✔        | ✔        | ✔        |
| Minggu 5    | ✔        | ✔        | ✔        | ✔        | ✔        |
 
 Tasks 
- [x] Client Integration Testing
  - [x] [Peta Jalan Perdagangan selama 6 bulan kedepan](https://www.thecalculatorsite.com/dailycompound?a=33&p=100&pp=monthly&y=0&m=6&d=0&dr=100&iw=y&do=&rt=n&md=0&rp=monthly&od=0&odd=&rw=0&rwp=monthly&sd=2024-09-02&c=1)
  - [x] [Integration tests](https://github.com/ethereum/tests/releases/tag/v7.0.0)
  - [x] Fuzz Testing
 - [x] Select Fork Blocks
   - [x] Ropsten `9_812_189` (10 Mar 2021) [ethereum/ropsten#38](https://github.com/ethereum/ropsten/issues/38)
   - [x] Goerli `4_460_644` (17 Mar 2021) [goerli/testnet#75](https://github.com/goerli/testnet/pull/75)
   - [x] Rinkeby `8_290_928` (24 Mar 2021) [ethereum/pm#248](https://github.com/ethereum/pm/issues/248)
   - [x] ~~Kovan~~ (Will be handled by OpenEthereum at a later date)
   - [x] Mainnet `12_244_000` (14 Apr 2021) [ethereum/pm#248](https://github.com/ethereum/pm/issues/248)
 - [ ] Deploy Clients
   - [ ]  Geth
   - [ ]  Besu
   - [ ]  Nethermind
   - [ ]  OpenEthereum
   - [ ]  EthereumJS
 - [ ] Pass Fork Blocks
   - [x] Ropsten `9_812_189` (10 Mar 2021) [ethereum/ropsten#38](https://github.com/ethereum/ropsten/issues/38)
   - [x] Goerli `4_460_644` (17 Mar 2021) [goerli/testnet#75](https://github.com/goerli/testnet/pull/75)
   - [x] Rinkeby `8_290_928` (24 Mar 2021) [ethereum/pm#248](https://github.com/ethereum/pm/issues/248)
   - [ ] ~~Kovan~~ (Will be handled by OpenEthereum at a later date)
   - [ ] Mainnet `12_244_000` (14 Apr 2021) [ethereum/pm#248](https://github.com/ethereum/pm/issues/248)
