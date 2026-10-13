# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T23:30:12Z**
- feed_generated_utc: 2026-10-13T23:30:14+00:00
- source_sha256: `334f5456357d004699a6cad13b155e09ab7f87019c18a7638e25a661b0233ad2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T23:30+00:00, close=83133.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-13T23:00+00:00, close=83483.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T20:00+00:00, close=83253, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|RLC_USDT|0.892200|-3.35|8.83|-3.04|5112244|1.12|
|CT_USDT|0.359460|-3.30|-3.26|-2.99|5440878|3.89|
|STRK_USDT|0.084880|-2.35|62.63|-2.04|37609250|1.18|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CT_USDT|0.359460|0.357960|0.359460|0.34|N|N/Y|N/N|N|N|
|RLC_USDT|0.892200|0.887000|0.892200|0.28|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.084880|0.082530|0.084880|0.17|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- CT_USDT: quote_utc=2026-10-13T23:30:02+00:00, last15m_closed_end=2026-10-13T23:30+00:00, prior8high=0.366370, depth_time=2026-10-13T23:30:09+00:00, book20_bid_proxy_usdt=9707, book20_ask_proxy_usdt=11437, funding_indicative=0.000050, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.30%, turnover=5440878. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T23:30:02+00:00, last15m_closed_end=2026-10-13T23:30+00:00, prior8high=0.903000, depth_time=2026-10-13T23:30:05+00:00, book20_bid_proxy_usdt=80316, book20_ask_proxy_usdt=53009, funding_indicative=-0.000454, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.35%, turnover=5112244. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T23:30:02+00:00, last15m_closed_end=2026-10-13T23:30+00:00, prior8high=0.085530, depth_time=2026-10-13T23:30:11+00:00, book20_bid_proxy_usdt=248615, book20_ask_proxy_usdt=138627, funding_indicative=-0.000007, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.35%, turnover=37609250. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
