# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T06:00:27Z**
- feed_generated_utc: 2026-11-01T06:00:29+00:00
- source_sha256: `10c6d1a766d7851446dd42f2d5592d9955d64d4972a503bad47df24f6dc39b34`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T06:00+00:00, close=77875.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-01T06:00+00:00, close=77875.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T04:00+00:00, close=77753.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.241010|-18.62|43.52|-19.02|30711694|2.90|
|AKE_USDT|0.009992|-10.28|-65.81|-10.68|11516609|3.00|
|XPL_USDT|0.073260|-9.90|1.45|-10.30|5183750|1.36|
|BLESS_USDT|0.009620|-8.93|18.57|-9.33|6288251|7.27|
|ENA_USDT|0.188500|-2.84|0.91|-3.24|42596185|0.53|
|ZEC_USDT|1248.320000|-2.82|9.00|-3.22|935175903|0.08|
|NEAR_USDT|4.384000|-2.05|-0.40|-2.45|52711875|2.28|
|XLM_USDT|0.169110|-1.53|0.41|-1.93|19941898|0.59|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.009992|0.008968|0.009968|0.92|N|Y/Y|Y/Y|Y|N|
|BLESS_USDT|0.009620|0.009370|0.009594|0.38|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.188500|0.185670|0.188390|2.30|N|Y/Y|Y/Y|Y|N|
|LSK_USDT|0.241010|0.228350|0.240000|0.53|N|Y/Y|N/N|Y|N|
|NEAR_USDT|4.384000|4.363000|4.384000|0.65|N|Y/Y|N/N|Y|N|
|XLM_USDT|0.169110|0.167510|0.169110|0.68|N|Y/Y|Y/N|Y|N|
|XPL_USDT|0.073260|0.069100|0.073260|1.87|N|Y/Y|N/N|Y|N|
|ZEC_USDT|1248.320000|1238.800000|1247.890000|0.61|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-01T06:00:03+00:00, last15m_closed_end=2026-11-01T06:00+00:00, prior8high=0.010385, depth_time=2026-11-01T06:00:10+00:00, book20_bid_proxy_usdt=6086, book20_ask_proxy_usdt=3389, funding_indicative=-0.002712, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.28%, turnover=11516609. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-11-01T06:00:04+00:00, last15m_closed_end=2026-11-01T06:00+00:00, prior8high=0.009822, depth_time=2026-11-01T06:00:16+00:00, book20_bid_proxy_usdt=15854, book20_ask_proxy_usdt=12126, funding_indicative=0.000050, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.93%, turnover=6288251. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-01T06:00:03+00:00, last15m_closed_end=2026-11-01T06:00+00:00, prior8high=0.188950, depth_time=2026-11-01T06:00:18+00:00, book20_bid_proxy_usdt=169037, book20_ask_proxy_usdt=158439, funding_indicative=0.000006, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.84%, turnover=42596185. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-11-01T06:00:03+00:00, last15m_closed_end=2026-11-01T06:00+00:00, prior8high=0.247730, depth_time=2026-11-01T06:00:08+00:00, book20_bid_proxy_usdt=7683, book20_ask_proxy_usdt=3936, funding_indicative=-0.002588, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-18.62%, turnover=30711694. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-01T06:00:03+00:00, last15m_closed_end=2026-11-01T06:00+00:00, prior8high=4.420000, depth_time=2026-11-01T06:00:22+00:00, book20_bid_proxy_usdt=3459083, book20_ask_proxy_usdt=3676248, funding_indicative=0.000100, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.05%, turnover=52711875. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-01T06:00:04+00:00, last15m_closed_end=2026-11-01T06:00+00:00, prior8high=0.169380, depth_time=2026-11-01T06:00:25+00:00, book20_bid_proxy_usdt=132816, book20_ask_proxy_usdt=174211, funding_indicative=0.000097, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.53%, turnover=19941898. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-01T06:00:04+00:00, last15m_closed_end=2026-11-01T06:00+00:00, prior8high=0.086230, depth_time=2026-11-01T06:00:13+00:00, book20_bid_proxy_usdt=368800, book20_ask_proxy_usdt=268486, funding_indicative=0.000050, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.90%, turnover=5183750. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-01T06:00:03+00:00, last15m_closed_end=2026-11-01T06:00+00:00, prior8high=1251.980000, depth_time=2026-11-01T06:00:20+00:00, book20_bid_proxy_usdt=1109603, book20_ask_proxy_usdt=702822, funding_indicative=-0.000131, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.82%, turnover=935175903. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
