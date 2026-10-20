# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T14:15:20Z**
- feed_generated_utc: 2026-10-20T14:15:22+00:00
- source_sha256: `12dddf02c538d586368746aec7979e159eda737552fb1664e08cdd6d7d0e17ca`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T14:15+00:00, close=83198.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T14:00+00:00, close=82114, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T12:00+00:00, close=81467.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.065225|-25.06|291.45|-26.65|8432245|3.22|
|BTW_USDT|1.709000|-2.45|-2.66|-4.04|35356375|1.17|
|Q_USDT|0.123242|-2.17|300.25|-3.76|6695065|0.08|
|AKE_USDT|0.030739|-0.08|30.58|-1.67|6580471|2.60|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.065225|0.065000|0.065225|1.12|N|Y/Y|Y/N|Y|N|
|AKE_USDT|0.030739|0.029930|0.030739|0.82|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.709000|1.660700|1.709000|0.73|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.123242|0.121327|0.123112|0.58|N|N/N|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T14:15:01+00:00, last15m_closed_end=2026-10-20T14:15+00:00, prior8high=0.069163, depth_time=2026-10-20T14:15:10+00:00, book20_bid_proxy_usdt=14341, book20_ask_proxy_usdt=2622, funding_indicative=0.000061, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-25.06%, turnover=8432245. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-20T14:15:01+00:00, last15m_closed_end=2026-10-20T14:15+00:00, prior8high=0.030642, depth_time=2026-10-20T14:15:19+00:00, book20_bid_proxy_usdt=16035, book20_ask_proxy_usdt=7392, funding_indicative=0.000079, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.08%, turnover=6580471. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T14:15:01+00:00, last15m_closed_end=2026-10-20T14:15+00:00, prior8high=1.839100, depth_time=2026-10-20T14:15:13+00:00, book20_bid_proxy_usdt=13315, book20_ask_proxy_usdt=7008, funding_indicative=-0.002887, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.45%, turnover=35356375. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-20T14:15:01+00:00, last15m_closed_end=2026-10-20T14:15+00:00, prior8high=0.130897, depth_time=2026-10-20T14:15:16+00:00, book20_bid_proxy_usdt=17151, book20_ask_proxy_usdt=18379, funding_indicative=0.000050, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.17%, turnover=6695065. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
