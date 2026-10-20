# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T20:45:14Z**
- feed_generated_utc: 2026-10-20T20:45:17+00:00
- source_sha256: `e002750dce4a5c9f8824025d2e0689fb741c02839f11348f760fc06cbfbcd0fc`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T20:45+00:00, close=82700, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T20:00+00:00, close=82561, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-20T20:00+00:00, close=82561, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.058243|-9.88|260.03|-10.02|7429367|6.34|
|BTW_USDT|1.676400|-9.36|-14.14|-9.50|28913268|2.39|
|BAT_USDT|0.199440|-7.56|12.43|-7.70|11287797|1.50|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.058243|0.057751|0.058243|0.69|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.199440|0.198230|0.199440|0.36|N|Y/N|N/N|N|N|
|BTW_USDT|1.676400|1.657000|1.676400|0.98|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T20:44:59+00:00, last15m_closed_end=2026-10-20T20:45+00:00, prior8high=0.063088, depth_time=2026-10-20T20:45:08+00:00, book20_bid_proxy_usdt=5288, book20_ask_proxy_usdt=7743, funding_indicative=0.000047, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.88%, turnover=7429367. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-20T20:45:00+00:00, last15m_closed_end=2026-10-20T20:45+00:00, prior8high=0.204900, depth_time=2026-10-20T20:45:12+00:00, book20_bid_proxy_usdt=27975, book20_ask_proxy_usdt=15453, funding_indicative=0.000058, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-7.56%, turnover=11287797. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T20:45:00+00:00, last15m_closed_end=2026-10-20T20:45+00:00, prior8high=1.754000, depth_time=2026-10-20T20:45:11+00:00, book20_bid_proxy_usdt=9585, book20_ask_proxy_usdt=5724, funding_indicative=-0.003157, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.36%, turnover=28913268. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
