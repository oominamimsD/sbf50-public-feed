# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T14:00:42Z**
- feed_generated_utc: 2026-10-25T14:00:45+00:00
- source_sha256: `b53fb41d01a31de1a3401d4b3b3553e84ae8fb50f1354dfd1b816b2166fd4197`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T14:00+00:00, close=80346.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T14:00+00:00, close=80346.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T12:00+00:00, close=80542.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.047210|-29.95|52.53|-30.66|5814680|4.24|
|IRYS_USDT|0.036300|-21.17|184.48|-21.88|24474942|2.75|
|BTW_USDT|1.688200|-3.04|-25.61|-3.75|12127574|1.78|
|STRK_USDT|0.045340|-2.97|-31.45|-3.68|10202841|2.21|
|PENGU_USDT|0.007355|-2.58|-1.31|-3.29|5933563|1.36|
|DOT_USDT|1.025700|-2.23|-8.20|-2.94|12604961|1.95|
|APT_USDT|0.693500|-1.85|-13.04|-2.56|5874975|1.44|
|SUI_USDT|0.911600|-1.73|-7.15|-2.44|69928366|1.10|
|SEI_USDT|0.052420|-1.65|-15.46|-2.36|6161139|3.82|
|FARTCOIN_USDT|0.122730|-1.11|-17.10|-1.82|8636814|0.81|
|ARB_USDT|0.165340|-1.10|-10.10|-1.81|15419450|0.60|
|OP_USDT|0.110090|-0.76|-14.65|-1.47|6035922|0.91|
|ONDO_USDT|0.401800|-0.69|-8.59|-1.40|14879622|2.49|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.693500|0.692600|0.693500|0.54|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.165340|0.164550|0.165340|0.14|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.688200|1.638700|1.686700|1.49|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.025700|1.018400|1.025700|0.37|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.122730|0.122670|0.122730|1.30|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.036300|0.033150|0.036460|2.22|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.401800|0.400100|0.401800|0.45|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.110090|0.109710|0.110090|0.53|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.047210|0.045450|0.047500|0.82|N|Y/Y|N/N|Y|N|
|PENGU_USDT|0.007355|0.007341|0.007355|0.61|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.052420|0.052220|0.052420|0.17|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.045340|0.045250|0.045350|0.09|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.911600|0.911900|0.911600|1.05|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-25T14:00:04+00:00, last15m_closed_end=2026-10-25T14:00+00:00, prior8high=0.698900, depth_time=2026-10-25T14:00:25+00:00, book20_bid_proxy_usdt=157053, book20_ask_proxy_usdt=189614, funding_indicative=-0.000126, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.85%, turnover=5874975. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-25T14:00:04+00:00, last15m_closed_end=2026-10-25T14:00+00:00, prior8high=0.166330, depth_time=2026-10-25T14:00:36+00:00, book20_bid_proxy_usdt=78585, book20_ask_proxy_usdt=126212, funding_indicative=0.000049, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.10%, turnover=15419450. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-25T14:00:04+00:00, last15m_closed_end=2026-10-25T14:00+00:00, prior8high=1.701100, depth_time=2026-10-25T14:00:13+00:00, book20_bid_proxy_usdt=7266, book20_ask_proxy_usdt=7105, funding_indicative=-0.009396, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.04%, turnover=12127574. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T14:00:04+00:00, last15m_closed_end=2026-10-25T14:00+00:00, prior8high=1.031100, depth_time=2026-10-25T14:00:23+00:00, book20_bid_proxy_usdt=335887, book20_ask_proxy_usdt=262262, funding_indicative=-0.000071, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.23%, turnover=12604961. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-25T14:00:04+00:00, last15m_closed_end=2026-10-25T14:00+00:00, prior8high=0.124600, depth_time=2026-10-25T14:00:32+00:00, book20_bid_proxy_usdt=59955, book20_ask_proxy_usdt=76155, funding_indicative=0.000012, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.11%, turnover=8636814. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T14:00:03+00:00, last15m_closed_end=2026-10-25T14:00+00:00, prior8high=0.036030, depth_time=2026-10-25T14:00:12+00:00, book20_bid_proxy_usdt=39956, book20_ask_proxy_usdt=52729, funding_indicative=-0.000004, next_funding_utc=2026-10-25T15:00:00+00:00, funding_cycle_h=1, 24h_change=-21.17%, turnover=24474942. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-25T14:00:03+00:00, last15m_closed_end=2026-10-25T14:00+00:00, prior8high=0.404800, depth_time=2026-10-25T14:00:41+00:00, book20_bid_proxy_usdt=1910061, book20_ask_proxy_usdt=1936154, funding_indicative=0.000011, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.69%, turnover=14879622. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-25T14:00:04+00:00, last15m_closed_end=2026-10-25T14:00+00:00, prior8high=0.110870, depth_time=2026-10-25T14:00:37+00:00, book20_bid_proxy_usdt=129527, book20_ask_proxy_usdt=109834, funding_indicative=0.000004, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.76%, turnover=6035922. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T14:00:03+00:00, last15m_closed_end=2026-10-25T14:00+00:00, prior8high=0.047940, depth_time=2026-10-25T14:00:09+00:00, book20_bid_proxy_usdt=90106, book20_ask_proxy_usdt=82557, funding_indicative=-0.000794, next_funding_utc=2026-10-25T15:00:00+00:00, funding_cycle_h=1, 24h_change=-29.95%, turnover=5814680. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-25T14:00:04+00:00, last15m_closed_end=2026-10-25T14:00+00:00, prior8high=0.007422, depth_time=2026-10-25T14:00:18+00:00, book20_bid_proxy_usdt=210343, book20_ask_proxy_usdt=279334, funding_indicative=-0.000052, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.58%, turnover=5933563. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-25T14:00:04+00:00, last15m_closed_end=2026-10-25T14:00+00:00, prior8high=0.052880, depth_time=2026-10-25T14:00:30+00:00, book20_bid_proxy_usdt=328390, book20_ask_proxy_usdt=242529, funding_indicative=-0.000029, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.65%, turnover=6161139. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T14:00:04+00:00, last15m_closed_end=2026-10-25T14:00+00:00, prior8high=0.046180, depth_time=2026-10-25T14:00:17+00:00, book20_bid_proxy_usdt=1085770, book20_ask_proxy_usdt=828121, funding_indicative=0.000021, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.97%, turnover=10202841. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T14:00:03+00:00, last15m_closed_end=2026-10-25T14:00+00:00, prior8high=0.920400, depth_time=2026-10-25T14:00:27+00:00, book20_bid_proxy_usdt=2035383, book20_ask_proxy_usdt=1098210, funding_indicative=-0.000063, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.73%, turnover=69928366. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
