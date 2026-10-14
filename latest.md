# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T13:00:44Z**
- feed_generated_utc: 2026-10-14T13:00:48+00:00
- source_sha256: `29cc6d903ba77cb4a3867a9503c4d3b5d5698dc132d5cd7e10d416b0c7da3d12`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T13:00+00:00, close=82699.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T13:00+00:00, close=82699.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T12:00+00:00, close=83424.1, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.078820|-9.32|51.02|-8.49|28428324|1.27|
|W_USDT|0.015603|-7.14|7.51|-6.31|6506740|3.85|
|TIA_USDT|0.544900|-5.61|14.40|-4.78|35443890|1.83|
|UNI_USDT|7.194000|-4.99|-16.97|-4.16|20833594|1.39|
|SILVER_USDT|57.570000|-3.06|-6.19|-2.23|315977806|1.74|
|ONDO_USDT|0.454100|-2.46|-9.86|-1.63|31739936|2.20|
|ICP_USDT|3.037000|-2.41|-10.72|-1.58|9192732|3.29|
|XLM_USDT|0.186700|-2.24|-12.62|-1.41|11215256|4.29|
|LDO_USDT|0.409500|-2.22|-12.46|-1.39|5925163|2.44|
|AVAX_USDT|10.008000|-2.17|-13.01|-1.34|36523437|3.00|
|RENDER_USDT|1.945000|-2.11|-8.68|-1.28|9026447|5.14|
|APT_USDT|0.803800|-2.03|-2.66|-1.20|11293112|1.24|
|PUMPFUN_USDT|0.004827|-2.00|-22.96|-1.17|18906655|2.07|
|PEPE_USDT|0.000004|-1.92|-4.62|-1.09|77442042|3.66|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.803800|0.800000|0.803800|2.55|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|10.008000|10.012000|10.008000|3.91|Y|Y/Y|Y/Y|Y|Y|
|ICP_USDT|3.037000|3.029000|3.037000|2.91|N|Y/Y|Y/Y|Y|N|
|LDO_USDT|0.409500|0.409300|0.409500|2.35|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.454100|0.452400|0.454100|2.70|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|2.01|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004827|0.004964|0.004827|21.16|Y|Y/Y|Y/Y|Y|Y|
|RENDER_USDT|1.945000|1.956000|1.945000|9.34|Y|Y/Y|Y/Y|Y|Y|
|SILVER_USDT|57.570000|57.610000|57.570000|4.41|Y|Y/Y|Y/Y|Y|Y|
|STRK_USDT|0.078820|0.077420|0.078820|1.46|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.544900|0.540500|0.544900|1.51|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.194000|7.227000|7.194000|5.22|Y|Y/Y|Y/Y|Y|Y|
|W_USDT|0.015603|0.015559|0.015603|1.12|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.186700|0.186830|0.186720|3.40|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-14T12:59:59+00:00, last15m_closed_end=2026-10-14T13:00+00:00, prior8high=0.828800, depth_time=2026-10-14T13:00:37+00:00, book20_bid_proxy_usdt=123793, book20_ask_proxy_usdt=131094, funding_indicative=-0.000005, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.03%, turnover=11293112. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-14T12:59:59+00:00, last15m_closed_end=2026-10-14T13:00+00:00, prior8high=10.294000, depth_time=2026-10-14T13:00:31+00:00, book20_bid_proxy_usdt=328378, book20_ask_proxy_usdt=581319, funding_indicative=0.000011, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.17%, turnover=36523437. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-14T12:59:59+00:00, last15m_closed_end=2026-10-14T13:00+00:00, prior8high=3.118000, depth_time=2026-10-14T13:00:23+00:00, book20_bid_proxy_usdt=697118, book20_ask_proxy_usdt=715738, funding_indicative=0.000100, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.41%, turnover=9192732. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-14T12:59:59+00:00, last15m_closed_end=2026-10-14T13:00+00:00, prior8high=0.422000, depth_time=2026-10-14T13:00:27+00:00, book20_bid_proxy_usdt=550708, book20_ask_proxy_usdt=502806, funding_indicative=0.000098, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.22%, turnover=5925163. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-14T12:59:59+00:00, last15m_closed_end=2026-10-14T13:00+00:00, prior8high=0.467700, depth_time=2026-10-14T13:00:21+00:00, book20_bid_proxy_usdt=1318729, book20_ask_proxy_usdt=1460317, funding_indicative=-0.000025, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.46%, turnover=31739936. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-14T12:59:59+00:00, last15m_closed_end=2026-10-14T13:00+00:00, prior8high=0.000004, depth_time=2026-10-14T13:00:43+00:00, book20_bid_proxy_usdt=22905, book20_ask_proxy_usdt=966519, funding_indicative=-0.000001, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.92%, turnover=77442042. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-14T12:59:59+00:00, last15m_closed_end=2026-10-14T13:00+00:00, prior8high=0.005134, depth_time=2026-10-14T13:00:41+00:00, book20_bid_proxy_usdt=764030, book20_ask_proxy_usdt=1204760, funding_indicative=0.000050, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.00%, turnover=18906655. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RENDER_USDT: quote_utc=2026-10-14T12:59:59+00:00, last15m_closed_end=2026-10-14T13:00+00:00, prior8high=2.007000, depth_time=2026-10-14T13:00:34+00:00, book20_bid_proxy_usdt=1040013, book20_ask_proxy_usdt=1742418, funding_indicative=0.000038, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.11%, turnover=9026447. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-14T12:59:59+00:00, last15m_closed_end=2026-10-14T13:00+00:00, prior8high=58.910000, depth_time=2026-10-14T13:00:18+00:00, book20_bid_proxy_usdt=37616944, book20_ask_proxy_usdt=39253506, funding_indicative=0.000118, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.06%, turnover=315977806. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T12:59:59+00:00, last15m_closed_end=2026-10-14T13:00+00:00, prior8high=0.080580, depth_time=2026-10-14T13:00:07+00:00, book20_bid_proxy_usdt=180785, book20_ask_proxy_usdt=321311, funding_indicative=0.000050, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.32%, turnover=28428324. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T12:59:59+00:00, last15m_closed_end=2026-10-14T13:00+00:00, prior8high=0.560900, depth_time=2026-10-14T13:00:13+00:00, book20_bid_proxy_usdt=147391, book20_ask_proxy_usdt=201540, funding_indicative=-0.000019, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.61%, turnover=35443890. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-14T12:59:59+00:00, last15m_closed_end=2026-10-14T13:00+00:00, prior8high=7.406000, depth_time=2026-10-14T13:00:15+00:00, book20_bid_proxy_usdt=1307351, book20_ask_proxy_usdt=1219773, funding_indicative=0.000076, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.99%, turnover=20833594. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T12:59:59+00:00, last15m_closed_end=2026-10-14T13:00+00:00, prior8high=0.016209, depth_time=2026-10-14T13:00:10+00:00, book20_bid_proxy_usdt=62686, book20_ask_proxy_usdt=22956, funding_indicative=-0.000212, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.14%, turnover=6506740. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-10-14T12:59:59+00:00, last15m_closed_end=2026-10-14T13:00+00:00, prior8high=0.190870, depth_time=2026-10-14T13:00:26+00:00, book20_bid_proxy_usdt=44340, book20_ask_proxy_usdt=155887, funding_indicative=-0.000066, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.24%, turnover=11215256. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
