# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T03:15:30Z**
- feed_generated_utc: 2026-11-01T03:15:33+00:00
- source_sha256: `d107fea3ae81ee895288f0399b9bc51aff8d5e44bf385af1b38c8422c950ad0c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T03:15+00:00, close=77756.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-01T03:00+00:00, close=77690, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T00:00+00:00, close=77522.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.228080|-22.98|35.82|-23.23|29844948|1.31|
|AKE_USDT|0.008873|-20.33|-69.64|-20.58|11547893|2.26|
|BLESS_USDT|0.009318|-11.79|14.85|-12.04|7158138|2.15|
|ENA_USDT|0.187720|-3.24|0.49|-3.49|44392171|0.53|
|ZEC_USDT|1246.000000|-3.00|8.80|-3.25|974058548|0.08|
|BTW_USDT|1.102300|-1.74|-36.69|-1.99|5252424|3.63|
|XLM_USDT|0.168900|-1.65|0.29|-1.90|19910657|0.59|
|FARTCOIN_USDT|0.120490|-1.22|-1.22|-1.47|6329016|0.83|
|TRX_USDT|0.309680|-0.84|-5.85|-1.09|10901924|0.32|
|ONDO_USDT|0.409200|-0.77|1.94|-1.02|23424192|2.44|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.008873|0.008372|0.008858|2.77|N|Y/Y|Y/Y|Y|N|
|BLESS_USDT|0.009318|0.009219|0.009318|0.87|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.102300|1.057700|1.102300|1.34|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.187720|0.186020|0.187720|0.79|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.120490|0.119750|0.120490|0.38|N|Y/Y|Y/Y|Y|N|
|LSK_USDT|0.228080|0.227710|0.228070|0.74|N|Y/Y|N/N|Y|N|
|ONDO_USDT|0.409200|0.407900|0.409200|0.47|N|Y/N|N/N|Y|N|
|TRX_USDT|0.309680|0.305880|0.309680|0.12|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.168900|0.168390|0.168900|0.59|N|Y/Y|N/N|Y|N|
|ZEC_USDT|1246.000000|1238.980000|1246.000000|0.53|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-01T03:15:00+00:00, last15m_closed_end=2026-11-01T03:15+00:00, prior8high=0.011523, depth_time=2026-11-01T03:15:10+00:00, book20_bid_proxy_usdt=6282, book20_ask_proxy_usdt=8539, funding_indicative=-0.002443, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-20.33%, turnover=11547893. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-11-01T03:15:01+00:00, last15m_closed_end=2026-11-01T03:15+00:00, prior8high=0.009563, depth_time=2026-11-01T03:15:12+00:00, book20_bid_proxy_usdt=10503, book20_ask_proxy_usdt=18073, funding_indicative=0.000050, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-11.79%, turnover=7158138. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-01T03:15:00+00:00, last15m_closed_end=2026-11-01T03:15+00:00, prior8high=1.139700, depth_time=2026-11-01T03:15:19+00:00, book20_bid_proxy_usdt=16031, book20_ask_proxy_usdt=13296, funding_indicative=-0.000274, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.74%, turnover=5252424. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-01T03:15:00+00:00, last15m_closed_end=2026-11-01T03:15+00:00, prior8high=0.190060, depth_time=2026-11-01T03:15:15+00:00, book20_bid_proxy_usdt=183638, book20_ask_proxy_usdt=123066, funding_indicative=0.000050, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.24%, turnover=44392171. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-01T03:15:01+00:00, last15m_closed_end=2026-11-01T03:15+00:00, prior8high=0.120890, depth_time=2026-11-01T03:15:24+00:00, book20_bid_proxy_usdt=93305, book20_ask_proxy_usdt=109541, funding_indicative=0.000050, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.22%, turnover=6329016. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-11-01T03:15:00+00:00, last15m_closed_end=2026-11-01T03:15+00:00, prior8high=0.243060, depth_time=2026-11-01T03:15:08+00:00, book20_bid_proxy_usdt=9592, book20_ask_proxy_usdt=12681, funding_indicative=-0.000966, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-22.98%, turnover=29844948. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-01T03:15:00+00:00, last15m_closed_end=2026-11-01T03:15+00:00, prior8high=0.412300, depth_time=2026-11-01T03:15:30+00:00, book20_bid_proxy_usdt=1903946, book20_ask_proxy_usdt=2388811, funding_indicative=0.000050, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.77%, turnover=23424192. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-11-01T03:15:01+00:00, last15m_closed_end=2026-11-01T03:15+00:00, prior8high=0.309960, depth_time=2026-11-01T03:15:26+00:00, book20_bid_proxy_usdt=137514, book20_ask_proxy_usdt=143001, funding_indicative=-0.001367, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.84%, turnover=10901924. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-01T03:15:01+00:00, last15m_closed_end=2026-11-01T03:15+00:00, prior8high=0.169340, depth_time=2026-11-01T03:15:21+00:00, book20_bid_proxy_usdt=174233, book20_ask_proxy_usdt=183640, funding_indicative=-0.000012, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.65%, turnover=19910657. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-01T03:15:00+00:00, last15m_closed_end=2026-11-01T03:15+00:00, prior8high=1263.460000, depth_time=2026-11-01T03:15:17+00:00, book20_bid_proxy_usdt=223176, book20_ask_proxy_usdt=385917, funding_indicative=-0.000101, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.00%, turnover=974058548. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
