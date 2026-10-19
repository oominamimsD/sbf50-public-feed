# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T10:30:21Z**
- feed_generated_utc: 2026-10-19T10:30:23+00:00
- source_sha256: `05b5a5b5d2a4b3387fc608e3fa0bdba2e0766c57b57d1e360e52b17f1a766a76`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T10:30+00:00, close=82299.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-19T10:00+00:00, close=82729.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T08:00+00:00, close=82695, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|2.141100|-7.12|27.27|-8.55|21509899|1.40|
|STRK_USDT|0.059090|-4.01|-50.45|-5.44|18039575|3.38|
|HBAR_USDT|0.083360|-2.82|-11.11|-4.25|44328243|1.20|
|TIA_USDT|0.605700|-1.97|2.88|-3.40|52927953|1.65|
|SAND_USDT|0.057820|-1.59|-12.97|-3.02|15603719|3.46|
|SEI_USDT|0.059900|-0.56|-15.50|-1.99|8831982|3.34|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|2.141100|2.149000|2.141100|1.51|Y|Y/Y|N/N|N|N|
|HBAR_USDT|0.083360|0.083930|0.083360|4.09|Y|Y/Y|Y/Y|N|Y|
|SAND_USDT|0.057820|0.058090|0.057820|1.30|N|Y/Y|N/N|N|N|
|SEI_USDT|0.059900|0.060140|0.059890|5.34|Y|Y/Y|Y/Y|N|Y|
|STRK_USDT|0.059090|0.058950|0.059090|3.81|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.605700|0.605200|0.605700|0.68|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-19T10:29:59+00:00, last15m_closed_end=2026-10-19T10:30+00:00, prior8high=2.310800, depth_time=2026-10-19T10:30:07+00:00, book20_bid_proxy_usdt=8728, book20_ask_proxy_usdt=7032, funding_indicative=-0.000592, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.12%, turnover=21509899. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T10:29:59+00:00, last15m_closed_end=2026-10-19T10:30+00:00, prior8high=0.084960, depth_time=2026-10-19T10:30:12+00:00, book20_bid_proxy_usdt=374549, book20_ask_proxy_usdt=725626, funding_indicative=-0.000042, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.82%, turnover=44328243. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-19T10:29:59+00:00, last15m_closed_end=2026-10-19T10:30+00:00, prior8high=0.059300, depth_time=2026-10-19T10:30:17+00:00, book20_bid_proxy_usdt=455798, book20_ask_proxy_usdt=753606, funding_indicative=-0.003647, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.59%, turnover=15603719. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-19T10:29:59+00:00, last15m_closed_end=2026-10-19T10:30+00:00, prior8high=0.061600, depth_time=2026-10-19T10:30:20+00:00, book20_bid_proxy_usdt=265064, book20_ask_proxy_usdt=447732, funding_indicative=0.000037, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.56%, turnover=8831982. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T10:29:59+00:00, last15m_closed_end=2026-10-19T10:30+00:00, prior8high=0.059970, depth_time=2026-10-19T10:30:10+00:00, book20_bid_proxy_usdt=610566, book20_ask_proxy_usdt=647482, funding_indicative=0.000050, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.01%, turnover=18039575. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T10:29:59+00:00, last15m_closed_end=2026-10-19T10:30+00:00, prior8high=0.614100, depth_time=2026-10-19T10:30:14+00:00, book20_bid_proxy_usdt=164610, book20_ask_proxy_usdt=243488, funding_indicative=0.000004, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.97%, turnover=52927953. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
