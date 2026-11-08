# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T01:30:15Z**
- feed_generated_utc: 2026-11-08T01:30:16+00:00
- source_sha256: `9f4139f338a61fcb5a07d5a8457c4b4a74c8337878efc90c01c1d5d55fb0d857`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T01:30+00:00, close=75752.4, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T01:00+00:00, close=75774, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T00:00+00:00, close=75836.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|QNT_USDT|194.620000|-2.12|-3.19|-2.15|42780548|0.51|
|WLD_USDT|0.330500|-1.51|-18.27|-1.54|25980810|3.03|
|ENA_USDT|0.156250|-1.22|-19.46|-1.25|27585508|0.64|
|TIA_USDT|0.436300|-1.20|-10.97|-1.23|7023217|2.29|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ENA_USDT|0.156250|0.157250|0.156240|1.99|Y|Y/Y|Y/Y|Y|Y|
|QNT_USDT|194.620000|194.800000|194.620000|1.27|N|Y/Y|N/N|Y|N|
|TIA_USDT|0.436300|0.436700|0.436300|1.50|Y|Y/Y|N/N|Y|N|
|WLD_USDT|0.330500|0.331200|0.330500|0.99|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ENA_USDT: quote_utc=2026-11-08T01:30:00+00:00, last15m_closed_end=2026-11-08T01:30+00:00, prior8high=0.159120, depth_time=2026-11-08T01:30:12+00:00, book20_bid_proxy_usdt=365038, book20_ask_proxy_usdt=147442, funding_indicative=-0.000051, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.22%, turnover=27585508. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T01:30:00+00:00, last15m_closed_end=2026-11-08T01:30+00:00, prior8high=196.770000, depth_time=2026-11-08T01:30:05+00:00, book20_bid_proxy_usdt=95647, book20_ask_proxy_usdt=57962, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.12%, turnover=42780548. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T01:30:00+00:00, last15m_closed_end=2026-11-08T01:30+00:00, prior8high=0.443200, depth_time=2026-11-08T01:30:13+00:00, book20_bid_proxy_usdt=345767, book20_ask_proxy_usdt=201379, funding_indicative=-0.000001, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.20%, turnover=7023217. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T01:30:00+00:00, last15m_closed_end=2026-11-08T01:30+00:00, prior8high=0.335400, depth_time=2026-11-08T01:30:09+00:00, book20_bid_proxy_usdt=3700751, book20_ask_proxy_usdt=3104288, funding_indicative=-0.000099, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.51%, turnover=25980810. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
