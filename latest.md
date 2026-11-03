# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T10:30:40Z**
- feed_generated_utc: 2026-11-03T10:30:43+00:00
- source_sha256: `fd7c0686c938a732921a111f0c1d75290be10eb73fc3e3f136dd12722cadb81c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T10:30+00:00, close=77021.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T10:00+00:00, close=77039.4, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-03T08:00+00:00, close=76799.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|0.891900|-18.68|-25.40|-18.11|10112559|1.12|
|AKE_USDT|0.004618|-16.06|-84.99|-15.49|13419827|2.16|
|XPL_USDT|0.063540|-8.68|-14.47|-8.11|11511635|1.57|
|ZEC_USDT|1156.860000|-7.75|-7.28|-7.18|1777304139|0.09|
|NEAR_USDT|3.846000|-4.08|-15.89|-3.51|76772643|2.60|
|SILVER_USDT|49.050000|-3.93|-9.55|-3.36|446704466|2.04|
|TIA_USDT|0.438900|-3.93|-18.06|-3.36|12702790|2.28|
|XLM_USDT|0.161920|-3.38|-4.52|-2.81|33920066|0.62|
|OP_USDT|0.108860|-3.17|-2.54|-2.60|10688652|0.92|
|DASH_USDT|45.760000|-3.05|-12.37|-2.48|8876084|2.19|
|ENA_USDT|0.170190|-2.77|-19.09|-2.20|67715941|0.59|
|FARTCOIN_USDT|0.116330|-2.45|-9.35|-1.88|9784987|0.86|
|WLD_USDT|0.371900|-2.43|-16.42|-1.86|50637001|2.69|
|APT_USDT|0.614600|-1.99|-12.45|-1.42|5328587|1.63|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004618|0.004421|0.004618|0.40|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.614600|0.606300|0.614600|0.86|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|0.891900|0.893200|0.890800|2.49|Y|Y/Y|Y/Y|Y|Y|
|DASH_USDT|45.760000|45.380000|45.760000|1.24|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.170190|0.166740|0.170190|0.70|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.116330|0.114330|0.116330|1.61|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.846000|3.743000|3.846000|0.83|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.108860|0.107010|0.108860|0.99|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|49.050000|48.730000|49.040000|0.19|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.438900|0.434300|0.438900|0.47|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.371900|0.363300|0.371900|0.84|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.161920|0.160820|0.161920|1.12|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.063540|0.063500|0.063540|0.46|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1156.860000|1124.290000|1156.860000|1.39|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T10:30:01+00:00, last15m_closed_end=2026-11-03T10:30+00:00, prior8high=0.004638, depth_time=2026-11-03T10:30:09+00:00, book20_bid_proxy_usdt=34658, book20_ask_proxy_usdt=36438, funding_indicative=-0.001345, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-16.06%, turnover=13419827. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-11-03T10:30:01+00:00, last15m_closed_end=2026-11-03T10:30+00:00, prior8high=0.614700, depth_time=2026-11-03T10:30:39+00:00, book20_bid_proxy_usdt=161162, book20_ask_proxy_usdt=204612, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.99%, turnover=5328587. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-03T10:30:01+00:00, last15m_closed_end=2026-11-03T10:30+00:00, prior8high=0.931300, depth_time=2026-11-03T10:30:07+00:00, book20_bid_proxy_usdt=45512, book20_ask_proxy_usdt=23212, funding_indicative=-0.000265, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-18.68%, turnover=10112559. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-03T10:30:01+00:00, last15m_closed_end=2026-11-03T10:30+00:00, prior8high=45.880000, depth_time=2026-11-03T10:30:28+00:00, book20_bid_proxy_usdt=745518, book20_ask_proxy_usdt=749165, funding_indicative=0.000073, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.05%, turnover=8876084. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-03T10:30:01+00:00, last15m_closed_end=2026-11-03T10:30+00:00, prior8high=0.170000, depth_time=2026-11-03T10:30:32+00:00, book20_bid_proxy_usdt=121550, book20_ask_proxy_usdt=206218, funding_indicative=0.000050, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.77%, turnover=67715941. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-03T10:30:01+00:00, last15m_closed_end=2026-11-03T10:30+00:00, prior8high=0.116560, depth_time=2026-11-03T10:30:35+00:00, book20_bid_proxy_usdt=69570, book20_ask_proxy_usdt=87992, funding_indicative=0.000050, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.45%, turnover=9784987. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-03T10:30:01+00:00, last15m_closed_end=2026-11-03T10:30+00:00, prior8high=3.846000, depth_time=2026-11-03T10:30:18+00:00, book20_bid_proxy_usdt=4367029, book20_ask_proxy_usdt=5811294, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.08%, turnover=76772643. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-03T10:30:01+00:00, last15m_closed_end=2026-11-03T10:30+00:00, prior8high=0.108570, depth_time=2026-11-03T10:30:28+00:00, book20_bid_proxy_usdt=128070, book20_ask_proxy_usdt=110618, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.17%, turnover=10688652. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-11-03T10:30:01+00:00, last15m_closed_end=2026-11-03T10:30+00:00, prior8high=49.200000, depth_time=2026-11-03T10:30:20+00:00, book20_bid_proxy_usdt=66890462, book20_ask_proxy_usdt=62209097, funding_indicative=0.000017, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.93%, turnover=446704466. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-03T10:30:01+00:00, last15m_closed_end=2026-11-03T10:30+00:00, prior8high=0.439400, depth_time=2026-11-03T10:30:22+00:00, book20_bid_proxy_usdt=420776, book20_ask_proxy_usdt=397715, funding_indicative=0.000050, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.93%, turnover=12702790. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-03T10:30:01+00:00, last15m_closed_end=2026-11-03T10:30+00:00, prior8high=0.371300, depth_time=2026-11-03T10:30:37+00:00, book20_bid_proxy_usdt=4036839, book20_ask_proxy_usdt=5082717, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.43%, turnover=50637001. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-03T10:30:01+00:00, last15m_closed_end=2026-11-03T10:30+00:00, prior8high=0.162210, depth_time=2026-11-03T10:30:22+00:00, book20_bid_proxy_usdt=142416, book20_ask_proxy_usdt=246292, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.38%, turnover=33920066. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-03T10:30:01+00:00, last15m_closed_end=2026-11-03T10:30+00:00, prior8high=0.064320, depth_time=2026-11-03T10:30:11+00:00, book20_bid_proxy_usdt=322510, book20_ask_proxy_usdt=547972, funding_indicative=0.000050, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.68%, turnover=11511635. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-03T10:30:01+00:00, last15m_closed_end=2026-11-03T10:30+00:00, prior8high=1151.100000, depth_time=2026-11-03T10:30:14+00:00, book20_bid_proxy_usdt=345316, book20_ask_proxy_usdt=435739, funding_indicative=0.000057, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-7.75%, turnover=1777304139. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
