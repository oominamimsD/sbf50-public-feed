# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T03:15:47Z**
- feed_generated_utc: 2026-10-17T03:15:50+00:00
- source_sha256: `9870a7ccab36e468ee469352e5292b1d5311dffd50ac13cf1b7d945eef6a1f74`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 17; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T03:15+00:00, close=81426.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-17T03:00+00:00, close=81449.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T00:00+00:00, close=81578.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.950000|-7.20|-4.26|-7.32|15389066|1.54|
|STRK_USDT|0.070500|-4.66|-6.38|-4.78|21922044|1.42|
|RIVER_USDT|1.075000|-4.52|-9.05|-4.64|5211845|9.31|
|ZEC_USDT|1145.400000|-3.58|-5.98|-3.70|1384119941|0.09|
|ARB_USDT|0.188130|-3.49|4.05|-3.61|33100946|0.53|
|TAO_USDT|273.830000|-2.41|-0.30|-2.53|78805118|0.36|
|FET_USDT|0.194900|-2.35|-10.18|-2.47|11493892|5.13|
|APT_USDT|0.836700|-2.26|4.52|-2.38|12493105|1.20|
|OP_USDT|0.137230|-1.97|11.36|-2.09|14602828|1.46|
|FILECOIN_USDT|1.143900|-1.96|6.90|-2.08|22159772|0.87|
|SUI_USDT|1.004700|-1.54|-5.00|-1.66|96343277|0.99|
|FARTCOIN_USDT|0.152380|-1.51|-6.72|-1.63|7120452|0.66|
|AVAX_USDT|9.943000|-1.38|-2.44|-1.50|122355279|1.01|
|ENA_USDT|0.197220|-1.35|-8.51|-1.47|39875392|0.51|
|AAVE_USDT|155.160000|-1.34|-8.64|-1.46|29826708|0.64|
|ICP_USDT|2.997000|-1.34|-0.72|-1.46|8830386|3.34|
|ONDO_USDT|0.452500|-1.00|-5.74|-1.12|28253253|2.21|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|155.160000|154.300000|155.160000|0.89|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.836700|0.833600|0.836700|1.60|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.188130|0.187590|0.188130|2.41|N|Y/Y|N/N|Y|N|
|AVAX_USDT|9.943000|9.881000|9.943000|0.91|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.197220|0.196360|0.197220|0.31|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.152380|0.152400|0.152380|1.08|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.194900|0.194100|0.194900|2.38|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|1.143900|1.134300|1.143900|0.79|N|N/N|N/N|Y|N|
|OP_USDT|0.137230|0.137110|0.137230|0.62|N|N/Y|Y/Y|Y|N|
|RIVER_USDT|1.075000|1.075000|1.075000|1.22|N|Y/Y|N/N|Y|N|
|STRK_USDT|0.070500|0.070190|0.070470|1.88|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|1.004700|1.001200|1.004700|0.42|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|273.830000|273.080000|273.830000|0.63|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1145.400000|1140.370000|1145.400000|0.64|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.950000|1.943800|1.950000|1.81|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-17T03:15:01+00:00, last15m_closed_end=2026-10-17T03:15+00:00, prior8high=155.480000, depth_time=2026-10-17T03:15:46+00:00, book20_bid_proxy_usdt=298487, book20_ask_proxy_usdt=327677, funding_indicative=0.000049, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.34%, turnover=29826708. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-17T03:15:01+00:00, last15m_closed_end=2026-10-17T03:15+00:00, prior8high=0.848700, depth_time=2026-10-17T03:15:30+00:00, book20_bid_proxy_usdt=84626, book20_ask_proxy_usdt=126292, funding_indicative=0.000057, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.26%, turnover=12493105. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-17T03:15:00+00:00, last15m_closed_end=2026-10-17T03:15+00:00, prior8high=0.190730, depth_time=2026-10-17T03:15:22+00:00, book20_bid_proxy_usdt=67326, book20_ask_proxy_usdt=77325, funding_indicative=-0.000090, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.49%, turnover=33100946. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-17T03:15:01+00:00, last15m_closed_end=2026-10-17T03:15+00:00, prior8high=9.991000, depth_time=2026-10-17T03:15:41+00:00, book20_bid_proxy_usdt=587147, book20_ask_proxy_usdt=1390737, funding_indicative=0.000081, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.38%, turnover=122355279. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-17T03:15:01+00:00, last15m_closed_end=2026-10-17T03:15+00:00, prior8high=0.198780, depth_time=2026-10-17T03:15:43+00:00, book20_bid_proxy_usdt=281516, book20_ask_proxy_usdt=184774, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.35%, turnover=39875392. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-17T03:15:01+00:00, last15m_closed_end=2026-10-17T03:15+00:00, prior8high=0.153930, depth_time=2026-10-17T03:15:40+00:00, book20_bid_proxy_usdt=69139, book20_ask_proxy_usdt=58096, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.51%, turnover=7120452. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-17T03:15:01+00:00, last15m_closed_end=2026-10-17T03:15+00:00, prior8high=0.196800, depth_time=2026-10-17T03:15:27+00:00, book20_bid_proxy_usdt=1815967, book20_ask_proxy_usdt=1257390, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.35%, turnover=11493892. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-17T03:15:00+00:00, last15m_closed_end=2026-10-17T03:15+00:00, prior8high=1.161000, depth_time=2026-10-17T03:15:34+00:00, book20_bid_proxy_usdt=599228, book20_ask_proxy_usdt=388992, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.96%, turnover=22159772. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-17T03:15:01+00:00, last15m_closed_end=2026-10-17T03:15+00:00, prior8high=0.139760, depth_time=2026-10-17T03:15:32+00:00, book20_bid_proxy_usdt=42144, book20_ask_proxy_usdt=66232, funding_indicative=-0.000048, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.97%, turnover=14602828. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-17T03:15:01+00:00, last15m_closed_end=2026-10-17T03:15+00:00, prior8high=1.093000, depth_time=2026-10-17T03:15:13+00:00, book20_bid_proxy_usdt=530082, book20_ask_proxy_usdt=412970, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.52%, turnover=5211845. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T03:15:00+00:00, last15m_closed_end=2026-10-17T03:15+00:00, prior8high=0.074750, depth_time=2026-10-17T03:15:10+00:00, book20_bid_proxy_usdt=288828, book20_ask_proxy_usdt=319315, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.66%, turnover=21922044. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-17T03:15:00+00:00, last15m_closed_end=2026-10-17T03:15+00:00, prior8high=1.010300, depth_time=2026-10-17T03:15:37+00:00, book20_bid_proxy_usdt=663111, book20_ask_proxy_usdt=1774373, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.54%, turnover=96343277. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-17T03:15:00+00:00, last15m_closed_end=2026-10-17T03:15+00:00, prior8high=275.370000, depth_time=2026-10-17T03:15:23+00:00, book20_bid_proxy_usdt=89846, book20_ask_proxy_usdt=107670, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.41%, turnover=78805118. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T03:15:00+00:00, last15m_closed_end=2026-10-17T03:15+00:00, prior8high=1157.920000, depth_time=2026-10-17T03:15:17+00:00, book20_bid_proxy_usdt=203025, book20_ask_proxy_usdt=380872, funding_indicative=0.000064, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.58%, turnover=1384119941. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T03:15:00+00:00, last15m_closed_end=2026-10-17T03:15+00:00, prior8high=1.978100, depth_time=2026-10-17T03:15:08+00:00, book20_bid_proxy_usdt=42411, book20_ask_proxy_usdt=60021, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.20%, turnover=15389066. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
