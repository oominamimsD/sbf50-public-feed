# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T01:30:36Z**
- feed_generated_utc: 2026-11-01T01:30:38+00:00
- source_sha256: `2f123069898c9a9a3aa4e81b7c5b2151ad1c0875e80d1e43b03ce0a46250fdab`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T01:30+00:00, close=77610.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-01T01:00+00:00, close=77641.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T00:00+00:00, close=77522.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.239500|-19.13|42.62|-19.21|29618811|0.83|
|BLESS_USDT|0.009377|-11.23|15.57|-11.31|7739315|3.20|
|Q_USDT|0.030360|-5.36|-61.53|-5.44|9950535|6.59|
|BTW_USDT|1.066800|-4.91|-38.73|-4.99|5407978|0.94|
|TIA_USDT|0.472800|-3.52|-10.06|-3.60|8568663|2.12|
|ENA_USDT|0.188660|-2.75|1.00|-2.83|44174195|0.53|
|ZEC_USDT|1256.440000|-2.18|9.71|-2.26|1011952391|0.08|
|XLM_USDT|0.168950|-1.62|0.32|-1.70|20720982|0.59|
|FET_USDT|0.160800|-1.53|-6.67|-1.61|5458760|6.22|
|TRX_USDT|0.307720|-1.47|-6.44|-1.55|11139755|0.33|
|FARTCOIN_USDT|0.120240|-1.43|-1.42|-1.51|6418734|3.33|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.009377|0.009328|0.009383|1.36|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.066800|1.049300|1.066800|0.99|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.188660|0.188460|0.188690|0.40|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.120240|0.119900|0.120240|0.67|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.160800|0.159200|0.160800|0.24|N|Y/Y|Y/Y|Y|N|
|LSK_USDT|0.239500|0.233000|0.238800|1.09|N|Y/Y|N/N|Y|N|
|Q_USDT|0.030360|0.030300|0.030390|1.21|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.472800|0.472200|0.472800|1.24|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.307720|0.300770|0.308100|0.84|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.168950|0.168810|0.168960|0.56|N|Y/N|N/N|Y|N|
|ZEC_USDT|1256.440000|1243.100000|1256.130000|1.23|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-11-01T01:30:04+00:00, last15m_closed_end=2026-11-01T01:30+00:00, prior8high=0.009626, depth_time=2026-11-01T01:30:11+00:00, book20_bid_proxy_usdt=21620, book20_ask_proxy_usdt=10210, funding_indicative=0.000050, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-11.23%, turnover=7739315. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-01T01:30:04+00:00, last15m_closed_end=2026-11-01T01:30+00:00, prior8high=1.104900, depth_time=2026-11-01T01:30:17+00:00, book20_bid_proxy_usdt=32744, book20_ask_proxy_usdt=11716, funding_indicative=-0.000524, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.91%, turnover=5407978. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-01T01:30:04+00:00, last15m_closed_end=2026-11-01T01:30+00:00, prior8high=0.189790, depth_time=2026-11-01T01:30:22+00:00, book20_bid_proxy_usdt=130336, book20_ask_proxy_usdt=156435, funding_indicative=0.000037, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.75%, turnover=44174195. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-01T01:30:04+00:00, last15m_closed_end=2026-11-01T01:30+00:00, prior8high=0.120690, depth_time=2026-11-01T01:30:35+00:00, book20_bid_proxy_usdt=81710, book20_ask_proxy_usdt=71929, funding_indicative=0.000050, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.43%, turnover=6418734. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-11-01T01:30:04+00:00, last15m_closed_end=2026-11-01T01:30+00:00, prior8high=0.161000, depth_time=2026-11-01T01:30:30+00:00, book20_bid_proxy_usdt=1396741, book20_ask_proxy_usdt=982920, funding_indicative=-0.000185, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.53%, turnover=5458760. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-11-01T01:30:04+00:00, last15m_closed_end=2026-11-01T01:30+00:00, prior8high=0.253830, depth_time=2026-11-01T01:30:09+00:00, book20_bid_proxy_usdt=8562, book20_ask_proxy_usdt=8023, funding_indicative=-0.001710, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-19.13%, turnover=29618811. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-11-01T01:30:04+00:00, last15m_closed_end=2026-11-01T01:30+00:00, prior8high=0.031640, depth_time=2026-11-01T01:30:14+00:00, book20_bid_proxy_usdt=70923, book20_ask_proxy_usdt=57904, funding_indicative=-0.000985, next_funding_utc=2026-11-01T02:00:00+00:00, funding_cycle_h=1, 24h_change=-5.36%, turnover=9950535. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-01T01:30:04+00:00, last15m_closed_end=2026-11-01T01:30+00:00, prior8high=0.475500, depth_time=2026-11-01T01:30:17+00:00, book20_bid_proxy_usdt=243281, book20_ask_proxy_usdt=267496, funding_indicative=-0.000103, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.52%, turnover=8568663. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-11-01T01:30:04+00:00, last15m_closed_end=2026-11-01T01:30+00:00, prior8high=0.308430, depth_time=2026-11-01T01:30:32+00:00, book20_bid_proxy_usdt=31796, book20_ask_proxy_usdt=50310, funding_indicative=-0.001886, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.47%, turnover=11139755. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-01T01:30:04+00:00, last15m_closed_end=2026-11-01T01:30+00:00, prior8high=0.170180, depth_time=2026-11-01T01:30:26+00:00, book20_bid_proxy_usdt=204163, book20_ask_proxy_usdt=206071, funding_indicative=-0.000040, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.62%, turnover=20720982. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-01T01:30:04+00:00, last15m_closed_end=2026-11-01T01:30+00:00, prior8high=1258.610000, depth_time=2026-11-01T01:30:25+00:00, book20_bid_proxy_usdt=282256, book20_ask_proxy_usdt=142477, funding_indicative=-0.000090, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.18%, turnover=1011952391. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
