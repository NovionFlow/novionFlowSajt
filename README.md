# novionflow.rs

Statički sajt za NOVION FLOW (GitHub Pages, domen `novionflow.rs`). Bez build koraka, bez JavaScript-a,
bez spoljnih resursa (fontovi su lokalni); jedini spoljni servis je Web3Forms za formu zahteva licence.

- `index.html` — početna, `privatnost.html` — politika privatnosti, `hvala.html` — posle slanja forme, `assets/` — stil, logo, fontovi.
- Pre objave: zameniti sve elemente sa klasom `dopuniti` (podaci firme, kontakt, cene).
- Forma (`#kontakt` u `index.html`): `access_key` sa web3forms.com (javni ključ, vezan za novionflow@gmail.com); posle slanja
  Web3Forms preusmerava na `https://novionflow.rs/hvala.html`.
- Download: installer se objavljuje kao GitHub Release; broj verzije i veličina u `index.html` se tada ažuriraju.
- `licenca.novionflow.rs` je licencni server i nema veze sa ovim repozitorijumom.
