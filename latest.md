# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-29T18:15:36Z**
- feed_generated_utc: 2026-10-29T18:15:39+00:00
- source_sha256: `07179a2868da5bc0036fe5c1c14ebe056fd40a7f23502e38782e49962f473e0c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1195; contracts: 1187; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-29T18:15+00:00, close=80834.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-29T18:00+00:00, close=80857.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-29T16:00+00:00, close=81732.5, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IDOL_USDT|0.010775|-28.81|37.96|-27.72|5584018|5.57|
|BTW_USDT|1.516400|-7.42|-15.28|-6.33|9683848|3.30|
|APT_USDT|0.676900|-3.75|-12.34|-2.66|9399017|4.43|
|NEAR_USDT|4.489000|-3.44|-9.20|-2.35|116218069|4.45|
|QNT_USDT|192.550000|-3.11|0.96|-2.02|63780471|0.52|
|FARTCOIN_USDT|0.130380|-2.99|-8.72|-1.90|11216776|1.53|
|WLD_USDT|0.423300|-2.97|-20.44|-1.88|84218396|2.36|
|TRUMPOFFICIAL_USDT|1.678000|-2.89|-3.78|-1.80|6660693|5.96|
|FET_USDT|0.179500|-2.86|-3.13|-1.77|9467881|5.57|
|DOT_USDT|0.990500|-2.64|-11.90|-1.55|11102822|1.01|
|SEI_USDT|0.052070|-2.56|-10.33|-1.47|5720476|1.92|
|HBAR_USDT|0.073590|-2.23|-8.13|-1.14|14945631|1.36|
|ICP_USDT|2.571000|-2.13|-6.40|-1.04|5414002|3.89|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.676900|0.672400|0.676900|0.47|N|Y/N|N/Y|N|N|
|BTW_USDT|1.516400|1.509900|1.516400|0.72|N|Y/Y|Y/N|N|N|
|DOT_USDT|0.990500|0.985600|0.990500|0.34|N|Y/N|N/Y|N|N|
|FARTCOIN_USDT|0.130380|0.129390|0.130330|0.41|N|Y/N|N/Y|N|N|
|FET_USDT|0.179500|0.178800|0.179500|1.07|N|Y/N|N/N|N|N|
|HBAR_USDT|0.073590|0.073260|0.073590|0.74|N|Y/N|Y/Y|N|N|
|ICP_USDT|2.571000|2.555000|2.571000|0.74|N|Y/N|N/Y|N|N|
|IDOL_USDT|0.010775|0.011819|0.010787|2.51|Y|Y/N|N/N|N|N|
|NEAR_USDT|4.489000|4.452000|4.489000|0.36|N|Y/N|N/Y|N|N|
|QNT_USDT|192.550000|190.720000|192.440000|0.36|N|Y/N|N/Y|N|N|
|SEI_USDT|0.052070|0.051850|0.052070|0.66|N|Y/N|N/Y|N|N|
|TRUMPOFFICIAL_USDT|1.678000|1.667000|1.678000|0.44|N|Y/N|N/Y|N|N|
|WLD_USDT|0.423300|0.418500|0.423300|0.48|N|Y/N|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-29T18:15:01+00:00, last15m_closed_end=2026-10-29T18:15+00:00, prior8high=0.707400, depth_time=2026-10-29T18:15:12+00:00, book20_bid_proxy_usdt=178226, book20_ask_proxy_usdt=159726, funding_indicative=0.000100, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.75%, turnover=9399017. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-29T18:15:01+00:00, last15m_closed_end=2026-10-29T18:15+00:00, prior8high=1.638100, depth_time=2026-10-29T18:15:09+00:00, book20_bid_proxy_usdt=30155, book20_ask_proxy_usdt=10620, funding_indicative=-0.000046, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-7.42%, turnover=9683848. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-29T18:15:01+00:00, last15m_closed_end=2026-10-29T18:15+00:00, prior8high=1.023800, depth_time=2026-10-29T18:15:29+00:00, book20_bid_proxy_usdt=52379, book20_ask_proxy_usdt=629897, funding_indicative=0.000087, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.64%, turnover=11102822. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-29T18:15:01+00:00, last15m_closed_end=2026-10-29T18:15+00:00, prior8high=0.136060, depth_time=2026-10-29T18:15:19+00:00, book20_bid_proxy_usdt=46988, book20_ask_proxy_usdt=81398, funding_indicative=0.000050, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.99%, turnover=11216776. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-29T18:15:01+00:00, last15m_closed_end=2026-10-29T18:15+00:00, prior8high=0.185600, depth_time=2026-10-29T18:15:26+00:00, book20_bid_proxy_usdt=1547325, book20_ask_proxy_usdt=885739, funding_indicative=0.000100, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.86%, turnover=9467881. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-29T18:15:01+00:00, last15m_closed_end=2026-10-29T18:15+00:00, prior8high=0.075780, depth_time=2026-10-29T18:15:33+00:00, book20_bid_proxy_usdt=542573, book20_ask_proxy_usdt=745936, funding_indicative=0.000100, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.23%, turnover=14945631. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-29T18:15:01+00:00, last15m_closed_end=2026-10-29T18:15+00:00, prior8high=2.641000, depth_time=2026-10-29T18:15:34+00:00, book20_bid_proxy_usdt=962672, book20_ask_proxy_usdt=853847, funding_indicative=0.000077, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.13%, turnover=5414002. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-10-29T18:15:01+00:00, last15m_closed_end=2026-10-29T18:15+00:00, prior8high=0.015270, depth_time=2026-10-29T18:15:07+00:00, book20_bid_proxy_usdt=7495, book20_ask_proxy_usdt=10492, funding_indicative=0.000152, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-28.81%, turnover=5584018. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-29T18:15:01+00:00, last15m_closed_end=2026-10-29T18:15+00:00, prior8high=4.689000, depth_time=2026-10-29T18:15:15+00:00, book20_bid_proxy_usdt=699287, book20_ask_proxy_usdt=5272944, funding_indicative=0.000100, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.44%, turnover=116218069. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-29T18:15:01+00:00, last15m_closed_end=2026-10-29T18:15+00:00, prior8high=199.910000, depth_time=2026-10-29T18:15:17+00:00, book20_bid_proxy_usdt=102230, book20_ask_proxy_usdt=74548, funding_indicative=-0.000048, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.11%, turnover=63780471. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-29T18:15:01+00:00, last15m_closed_end=2026-10-29T18:15+00:00, prior8high=0.053940, depth_time=2026-10-29T18:15:31+00:00, book20_bid_proxy_usdt=160646, book20_ask_proxy_usdt=231611, funding_indicative=0.000100, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.56%, turnover=5720476. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-10-29T18:15:02+00:00, last15m_closed_end=2026-10-29T18:15+00:00, prior8high=1.739000, depth_time=2026-10-29T18:15:23+00:00, book20_bid_proxy_usdt=1910695, book20_ask_proxy_usdt=2128954, funding_indicative=0.000050, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.89%, turnover=6660693. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-29T18:15:01+00:00, last15m_closed_end=2026-10-29T18:15+00:00, prior8high=0.443700, depth_time=2026-10-29T18:15:22+00:00, book20_bid_proxy_usdt=2697505, book20_ask_proxy_usdt=4057578, funding_indicative=0.000037, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.97%, turnover=84218396. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
