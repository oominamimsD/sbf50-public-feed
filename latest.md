# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T01:00:37Z**
- feed_generated_utc: 2026-11-05T01:00:38+00:00
- source_sha256: `eae5573be8360c7040550aa13b2986f448b481a745e4e599e661142e19ab6c81`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T01:00+00:00, close=80509.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-05T01:00+00:00, close=80509.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-05T00:00+00:00, close=80466.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002438|-23.54|-87.86|-25.04|16139117|4.10|
|TRUMPOFFICIAL_USDT|1.244000|-12.76|-27.20|-14.26|27138224|8.04|
|VVV_USDT|21.230000|-9.58|-10.86|-11.08|5094567|1.89|
|BTW_USDT|1.014700|-8.30|-41.61|-9.80|6003040|0.98|
|EVAA_USDT|1.522300|-7.05|2.51|-8.55|5000668|1.97|
|IDOL_USDT|0.021212|-4.21|145.02|-5.71|6128202|0.47|
|ZRO_USDT|1.811700|-4.12|5.82|-5.62|10463659|0.55|
|WLFI_USDT|0.047690|-3.69|-9.12|-5.19|5018845|2.10|
|WLD_USDT|0.376300|-3.63|-13.05|-5.13|73350878|2.66|
|OP_USDT|0.109630|-3.35|-1.30|-4.85|10931616|0.91|
|PUMPFUN_USDT|0.004281|-3.29|1.75|-4.79|16278975|2.34|
|CLANKER_USDT|17.050000|-0.87|27.61|-2.37|20017506|5.87|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002438|0.002379|0.002438|0.60|N|Y/Y|Y/Y|N|N|
|BTW_USDT|1.014700|1.012900|1.014700|1.51|N|Y/Y|Y/N|N|N|
|CLANKER_USDT|17.050000|16.300000|17.050000|0.46|N|Y/Y|N/N|N|N|
|EVAA_USDT|1.522300|1.521100|1.522300|0.27|N|Y/Y|N/N|N|N|
|IDOL_USDT|0.021212|0.021242|0.021211|0.72|N|Y/Y|N/N|N|N|
|OP_USDT|0.109630|0.109240|0.109630|2.38|N|Y/Y|Y/N|N|N|
|PUMPFUN_USDT|0.004281|0.004236|0.004281|0.60|N|Y/Y|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.244000|1.243000|1.244000|1.25|N|Y/Y|Y/Y|N|N|
|VVV_USDT|21.230000|20.977000|21.230000|0.89|N|Y/Y|Y/Y|N|N|
|WLD_USDT|0.376300|0.373600|0.376300|6.76|N|Y/Y|Y/Y|N|N|
|WLFI_USDT|0.047690|0.047580|0.047690|0.72|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.811700|1.811900|1.811700|0.40|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T01:00:00+00:00, last15m_closed_end=2026-11-05T01:00+00:00, prior8high=0.002594, depth_time=2026-11-05T01:00:07+00:00, book20_bid_proxy_usdt=91973, book20_ask_proxy_usdt=59694, funding_indicative=-0.001011, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-23.54%, turnover=16139117. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-05T01:00:00+00:00, last15m_closed_end=2026-11-05T01:00+00:00, prior8high=1.044500, depth_time=2026-11-05T01:00:13+00:00, book20_bid_proxy_usdt=22309, book20_ask_proxy_usdt=38615, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.30%, turnover=6003040. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CLANKER_USDT: quote_utc=2026-11-05T01:00:00+00:00, last15m_closed_end=2026-11-05T01:00+00:00, prior8high=20.470000, depth_time=2026-11-05T01:00:35+00:00, book20_bid_proxy_usdt=143848, book20_ask_proxy_usdt=141681, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.87%, turnover=20017506. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-11-05T01:00:00+00:00, last15m_closed_end=2026-11-05T01:00+00:00, prior8high=1.574200, depth_time=2026-11-05T01:00:16+00:00, book20_bid_proxy_usdt=50797, book20_ask_proxy_usdt=19442, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.05%, turnover=5000668. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-05T01:00:00+00:00, last15m_closed_end=2026-11-05T01:00+00:00, prior8high=0.022404, depth_time=2026-11-05T01:00:17+00:00, book20_bid_proxy_usdt=3849, book20_ask_proxy_usdt=8571, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.21%, turnover=6128202. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-05T01:00:00+00:00, last15m_closed_end=2026-11-05T01:00+00:00, prior8high=0.112460, depth_time=2026-11-05T01:00:31+00:00, book20_bid_proxy_usdt=72525, book20_ask_proxy_usdt=114999, funding_indicative=0.000010, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.35%, turnover=10931616. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-05T01:00:00+00:00, last15m_closed_end=2026-11-05T01:00+00:00, prior8high=0.004317, depth_time=2026-11-05T01:00:33+00:00, book20_bid_proxy_usdt=2329817, book20_ask_proxy_usdt=2297208, funding_indicative=0.000005, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.29%, turnover=16278975. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-05T01:00:00+00:00, last15m_closed_end=2026-11-05T01:00+00:00, prior8high=1.286000, depth_time=2026-11-05T01:00:10+00:00, book20_bid_proxy_usdt=1030857, book20_ask_proxy_usdt=946017, funding_indicative=-0.000437, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-12.76%, turnover=27138224. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-05T01:00:00+00:00, last15m_closed_end=2026-11-05T01:00+00:00, prior8high=22.471000, depth_time=2026-11-05T01:00:12+00:00, book20_bid_proxy_usdt=32238, book20_ask_proxy_usdt=16091, funding_indicative=-0.000428, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.58%, turnover=5094567. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-05T01:00:00+00:00, last15m_closed_end=2026-11-05T01:00+00:00, prior8high=0.383400, depth_time=2026-11-05T01:00:28+00:00, book20_bid_proxy_usdt=2897039, book20_ask_proxy_usdt=2203842, funding_indicative=-0.000374, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.63%, turnover=73350878. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLFI_USDT: quote_utc=2026-11-05T01:00:00+00:00, last15m_closed_end=2026-11-05T01:00+00:00, prior8high=0.048300, depth_time=2026-11-05T01:00:25+00:00, book20_bid_proxy_usdt=367200, book20_ask_proxy_usdt=311505, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.69%, turnover=5018845. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-05T01:00:00+00:00, last15m_closed_end=2026-11-05T01:00+00:00, prior8high=1.856300, depth_time=2026-11-05T01:00:22+00:00, book20_bid_proxy_usdt=28428, book20_ask_proxy_usdt=100731, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.12%, turnover=10463659. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
