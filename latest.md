# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-29T14:00:33Z**
- feed_generated_utc: 2026-10-29T14:00:35+00:00
- source_sha256: `d6ae1780155d4032e3a6aab167ae0af49f004ca2f48c667676dcfa6c7d9b7776`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1194; contracts: 1186; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-29T14:00+00:00, close=80275.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-29T14:00+00:00, close=80275.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-29T12:00+00:00, close=80133.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.042580|-26.31|-63.34|-26.02|33677196|9.39|
|BLESS_USDT|0.009653|-11.46|19.94|-11.17|9290698|9.32|
|EVAA_USDT|1.240200|-10.94|120.04|-10.65|18602528|5.64|
|JASMY_USDT|0.003868|-8.07|-20.67|-7.78|7642768|5.18|
|DASH_USDT|50.490000|-4.73|-5.21|-4.44|14561561|1.98|
|NEAR_USDT|4.449000|-3.17|-17.38|-2.88|103064401|2.25|
|SILVER_USDT|52.370000|-2.53|-9.17|-2.24|529576024|3.82|
|HBAR_USDT|0.074390|-2.00|-13.43|-1.71|14488496|1.34|
|WLD_USDT|0.421400|-1.88|-26.53|-1.59|77522834|2.37|
|XRP_USDT|1.290400|-1.71|-6.51|-1.42|285578828|0.78|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.009653|0.009420|0.009661|0.50|N|Y/Y|Y/N|Y|N|
|DASH_USDT|50.490000|49.890000|50.490000|1.24|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.240200|1.202700|1.240200|0.61|N|Y/Y|N/N|Y|N|
|HBAR_USDT|0.074390|0.073220|0.074400|1.03|N|N/Y|Y/Y|Y|N|
|JASMY_USDT|0.003868|0.003825|0.003868|1.19|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.449000|4.381000|4.449000|1.36|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.042580|0.039240|0.042590|0.36|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|52.370000|52.160000|52.370000|2.33|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.421400|0.416800|0.421400|0.79|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.290400|1.285700|1.290400|2.68|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-10-29T14:00:00+00:00, last15m_closed_end=2026-10-29T14:00+00:00, prior8high=0.009935, depth_time=2026-10-29T14:00:13+00:00, book20_bid_proxy_usdt=11702, book20_ask_proxy_usdt=4126, funding_indicative=0.000180, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-11.46%, turnover=9290698. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-29T14:00:01+00:00, last15m_closed_end=2026-10-29T14:00+00:00, prior8high=50.590000, depth_time=2026-10-29T14:00:20+00:00, book20_bid_proxy_usdt=456189, book20_ask_proxy_usdt=481646, funding_indicative=0.000026, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.73%, turnover=14561561. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-29T14:00:00+00:00, last15m_closed_end=2026-10-29T14:00+00:00, prior8high=1.285900, depth_time=2026-10-29T14:00:14+00:00, book20_bid_proxy_usdt=15206, book20_ask_proxy_usdt=12117, funding_indicative=0.000193, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.94%, turnover=18602528. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-29T14:00:01+00:00, last15m_closed_end=2026-10-29T14:00+00:00, prior8high=0.074510, depth_time=2026-10-29T14:00:27+00:00, book20_bid_proxy_usdt=724574, book20_ask_proxy_usdt=489159, funding_indicative=0.000100, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.00%, turnover=14488496. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JASMY_USDT: quote_utc=2026-10-29T14:00:01+00:00, last15m_closed_end=2026-10-29T14:00+00:00, prior8high=0.003998, depth_time=2026-10-29T14:00:17+00:00, book20_bid_proxy_usdt=101859, book20_ask_proxy_usdt=133325, funding_indicative=-0.000354, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.07%, turnover=7642768. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-29T14:00:00+00:00, last15m_closed_end=2026-10-29T14:00+00:00, prior8high=4.511000, depth_time=2026-10-29T14:00:23+00:00, book20_bid_proxy_usdt=464943, book20_ask_proxy_usdt=375975, funding_indicative=0.000083, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.17%, turnover=103064401. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-29T14:00:00+00:00, last15m_closed_end=2026-10-29T14:00+00:00, prior8high=0.042860, depth_time=2026-10-29T14:00:11+00:00, book20_bid_proxy_usdt=56602, book20_ask_proxy_usdt=41876, funding_indicative=0.000050, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-26.31%, turnover=33677196. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-29T14:00:00+00:00, last15m_closed_end=2026-10-29T14:00+00:00, prior8high=52.850000, depth_time=2026-10-29T14:00:25+00:00, book20_bid_proxy_usdt=55051340, book20_ask_proxy_usdt=44660456, funding_indicative=0.000085, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.53%, turnover=529576024. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-29T14:00:00+00:00, last15m_closed_end=2026-10-29T14:00+00:00, prior8high=0.424500, depth_time=2026-10-29T14:00:29+00:00, book20_bid_proxy_usdt=2720065, book20_ask_proxy_usdt=3411889, funding_indicative=0.000050, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.88%, turnover=77522834. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-10-29T14:00:00+00:00, last15m_closed_end=2026-10-29T14:00+00:00, prior8high=1.294800, depth_time=2026-10-29T14:00:32+00:00, book20_bid_proxy_usdt=3690023, book20_ask_proxy_usdt=2821263, funding_indicative=0.000100, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.71%, turnover=285578828. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
