# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T17:00:25Z**
- feed_generated_utc: 2026-10-26T17:00:29+00:00
- source_sha256: `854d54c3041c20b3b45deabf2781e0d506433dd8ed5cb32badfc377b0dcdfdc1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T17:00+00:00, close=80200, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T17:00+00:00, close=80200, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-26T16:00+00:00, close=80399.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|0.952000|-21.12|-45.66|-20.86|16840379|3.15|
|IRYS_USDT|0.026700|-3.19|117.42|-2.93|9963738|3.75|
|ARB_USDT|0.168290|-2.10|-13.97|-1.84|20115431|0.59|
|LIT_USDT|3.091900|-1.83|1.97|-1.57|5097465|0.32|
|APT_USDT|0.695400|-1.64|-8.84|-1.38|5986610|1.44|
|AAVE_USDT|135.620000|-1.63|-7.87|-1.37|29125245|0.74|
|NEAR_USDT|4.512000|-1.33|-7.99|-1.07|123675119|2.21|
|WLD_USDT|0.439100|-1.32|-13.27|-1.06|70587849|2.28|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|135.620000|134.780000|135.620000|1.00|N|Y/N|Y/Y|Y|N|
|APT_USDT|0.695400|0.689500|0.695400|2.17|N|Y/N|Y/Y|Y|N|
|ARB_USDT|0.168290|0.166950|0.168290|1.36|N|Y/N|Y/Y|Y|N|
|BTW_USDT|0.952000|0.904000|0.952000|1.76|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.026700|0.026240|0.026730|0.77|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.091900|3.062900|3.091900|0.96|N|Y/N|Y/Y|Y|N|
|NEAR_USDT|4.512000|4.474000|4.513000|0.73|N|Y/N|Y/Y|Y|N|
|WLD_USDT|0.439100|0.435100|0.438900|1.01|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-26T17:00:03+00:00, last15m_closed_end=2026-10-26T17:00+00:00, prior8high=138.650000, depth_time=2026-10-26T17:00:17+00:00, book20_bid_proxy_usdt=284576, book20_ask_proxy_usdt=336787, funding_indicative=0.000087, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.63%, turnover=29125245. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-26T17:00:03+00:00, last15m_closed_end=2026-10-26T17:00+00:00, prior8high=0.713400, depth_time=2026-10-26T17:00:18+00:00, book20_bid_proxy_usdt=108580, book20_ask_proxy_usdt=150325, funding_indicative=-0.000019, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.64%, turnover=5986610. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-26T17:00:03+00:00, last15m_closed_end=2026-10-26T17:00+00:00, prior8high=0.172850, depth_time=2026-10-26T17:00:13+00:00, book20_bid_proxy_usdt=74587, book20_ask_proxy_usdt=106435, funding_indicative=-0.000024, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.10%, turnover=20115431. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T17:00:02+00:00, last15m_closed_end=2026-10-26T17:00+00:00, prior8high=1.634800, depth_time=2026-10-26T17:00:08+00:00, book20_bid_proxy_usdt=26717, book20_ask_proxy_usdt=13008, funding_indicative=-0.009115, next_funding_utc=2026-10-26T20:00:00+00:00, funding_cycle_h=4, 24h_change=-21.12%, turnover=16840379. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T17:00:02+00:00, last15m_closed_end=2026-10-26T17:00+00:00, prior8high=0.028060, depth_time=2026-10-26T17:00:10+00:00, book20_bid_proxy_usdt=112022, book20_ask_proxy_usdt=90128, funding_indicative=-0.000681, next_funding_utc=2026-10-26T18:00:00+00:00, funding_cycle_h=1, 24h_change=-3.19%, turnover=9963738. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T17:00:03+00:00, last15m_closed_end=2026-10-26T17:00+00:00, prior8high=3.171900, depth_time=2026-10-26T17:00:15+00:00, book20_bid_proxy_usdt=24269, book20_ask_proxy_usdt=16505, funding_indicative=0.000050, next_funding_utc=2026-10-26T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.83%, turnover=5097465. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-26T17:00:02+00:00, last15m_closed_end=2026-10-26T17:00+00:00, prior8high=4.663000, depth_time=2026-10-26T17:00:22+00:00, book20_bid_proxy_usdt=3792622, book20_ask_proxy_usdt=5501275, funding_indicative=0.000100, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.33%, turnover=123675119. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T17:00:02+00:00, last15m_closed_end=2026-10-26T17:00+00:00, prior8high=0.452700, depth_time=2026-10-26T17:00:25+00:00, book20_bid_proxy_usdt=2274290, book20_ask_proxy_usdt=2828798, funding_indicative=-0.000127, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.32%, turnover=70587849. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
