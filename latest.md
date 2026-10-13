# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T19:00:20Z**
- feed_generated_utc: 2026-10-13T19:00:22+00:00
- source_sha256: `7c63d306a1c2d17dd8ada5cd5fad1a7a19ad3c4e1506e4f1d6e696fa23e54a7b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T19:00+00:00, close=83113.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-13T19:00+00:00, close=83113.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-13T16:00+00:00, close=83393, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOS_USDT|0.206900|-5.22|-3.99|-4.91|9494963|9.66|
|PYTH_USDT|0.079310|-4.26|1.90|-3.95|6665064|1.26|
|W_USDT|0.016088|-4.25|10.85|-3.94|10235505|4.35|
|CT_USDT|0.358560|-3.55|-3.50|-3.24|5817354|1.67|
|RLC_USDT|0.894600|-3.09|9.12|-2.78|5680811|1.12|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CT_USDT|0.358560|0.356810|0.358480|0.50|N|Y/N|N/N|Y|N|
|DOS_USDT|0.206900|0.207900|0.206900|1.64|Y|Y/Y|Y/Y|Y|Y|
|PYTH_USDT|0.079310|0.077640|0.079310|0.31|N|Y/Y|Y/N|Y|N|
|RLC_USDT|0.894600|0.874600|0.894500|0.63|N|Y/Y|Y/Y|Y|N|
|W_USDT|0.016088|0.015938|0.016090|0.86|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- CT_USDT: quote_utc=2026-10-13T19:00:03+00:00, last15m_closed_end=2026-10-13T19:00+00:00, prior8high=0.383340, depth_time=2026-10-13T19:00:16+00:00, book20_bid_proxy_usdt=7692, book20_ask_proxy_usdt=11484, funding_indicative=0.000050, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.55%, turnover=5817354. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOS_USDT: quote_utc=2026-10-13T19:00:02+00:00, last15m_closed_end=2026-10-13T19:00+00:00, prior8high=0.216700, depth_time=2026-10-13T19:00:09+00:00, book20_bid_proxy_usdt=126341, book20_ask_proxy_usdt=115393, funding_indicative=-0.000045, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.22%, turnover=9494963. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-13T19:00:03+00:00, last15m_closed_end=2026-10-13T19:00+00:00, prior8high=0.080250, depth_time=2026-10-13T19:00:12+00:00, book20_bid_proxy_usdt=99250, book20_ask_proxy_usdt=108987, funding_indicative=-0.000001, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.26%, turnover=6665064. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T19:00:03+00:00, last15m_closed_end=2026-10-13T19:00+00:00, prior8high=0.926400, depth_time=2026-10-13T19:00:19+00:00, book20_bid_proxy_usdt=40952, book20_ask_proxy_usdt=37186, funding_indicative=-0.000624, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.09%, turnover=5680811. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-13T19:00:02+00:00, last15m_closed_end=2026-10-13T19:00+00:00, prior8high=0.017093, depth_time=2026-10-13T19:00:15+00:00, book20_bid_proxy_usdt=44424, book20_ask_proxy_usdt=32985, funding_indicative=-0.000316, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.25%, turnover=10235505. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
