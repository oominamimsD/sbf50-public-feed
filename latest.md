# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T20:45:38Z**
- feed_generated_utc: 2026-11-10T20:45:39+00:00
- source_sha256: `909ef95ccf30227037204da8edc41bf5f311bc6d94f123211da429a40553fb75`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T20:45+00:00, close=73654.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-10T20:00+00:00, close=73437.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T20:00+00:00, close=73437.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PIEVERSE_USDT|1.802200|-11.05|53.32|-11.69|7036189|1.66|
|DASH_USDT|42.800000|-5.18|-7.23|-5.82|13618440|2.34|
|ZEC_USDT|1048.210000|-4.12|-12.92|-4.76|2323309683|0.10|
|AKE_USDT|0.002821|-3.19|-32.12|-3.83|15932089|3.54|
|UNI_USDT|6.679000|-2.21|-9.16|-2.85|29605160|1.50|
|JCT_USDT|0.005201|-1.40|24.48|-2.04|20838938|1.92|
|ANTHROPIC_USDT|1299.930000|-1.33|-22.34|-1.97|8133057|0.39|
|ARB_USDT|0.159580|-1.11|-0.18|-1.75|34556967|0.63|
|DOT_USDT|0.834200|-0.89|-11.50|-1.53|8898874|1.20|
|ENA_USDT|0.147950|-0.83|-14.07|-1.47|30652062|0.68|
|PEPE_USDT|0.000005|-0.75|6.51|-1.39|70778057|3.45|
|ONDO_USDT|0.363300|-0.68|-6.65|-1.32|14992098|2.75|
|WLD_USDT|0.306200|-0.61|-17.71|-1.25|29791711|3.27|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002821|0.002801|0.002821|0.58|N|Y/Y|Y/Y|Y|N|
|ANTHROPIC_USDT|1299.930000|1285.250000|1299.930000|0.18|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.159580|0.158120|0.159580|1.06|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|42.800000|42.600000|42.800000|0.50|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.834200|0.832700|0.834300|1.02|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.147950|0.147450|0.147950|0.23|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.005201|0.005022|0.005201|0.59|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.363300|0.358400|0.363500|1.32|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.88|N|Y/N|N/N|Y|N|
|PIEVERSE_USDT|1.802200|1.795400|1.802200|0.84|N|Y/Y|N/N|Y|N|
|UNI_USDT|6.679000|6.649000|6.679000|0.41|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.306200|0.304400|0.306200|0.79|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1048.210000|1020.790000|1048.460000|0.79|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-10T20:44:59+00:00, last15m_closed_end=2026-11-10T20:45+00:00, prior8high=0.002915, depth_time=2026-11-10T20:45:14+00:00, book20_bid_proxy_usdt=37744, book20_ask_proxy_usdt=38007, funding_indicative=0.000050, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.19%, turnover=15932089. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-10T20:44:58+00:00, last15m_closed_end=2026-11-10T20:45+00:00, prior8high=1302.440000, depth_time=2026-11-10T20:45:22+00:00, book20_bid_proxy_usdt=3565, book20_ask_proxy_usdt=15893, funding_indicative=0.000050, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.33%, turnover=8133057. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T20:44:59+00:00, last15m_closed_end=2026-11-10T20:45+00:00, prior8high=0.160720, depth_time=2026-11-10T20:45:25+00:00, book20_bid_proxy_usdt=71152, book20_ask_proxy_usdt=61360, funding_indicative=-0.000193, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.11%, turnover=34556967. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T20:44:59+00:00, last15m_closed_end=2026-11-10T20:45+00:00, prior8high=43.620000, depth_time=2026-11-10T20:45:09+00:00, book20_bid_proxy_usdt=986290, book20_ask_proxy_usdt=579422, funding_indicative=-0.000176, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.18%, turnover=13618440. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T20:44:59+00:00, last15m_closed_end=2026-11-10T20:45+00:00, prior8high=0.844500, depth_time=2026-11-10T20:45:26+00:00, book20_bid_proxy_usdt=691637, book20_ask_proxy_usdt=428951, funding_indicative=-0.000008, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.89%, turnover=8898874. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-10T20:44:59+00:00, last15m_closed_end=2026-11-10T20:45+00:00, prior8high=0.150710, depth_time=2026-11-10T20:45:29+00:00, book20_bid_proxy_usdt=221295, book20_ask_proxy_usdt=148894, funding_indicative=0.000050, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.83%, turnover=30652062. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T20:44:59+00:00, last15m_closed_end=2026-11-10T20:45+00:00, prior8high=0.005277, depth_time=2026-11-10T20:45:19+00:00, book20_bid_proxy_usdt=46134, book20_ask_proxy_usdt=67700, funding_indicative=0.000215, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.40%, turnover=20838938. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-10T20:44:59+00:00, last15m_closed_end=2026-11-10T20:45+00:00, prior8high=0.366300, depth_time=2026-11-10T20:45:31+00:00, book20_bid_proxy_usdt=2274595, book20_ask_proxy_usdt=2722941, funding_indicative=-0.000006, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.68%, turnover=14992098. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-10T20:44:59+00:00, last15m_closed_end=2026-11-10T20:45+00:00, prior8high=0.000005, depth_time=2026-11-10T20:45:30+00:00, book20_bid_proxy_usdt=31893, book20_ask_proxy_usdt=49554, funding_indicative=0.000073, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.75%, turnover=70778057. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-10T20:44:59+00:00, last15m_closed_end=2026-11-10T20:45+00:00, prior8high=1.873800, depth_time=2026-11-10T20:45:06+00:00, book20_bid_proxy_usdt=21976, book20_ask_proxy_usdt=13677, funding_indicative=0.000178, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-11.05%, turnover=7036189. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-10T20:44:59+00:00, last15m_closed_end=2026-11-10T20:45+00:00, prior8high=6.774000, depth_time=2026-11-10T20:45:16+00:00, book20_bid_proxy_usdt=3191965, book20_ask_proxy_usdt=2895457, funding_indicative=-0.000012, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.21%, turnover=29605160. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-10T20:44:59+00:00, last15m_closed_end=2026-11-10T20:45+00:00, prior8high=0.310500, depth_time=2026-11-10T20:45:36+00:00, book20_bid_proxy_usdt=5730476, book20_ask_proxy_usdt=5210692, funding_indicative=0.000009, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.61%, turnover=29791711. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T20:44:59+00:00, last15m_closed_end=2026-11-10T20:45+00:00, prior8high=1044.410000, depth_time=2026-11-10T20:45:11+00:00, book20_bid_proxy_usdt=213999, book20_ask_proxy_usdt=263797, funding_indicative=0.000018, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.12%, turnover=2323309683. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
