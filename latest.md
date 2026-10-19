# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T01:15:23Z**
- feed_generated_utc: 2026-10-19T01:15:25+00:00
- source_sha256: `a30be29801ce6b43741ce0e877dde9399e3defec70852ead71f624cc9f29966a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T01:15+00:00, close=82440.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T01:00+00:00, close=82269.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T00:00+00:00, close=82076.8, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.107932|-11.51|281.08|-13.11|9650074|0.09|
|AGT_USDT|0.062658|-7.21|254.30|-8.81|9739342|1.27|
|HBAR_USDT|0.084560|-1.42|-9.83|-3.02|50592481|1.18|
|STRK_USDT|0.060970|-0.95|-48.88|-2.55|16875257|3.28|
|BTW_USDT|2.306400|0.04|37.10|-1.56|22385905|1.74|
|ICNT_USDT|0.180100|0.39|69.90|-1.21|7680311|5.55|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.062658|0.060544|0.062650|1.08|N|Y/Y|N/N|N|N|
|BTW_USDT|2.306400|2.230700|2.306400|1.15|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.084560|0.084330|0.084560|2.41|N|Y/Y|N/Y|N|N|
|ICNT_USDT|0.180100|0.179800|0.180100|0.80|N|Y/Y|N/N|N|N|
|Q_USDT|0.107932|0.109060|0.107932|1.22|N|Y/Y|N/N|N|N|
|STRK_USDT|0.060970|0.059540|0.060970|1.40|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-19T01:15:00+00:00, last15m_closed_end=2026-10-19T01:15+00:00, prior8high=0.068584, depth_time=2026-10-19T01:15:10+00:00, book20_bid_proxy_usdt=2967, book20_ask_proxy_usdt=1672, funding_indicative=0.000175, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.21%, turnover=9739342. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-19T01:15:00+00:00, last15m_closed_end=2026-10-19T01:15+00:00, prior8high=2.484000, depth_time=2026-10-19T01:15:19+00:00, book20_bid_proxy_usdt=14239, book20_ask_proxy_usdt=13337, funding_indicative=-0.000440, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=0.04%, turnover=22385905. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T01:15:00+00:00, last15m_closed_end=2026-10-19T01:15+00:00, prior8high=0.085750, depth_time=2026-10-19T01:15:12+00:00, book20_bid_proxy_usdt=594032, book20_ask_proxy_usdt=550018, funding_indicative=-0.000032, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.42%, turnover=50592481. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-19T01:15:00+00:00, last15m_closed_end=2026-10-19T01:15+00:00, prior8high=0.193800, depth_time=2026-10-19T01:15:22+00:00, book20_bid_proxy_usdt=191673, book20_ask_proxy_usdt=159802, funding_indicative=0.000002, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=0.39%, turnover=7680311. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-19T01:15:00+00:00, last15m_closed_end=2026-10-19T01:15+00:00, prior8high=0.117260, depth_time=2026-10-19T01:15:08+00:00, book20_bid_proxy_usdt=8489, book20_ask_proxy_usdt=9988, funding_indicative=0.000106, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-11.51%, turnover=9650074. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T01:15:00+00:00, last15m_closed_end=2026-10-19T01:15+00:00, prior8high=0.060870, depth_time=2026-10-19T01:15:15+00:00, book20_bid_proxy_usdt=343320, book20_ask_proxy_usdt=309895, funding_indicative=0.000041, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.95%, turnover=16875257. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
