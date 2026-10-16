# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T18:30:42Z**
- feed_generated_utc: 2026-10-16T18:30:44+00:00
- source_sha256: `c736484ce4001e3c55829b4f37a716a7f21a99c3b4dc0af86d8dedd0e4451a29`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 18; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T18:30+00:00, close=81384, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T18:00+00:00, close=81185.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-16T16:00+00:00, close=81322.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.195100|-4.84|60.36|-4.91|22089950|2.05|
|INJ_USDT|8.559000|-4.66|23.52|-4.73|113611837|1.17|
|ZRO_USDT|2.024700|-3.64|-0.59|-3.71|15862879|0.49|
|OP_USDT|0.135530|-3.19|9.99|-3.26|14821093|0.74|
|ZEC_USDT|1152.350000|-3.00|-5.41|-3.07|1530566437|0.09|
|PYTH_USDT|0.083710|-2.97|-1.96|-3.04|5719942|2.39|
|STRK_USDT|0.071960|-2.69|-4.44|-2.76|27337950|1.39|
|APT_USDT|0.840400|-1.83|4.98|-1.90|12511096|4.76|
|TAO_USDT|275.700000|-1.75|0.37|-1.82|82539122|1.09|
|WLD_USDT|0.500400|-1.63|1.60|-1.70|92794848|4.00|
|ARB_USDT|0.191830|-1.59|6.10|-1.66|36707146|0.52|
|FARTCOIN_USDT|0.152580|-1.38|-6.60|-1.45|7565151|0.66|
|HBAR_USDT|0.083040|-1.27|-8.60|-1.34|22578855|1.20|
|AAVE_USDT|155.300000|-1.25|-8.56|-1.32|32650452|1.29|
|DOT_USDT|1.156100|-1.25|-2.68|-1.32|22485739|0.86|
|BCH_USDT|274.580000|-1.25|-0.27|-1.32|5846470|5.83|
|ENA_USDT|0.197960|-0.98|-8.17|-1.05|37829585|0.51|
|ICP_USDT|3.009000|-0.95|-0.33|-1.02|9040932|3.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|155.300000|153.780000|155.330000|1.14|N|Y/Y|Y/N|Y|N|
|APT_USDT|0.840400|0.825100|0.840400|0.81|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.191830|0.189190|0.191850|0.68|N|Y/Y|N/N|Y|N|
|BAT_USDT|0.195100|0.191460|0.195100|0.67|N|Y/N|N/N|Y|N|
|DOT_USDT|1.156100|1.134400|1.156100|0.41|N|N/N|N/N|Y|N|
|FARTCOIN_USDT|0.152580|0.150210|0.152580|0.70|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.083040|0.082050|0.083040|0.87|N|Y/Y|Y/N|Y|N|
|INJ_USDT|8.559000|8.573000|8.559000|1.08|N|Y/Y|N/N|Y|N|
|OP_USDT|0.135530|0.133270|0.135530|0.59|N|Y/Y|N/N|Y|N|
|PYTH_USDT|0.083710|0.083450|0.083710|0.24|N|Y/Y|Y/N|Y|N|
|STRK_USDT|0.071960|0.072230|0.071960|1.78|Y|Y/Y|Y/Y|Y|Y|
|TAO_USDT|275.700000|272.270000|275.820000|0.98|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.500400|0.492700|0.500300|0.89|N|Y/Y|N/N|Y|N|
|ZEC_USDT|1152.350000|1133.160000|1152.380000|0.76|N|Y/Y|Y/N|Y|N|
|ZRO_USDT|2.024700|1.975000|2.024700|0.56|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-16T18:30:00+00:00, last15m_closed_end=2026-10-16T18:30+00:00, prior8high=158.030000, depth_time=2026-10-16T18:30:39+00:00, book20_bid_proxy_usdt=281219, book20_ask_proxy_usdt=290330, funding_indicative=0.000091, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.25%, turnover=32650452. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-16T18:30:00+00:00, last15m_closed_end=2026-10-16T18:30+00:00, prior8high=0.858800, depth_time=2026-10-16T18:30:25+00:00, book20_bid_proxy_usdt=195784, book20_ask_proxy_usdt=112877, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.83%, turnover=12511096. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-16T18:30:00+00:00, last15m_closed_end=2026-10-16T18:30+00:00, prior8high=0.196000, depth_time=2026-10-16T18:30:32+00:00, book20_bid_proxy_usdt=75591, book20_ask_proxy_usdt=37696, funding_indicative=0.000038, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.59%, turnover=36707146. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-16T18:30:00+00:00, last15m_closed_end=2026-10-16T18:30+00:00, prior8high=0.205380, depth_time=2026-10-16T18:30:08+00:00, book20_bid_proxy_usdt=23950, book20_ask_proxy_usdt=30093, funding_indicative=-0.000258, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.84%, turnover=22089950. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-16T18:30:00+00:00, last15m_closed_end=2026-10-16T18:30+00:00, prior8high=1.189900, depth_time=2026-10-16T18:30:41+00:00, book20_bid_proxy_usdt=209037, book20_ask_proxy_usdt=147681, funding_indicative=0.000089, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.25%, turnover=22485739. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-16T18:30:01+00:00, last15m_closed_end=2026-10-16T18:30+00:00, prior8high=0.155460, depth_time=2026-10-16T18:30:34+00:00, book20_bid_proxy_usdt=67119, book20_ask_proxy_usdt=91714, funding_indicative=0.000050, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.38%, turnover=7565151. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-16T18:30:00+00:00, last15m_closed_end=2026-10-16T18:30+00:00, prior8high=0.084280, depth_time=2026-10-16T18:30:37+00:00, book20_bid_proxy_usdt=1421746, book20_ask_proxy_usdt=572518, funding_indicative=0.000045, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.27%, turnover=22578855. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-16T18:30:00+00:00, last15m_closed_end=2026-10-16T18:30+00:00, prior8high=9.045000, depth_time=2026-10-16T18:30:10+00:00, book20_bid_proxy_usdt=297052, book20_ask_proxy_usdt=225297, funding_indicative=-0.000032, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.66%, turnover=113611837. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-16T18:30:00+00:00, last15m_closed_end=2026-10-16T18:30+00:00, prior8high=0.140210, depth_time=2026-10-16T18:30:15+00:00, book20_bid_proxy_usdt=36646, book20_ask_proxy_usdt=45302, funding_indicative=0.000055, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.19%, turnover=14821093. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-16T18:30:00+00:00, last15m_closed_end=2026-10-16T18:30+00:00, prior8high=0.087250, depth_time=2026-10-16T18:30:20+00:00, book20_bid_proxy_usdt=221277, book20_ask_proxy_usdt=90256, funding_indicative=-0.000055, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.97%, turnover=5719942. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T18:30:00+00:00, last15m_closed_end=2026-10-16T18:30+00:00, prior8high=0.074470, depth_time=2026-10-16T18:30:23+00:00, book20_bid_proxy_usdt=705541, book20_ask_proxy_usdt=283803, funding_indicative=0.000050, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.69%, turnover=27337950. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-16T18:30:00+00:00, last15m_closed_end=2026-10-16T18:30+00:00, prior8high=282.080000, depth_time=2026-10-16T18:30:27+00:00, book20_bid_proxy_usdt=83453, book20_ask_proxy_usdt=38265, funding_indicative=0.000050, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.75%, turnover=82539122. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-16T18:30:00+00:00, last15m_closed_end=2026-10-16T18:30+00:00, prior8high=0.516400, depth_time=2026-10-16T18:30:29+00:00, book20_bid_proxy_usdt=1602566, book20_ask_proxy_usdt=1421313, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.63%, turnover=92794848. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-16T18:30:00+00:00, last15m_closed_end=2026-10-16T18:30+00:00, prior8high=1189.000000, depth_time=2026-10-16T18:30:17+00:00, book20_bid_proxy_usdt=735434, book20_ask_proxy_usdt=93673, funding_indicative=0.000039, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.00%, turnover=1530566437. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-16T18:30:00+00:00, last15m_closed_end=2026-10-16T18:30+00:00, prior8high=2.125800, depth_time=2026-10-16T18:30:13+00:00, book20_bid_proxy_usdt=40346, book20_ask_proxy_usdt=26012, funding_indicative=0.000050, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.64%, turnover=15862879. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
