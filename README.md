Software engineer in Bishkek, Kyrgyzstan. Member of Technical Staff at CloudX. Before that I built production LLM agents at KyoHealth and data pipelines at Thomson Reuters.

Outside work I write systems and simulation code, mostly in Rust:

- [chainpulse](https://github.com/kubanemil/chainpulse): EVM event indexer that stays correct through chain reorgs. The integration tests force reorgs on a local chain and check the database against the canonical one.
- [physicall](https://github.com/kubanemil/physicall): GPU physics engine in Rust and WebGPU, with XPBD cloth and ropes and N-body gravity. A CPU reference solver checks every GPU kernel. [Live demo](https://kubanemil.github.io/physicall/).
- [legaldocs](https://github.com/kubanemil/legaldocs): document processing where the server that stores your files cannot read them. The client checks the enclave's attestation before sending anything, and results come back sealed to the client's own key.
- [LimeRocket](https://github.com/kubanemil/LimeRocket): sizes a small liquid-propellant rocket from one YAML file, from engine chemistry to nozzle shape, tank blowdown and flight. Its CEA results match NASA's reference outputs within 0.001%.
- [culling_game_onchain](https://github.com/kubanemil/culling_game_onchain): card duels on Solana where no admin picks the winner. Both players commit to a card and a secret, and the reveal decides. Also a token sale with an allowlist and vesting, and governance that can't be bypassed. Every known attack has its own test.
- [solana-poh](https://github.com/kubanemil/solana-poh): Solana's Proof of History in Rust with Python bindings. Verifies a full mainnet slot in 26 ms on 4 cores.
- [physlib](https://github.com/leanprover-community/physlib/pulls?q=author%3Akubanemil): formalizing quantum mechanics results in Lean 4.

Python, TypeScript and Rust. Postgres, AWS, Solana.

emil3toktobekov@gmail.com
