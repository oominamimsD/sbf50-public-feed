# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T14:45:39Z**
- feed_generated_utc: 2026-10-27T14:45:43+00:00
- source_sha256: `b8e506b4a9ecdfef68ba8ac344c4055854a85b23de45f314c583f78b202dd72b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T14:45+00:00, close=80256.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T14:00+00:00, close=80014.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-27T12:00+00:00, close=79880.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.025070|-9.10|104.15|-8.92|6540989|7.98|
|QNT_USDT|199.010000|-5.35|1.69|-5.17|98835502|1.00|
|AAVE_USDT|131.700000|-3.67|-10.54|-3.49|27809998|1.52|
|WLD_USDT|0.429200|-3.55|-15.22|-3.37|72949790|2.33|
|DOT_USDT|0.986600|-3.52|-13.96|-3.34|11351158|1.01|
|FILECOIN_USDT|0.890400|-3.29|-12.01|-3.11|6062910|1.12|
|PUMPFUN_USDT|0.004197|-3.02|-5.81|-2.84|21550241|2.38|
|APT_USDT|0.682700|-2.74|-10.51|-2.56|5226626|1.47|
|ICP_USDT|2.575000|-2.09|-9.74|-1.91|5409078|3.89|
|HBAR_USDT|0.075900|-1.88|-7.29|-1.70|9818721|1.32|
|TAO_USDT|249.700000|-1.50|-6.93|-1.32|52470041|1.20|
|SOL_USDT|100.520000|-1.29|-3.42|-1.11|709721147|0.99|
|TIA_USDT|0.529000|-1.25|-13.06|-1.07|17695570|1.89|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|131.700000|130.180000|131.640000|1.43|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.682700|0.672700|0.682700|3.03|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.986600|0.977000|0.986600|0.82|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.890400|0.880500|0.891500|1.24|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.075900|0.075590|0.075940|0.80|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|2.575000|2.552000|2.575000|0.60|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.025070|0.024590|0.025070|0.52|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004197|0.004167|0.004197|1.53|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|199.010000|196.560000|199.160000|0.96|N|Y/Y|N/N|Y|N|
|SOL_USDT|100.520000|99.820000|100.520000|0.98|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|249.700000|247.440000|249.930000|1.00|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.529000|0.519500|0.529000|1.36|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.429200|0.424600|0.429200|0.67|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T14:45:01+00:00, last15m_closed_end=2026-10-27T14:45+00:00, prior8high=133.100000, depth_time=2026-10-27T14:45:14+00:00, book20_bid_proxy_usdt=308542, book20_ask_proxy_usdt=338127, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.67%, turnover=27809998. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-27T14:45:01+00:00, last15m_closed_end=2026-10-27T14:45+00:00, prior8high=0.690800, depth_time=2026-10-27T14:45:26+00:00, book20_bid_proxy_usdt=186073, book20_ask_proxy_usdt=186102, funding_indicative=-0.000026, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.74%, turnover=5226626. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T14:45:01+00:00, last15m_closed_end=2026-10-27T14:45+00:00, prior8high=0.996900, depth_time=2026-10-27T14:45:19+00:00, book20_bid_proxy_usdt=479176, book20_ask_proxy_usdt=531918, funding_indicative=-0.000146, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.52%, turnover=11351158. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T14:45:01+00:00, last15m_closed_end=2026-10-27T14:45+00:00, prior8high=0.902000, depth_time=2026-10-27T14:45:21+00:00, book20_bid_proxy_usdt=1289644, book20_ask_proxy_usdt=1227162, funding_indicative=0.000025, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.29%, turnover=6062910. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-27T14:45:01+00:00, last15m_closed_end=2026-10-27T14:45+00:00, prior8high=0.076600, depth_time=2026-10-27T14:45:29+00:00, book20_bid_proxy_usdt=891041, book20_ask_proxy_usdt=909582, funding_indicative=0.000078, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.88%, turnover=9818721. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-27T14:45:01+00:00, last15m_closed_end=2026-10-27T14:45+00:00, prior8high=2.608000, depth_time=2026-10-27T14:45:28+00:00, book20_bid_proxy_usdt=1201440, book20_ask_proxy_usdt=912613, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.09%, turnover=5409078. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T14:45:01+00:00, last15m_closed_end=2026-10-27T14:45+00:00, prior8high=0.025580, depth_time=2026-10-27T14:45:08+00:00, book20_bid_proxy_usdt=131224, book20_ask_proxy_usdt=97327, funding_indicative=-0.000428, next_funding_utc=2026-10-27T15:00:00+00:00, funding_cycle_h=1, 24h_change=-9.10%, turnover=6540989. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T14:45:01+00:00, last15m_closed_end=2026-10-27T14:45+00:00, prior8high=0.004256, depth_time=2026-10-27T14:45:23+00:00, book20_bid_proxy_usdt=2555636, book20_ask_proxy_usdt=1969422, funding_indicative=0.000050, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.02%, turnover=21550241. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T14:45:01+00:00, last15m_closed_end=2026-10-27T14:45+00:00, prior8high=203.620000, depth_time=2026-10-27T14:45:11+00:00, book20_bid_proxy_usdt=99129, book20_ask_proxy_usdt=64162, funding_indicative=-0.000207, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.35%, turnover=98835502. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-10-27T14:45:01+00:00, last15m_closed_end=2026-10-27T14:45+00:00, prior8high=101.160000, depth_time=2026-10-27T14:45:36+00:00, book20_bid_proxy_usdt=17642864, book20_ask_proxy_usdt=16457292, funding_indicative=0.000076, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.29%, turnover=709721147. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T14:45:01+00:00, last15m_closed_end=2026-10-27T14:45+00:00, prior8high=251.610000, depth_time=2026-10-27T14:45:34+00:00, book20_bid_proxy_usdt=126521, book20_ask_proxy_usdt=55391, funding_indicative=0.000050, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.50%, turnover=52470041. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-27T14:45:01+00:00, last15m_closed_end=2026-10-27T14:45+00:00, prior8high=0.531400, depth_time=2026-10-27T14:45:36+00:00, book20_bid_proxy_usdt=379995, book20_ask_proxy_usdt=510014, funding_indicative=0.000000, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.25%, turnover=17695570. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T14:45:01+00:00, last15m_closed_end=2026-10-27T14:45+00:00, prior8high=0.438400, depth_time=2026-10-27T14:45:16+00:00, book20_bid_proxy_usdt=3784718, book20_ask_proxy_usdt=3311786, funding_indicative=-0.000038, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.55%, turnover=72949790. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
