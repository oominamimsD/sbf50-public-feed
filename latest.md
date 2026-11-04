# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T05:30:23Z**
- feed_generated_utc: 2026-11-04T05:30:25+00:00
- source_sha256: `72733bb34a38916a3503b1a1a56af755a21464597b269e3b2df7ec0e0038a92e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1194; contracts: 1186; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T05:30+00:00, close=77382.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T05:00+00:00, close=77357.9, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-04T04:00+00:00, close=76468.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.037190|-30.88|-21.73|-30.52|11637425|5.38|
|AKE_USDT|0.003032|-27.04|-85.64|-26.68|12398493|6.59|
|ICNT_USDT|0.209900|-10.10|18.38|-9.74|5167116|9.53|
|TRUMPOFFICIAL_USDT|1.508000|-6.21|-10.66|-5.85|8268228|6.63|
|XPL_USDT|0.062200|-2.88|-15.74|-2.52|7415357|1.61|
|XLM_USDT|0.160930|-2.34|-4.89|-1.98|37882004|0.62|
|Q_USDT|0.027630|-1.91|-56.54|-1.55|7362615|7.24|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.037190|0.036380|0.037190|0.95|N|Y/Y|N/N|Y|N|
|AKE_USDT|0.003032|0.003071|0.003033|2.52|Y|Y/Y|Y/Y|Y|Y|
|ICNT_USDT|0.209900|0.209100|0.209900|0.50|N|Y/Y|N/N|Y|N|
|Q_USDT|0.027630|0.027540|0.027630|0.25|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.508000|1.491000|1.507000|0.55|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.160930|0.157780|0.160930|0.71|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.062200|0.060420|0.062170|0.12|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T05:30:03+00:00, last15m_closed_end=2026-11-04T05:30+00:00, prior8high=0.038630, depth_time=2026-11-04T05:30:07+00:00, book20_bid_proxy_usdt=37973, book20_ask_proxy_usdt=33625, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-30.88%, turnover=11637425. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T05:30:03+00:00, last15m_closed_end=2026-11-04T05:30+00:00, prior8high=0.003654, depth_time=2026-11-04T05:30:11+00:00, book20_bid_proxy_usdt=74191, book20_ask_proxy_usdt=43622, funding_indicative=0.000050, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-27.04%, turnover=12398493. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-11-04T05:30:03+00:00, last15m_closed_end=2026-11-04T05:30+00:00, prior8high=0.217900, depth_time=2026-11-04T05:30:12+00:00, book20_bid_proxy_usdt=148138, book20_ask_proxy_usdt=147477, funding_indicative=0.000050, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.10%, turnover=5167116. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-11-04T05:30:03+00:00, last15m_closed_end=2026-11-04T05:30+00:00, prior8high=0.028470, depth_time=2026-11-04T05:30:22+00:00, book20_bid_proxy_usdt=87587, book20_ask_proxy_usdt=39547, funding_indicative=-0.000523, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.91%, turnover=7362615. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T05:30:03+00:00, last15m_closed_end=2026-11-04T05:30+00:00, prior8high=1.519000, depth_time=2026-11-04T05:30:15+00:00, book20_bid_proxy_usdt=2277225, book20_ask_proxy_usdt=2810484, funding_indicative=-0.000201, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.21%, turnover=8268228. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-04T05:30:03+00:00, last15m_closed_end=2026-11-04T05:30+00:00, prior8high=0.161230, depth_time=2026-11-04T05:30:20+00:00, book20_bid_proxy_usdt=124328, book20_ask_proxy_usdt=178670, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.34%, turnover=37882004. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-04T05:30:03+00:00, last15m_closed_end=2026-11-04T05:30+00:00, prior8high=0.062380, depth_time=2026-11-04T05:30:18+00:00, book20_bid_proxy_usdt=365296, book20_ask_proxy_usdt=425724, funding_indicative=0.000050, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.88%, turnover=7415357. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
