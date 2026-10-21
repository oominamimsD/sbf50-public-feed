# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T19:00:19Z**
- feed_generated_utc: 2026-10-21T19:00:22+00:00
- source_sha256: `ffa232906ac1e0c62b162f01fcd9c92a9159ba36f97044dcd2e4403d1ac04f8f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T19:00+00:00, close=84374.8, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T19:00+00:00, close=84374.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T16:00+00:00, close=84499, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BR_USDT|0.514830|-11.11|26.26|-10.97|14452438|1.55|
|AKE_USDT|0.025671|-6.07|-0.81|-5.93|9970692|1.17|
|INJ_USDT|8.546000|-2.33|11.87|-2.19|55637178|1.17|
|TIA_USDT|0.620400|-1.91|16.28|-1.77|39021554|3.22|
|WLD_USDT|0.570200|-1.33|16.62|-1.19|139615847|1.75|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.025671|0.025666|0.025671|0.87|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.514830|0.513880|0.514830|0.77|N|Y/Y|Y/Y|N|N|
|INJ_USDT|8.546000|8.565000|8.546000|2.16|Y|Y/Y|N/N|N|N|
|TIA_USDT|0.620400|0.626600|0.620300|1.44|Y|Y/N|N/N|N|N|
|WLD_USDT|0.570200|0.569800|0.570200|1.57|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-21T19:00:01+00:00, last15m_closed_end=2026-10-21T19:00+00:00, prior8high=0.026672, depth_time=2026-10-21T19:00:10+00:00, book20_bid_proxy_usdt=14971, book20_ask_proxy_usdt=14803, funding_indicative=0.000050, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-6.07%, turnover=9970692. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T19:00:01+00:00, last15m_closed_end=2026-10-21T19:00+00:00, prior8high=0.535870, depth_time=2026-10-21T19:00:08+00:00, book20_bid_proxy_usdt=2821, book20_ask_proxy_usdt=4100, funding_indicative=-0.000165, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-11.11%, turnover=14452438. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-21T19:00:01+00:00, last15m_closed_end=2026-10-21T19:00+00:00, prior8high=8.717000, depth_time=2026-10-21T19:00:14+00:00, book20_bid_proxy_usdt=175574, book20_ask_proxy_usdt=218802, funding_indicative=0.000056, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.33%, turnover=55637178. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T19:00:01+00:00, last15m_closed_end=2026-10-21T19:00+00:00, prior8high=0.646300, depth_time=2026-10-21T19:00:16+00:00, book20_bid_proxy_usdt=139080, book20_ask_proxy_usdt=341348, funding_indicative=-0.000087, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.91%, turnover=39021554. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-21T19:00:01+00:00, last15m_closed_end=2026-10-21T19:00+00:00, prior8high=0.577500, depth_time=2026-10-21T19:00:18+00:00, book20_bid_proxy_usdt=1775737, book20_ask_proxy_usdt=1537284, funding_indicative=0.000100, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.33%, turnover=139615847. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
