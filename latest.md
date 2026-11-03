# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T10:00:45Z**
- feed_generated_utc: 2026-11-03T10:00:47+00:00
- source_sha256: `846e470231915ea648aeb564b57e94a5742e0b304b5b835be884dea33af52de7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T10:00+00:00, close=77039.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T10:00+00:00, close=77039.4, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-03T08:00+00:00, close=76799.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|0.901300|-17.82|-24.62|-17.31|9895418|1.11|
|AKE_USDT|0.004569|-16.95|-85.15|-16.44|13301170|4.38|
|ZEC_USDT|1149.470000|-8.34|-7.87|-7.83|1745495786|0.09|
|XPL_USDT|0.063900|-8.16|-13.98|-7.65|11478550|1.56|
|NEAR_USDT|3.842000|-5.69|-15.98|-5.18|75881401|2.60|
|OP_USDT|0.108350|-4.41|-2.99|-3.90|10572907|1.85|
|TIA_USDT|0.437900|-4.15|-18.25|-3.64|12614864|2.28|
|DASH_USDT|45.830000|-3.90|-12.23|-3.39|8785150|2.18|
|SILVER_USDT|49.130000|-3.77|-9.40|-3.26|442412062|2.04|
|QNT_USDT|195.680000|-3.34|-6.94|-2.83|47297178|0.51|
|XLM_USDT|0.162170|-3.23|-4.37|-2.72|33443405|0.62|
|FARTCOIN_USDT|0.116510|-3.19|-9.21|-2.68|9670442|2.57|
|ENA_USDT|0.169750|-3.02|-19.30|-2.51|67269346|0.59|
|WLD_USDT|0.370200|-2.88|-16.80|-2.37|49904040|5.40|
|TRUMPOFFICIAL_USDT|1.593000|-2.56|-5.68|-2.05|9109088|6.28|
|APT_USDT|0.613500|-2.54|-12.60|-2.03|5278793|3.26|
|ONDO_USDT|0.383400|-2.51|-8.45|-2.00|16591302|2.61|
|TAO_USDT|223.000000|-1.82|-12.03|-1.31|39579618|1.35|
|HBAR_USDT|0.069690|-1.51|-9.91|-1.00|8628305|2.87|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004569|0.004385|0.004571|0.76|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|0.901300|0.906600|0.898100|2.53|Y|Y/Y|Y/Y|Y|Y|
|DASH_USDT|45.830000|45.380000|45.830000|0.20|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.169750|0.166740|0.169660|0.37|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.116510|0.114330|0.116510|0.30|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.842000|3.743000|3.842000|1.01|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.108350|0.107010|0.108350|0.87|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|195.680000|193.300000|195.710000|1.25|N|N/Y|Y/Y|Y|N|
|SILVER_USDT|49.130000|48.730000|49.120000|0.42|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.437900|0.434300|0.437900|0.34|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.593000|1.557000|1.593000|0.22|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.370200|0.363300|0.370000|0.87|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.162170|0.160820|0.162120|0.58|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.063900|0.063500|0.063910|0.78|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1149.470000|1124.290000|1148.740000|1.19|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T10:00:02+00:00, last15m_closed_end=2026-11-03T10:00+00:00, prior8high=0.004638, depth_time=2026-11-03T10:00:10+00:00, book20_bid_proxy_usdt=37252, book20_ask_proxy_usdt=26470, funding_indicative=-0.001186, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-16.95%, turnover=13301170. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-03T10:00:02+00:00, last15m_closed_end=2026-11-03T10:00+00:00, prior8high=0.934200, depth_time=2026-11-03T10:00:08+00:00, book20_bid_proxy_usdt=37158, book20_ask_proxy_usdt=21157, funding_indicative=-0.000172, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-17.82%, turnover=9895418. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-03T10:00:03+00:00, last15m_closed_end=2026-11-03T10:00+00:00, prior8high=45.840000, depth_time=2026-11-03T10:00:26+00:00, book20_bid_proxy_usdt=586433, book20_ask_proxy_usdt=631765, funding_indicative=0.000090, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.90%, turnover=8785150. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-03T10:00:02+00:00, last15m_closed_end=2026-11-03T10:00+00:00, prior8high=0.169970, depth_time=2026-11-03T10:00:39+00:00, book20_bid_proxy_usdt=237474, book20_ask_proxy_usdt=218573, funding_indicative=0.000050, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.02%, turnover=67269346. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-03T10:00:03+00:00, last15m_closed_end=2026-11-03T10:00+00:00, prior8high=0.116410, depth_time=2026-11-03T10:00:36+00:00, book20_bid_proxy_usdt=89743, book20_ask_proxy_usdt=88834, funding_indicative=0.000050, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.19%, turnover=9670442. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-03T10:00:02+00:00, last15m_closed_end=2026-11-03T10:00+00:00, prior8high=3.828000, depth_time=2026-11-03T10:00:18+00:00, book20_bid_proxy_usdt=5823318, book20_ask_proxy_usdt=4435726, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.69%, turnover=75881401. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-03T10:00:03+00:00, last15m_closed_end=2026-11-03T10:00+00:00, prior8high=0.108570, depth_time=2026-11-03T10:00:21+00:00, book20_bid_proxy_usdt=163411, book20_ask_proxy_usdt=129371, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.41%, turnover=10572907. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-03T10:00:02+00:00, last15m_closed_end=2026-11-03T10:00+00:00, prior8high=196.360000, depth_time=2026-11-03T10:00:30+00:00, book20_bid_proxy_usdt=82091, book20_ask_proxy_usdt=69996, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.34%, turnover=47297178. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-11-03T10:00:02+00:00, last15m_closed_end=2026-11-03T10:00+00:00, prior8high=49.270000, depth_time=2026-11-03T10:00:28+00:00, book20_bid_proxy_usdt=66652235, book20_ask_proxy_usdt=61274463, funding_indicative=0.000000, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.77%, turnover=442412062. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-03T10:00:03+00:00, last15m_closed_end=2026-11-03T10:00+00:00, prior8high=0.439600, depth_time=2026-11-03T10:00:23+00:00, book20_bid_proxy_usdt=294603, book20_ask_proxy_usdt=411708, funding_indicative=0.000050, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.15%, turnover=12614864. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-03T10:00:03+00:00, last15m_closed_end=2026-11-03T10:00+00:00, prior8high=1.589000, depth_time=2026-11-03T10:00:43+00:00, book20_bid_proxy_usdt=2207248, book20_ask_proxy_usdt=1722409, funding_indicative=-0.000002, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.56%, turnover=9109088. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-03T10:00:02+00:00, last15m_closed_end=2026-11-03T10:00+00:00, prior8high=0.369100, depth_time=2026-11-03T10:00:41+00:00, book20_bid_proxy_usdt=4613652, book20_ask_proxy_usdt=4371012, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.88%, turnover=49904040. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-03T10:00:03+00:00, last15m_closed_end=2026-11-03T10:00+00:00, prior8high=0.162140, depth_time=2026-11-03T10:00:31+00:00, book20_bid_proxy_usdt=126487, book20_ask_proxy_usdt=188958, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.23%, turnover=33443405. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-03T10:00:03+00:00, last15m_closed_end=2026-11-03T10:00+00:00, prior8high=0.064320, depth_time=2026-11-03T10:00:15+00:00, book20_bid_proxy_usdt=445391, book20_ask_proxy_usdt=617061, funding_indicative=0.000050, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.16%, turnover=11478550. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-03T10:00:02+00:00, last15m_closed_end=2026-11-03T10:00+00:00, prior8high=1148.250000, depth_time=2026-11-03T10:00:13+00:00, book20_bid_proxy_usdt=496326, book20_ask_proxy_usdt=90042, funding_indicative=0.000071, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.34%, turnover=1745495786. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
