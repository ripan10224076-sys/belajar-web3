# Modul 2: Apa itu Smart Contract? 📜

Setelah paham dasar Blockchain, sekarang kita masuk ke "Otak" dari Web3, yaitu **Smart Contract**.

### Definisi Sederhana
Smart Contract adalah program komputer yang berjalan di atas Blockchain. Bayangkan seperti **Mesin Minuman Otomatis (Vending Machine)**:
* Kamu masukkan uang (Input).
* Mesin mengecek apakah uang cukup (Logika).
* Mesin mengeluarkan minuman secara otomatis (Output).
* **Tanpa perlu pelayan/orang tengah.**

### Bahasa Pemrograman: Solidity
Bahasa paling populer untuk membuat Smart Contract di Ethereum adalah **Solidity**.

### Contoh Kode Dasar:
```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

contract HaloWeb3 {
    string public pesan = "Halo CampCoding!";
}
