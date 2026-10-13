# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T06:45:33Z**
- feed_generated_utc: 2026-10-13T06:45:36+00:00
- source_sha256: `be5d6be04f802f6a9da3dfc583f66e899e4ce17f73e93edfeb78c70209d32d6d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T06:45+00:00, close=83690.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-13T06:00+00:00, close=83646.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T04:00+00:00, close=83297.9, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOS_USDT|0.229500|-20.72|7.74|-21.93|9314003|4.36|
|W_USDT|0.019354|-19.55|36.84|-20.76|34518266|1.55|
|ZRO_USDT|2.091600|-7.49|2.24|-8.70|29665651|0.48|
|LIT_USDT|3.414700|-5.80|-10.18|-7.01|10641839|0.29|
|NEAR_USDT|5.291000|-4.64|5.35|-5.85|278356791|1.89|
|PUMPFUN_USDT|0.005084|-4.23|-19.74|-5.44|31504674|1.97|
|RLC_USDT|0.951900|-3.71|73.70|-4.92|6925648|1.05|
|ICP_USDT|3.189000|-3.21|-7.99|-4.42|17186527|3.13|
|STRK_USDT|0.087860|-3.09|68.60|-4.30|64287691|1.14|
|HBAR_USDT|0.088200|-2.54|-12.41|-3.75|22226278|1.13|
|PONS_USDT|0.290400|-1.45|-24.27|-2.66|6309058|3.44|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOS_USDT|0.229500|0.227700|0.229500|1.15|N|Y/Y|Y/N|N|N|
|HBAR_USDT|0.088200|0.087540|0.088200|0.26|N|Y/Y|Y/Y|N|N|
|ICP_USDT|3.189000|3.155000|3.189000|1.02|N|Y/Y|Y/Y|N|N|
|LIT_USDT|3.414700|3.430300|3.414900|1.38|Y|Y/Y|Y/Y|N|Y|
|NEAR_USDT|5.291000|5.280000|5.291000|0.73|N|Y/Y|Y/Y|N|N|
|PONS_USDT|0.290400|0.282200|0.290400|0.42|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.005084|0.005054|0.005084|0.46|N|Y/Y|Y/Y|N|N|
|RLC_USDT|0.951900|0.945000|0.951500|1.05|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.087860|0.085720|0.087860|0.46|N|Y/Y|Y/Y|N|N|
|W_USDT|0.019354|0.019044|0.019372|2.14|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|2.091600|2.087100|2.091600|1.15|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOS_USDT: quote_utc=2026-10-13T06:45:02+00:00, last15m_closed_end=2026-10-13T06:45+00:00, prior8high=0.251000, depth_time=2026-10-13T06:45:05+00:00, book20_bid_proxy_usdt=100648, book20_ask_proxy_usdt=111390, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-20.72%, turnover=9314003. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-13T06:45:03+00:00, last15m_closed_end=2026-10-13T06:45+00:00, prior8high=0.088580, depth_time=2026-10-13T06:45:30+00:00, book20_bid_proxy_usdt=387716, book20_ask_proxy_usdt=777284, funding_indicative=-0.000009, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.54%, turnover=22226278. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-13T06:45:03+00:00, last15m_closed_end=2026-10-13T06:45+00:00, prior8high=3.205000, depth_time=2026-10-13T06:45:23+00:00, book20_bid_proxy_usdt=662970, book20_ask_proxy_usdt=727626, funding_indicative=-0.000022, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.21%, turnover=17186527. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-13T06:45:03+00:00, last15m_closed_end=2026-10-13T06:45+00:00, prior8high=3.476600, depth_time=2026-10-13T06:45:14+00:00, book20_bid_proxy_usdt=48402, book20_ask_proxy_usdt=32947, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.80%, turnover=10641839. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-13T06:45:02+00:00, last15m_closed_end=2026-10-13T06:45+00:00, prior8high=5.363000, depth_time=2026-10-13T06:45:18+00:00, book20_bid_proxy_usdt=3148083, book20_ask_proxy_usdt=3585947, funding_indicative=-0.000088, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.64%, turnover=278356791. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PONS_USDT: quote_utc=2026-10-13T06:45:03+00:00, last15m_closed_end=2026-10-13T06:45+00:00, prior8high=0.291800, depth_time=2026-10-13T06:45:32+00:00, book20_bid_proxy_usdt=227306, book20_ask_proxy_usdt=212633, funding_indicative=0.000081, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.45%, turnover=6309058. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-13T06:45:03+00:00, last15m_closed_end=2026-10-13T06:45+00:00, prior8high=0.005119, depth_time=2026-10-13T06:45:20+00:00, book20_bid_proxy_usdt=1461858, book20_ask_proxy_usdt=1356061, funding_indicative=0.000031, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.23%, turnover=31504674. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T06:45:03+00:00, last15m_closed_end=2026-10-13T06:45+00:00, prior8high=0.964300, depth_time=2026-10-13T06:45:23+00:00, book20_bid_proxy_usdt=46868, book20_ask_proxy_usdt=59734, funding_indicative=-0.000610, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.71%, turnover=6925648. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T06:45:02+00:00, last15m_closed_end=2026-10-13T06:45+00:00, prior8high=0.089670, depth_time=2026-10-13T06:45:28+00:00, book20_bid_proxy_usdt=138501, book20_ask_proxy_usdt=150478, funding_indicative=0.000023, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.09%, turnover=64287691. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-13T06:45:02+00:00, last15m_closed_end=2026-10-13T06:45+00:00, prior8high=0.019841, depth_time=2026-10-13T06:45:11+00:00, book20_bid_proxy_usdt=13576, book20_ask_proxy_usdt=31207, funding_indicative=-0.000493, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-19.55%, turnover=34518266. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-13T06:45:03+00:00, last15m_closed_end=2026-10-13T06:45+00:00, prior8high=2.149200, depth_time=2026-10-13T06:45:13+00:00, book20_bid_proxy_usdt=75586, book20_ask_proxy_usdt=34152, funding_indicative=0.000021, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.49%, turnover=29665651. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
