# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T06:00:45Z**
- feed_generated_utc: 2026-11-05T06:00:47+00:00
- source_sha256: `03b99600e90d5f2695d3b17889d063224af2b31732d34d30f3fab514e9750e3e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 21; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T06:00+00:00, close=80368, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-05T06:00+00:00, close=80368, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-05T04:00+00:00, close=80514.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TRUMPOFFICIAL_USDT|1.264000|-11.36|-26.03|-11.47|26558614|7.90|
|IDOL_USDT|0.020269|-8.47|134.13|-8.58|5206981|2.96|
|VVV_USDT|21.501000|-8.42|-9.72|-8.53|5237626|1.40|
|BTW_USDT|1.038200|-6.18|-40.26|-6.29|5630183|3.85|
|WLD_USDT|0.373600|-4.71|-13.67|-4.82|65693452|2.68|
|ZRO_USDT|1.807500|-4.34|5.57|-4.45|8949427|0.55|
|PEPE_USDT|0.000005|-4.29|2.07|-4.40|129772178|0.20|
|DOT_USDT|0.939400|-3.81|-6.39|-3.92|11554530|1.06|
|SEI_USDT|0.048100|-3.70|-8.98|-3.81|6426710|2.08|
|NEAR_USDT|4.007000|-3.58|-13.43|-3.69|78384033|2.50|
|ENA_USDT|0.179120|-3.57|-8.69|-3.68|96776665|0.56|
|HYPE_USDT|83.255000|-3.52|4.25|-3.63|81318334|0.12|
|OP_USDT|0.109660|-3.33|-1.27|-3.44|9101946|0.91|
|LIT_USDT|3.375300|-3.17|14.89|-3.28|9194462|0.30|
|PUMPFUN_USDT|0.004305|-2.75|2.32|-2.86|14711456|2.32|
|PENGU_USDT|0.007203|-2.53|-7.12|-2.64|7247604|2.78|
|ARB_USDT|0.162980|-2.16|-2.82|-2.27|21605691|0.61|
|AAVE_USDT|131.550000|-1.85|-0.87|-1.96|15854894|0.76|
|FET_USDT|0.160300|-1.83|-11.77|-1.94|7613601|6.24|
|SHIB_USDT|0.000005|-1.52|-4.87|-1.63|7624722|2.12|
|AVAX_USDT|8.733000|-1.45|-1.73|-1.56|24871620|1.15|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.038200|1.015400|1.038200|1.18|N|N/Y|Y/Y|N|N|
|DOT_USDT|0.939400|0.939400|0.939200|2.06|Y|Y/Y|N/N|N|N|
|ENA_USDT|0.179120|0.178600|0.179130|1.44|N|Y/Y|N/N|N|N|
|HYPE_USDT|83.255000|83.085000|83.255000|1.67|N|Y/Y|Y/Y|N|N|
|IDOL_USDT|0.020269|0.020288|0.020269|2.76|Y|Y/Y|N/N|N|N|
|LIT_USDT|3.375300|3.352400|3.375300|0.74|N|Y/N|N/N|N|N|
|NEAR_USDT|4.007000|4.001000|4.007000|0.98|N|Y/N|N/Y|N|N|
|OP_USDT|0.109660|0.109200|0.109660|1.72|N|Y/Y|Y/Y|N|N|
|PEPE_USDT|0.000005|0.000005|0.000005|1.23|N|Y/Y|N/N|N|N|
|PUMPFUN_USDT|0.004305|0.004297|0.004305|0.85|N|N/N|N/N|N|N|
|SEI_USDT|0.048100|0.048100|0.048100|1.66|N|Y/Y|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.264000|1.243000|1.264000|0.46|N|Y/Y|Y/Y|N|N|
|VVV_USDT|21.501000|21.470000|21.501000|1.41|N|Y/Y|Y/Y|N|N|
|WLD_USDT|0.373600|0.371600|0.373500|0.96|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.807500|1.802800|1.807500|0.66|N|Y/Y|N/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-11-05T06:00:01+00:00, last15m_closed_end=2026-11-05T06:00+00:00, prior8high=1.046800, depth_time=2026-11-05T06:00:16+00:00, book20_bid_proxy_usdt=18275, book20_ask_proxy_usdt=15499, funding_indicative=0.000050, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.18%, turnover=5630183. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-05T06:00:01+00:00, last15m_closed_end=2026-11-05T06:00+00:00, prior8high=0.957000, depth_time=2026-11-05T06:00:26+00:00, book20_bid_proxy_usdt=417082, book20_ask_proxy_usdt=858333, funding_indicative=-0.000154, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.81%, turnover=11554530. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-05T06:00:01+00:00, last15m_closed_end=2026-11-05T06:00+00:00, prior8high=0.183000, depth_time=2026-11-05T06:00:34+00:00, book20_bid_proxy_usdt=115783, book20_ask_proxy_usdt=178454, funding_indicative=0.000050, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.57%, turnover=96776665. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-05T06:00:01+00:00, last15m_closed_end=2026-11-05T06:00+00:00, prior8high=84.013000, depth_time=2026-11-05T06:00:36+00:00, book20_bid_proxy_usdt=130578, book20_ask_proxy_usdt=70782, funding_indicative=0.000050, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.52%, turnover=81318334. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-05T06:00:01+00:00, last15m_closed_end=2026-11-05T06:00+00:00, prior8high=0.021370, depth_time=2026-11-05T06:00:10+00:00, book20_bid_proxy_usdt=5670, book20_ask_proxy_usdt=11253, funding_indicative=0.000050, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.47%, turnover=5206981. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-05T06:00:01+00:00, last15m_closed_end=2026-11-05T06:00+00:00, prior8high=3.438400, depth_time=2026-11-05T06:00:42+00:00, book20_bid_proxy_usdt=34134, book20_ask_proxy_usdt=21268, funding_indicative=0.000050, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.17%, turnover=9194462. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-05T06:00:00+00:00, last15m_closed_end=2026-11-05T06:00+00:00, prior8high=4.063000, depth_time=2026-11-05T06:00:31+00:00, book20_bid_proxy_usdt=3470264, book20_ask_proxy_usdt=4730327, funding_indicative=0.000100, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.58%, turnover=78384033. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-05T06:00:01+00:00, last15m_closed_end=2026-11-05T06:00+00:00, prior8high=0.111460, depth_time=2026-11-05T06:00:39+00:00, book20_bid_proxy_usdt=139726, book20_ask_proxy_usdt=156321, funding_indicative=0.000060, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.33%, turnover=9101946. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-05T06:00:01+00:00, last15m_closed_end=2026-11-05T06:00+00:00, prior8high=0.000005, depth_time=2026-11-05T06:00:24+00:00, book20_bid_proxy_usdt=41236, book20_ask_proxy_usdt=51360, funding_indicative=0.000017, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.29%, turnover=129772178. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-05T06:00:01+00:00, last15m_closed_end=2026-11-05T06:00+00:00, prior8high=0.004377, depth_time=2026-11-05T06:00:44+00:00, book20_bid_proxy_usdt=1719219, book20_ask_proxy_usdt=2277260, funding_indicative=0.000026, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.75%, turnover=14711456. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-11-05T06:00:01+00:00, last15m_closed_end=2026-11-05T06:00+00:00, prior8high=0.049330, depth_time=2026-11-05T06:00:29+00:00, book20_bid_proxy_usdt=315668, book20_ask_proxy_usdt=256172, funding_indicative=0.000100, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.70%, turnover=6426710. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-05T06:00:01+00:00, last15m_closed_end=2026-11-05T06:00+00:00, prior8high=1.283000, depth_time=2026-11-05T06:00:07+00:00, book20_bid_proxy_usdt=1534235, book20_ask_proxy_usdt=1202002, funding_indicative=-0.000377, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-11.36%, turnover=26558614. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-05T06:00:01+00:00, last15m_closed_end=2026-11-05T06:00+00:00, prior8high=22.117000, depth_time=2026-11-05T06:00:13+00:00, book20_bid_proxy_usdt=29295, book20_ask_proxy_usdt=16451, funding_indicative=-0.000240, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.42%, turnover=5237626. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-05T06:00:01+00:00, last15m_closed_end=2026-11-05T06:00+00:00, prior8high=0.377500, depth_time=2026-11-05T06:00:18+00:00, book20_bid_proxy_usdt=2612492, book20_ask_proxy_usdt=3186110, funding_indicative=-0.000386, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.71%, turnover=65693452. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-05T06:00:01+00:00, last15m_closed_end=2026-11-05T06:00+00:00, prior8high=1.849200, depth_time=2026-11-05T06:00:20+00:00, book20_bid_proxy_usdt=23604, book20_ask_proxy_usdt=59754, funding_indicative=0.000050, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.34%, turnover=8949427. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
