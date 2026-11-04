# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T18:45:25Z**
- feed_generated_utc: 2026-11-04T18:45:27+00:00
- source_sha256: `8e14391044fa78b41ac0ebfdc37c3b02ca64863d35854f3fbcf650dd23f6ffd0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T18:45+00:00, close=80329.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T18:00+00:00, close=80387.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T16:00+00:00, close=80272.3, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.032580|-9.24|-27.74|-9.31|5784448|3.07|
|TRUMPOFFICIAL_USDT|1.298000|-8.84|-24.04|-8.91|23994502|7.70|
|AKE_USDT|0.002617|-6.86|-86.97|-6.93|17930559|7.64|
|PUMPFUN_USDT|0.004203|-5.55|-0.09|-5.62|18692500|2.38|
|ZRO_USDT|1.804900|-3.20|5.42|-3.27|11236686|0.55|
|WLFI_USDT|0.046780|-2.13|-10.86|-2.20|6028660|2.14|
|XMR_USDT|627.990000|-1.87|3.95|-1.94|9858908|0.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.032580|0.032400|0.032580|0.80|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.002617|0.002421|0.002618|0.28|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.004203|0.004219|0.004203|1.11|N|Y/N|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.298000|1.215000|1.298000|1.40|N|Y/Y|Y/Y|N|N|
|WLFI_USDT|0.046780|0.046430|0.046780|0.50|N|Y/Y|Y/Y|N|N|
|XMR_USDT|627.990000|629.550000|627.990000|0.99|N|Y/Y|N/N|N|N|
|ZRO_USDT|1.804900|1.806000|1.804900|0.76|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T18:45:00+00:00, last15m_closed_end=2026-11-04T18:45+00:00, prior8high=0.035620, depth_time=2026-11-04T18:45:06+00:00, book20_bid_proxy_usdt=49189, book20_ask_proxy_usdt=17760, funding_indicative=0.000053, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-9.24%, turnover=5784448. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T18:45:00+00:00, last15m_closed_end=2026-11-04T18:45+00:00, prior8high=0.002842, depth_time=2026-11-04T18:45:13+00:00, book20_bid_proxy_usdt=60190, book20_ask_proxy_usdt=77203, funding_indicative=-0.000199, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-6.86%, turnover=17930559. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-04T18:45:00+00:00, last15m_closed_end=2026-11-04T18:45+00:00, prior8high=0.004490, depth_time=2026-11-04T18:45:16+00:00, book20_bid_proxy_usdt=1315112, book20_ask_proxy_usdt=2046856, funding_indicative=0.000050, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.55%, turnover=18692500. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T18:45:00+00:00, last15m_closed_end=2026-11-04T18:45+00:00, prior8high=1.413000, depth_time=2026-11-04T18:45:08+00:00, book20_bid_proxy_usdt=1382729, book20_ask_proxy_usdt=916457, funding_indicative=-0.000434, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-8.84%, turnover=23994502. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLFI_USDT: quote_utc=2026-11-04T18:45:00+00:00, last15m_closed_end=2026-11-04T18:45+00:00, prior8high=0.048210, depth_time=2026-11-04T18:45:21+00:00, book20_bid_proxy_usdt=148925, book20_ask_proxy_usdt=369141, funding_indicative=0.000050, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.13%, turnover=6028660. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-11-04T18:45:00+00:00, last15m_closed_end=2026-11-04T18:45+00:00, prior8high=638.740000, depth_time=2026-11-04T18:45:25+00:00, book20_bid_proxy_usdt=6218, book20_ask_proxy_usdt=19820, funding_indicative=0.000167, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.87%, turnover=9858908. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-04T18:45:00+00:00, last15m_closed_end=2026-11-04T18:45+00:00, prior8high=1.872200, depth_time=2026-11-04T18:45:18+00:00, book20_bid_proxy_usdt=30251, book20_ask_proxy_usdt=31116, funding_indicative=0.000050, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.20%, turnover=11236686. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
