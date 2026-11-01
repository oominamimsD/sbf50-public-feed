# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T00:15:35Z**
- feed_generated_utc: 2026-11-01T00:15:38+00:00
- source_sha256: `c0f19742de9d52feda7581d7e2526162912acbd648870e7e566ac7324d6dd418`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T00:15+00:00, close=77491.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-01T00:00+00:00, close=77522.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T00:00+00:00, close=77522.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BLESS_USDT|0.009502|-10.05|17.12|-9.97|7773114|4.21|
|INJ_USDT|7.220000|-3.55|-3.91|-3.47|20446156|4.16|
|Q_USDT|0.030960|-3.49|-60.77|-3.41|10480357|3.23|
|BTW_USDT|1.086800|-3.12|-37.58|-3.04|5437264|2.76|
|ENA_USDT|0.188700|-2.73|1.02|-2.65|44773909|0.53|
|ZEC_USDT|1250.260000|-2.66|9.17|-2.58|1030714253|0.16|
|TRX_USDT|0.304000|-2.66|-7.57|-2.58|10581221|0.33|
|FET_USDT|0.159500|-2.32|-7.42|-2.24|5830818|6.27|
|FARTCOIN_USDT|0.120020|-1.61|-1.60|-1.53|6335045|0.83|
|WLD_USDT|0.398400|-1.48|-13.76|-1.40|34008817|2.51|
|XLM_USDT|0.169400|-1.36|0.58|-1.28|21298084|0.59|
|AKE_USDT|0.010993|-1.30|-62.39|-1.22|11437768|2.73|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.010993|0.010836|0.010993|0.40|N|Y/Y|Y/Y|Y|N|
|BLESS_USDT|0.009502|0.009300|0.009502|0.97|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.086800|1.066200|1.086800|1.16|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.188700|0.187820|0.188700|1.35|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.120020|0.119850|0.120020|0.80|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.159500|0.159200|0.159500|0.15|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.220000|7.188000|7.218000|1.85|N|N/Y|Y/Y|Y|N|
|Q_USDT|0.030960|0.031060|0.030960|1.07|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.304000|0.300760|0.304000|2.32|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.398400|0.397300|0.398400|1.28|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.169400|0.169430|0.169400|0.84|N|N/N|N/N|Y|N|
|ZEC_USDT|1250.260000|1243.100000|1250.260000|0.80|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-01T00:15:00+00:00, last15m_closed_end=2026-11-01T00:15+00:00, prior8high=0.011387, depth_time=2026-11-01T00:15:34+00:00, book20_bid_proxy_usdt=16082, book20_ask_proxy_usdt=15846, funding_indicative=-0.000306, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.30%, turnover=11437768. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-11-01T00:15:00+00:00, last15m_closed_end=2026-11-01T00:15+00:00, prior8high=0.009563, depth_time=2026-11-01T00:15:06+00:00, book20_bid_proxy_usdt=10796, book20_ask_proxy_usdt=13491, funding_indicative=0.000050, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.05%, turnover=7773114. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-01T00:15:00+00:00, last15m_closed_end=2026-11-01T00:15+00:00, prior8high=1.111700, depth_time=2026-11-01T00:15:15+00:00, book20_bid_proxy_usdt=15834, book20_ask_proxy_usdt=16516, funding_indicative=-0.000145, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.12%, turnover=5437264. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-01T00:15:00+00:00, last15m_closed_end=2026-11-01T00:15+00:00, prior8high=0.191470, depth_time=2026-11-01T00:15:17+00:00, book20_bid_proxy_usdt=128472, book20_ask_proxy_usdt=170888, funding_indicative=0.000005, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.73%, turnover=44773909. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-01T00:15:00+00:00, last15m_closed_end=2026-11-01T00:15+00:00, prior8high=0.121480, depth_time=2026-11-01T00:15:26+00:00, book20_bid_proxy_usdt=130810, book20_ask_proxy_usdt=77937, funding_indicative=0.000050, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.61%, turnover=6335045. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-11-01T00:15:00+00:00, last15m_closed_end=2026-11-01T00:15+00:00, prior8high=0.161300, depth_time=2026-11-01T00:15:25+00:00, book20_bid_proxy_usdt=1272228, book20_ask_proxy_usdt=1066452, funding_indicative=-0.000148, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.32%, turnover=5830818. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-11-01T00:15:00+00:00, last15m_closed_end=2026-11-01T00:15+00:00, prior8high=7.312000, depth_time=2026-11-01T00:15:10+00:00, book20_bid_proxy_usdt=363903, book20_ask_proxy_usdt=312023, funding_indicative=0.000073, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.55%, turnover=20446156. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-11-01T00:15:00+00:00, last15m_closed_end=2026-11-01T00:15+00:00, prior8high=0.032540, depth_time=2026-11-01T00:15:12+00:00, book20_bid_proxy_usdt=47728, book20_ask_proxy_usdt=45881, funding_indicative=-0.000928, next_funding_utc=2026-11-01T01:00:00+00:00, funding_cycle_h=1, 24h_change=-3.49%, turnover=10480357. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-11-01T00:15:00+00:00, last15m_closed_end=2026-11-01T00:15+00:00, prior8high=0.304080, depth_time=2026-11-01T00:15:19+00:00, book20_bid_proxy_usdt=105703, book20_ask_proxy_usdt=52215, funding_indicative=-0.001252, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.66%, turnover=10581221. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-01T00:15:00+00:00, last15m_closed_end=2026-11-01T00:15+00:00, prior8high=0.400500, depth_time=2026-11-01T00:15:26+00:00, book20_bid_proxy_usdt=2549186, book20_ask_proxy_usdt=2998992, funding_indicative=0.000100, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.48%, turnover=34008817. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-01T00:15:00+00:00, last15m_closed_end=2026-11-01T00:15+00:00, prior8high=0.170750, depth_time=2026-11-01T00:15:32+00:00, book20_bid_proxy_usdt=199324, book20_ask_proxy_usdt=245237, funding_indicative=-0.000065, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.36%, turnover=21298084. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-01T00:15:00+00:00, last15m_closed_end=2026-11-01T00:15+00:00, prior8high=1284.960000, depth_time=2026-11-01T00:15:19+00:00, book20_bid_proxy_usdt=809028, book20_ask_proxy_usdt=108250, funding_indicative=-0.000049, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.66%, turnover=1030714253. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
