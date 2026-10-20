# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T18:00:25Z**
- feed_generated_utc: 2026-10-20T18:00:27+00:00
- source_sha256: `9e026c9bc865499c4b64127ab8b9289121fb1f436dd1d3be0fd99ed96917a289`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T18:00+00:00, close=82781.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T18:00+00:00, close=82781.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-20T16:00+00:00, close=82581.9, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.718200|-6.32|-12.00|-6.56|33293511|2.33|
|INJ_USDT|8.539000|-4.12|8.95|-4.36|43598330|1.17|
|ARB_USDT|0.189000|-3.84|2.35|-4.08|104090008|0.53|
|PHA_USDT|0.057920|-3.83|5.25|-4.07|19951743|3.46|
|Q_USDT|0.124651|-3.39|203.08|-3.63|6808847|4.01|
|AGT_USDT|0.062068|-2.52|283.68|-2.76|7262043|0.16|
|STRK_USDT|0.056260|-2.00|-35.28|-2.24|17866147|3.55|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.062068|0.062222|0.062068|1.06|N|Y/Y|Y/Y|N|N|
|ARB_USDT|0.189000|0.186140|0.189000|0.25|N|Y/Y|Y/Y|N|N|
|BTW_USDT|1.718200|1.714000|1.718200|0.59|N|Y/Y|Y/Y|N|N|
|INJ_USDT|8.539000|8.469000|8.539000|0.82|N|Y/N|N/N|N|N|
|PHA_USDT|0.057920|0.056980|0.057940|0.49|N|Y/Y|N/N|N|N|
|Q_USDT|0.124651|0.121860|0.124602|0.60|N|Y/Y|N/N|N|N|
|STRK_USDT|0.056260|0.054760|0.056260|0.41|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T18:00:00+00:00, last15m_closed_end=2026-10-20T18:00+00:00, prior8high=0.066255, depth_time=2026-10-20T18:00:21+00:00, book20_bid_proxy_usdt=13167, book20_ask_proxy_usdt=5099, funding_indicative=0.000047, next_funding_utc=2026-10-20T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.52%, turnover=7262043. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-20T18:00:00+00:00, last15m_closed_end=2026-10-20T18:00+00:00, prior8high=0.190160, depth_time=2026-10-20T18:00:14+00:00, book20_bid_proxy_usdt=87236, book20_ask_proxy_usdt=48730, funding_indicative=-0.000122, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.84%, turnover=104090008. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T18:00:00+00:00, last15m_closed_end=2026-10-20T18:00+00:00, prior8high=1.889700, depth_time=2026-10-20T18:00:09+00:00, book20_bid_proxy_usdt=16702, book20_ask_proxy_usdt=16208, funding_indicative=-0.002846, next_funding_utc=2026-10-20T20:00:00+00:00, funding_cycle_h=4, 24h_change=-6.32%, turnover=33293511. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-20T18:00:00+00:00, last15m_closed_end=2026-10-20T18:00+00:00, prior8high=8.684000, depth_time=2026-10-20T18:00:11+00:00, book20_bid_proxy_usdt=222128, book20_ask_proxy_usdt=274540, funding_indicative=0.000124, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.12%, turnover=43598330. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-20T18:00:00+00:00, last15m_closed_end=2026-10-20T18:00+00:00, prior8high=0.058250, depth_time=2026-10-20T18:00:15+00:00, book20_bid_proxy_usdt=59971, book20_ask_proxy_usdt=76746, funding_indicative=-0.000100, next_funding_utc=2026-10-20T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.83%, turnover=19951743. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-20T18:00:00+00:00, last15m_closed_end=2026-10-20T18:00+00:00, prior8high=0.125637, depth_time=2026-10-20T18:00:19+00:00, book20_bid_proxy_usdt=15941, book20_ask_proxy_usdt=16942, funding_indicative=-0.000010, next_funding_utc=2026-10-20T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.39%, turnover=6808847. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-20T18:00:00+00:00, last15m_closed_end=2026-10-20T18:00+00:00, prior8high=0.056220, depth_time=2026-10-20T18:00:23+00:00, book20_bid_proxy_usdt=577379, book20_ask_proxy_usdt=699362, funding_indicative=0.000000, next_funding_utc=2026-10-20T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.00%, turnover=17866147. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
