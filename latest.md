# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T02:00:30Z**
- feed_generated_utc: 2026-10-31T02:00:32+00:00
- source_sha256: `d52e01ae9f7a2ec23cfa6ed92eee30fa3d64ecefaab5a47a145d2a997d2f0c7f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T02:00+00:00, close=77358.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T02:00+00:00, close=77358.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T00:00+00:00, close=77313.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.012397|-35.51|-64.57|-35.23|6232958|4.04|
|Q_USDT|0.035860|-24.12|-69.69|-23.84|19118069|8.37|
|EVAA_USDT|1.151200|-10.75|119.31|-10.47|6478943|1.74|
|BTW_USDT|1.124300|-7.63|-33.95|-7.35|9322541|2.67|
|BEAT_USDT|0.097760|-7.53|34.67|-7.25|8435993|1.02|
|BLESS_USDT|0.009320|-5.39|14.20|-5.11|12272714|1.07|
|TRX_USDT|0.324920|-3.41|-1.34|-3.13|7862116|0.62|
|HYPE_USDT|89.647000|-3.34|14.33|-3.06|118926194|0.11|
|LIT_USDT|2.782000|-2.86|-16.30|-2.58|6143712|2.52|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.012397|0.012618|0.012397|1.57|Y|Y/Y|Y/Y|Y|Y|
|BEAT_USDT|0.097760|0.096630|0.097760|1.35|N|Y/Y|N/N|Y|N|
|BLESS_USDT|0.009320|0.009223|0.009315|1.08|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.124300|1.107500|1.124300|0.36|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.151200|1.106900|1.150900|0.52|N|Y/Y|N/N|Y|N|
|HYPE_USDT|89.647000|89.156000|89.647000|0.64|N|Y/Y|N/N|Y|N|
|LIT_USDT|2.782000|2.749900|2.782000|1.03|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.035860|0.035810|0.035840|5.92|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.324920|0.321930|0.324920|1.34|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T02:00:01+00:00, last15m_closed_end=2026-10-31T02:00+00:00, prior8high=0.014222, depth_time=2026-10-31T02:00:09+00:00, book20_bid_proxy_usdt=4109, book20_ask_proxy_usdt=6534, funding_indicative=-0.000042, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-35.51%, turnover=6232958. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T02:00:01+00:00, last15m_closed_end=2026-10-31T02:00+00:00, prior8high=0.106950, depth_time=2026-10-31T02:00:19+00:00, book20_bid_proxy_usdt=10875, book20_ask_proxy_usdt=12120, funding_indicative=0.000163, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.53%, turnover=8435993. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-10-31T02:00:01+00:00, last15m_closed_end=2026-10-31T02:00+00:00, prior8high=0.009963, depth_time=2026-10-31T02:00:21+00:00, book20_bid_proxy_usdt=15655, book20_ask_proxy_usdt=17454, funding_indicative=0.000054, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.39%, turnover=12272714. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T02:00:01+00:00, last15m_closed_end=2026-10-31T02:00+00:00, prior8high=1.161000, depth_time=2026-10-31T02:00:16+00:00, book20_bid_proxy_usdt=13944, book20_ask_proxy_usdt=18474, funding_indicative=-0.000395, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.63%, turnover=9322541. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-31T02:00:01+00:00, last15m_closed_end=2026-10-31T02:00+00:00, prior8high=1.176200, depth_time=2026-10-31T02:00:13+00:00, book20_bid_proxy_usdt=12315, book20_ask_proxy_usdt=4780, funding_indicative=0.000110, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.75%, turnover=6478943. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T02:00:00+00:00, last15m_closed_end=2026-10-31T02:00+00:00, prior8high=90.278000, depth_time=2026-10-31T02:00:27+00:00, book20_bid_proxy_usdt=31288, book20_ask_proxy_usdt=95802, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.34%, turnover=118926194. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-31T02:00:01+00:00, last15m_closed_end=2026-10-31T02:00+00:00, prior8high=2.789800, depth_time=2026-10-31T02:00:29+00:00, book20_bid_proxy_usdt=24953, book20_ask_proxy_usdt=28494, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.86%, turnover=6143712. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T02:00:01+00:00, last15m_closed_end=2026-10-31T02:00+00:00, prior8high=0.049970, depth_time=2026-10-31T02:00:11+00:00, book20_bid_proxy_usdt=23168, book20_ask_proxy_usdt=41909, funding_indicative=-0.000194, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-24.12%, turnover=19118069. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T02:00:00+00:00, last15m_closed_end=2026-10-31T02:00+00:00, prior8high=0.330600, depth_time=2026-10-31T02:00:23+00:00, book20_bid_proxy_usdt=25342, book20_ask_proxy_usdt=48377, funding_indicative=-0.001342, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.41%, turnover=7862116. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
