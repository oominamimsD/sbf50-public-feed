# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T15:30:37Z**
- feed_generated_utc: 2026-10-28T15:30:42+00:00
- source_sha256: `0d7f8904cbca28704fe270d36d0e69e0d8fcba7cecc2e34b8d0bd8988e612e12`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.08 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T15:30+00:00, close=80681.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-28T15:00+00:00, close=80572.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-28T12:00+00:00, close=81305.7, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BEAT_USDT|0.080170|-11.98|7.30|-12.15|11616715|2.49|
|ENA_USDT|0.195740|-8.00|3.08|-8.17|85444262|0.51|
|AKE_USDT|0.019506|-7.66|-37.26|-7.83|6779821|2.05|
|INJ_USDT|7.782000|-5.00|-9.51|-5.17|24622220|1.28|
|QNT_USDT|194.410000|-1.75|-0.38|-1.92|67406036|0.51|
|DASH_USDT|53.250000|-1.69|6.62|-1.86|14192585|1.88|
|PUMPFUN_USDT|0.004213|-1.68|-6.60|-1.85|13359785|2.37|
|SILVER_USDT|53.740000|-1.64|-7.26|-1.81|251249325|1.86|
|ZEC_USDT|1274.120000|-1.43|6.97|-1.60|1576521635|1.96|
|ASTER_USDT|0.703700|-1.30|-1.44|-1.47|5697659|1.42|
|UNI_USDT|7.073000|-1.20|-2.72|-1.37|14320785|1.41|
|ADA_USDT|0.203300|-1.11|-8.17|-1.28|38431005|4.92|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.203300|0.201100|0.203300|0.58|N|Y/Y|N/N|Y|N|
|AKE_USDT|0.019506|0.019128|0.019506|0.64|N|Y/Y|Y/Y|Y|N|
|ASTER_USDT|0.703700|0.701400|0.703600|0.74|N|Y/Y|N/N|Y|N|
|BEAT_USDT|0.080170|0.078520|0.080170|0.29|N|Y/Y|Y/N|Y|N|
|DASH_USDT|53.250000|52.690000|53.250000|0.32|N|Y/Y|N/N|Y|N|
|ENA_USDT|0.195740|0.192810|0.195770|0.30|N|Y/Y|Y/N|Y|N|
|INJ_USDT|7.782000|7.748000|7.784000|0.79|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004213|0.004162|0.004214|0.43|N|Y/Y|N/N|Y|N|
|QNT_USDT|194.410000|192.380000|194.430000|0.69|N|Y/Y|N/N|Y|N|
|SILVER_USDT|53.740000|53.600000|53.730000|0.43|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.073000|6.969000|7.073000|2.05|N|Y/Y|N/N|Y|N|
|ZEC_USDT|1274.120000|1268.350000|1274.670000|0.91|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-10-28T15:30:03+00:00, last15m_closed_end=2026-10-28T15:30+00:00, prior8high=0.203700, depth_time=2026-10-28T15:30:36+00:00, book20_bid_proxy_usdt=7163905, book20_ask_proxy_usdt=5598620, funding_indicative=-0.000056, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.11%, turnover=38431005. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-28T15:30:03+00:00, last15m_closed_end=2026-10-28T15:30+00:00, prior8high=0.019953, depth_time=2026-10-28T15:30:14+00:00, book20_bid_proxy_usdt=7975, book20_ask_proxy_usdt=4954, funding_indicative=0.000050, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.66%, turnover=6779821. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ASTER_USDT: quote_utc=2026-10-28T15:30:03+00:00, last15m_closed_end=2026-10-28T15:30+00:00, prior8high=0.706400, depth_time=2026-10-28T15:30:29+00:00, book20_bid_proxy_usdt=963026, book20_ask_proxy_usdt=897233, funding_indicative=0.000027, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.30%, turnover=5697659. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-28T15:30:03+00:00, last15m_closed_end=2026-10-28T15:30+00:00, prior8high=0.080780, depth_time=2026-10-28T15:30:10+00:00, book20_bid_proxy_usdt=18224, book20_ask_proxy_usdt=9367, funding_indicative=0.000050, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-11.98%, turnover=11616715. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-28T15:30:03+00:00, last15m_closed_end=2026-10-28T15:30+00:00, prior8high=53.280000, depth_time=2026-10-28T15:30:14+00:00, book20_bid_proxy_usdt=920822, book20_ask_proxy_usdt=679063, funding_indicative=0.000085, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.69%, turnover=14192585. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-28T15:30:03+00:00, last15m_closed_end=2026-10-28T15:30+00:00, prior8high=0.199740, depth_time=2026-10-28T15:30:12+00:00, book20_bid_proxy_usdt=162144, book20_ask_proxy_usdt=127291, funding_indicative=-0.000040, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.00%, turnover=85444262. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-28T15:30:03+00:00, last15m_closed_end=2026-10-28T15:30+00:00, prior8high=7.877000, depth_time=2026-10-28T15:30:17+00:00, book20_bid_proxy_usdt=407605, book20_ask_proxy_usdt=277698, funding_indicative=0.000085, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.00%, turnover=24622220. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-28T15:30:03+00:00, last15m_closed_end=2026-10-28T15:30+00:00, prior8high=0.004262, depth_time=2026-10-28T15:30:24+00:00, book20_bid_proxy_usdt=2150968, book20_ask_proxy_usdt=2795878, funding_indicative=0.000026, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.68%, turnover=13359785. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-28T15:30:03+00:00, last15m_closed_end=2026-10-28T15:30+00:00, prior8high=197.860000, depth_time=2026-10-28T15:30:18+00:00, book20_bid_proxy_usdt=112910, book20_ask_proxy_usdt=110821, funding_indicative=-0.000192, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.75%, turnover=67406036. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-28T15:30:03+00:00, last15m_closed_end=2026-10-28T15:30+00:00, prior8high=54.330000, depth_time=2026-10-28T15:30:26+00:00, book20_bid_proxy_usdt=43129742, book20_ask_proxy_usdt=55693309, funding_indicative=0.000043, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.64%, turnover=251249325. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-28T15:30:03+00:00, last15m_closed_end=2026-10-28T15:30+00:00, prior8high=7.068000, depth_time=2026-10-28T15:30:34+00:00, book20_bid_proxy_usdt=2217565, book20_ask_proxy_usdt=1885444, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.20%, turnover=14320785. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-28T15:30:03+00:00, last15m_closed_end=2026-10-28T15:30+00:00, prior8high=1292.460000, depth_time=2026-10-28T15:30:28+00:00, book20_bid_proxy_usdt=1646505, book20_ask_proxy_usdt=212410, funding_indicative=0.000088, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.43%, turnover=1576521635. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
