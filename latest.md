# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T02:45:22Z**
- feed_generated_utc: 2026-10-31T02:45:24+00:00
- source_sha256: `1b0f6c19e7cadb2375b62d9eb22b9273effad571eed24d5539b6b532fb11bb89`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T02:45+00:00, close=77403.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T02:00+00:00, close=77358.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T00:00+00:00, close=77313.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.011569|-38.85|-66.94|-38.63|6630040|5.19|
|BEAT_USDT|0.097300|-7.46|34.04|-7.24|8835472|4.12|
|BLESS_USDT|0.009423|-4.34|15.46|-4.12|12579888|3.18|
|TRX_USDT|0.324240|-3.35|-1.54|-3.13|8293461|0.31|
|HYPE_USDT|90.106000|-2.42|14.92|-2.20|119873210|0.11|
|LIT_USDT|2.787900|-1.28|-16.12|-1.06|6275587|0.36|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.011569|0.011735|0.011561|1.27|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.097300|0.096310|0.097320|1.63|N|Y/Y|N/N|Y|N|
|BLESS_USDT|0.009423|0.009190|0.009423|1.79|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|90.106000|89.156000|90.084000|0.58|N|Y/Y|N/N|Y|N|
|LIT_USDT|2.787900|2.751900|2.787200|2.73|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.324240|0.321930|0.324240|0.24|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T02:45:02+00:00, last15m_closed_end=2026-10-31T02:45+00:00, prior8high=0.014222, depth_time=2026-10-31T02:45:08+00:00, book20_bid_proxy_usdt=4003, book20_ask_proxy_usdt=29247, funding_indicative=-0.000092, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-38.85%, turnover=6630040. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T02:45:02+00:00, last15m_closed_end=2026-10-31T02:45+00:00, prior8high=0.105170, depth_time=2026-10-31T02:45:10+00:00, book20_bid_proxy_usdt=13677, book20_ask_proxy_usdt=10572, funding_indicative=0.000111, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.46%, turnover=8835472. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-10-31T02:45:02+00:00, last15m_closed_end=2026-10-31T02:45+00:00, prior8high=0.009853, depth_time=2026-10-31T02:45:14+00:00, book20_bid_proxy_usdt=8374, book20_ask_proxy_usdt=14595, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.34%, turnover=12579888. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T02:45:02+00:00, last15m_closed_end=2026-10-31T02:45+00:00, prior8high=90.118000, depth_time=2026-10-31T02:45:18+00:00, book20_bid_proxy_usdt=91700, book20_ask_proxy_usdt=42074, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.42%, turnover=119873210. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-31T02:45:03+00:00, last15m_closed_end=2026-10-31T02:45+00:00, prior8high=2.792300, depth_time=2026-10-31T02:45:21+00:00, book20_bid_proxy_usdt=19589, book20_ask_proxy_usdt=20052, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.28%, turnover=6275587. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T02:45:02+00:00, last15m_closed_end=2026-10-31T02:45+00:00, prior8high=0.327100, depth_time=2026-10-31T02:45:12+00:00, book20_bid_proxy_usdt=25901, book20_ask_proxy_usdt=39347, funding_indicative=-0.001601, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.35%, turnover=8293461. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
