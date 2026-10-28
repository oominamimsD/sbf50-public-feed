# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T18:15:23Z**
- feed_generated_utc: 2026-10-28T18:15:27+00:00
- source_sha256: `b1603a870d360b3217b84dfda019a0f36e0ad580efff8caf82b92075064bb6cc`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T18:15+00:00, close=80804.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T18:00+00:00, close=80827.7, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-28T16:00+00:00, close=80528, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TIA_USDT|0.527300|-2.36|-16.63|-2.68|14878840|1.90|
|STRK_USDT|0.046050|-1.60|-25.68|-1.92|5138806|2.17|
|HBAR_USDT|0.074760|-1.51|-13.00|-1.83|11878844|1.34|
|WLD_USDT|0.426600|-1.43|-25.62|-1.75|63378595|2.35|
|APT_USDT|0.681500|-1.04|-18.44|-1.36|6358653|1.47|
|ONDO_USDT|0.415200|-0.95|-11.01|-1.27|16885735|2.41|
|OP_USDT|0.110280|-0.72|-16.39|-1.04|6512556|0.91|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.681500|0.675400|0.681500|1.66|N|Y/Y|Y/Y|N|N|
|HBAR_USDT|0.074760|0.074660|0.074770|3.32|N|Y/Y|Y/Y|N|N|
|ONDO_USDT|0.415200|0.412000|0.415200|3.43|N|Y/Y|N/N|N|N|
|OP_USDT|0.110280|0.109270|0.110280|2.22|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.046050|0.045520|0.046050|1.44|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.527300|0.523300|0.527300|2.54|N|Y/Y|N/Y|N|N|
|WLD_USDT|0.426600|0.416900|0.426600|1.31|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-28T18:15:01+00:00, last15m_closed_end=2026-10-28T18:15+00:00, prior8high=0.689600, depth_time=2026-10-28T18:15:18+00:00, book20_bid_proxy_usdt=134968, book20_ask_proxy_usdt=176972, funding_indicative=-0.000148, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.04%, turnover=6358653. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-28T18:15:01+00:00, last15m_closed_end=2026-10-28T18:15+00:00, prior8high=0.075940, depth_time=2026-10-28T18:15:13+00:00, book20_bid_proxy_usdt=1449797, book20_ask_proxy_usdt=783040, funding_indicative=0.000036, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.51%, turnover=11878844. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-28T18:15:01+00:00, last15m_closed_end=2026-10-28T18:15+00:00, prior8high=0.419600, depth_time=2026-10-28T18:15:19+00:00, book20_bid_proxy_usdt=1560324, book20_ask_proxy_usdt=1743222, funding_indicative=0.000050, next_funding_utc=2026-10-28T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.95%, turnover=16885735. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-28T18:15:02+00:00, last15m_closed_end=2026-10-28T18:15+00:00, prior8high=0.111150, depth_time=2026-10-28T18:15:22+00:00, book20_bid_proxy_usdt=128655, book20_ask_proxy_usdt=115396, funding_indicative=-0.000092, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.72%, turnover=6512556. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-28T18:15:01+00:00, last15m_closed_end=2026-10-28T18:15+00:00, prior8high=0.046920, depth_time=2026-10-28T18:15:11+00:00, book20_bid_proxy_usdt=794795, book20_ask_proxy_usdt=748340, funding_indicative=-0.000013, next_funding_utc=2026-10-28T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.60%, turnover=5138806. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-28T18:15:01+00:00, last15m_closed_end=2026-10-28T18:15+00:00, prior8high=0.541200, depth_time=2026-10-28T18:15:08+00:00, book20_bid_proxy_usdt=252133, book20_ask_proxy_usdt=326326, funding_indicative=0.000024, next_funding_utc=2026-10-28T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.36%, turnover=14878840. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-28T18:15:01+00:00, last15m_closed_end=2026-10-28T18:15+00:00, prior8high=0.433500, depth_time=2026-10-28T18:15:15+00:00, book20_bid_proxy_usdt=2799037, book20_ask_proxy_usdt=2687370, funding_indicative=0.000007, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.43%, turnover=63378595. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
