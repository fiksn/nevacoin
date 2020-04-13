NEVACOIN
======

Nevacoin is a proof-of-stake cryptocurrency with a focus on high performance, longevity and adoption services.

Nevacoin is one of the first cryptocurrencies to use the Blake2s hashing algorithm. Blake2s is a high speed optimized cryptographic hashing algorithm used for proof-of-work and proof-of-stake hashes in Nevacoin for performance with low load. This makes Nevacoin ideally suited for dedicated staking devices and low-power/low-spec systems.

Originally dependent on the "libb2" library version of the Blake2s reference distribution, the blake2s reference implementation has now been directly baked in for ease of compilation across platforms.  Users no longer need to download and install libb2 separately.

If you are technical and you wish to compile libb2 specifically for your platform you may still do so (the configure script will auto-detect and enable special CPU features), you can modify your .pro or daemon makefile.* to remove the blake2 source and object file references, add -lb2 to your LIBS and paths to the includes and library (refer to the old commits).

Nevacoin will feature a number of innovative solutions devised to foster the growth of the ecosystem.

SPECIFICATIONS
--------------
Type:                   PoW/Pos2.0 hybrid

PoW algorithm:          Blake2s

Difficulty retarget:    Every block

Block time:             91 seconds

Block reward:           5 NEVA  (both PoW and PoS have static rewards)

Coinbase maturity:      25 blocks

Block reward halving:   every 2628000 blocks

Last PoW block:         5256000

PoS start:              from the first block

Minimum PoS age:        4 hours

Maximum PoS age:        no max (PoS 2.0)

Max coins:              26280000 NEVAs

Network info:

P2P port: 7391
RPC port: 3791

Testnet P2P port: 17391
Testnet RPC port: 13791

NevaCoin blockchain snapshots/chain states/bootstrap.dat (pCloud: http://pc.cd/jjo )

Responsible disclosure and security contact: security@nevacoin.net

Exchanges and listing contact (digital currency exchange representatives should take note Neva is an open source network with no premine/instamine or any type of crowdfunding and no listing fee budget is awailable): listings@nevacoin.net

Developers contact: dev@nevacoin.net

Website: https://nevacoin.net

Forum: https://bitcointalk.org/index.php?topic=1388222

Facebook: https://www.facebook.com/nevacoin/

Twitter: https://twitter.com/nevacoin

Telegram: https://t.me/neva_coin

Reddit: https://www.reddit.com/r/BlockmasterSi

## Support development 

- Bitcoin (BTC): 3Dho3s7SchiGuq27r37ZLodf8CSba7tX1d
- Dynamic Trading Rights (DTR) : 0x1823FfcE4C3B78F9641202cC3996bF717B483F1d
- Ethereum (ETH): 0x1823FfcE4C3B78F9641202cC3996bF717B483F1d
- Litecoin (LTC): MRWtV5V9jtNBWHvnibJ8pHtgyLdFdEv9Ez
- Bitcoin Cash (BCH): bitcoincash:qq6d23evqsgzlqarmnurugvgm4z7u5f5ggdwez6ml2
- GoCrypto (GOC): simpleledger:qr6j9rtq2fpm2q4lp3jr2dnykd6vas8sscjdgq8zez
- Monero (XMR): 4GTDkmbNL8mHBYGV4WHqa9Df63PM6PGWWbrdz6bKB5CjMbgcCRitGFK7fy9zZi6dgfgofHqeRoJGjcJ2LMwST4JH55kk42PwWELGbcXXYV
- Ripple (XRP): rPkitTzAi3KahtGAbdCuq3XxZtDjRCG3U8 tag: 3910586522
- DigiByte (DGB): D7hdrJ25ut3ew2DS1TWMX2WW4TGrvwfJXL
- Dogecoin (DOGE): DS8a89ocpTRKZAvaZZMdz7CWw9rK5moqvy
- Stellar Lumens (XLM): GC62AZDYMGBGPS3MQ5QPTNRNPDRK6F32JAFHTJUBZ4GOSFXASULPKYHG memo:64c40ee2aac9d51b
- Cardano ADA (ADA): DdzFFzCqrht8tWQz2EPwobGccCE3r99kjEzdRhd89oCcP4wTuBLc94sFXuN1zUP8xdag9nkK3uxK8kpKY8sTGXsNh7qMSewB5aPVFRRQ
- Tron (TRX): TUaMUjHDWWY5YyptBgG56ZMXcPwi7u357o
- Tezos (XTZ): tz1NugV7B6eJAVnH6TZseuzB14gmL4PULGzx
- Tether USD (USDT): 0x1823FfcE4C3B78F9641202cC3996bF717B483F1d
- Stasis EUR (EURS): 0x1823FfcE4C3B78F9641202cC3996bF717B483F1d
- USD Coin (USDC): 0x1823FfcE4C3B78F9641202cC3996bF717B483F1d
- TrueUSD (TUSD): 0x1823FfcE4C3B78F9641202cC3996bF717B483F1d
- Paxos Standard Token (PAX): 0x1823FfcE4C3B78F9641202cC3996bF717B483F1d
- Dai (DAI): 0x1823FfcE4C3B78F9641202cC3996bF717B483F1d
- Gemini Dollar (GUSD): 0x1823FfcE4C3B78F9641202cC3996bF717B483F1d
- Binance Coin (BNB): 0x1823FfcE4C3B78F9641202cC3996bF717B483F1d
- SunContract (SNC): 0x1823FfcE4C3B78F9641202cC3996bF717B483F1d
- 0xcert (ZXC): 0x1823FfcE4C3B78F9641202cC3996bF717B483F1d
- Blockestate (BIT): 0x1823FfcE4C3B78F9641202cC3996bF717B483F1d
- Digital Assets Power Play (DPP): 0x1823FfcE4C3B78F9641202cC3996bF717B483F1d
- Viberate (VIB): 0x1823FfcE4C3B78F9641202cC3996bF717B483F1d
- CargoX (CXO): 0x1823FfcE4C3B78F9641202cC3996bF717B483F1d
- Xaurum (XAUR): 0x1823FfcE4C3B78F9641202cC3996bF717B483F1d
- Basic Attention Token (BAT): 0x1823FfcE4C3B78F9641202cC3996bF717B483F1d

