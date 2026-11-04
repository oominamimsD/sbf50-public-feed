# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T06:45:18Z**
- feed_generated_utc: 2026-11-04T06:45:20+00:00
- source_sha256: `bd1c09b01cbfd2415648590b8b65c37fc947abfd5264e5fb194be4f728b217e3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1194; contracts: 1186; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T06:45+00:00, close=77874.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T06:00+00:00, close=77721.7, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-04T04:00+00:00, close=76468.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.037060|-31.12|-22.01|-31.39|11167304|2.70|
|AKE_USDT|0.003188|-23.29|-84.90|-23.56|12670823|9.41|
|ICNT_USDT|0.208300|-10.79|17.48|-11.06|5014697|4.81|
|TRUMPOFFICIAL_USDT|1.520000|-5.47|-9.95|-5.74|8808879|6.58|
|Q_USDT|0.027780|-1.38|-56.30|-1.65|7463147|7.20|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.037060|0.036380|0.037060|1.16|N|Y/Y|N/N|Y|N|
|AKE_USDT|0.003188|0.002979|0.003186|0.53|N|Y/Y|Y/Y|Y|N|
|ICNT_USDT|0.208300|0.207400|0.208300|1.04|N|Y/Y|N/N|Y|N|
|Q_USDT|0.027780|0.027450|0.027800|0.37|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.520000|1.494000|1.519000|1.78|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T06:45:02+00:00, last15m_closed_end=2026-11-04T06:45+00:00, prior8high=0.038670, depth_time=2026-11-04T06:45:05+00:00, book20_bid_proxy_usdt=30801, book20_ask_proxy_usdt=40056, funding_indicative=0.000134, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-31.12%, turnover=11167304. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T06:45:02+00:00, last15m_closed_end=2026-11-04T06:45+00:00, prior8high=0.003623, depth_time=2026-11-04T06:45:10+00:00, book20_bid_proxy_usdt=58592, book20_ask_proxy_usdt=43764, funding_indicative=0.000050, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-23.29%, turnover=12670823. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-11-04T06:45:02+00:00, last15m_closed_end=2026-11-04T06:45+00:00, prior8high=0.215600, depth_time=2026-11-04T06:45:09+00:00, book20_bid_proxy_usdt=143264, book20_ask_proxy_usdt=150097, funding_indicative=0.000050, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.79%, turnover=5014697. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-11-04T06:45:02+00:00, last15m_closed_end=2026-11-04T06:45+00:00, prior8high=0.028280, depth_time=2026-11-04T06:45:17+00:00, book20_bid_proxy_usdt=111718, book20_ask_proxy_usdt=47584, funding_indicative=-0.000379, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.38%, turnover=7463147. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T06:45:02+00:00, last15m_closed_end=2026-11-04T06:45+00:00, prior8high=1.536000, depth_time=2026-11-04T06:45:15+00:00, book20_bid_proxy_usdt=3046878, book20_ask_proxy_usdt=2194692, funding_indicative=-0.000085, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.47%, turnover=8808879. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
