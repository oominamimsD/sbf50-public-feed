# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-24T23:00:22Z**
- feed_generated_utc: 2026-10-24T23:00:25+00:00
- source_sha256: `5e2ae59a93c214fec986242ce84ee589b5d933ac5f4ba3bad2061263d0ad08a0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-24T23:00+00:00, close=80571.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-24T23:00+00:00, close=80571.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-24T20:00+00:00, close=80455.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BIRB_USDT|0.085760|-12.18|76.75|-13.19|11622509|3.50|
|IRYS_USDT|0.044510|-3.34|248.82|-4.35|33696364|4.49|
|BTW_USDT|1.686800|-3.12|-25.67|-4.13|11050346|2.96|
|STRK_USDT|0.046480|-1.75|-29.73|-2.76|8238614|2.15|
|DOT_USDT|1.038300|-1.02|-7.07|-2.03|11231514|1.93|
|TIA_USDT|0.528800|-0.97|-19.63|-1.98|26498668|1.89|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.085760|0.083640|0.085560|0.89|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.686800|1.670600|1.685900|1.86|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.038300|1.033000|1.038300|0.43|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.044510|0.042610|0.044840|1.36|N|Y/Y|Y/N|Y|N|
|STRK_USDT|0.046480|0.046170|0.046480|0.20|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.528800|0.527500|0.528800|1.39|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-24T23:00:03+00:00, last15m_closed_end=2026-10-24T23:00+00:00, prior8high=0.094010, depth_time=2026-10-24T23:00:08+00:00, book20_bid_proxy_usdt=19836, book20_ask_proxy_usdt=14346, funding_indicative=-0.008771, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=4, 24h_change=-12.18%, turnover=11622509. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-24T23:00:03+00:00, last15m_closed_end=2026-10-24T23:00+00:00, prior8high=1.761200, depth_time=2026-10-24T23:00:13+00:00, book20_bid_proxy_usdt=12829, book20_ask_proxy_usdt=14195, funding_indicative=-0.006466, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.12%, turnover=11050346. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-24T23:00:04+00:00, last15m_closed_end=2026-10-24T23:00+00:00, prior8high=1.040800, depth_time=2026-10-24T23:00:18+00:00, book20_bid_proxy_usdt=300293, book20_ask_proxy_usdt=552260, funding_indicative=-0.000093, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.02%, turnover=11231514. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-24T23:00:03+00:00, last15m_closed_end=2026-10-24T23:00+00:00, prior8high=0.045590, depth_time=2026-10-24T23:00:11+00:00, book20_bid_proxy_usdt=57195, book20_ask_proxy_usdt=44560, funding_indicative=0.000012, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=1, 24h_change=-3.34%, turnover=33696364. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-24T23:00:04+00:00, last15m_closed_end=2026-10-24T23:00+00:00, prior8high=0.047030, depth_time=2026-10-24T23:00:16+00:00, book20_bid_proxy_usdt=1094076, book20_ask_proxy_usdt=775153, funding_indicative=0.000035, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.75%, turnover=8238614. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-24T23:00:04+00:00, last15m_closed_end=2026-10-24T23:00+00:00, prior8high=0.533100, depth_time=2026-10-24T23:00:19+00:00, book20_bid_proxy_usdt=327110, book20_ask_proxy_usdt=267243, funding_indicative=-0.000063, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.97%, turnover=26498668. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
