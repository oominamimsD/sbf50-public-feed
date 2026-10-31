# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T08:15:37Z**
- feed_generated_utc: 2026-10-31T08:15:40+00:00
- source_sha256: `e1281f99b108c15a5e79c7c4e1fb76efbd98c681fffc08baa08d30521181c141`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T08:15+00:00, close=77381.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T08:00+00:00, close=77316.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T08:00+00:00, close=77316.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.010396|-45.05|-70.29|-44.80|9281639|0.96|
|Q_USDT|0.032350|-31.86|-72.66|-31.61|18022606|3.10|
|BEAT_USDT|0.097350|-7.41|34.10|-7.16|8134463|1.03|
|EVAA_USDT|1.208000|-5.77|130.13|-5.52|5609709|4.96|
|BTW_USDT|1.138800|-5.06|-33.10|-4.81|9467999|1.76|
|HYPE_USDT|87.707000|-5.02|11.86|-4.77|102670588|0.68|
|TRX_USDT|0.321370|-4.21|-2.41|-3.96|5792453|0.31|
|WLD_USDT|0.396900|-3.64|-25.45|-3.39|48350548|2.52|
|ZRO_USDT|1.698500|-2.93|-6.12|-2.68|5541142|0.59|
|FET_USDT|0.162200|-2.64|-13.40|-2.39|6043091|6.17|
|DASH_USDT|47.800000|-2.52|-11.23|-2.27|13477198|4.18|
|LTC_USDT|54.710000|-1.81|-6.39|-1.56|6536950|3.66|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.010396|0.009349|0.010579|10.84|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.097350|0.096280|0.097350|0.50|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.138800|1.124600|1.138800|0.94|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|47.800000|47.750000|47.800000|2.71|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.208000|1.168700|1.208000|0.45|N|N/N|N/N|Y|N|
|FET_USDT|0.162200|0.161900|0.162100|0.79|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|87.707000|87.999000|87.706000|3.74|Y|Y/Y|N/N|Y|N|
|LTC_USDT|54.710000|54.780000|54.720000|12.14|Y|Y/Y|Y/Y|Y|Y|
|Q_USDT|0.032350|0.030010|0.032350|0.71|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.321370|0.321300|0.321360|3.24|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.396900|0.396200|0.396900|4.22|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.698500|1.676300|1.698600|2.34|N|Y/N|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T08:15:02+00:00, last15m_closed_end=2026-10-31T08:15+00:00, prior8high=0.013245, depth_time=2026-10-31T08:15:09+00:00, book20_bid_proxy_usdt=5989, book20_ask_proxy_usdt=3349, funding_indicative=-0.001589, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-45.05%, turnover=9281639. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T08:15:02+00:00, last15m_closed_end=2026-10-31T08:15+00:00, prior8high=0.098520, depth_time=2026-10-31T08:15:11+00:00, book20_bid_proxy_usdt=15143, book20_ask_proxy_usdt=8314, funding_indicative=0.000168, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.41%, turnover=8134463. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T08:15:02+00:00, last15m_closed_end=2026-10-31T08:15+00:00, prior8high=1.181700, depth_time=2026-10-31T08:15:19+00:00, book20_bid_proxy_usdt=7417, book20_ask_proxy_usdt=15660, funding_indicative=-0.000405, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.06%, turnover=9467999. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T08:15:02+00:00, last15m_closed_end=2026-10-31T08:15+00:00, prior8high=48.190000, depth_time=2026-10-31T08:15:33+00:00, book20_bid_proxy_usdt=1089231, book20_ask_proxy_usdt=494528, funding_indicative=0.000082, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.52%, turnover=13477198. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-31T08:15:02+00:00, last15m_closed_end=2026-10-31T08:15+00:00, prior8high=1.226600, depth_time=2026-10-31T08:15:14+00:00, book20_bid_proxy_usdt=12471, book20_ask_proxy_usdt=6509, funding_indicative=0.000230, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.77%, turnover=5609709. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T08:15:02+00:00, last15m_closed_end=2026-10-31T08:15+00:00, prior8high=0.164200, depth_time=2026-10-31T08:15:32+00:00, book20_bid_proxy_usdt=1143316, book20_ask_proxy_usdt=990824, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.64%, turnover=6043091. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T08:15:01+00:00, last15m_closed_end=2026-10-31T08:15+00:00, prior8high=89.040000, depth_time=2026-10-31T08:15:20+00:00, book20_bid_proxy_usdt=102576, book20_ask_proxy_usdt=678141, funding_indicative=0.000050, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.02%, turnover=102670588. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-31T08:15:02+00:00, last15m_closed_end=2026-10-31T08:15+00:00, prior8high=55.350000, depth_time=2026-10-31T08:15:36+00:00, book20_bid_proxy_usdt=1102009, book20_ask_proxy_usdt=1176197, funding_indicative=0.000022, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.81%, turnover=6536950. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T08:15:02+00:00, last15m_closed_end=2026-10-31T08:15+00:00, prior8high=0.033340, depth_time=2026-10-31T08:15:12+00:00, book20_bid_proxy_usdt=35503, book20_ask_proxy_usdt=47404, funding_indicative=-0.000799, next_funding_utc=2026-10-31T09:00:00+00:00, funding_cycle_h=1, 24h_change=-31.86%, turnover=18022606. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T08:15:02+00:00, last15m_closed_end=2026-10-31T08:15+00:00, prior8high=0.326220, depth_time=2026-10-31T08:15:24+00:00, book20_bid_proxy_usdt=105702, book20_ask_proxy_usdt=109375, funding_indicative=-0.000374, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.21%, turnover=5792453. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T08:15:02+00:00, last15m_closed_end=2026-10-31T08:15+00:00, prior8high=0.401700, depth_time=2026-10-31T08:15:26+00:00, book20_bid_proxy_usdt=2961864, book20_ask_proxy_usdt=2703382, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.64%, turnover=48350548. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-31T08:15:02+00:00, last15m_closed_end=2026-10-31T08:15+00:00, prior8high=1.728600, depth_time=2026-10-31T08:15:29+00:00, book20_bid_proxy_usdt=24914, book20_ask_proxy_usdt=45742, funding_indicative=0.000050, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.93%, turnover=5541142. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
