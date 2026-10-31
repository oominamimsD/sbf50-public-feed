# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T17:45:13Z**
- feed_generated_utc: 2026-10-31T17:45:15+00:00
- source_sha256: `1bab237570b449457b265dd9f085dc9d22d43100484a95a49a83345838d3b3cf`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T17:45+00:00, close=77592, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T17:00+00:00, close=77578.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T16:00+00:00, close=77560.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|WLD_USDT|0.398200|-1.53|-13.80|-1.57|42031987|2.51|
|TRX_USDT|0.307650|-1.49|-6.46|-1.53|6972547|0.97|
|FET_USDT|0.161300|-1.22|-6.38|-1.26|5956234|6.20|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|FET_USDT|0.161300|0.161400|0.161300|2.27|Y|Y/Y|Y/Y|Y|Y|
|TRX_USDT|0.307650|0.309160|0.307650|4.36|Y|Y/Y|Y/Y|Y|Y|
|WLD_USDT|0.398200|0.397600|0.398300|1.49|N|Y/N|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- FET_USDT: quote_utc=2026-10-31T17:45:02+00:00, last15m_closed_end=2026-10-31T17:45+00:00, prior8high=0.163800, depth_time=2026-10-31T17:45:12+00:00, book20_bid_proxy_usdt=1644951, book20_ask_proxy_usdt=1041240, funding_indicative=-0.000017, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.22%, turnover=5956234. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T17:45:02+00:00, last15m_closed_end=2026-10-31T17:45+00:00, prior8high=0.314740, depth_time=2026-10-31T17:45:09+00:00, book20_bid_proxy_usdt=993309, book20_ask_proxy_usdt=67963, funding_indicative=-0.000557, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.49%, turnover=6972547. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T17:45:01+00:00, last15m_closed_end=2026-10-31T17:45+00:00, prior8high=0.405900, depth_time=2026-10-31T17:45:07+00:00, book20_bid_proxy_usdt=2680278, book20_ask_proxy_usdt=2769406, funding_indicative=0.000027, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.53%, turnover=42031987. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
