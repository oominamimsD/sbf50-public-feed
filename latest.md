# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T07:30:28Z**
- feed_generated_utc: 2026-11-01T07:30:30+00:00
- source_sha256: `e0512fc61dd26d5a53225220718572312d7f52a002a6f3118c1cd50c96b283c9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T07:30+00:00, close=77857, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-01T07:00+00:00, close=77974.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T04:00+00:00, close=77753.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.231100|-21.96|37.62|-22.34|31258567|3.03|
|AKE_USDT|0.009363|-15.93|-67.96|-16.31|11546922|1.07|
|BLESS_USDT|0.009470|-10.35|16.72|-10.73|6293196|3.17|
|XPL_USDT|0.074440|-8.44|3.08|-8.82|5863632|1.34|
|ENA_USDT|0.187460|-3.37|0.35|-3.75|43512110|0.53|
|ZEC_USDT|1242.980000|-3.23|8.53|-3.61|944821105|0.32|
|NEAR_USDT|4.362000|-2.54|-0.90|-2.92|54034000|2.29|
|TIA_USDT|0.478500|-2.36|-8.97|-2.74|8674294|2.09|
|XLM_USDT|0.169150|-1.50|0.43|-1.88|20262542|0.59|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.009363|0.009211|0.009367|0.45|N|Y/Y|Y/Y|Y|N|
|BLESS_USDT|0.009470|0.009395|0.009470|1.54|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.187460|0.187300|0.187470|1.69|N|Y/Y|Y/Y|Y|N|
|LSK_USDT|0.231100|0.229230|0.231100|0.76|N|Y/Y|N/N|Y|N|
|NEAR_USDT|4.362000|4.359000|4.362000|0.77|N|Y/Y|N/N|Y|N|
|TIA_USDT|0.478500|0.479600|0.478400|1.89|Y|N/N|Y/Y|Y|N|
|XLM_USDT|0.169150|0.168600|0.169150|1.96|N|N/Y|Y/N|Y|N|
|XPL_USDT|0.074440|0.072520|0.074390|1.17|N|Y/Y|N/N|Y|N|
|ZEC_USDT|1242.980000|1241.440000|1243.190000|1.34|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-01T07:30:02+00:00, last15m_closed_end=2026-11-01T07:30+00:00, prior8high=0.010385, depth_time=2026-11-01T07:30:10+00:00, book20_bid_proxy_usdt=7932, book20_ask_proxy_usdt=6965, funding_indicative=-0.001944, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-15.93%, turnover=11546922. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-11-01T07:30:02+00:00, last15m_closed_end=2026-11-01T07:30+00:00, prior8high=0.009785, depth_time=2026-11-01T07:30:12+00:00, book20_bid_proxy_usdt=17367, book20_ask_proxy_usdt=13305, funding_indicative=0.000050, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.35%, turnover=6293196. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-01T07:30:02+00:00, last15m_closed_end=2026-11-01T07:30+00:00, prior8high=0.190760, depth_time=2026-11-01T07:30:17+00:00, book20_bid_proxy_usdt=106925, book20_ask_proxy_usdt=227262, funding_indicative=-0.000006, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.37%, turnover=43512110. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-11-01T07:30:01+00:00, last15m_closed_end=2026-11-01T07:30+00:00, prior8high=0.247730, depth_time=2026-11-01T07:30:08+00:00, book20_bid_proxy_usdt=12493, book20_ask_proxy_usdt=6298, funding_indicative=-0.002267, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-21.96%, turnover=31258567. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-01T07:30:01+00:00, last15m_closed_end=2026-11-01T07:30+00:00, prior8high=4.410000, depth_time=2026-11-01T07:30:23+00:00, book20_bid_proxy_usdt=5081052, book20_ask_proxy_usdt=3347994, funding_indicative=0.000100, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.54%, turnover=54034000. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-01T07:30:02+00:00, last15m_closed_end=2026-11-01T07:30+00:00, prior8high=0.486200, depth_time=2026-11-01T07:30:24+00:00, book20_bid_proxy_usdt=224984, book20_ask_proxy_usdt=220975, funding_indicative=-0.000145, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.36%, turnover=8674294. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-01T07:30:02+00:00, last15m_closed_end=2026-11-01T07:30+00:00, prior8high=0.169690, depth_time=2026-11-01T07:30:26+00:00, book20_bid_proxy_usdt=210879, book20_ask_proxy_usdt=175838, funding_indicative=0.000100, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.50%, turnover=20262542. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-01T07:30:02+00:00, last15m_closed_end=2026-11-01T07:30+00:00, prior8high=0.074870, depth_time=2026-11-01T07:30:15+00:00, book20_bid_proxy_usdt=306754, book20_ask_proxy_usdt=343202, funding_indicative=0.000050, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.44%, turnover=5863632. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-01T07:30:02+00:00, last15m_closed_end=2026-11-01T07:30+00:00, prior8high=1254.820000, depth_time=2026-11-01T07:30:20+00:00, book20_bid_proxy_usdt=439872, book20_ask_proxy_usdt=905253, funding_indicative=-0.000105, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.23%, turnover=944821105. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
