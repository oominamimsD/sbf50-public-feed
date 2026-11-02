# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-02T17:00:43Z**
- feed_generated_utc: 2026-11-02T17:00:46+00:00
- source_sha256: `9d3ff89ae5b473d8b01f93fe52cb4c9cbb416bc4b03b7f16c919e366d72e4d92`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-02T17:00+00:00, close=77464.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-02T17:00+00:00, close=77464.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-02T16:00+00:00, close=77479.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.129300|-4.29|-48.03|-4.27|7006500|7.74|
|Q_USDT|0.025230|-3.11|-57.27|-3.09|6990832|3.96|
|IDOL_USDT|0.013046|-2.43|68.03|-2.41|17698807|5.36|
|XPL_USDT|0.068900|-2.31|-7.25|-2.29|9361794|1.45|
|ENA_USDT|0.171190|-2.19|-18.62|-2.17|65104401|0.58|
|INJ_USDT|7.021000|-2.13|-11.50|-2.11|21566935|2.85|
|ZEC_USDT|1231.960000|-1.76|-1.26|-1.74|1559349557|0.08|
|LIT_USDT|3.077600|-1.69|-1.30|-1.67|11732356|0.33|
|WLD_USDT|0.378200|-1.51|-15.01|-1.49|48798615|2.64|
|LINK_USDT|11.186000|-1.33|-2.96|-1.31|166404501|0.89|
|FET_USDT|0.156700|-1.32|-11.26|-1.30|5137462|6.38|
|PUMPFUN_USDT|0.004050|-1.31|-6.42|-1.29|9465609|2.47|
|ONDO_USDT|0.388800|-1.14|-7.16|-1.12|16024123|2.57|
|DASH_USDT|47.180000|-1.06|-9.65|-1.04|9621703|2.12|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|47.180000|46.870000|47.180000|0.65|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.171190|0.171120|0.171200|1.10|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.156700|0.156500|0.156700|1.75|N|Y/Y|Y/Y|Y|N|
|IDOL_USDT|0.013046|0.012439|0.013044|0.34|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.021000|6.961000|7.021000|0.30|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.186000|11.147000|11.186000|0.57|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.077600|3.080000|3.077600|0.66|N|Y/Y|N/N|Y|N|
|ONDO_USDT|0.388800|0.387000|0.388800|0.38|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004050|0.004055|0.004052|1.66|Y|Y/Y|Y/Y|Y|Y|
|Q_USDT|0.025230|0.025280|0.025270|4.05|Y|Y/Y|Y/Y|Y|Y|
|UAI_USDT|0.129300|0.127300|0.129300|0.47|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.378200|0.377100|0.378200|0.65|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.068900|0.068860|0.068900|0.54|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1231.960000|1227.170000|1231.950000|0.81|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-11-02T17:00:04+00:00, last15m_closed_end=2026-11-02T17:00+00:00, prior8high=47.860000, depth_time=2026-11-02T17:00:42+00:00, book20_bid_proxy_usdt=724078, book20_ask_proxy_usdt=570566, funding_indicative=-0.000014, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.06%, turnover=9621703. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-02T17:00:04+00:00, last15m_closed_end=2026-11-02T17:00+00:00, prior8high=0.178750, depth_time=2026-11-02T17:00:21+00:00, book20_bid_proxy_usdt=164627, book20_ask_proxy_usdt=244496, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.19%, turnover=65104401. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-11-02T17:00:04+00:00, last15m_closed_end=2026-11-02T17:00+00:00, prior8high=0.159800, depth_time=2026-11-02T17:00:34+00:00, book20_bid_proxy_usdt=1631998, book20_ask_proxy_usdt=898905, funding_indicative=0.000018, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.32%, turnover=5137462. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-02T17:00:04+00:00, last15m_closed_end=2026-11-02T17:00+00:00, prior8high=0.014382, depth_time=2026-11-02T17:00:15+00:00, book20_bid_proxy_usdt=10000, book20_ask_proxy_usdt=12600, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.43%, turnover=17698807. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-11-02T17:00:04+00:00, last15m_closed_end=2026-11-02T17:00+00:00, prior8high=7.217000, depth_time=2026-11-02T17:00:23+00:00, book20_bid_proxy_usdt=307981, book20_ask_proxy_usdt=483372, funding_indicative=0.000098, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.13%, turnover=21566935. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-02T17:00:04+00:00, last15m_closed_end=2026-11-02T17:00+00:00, prior8high=11.398000, depth_time=2026-11-02T17:00:33+00:00, book20_bid_proxy_usdt=420574, book20_ask_proxy_usdt=563688, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.33%, turnover=166404501. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-02T17:00:04+00:00, last15m_closed_end=2026-11-02T17:00+00:00, prior8high=3.175600, depth_time=2026-11-02T17:00:28+00:00, book20_bid_proxy_usdt=30890, book20_ask_proxy_usdt=26949, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.69%, turnover=11732356. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-02T17:00:04+00:00, last15m_closed_end=2026-11-02T17:00+00:00, prior8high=0.395200, depth_time=2026-11-02T17:00:37+00:00, book20_bid_proxy_usdt=2784607, book20_ask_proxy_usdt=3136641, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.14%, turnover=16024123. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-02T17:00:04+00:00, last15m_closed_end=2026-11-02T17:00+00:00, prior8high=0.004222, depth_time=2026-11-02T17:00:38+00:00, book20_bid_proxy_usdt=1864319, book20_ask_proxy_usdt=2271247, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.31%, turnover=9465609. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-11-02T17:00:04+00:00, last15m_closed_end=2026-11-02T17:00+00:00, prior8high=0.026920, depth_time=2026-11-02T17:00:12+00:00, book20_bid_proxy_usdt=45875, book20_ask_proxy_usdt=56699, funding_indicative=-0.000451, next_funding_utc=2026-11-02T18:00:00+00:00, funding_cycle_h=1, 24h_change=-3.11%, turnover=6990832. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-02T17:00:04+00:00, last15m_closed_end=2026-11-02T17:00+00:00, prior8high=0.136800, depth_time=2026-11-02T17:00:09+00:00, book20_bid_proxy_usdt=114240, book20_ask_proxy_usdt=124182, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.29%, turnover=7006500. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-02T17:00:04+00:00, last15m_closed_end=2026-11-02T17:00+00:00, prior8high=0.385100, depth_time=2026-11-02T17:00:31+00:00, book20_bid_proxy_usdt=3346601, book20_ask_proxy_usdt=5011324, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.51%, turnover=48798615. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-02T17:00:04+00:00, last15m_closed_end=2026-11-02T17:00+00:00, prior8high=0.070990, depth_time=2026-11-02T17:00:18+00:00, book20_bid_proxy_usdt=371263, book20_ask_proxy_usdt=488138, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.31%, turnover=9361794. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-02T17:00:04+00:00, last15m_closed_end=2026-11-02T17:00+00:00, prior8high=1273.110000, depth_time=2026-11-02T17:00:26+00:00, book20_bid_proxy_usdt=1354957, book20_ask_proxy_usdt=182168, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.76%, turnover=1559349557. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
