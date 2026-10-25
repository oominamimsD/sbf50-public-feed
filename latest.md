# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T08:15:37Z**
- feed_generated_utc: 2026-10-25T08:15:40+00:00
- source_sha256: `81b4847d364355c59c7278698a96fce9587c4b0240d706fec5193b0b60b9ed9d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1180; contracts: 1172; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T08:15+00:00, close=80591.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T08:00+00:00, close=80645, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T08:00+00:00, close=80645, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.050000|-25.81|61.55|-26.84|13939114|6.00|
|IRYS_USDT|0.036830|-20.02|188.63|-21.05|33730946|2.71|
|BIRB_USDT|0.078600|-19.51|61.99|-20.54|5129909|3.82|
|BTW_USDT|1.684200|-3.27|-25.78|-4.30|11644891|1.19|
|STRK_USDT|0.045940|-1.69|-30.55|-2.72|8637646|2.18|
|DOT_USDT|1.027100|-1.15|-8.08|-2.18|11782204|0.97|
|AKE_USDT|0.028984|-0.84|0.07|-1.87|6181112|1.38|
|SUI_USDT|0.918100|-0.74|-6.48|-1.77|65786775|1.09|
|SEI_USDT|0.052650|-0.43|-15.09|-1.46|9677640|1.90|
|APT_USDT|0.699900|-0.28|-12.23|-1.31|6037479|1.43|
|PENGU_USDT|0.007432|-0.14|-0.28|-1.17|5477210|1.35|
|LINK_USDT|11.384000|0.01|-4.38|-1.02|49070019|0.88|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.028984|0.028767|0.028984|0.71|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.699900|0.697500|0.700200|4.92|N|Y/Y|Y/Y|Y|N|
|BIRB_USDT|0.078600|0.077430|0.078600|1.56|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.684200|1.590000|1.684200|2.38|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.027100|1.017100|1.027100|1.21|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.036830|0.036180|0.036830|0.79|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.384000|11.339000|11.384000|0.54|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.050000|0.049270|0.050070|1.87|N|Y/Y|N/N|Y|N|
|PENGU_USDT|0.007432|0.007419|0.007432|2.58|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.052650|0.052650|0.052650|2.76|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.045940|0.045710|0.045940|0.63|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.918100|0.911400|0.918100|0.87|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-25T08:15:00+00:00, last15m_closed_end=2026-10-25T08:15+00:00, prior8high=0.030007, depth_time=2026-10-25T08:15:23+00:00, book20_bid_proxy_usdt=10187, book20_ask_proxy_usdt=14204, funding_indicative=0.000050, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.84%, turnover=6181112. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-25T08:15:00+00:00, last15m_closed_end=2026-10-25T08:15+00:00, prior8high=0.707600, depth_time=2026-10-25T08:15:30+00:00, book20_bid_proxy_usdt=173786, book20_ask_proxy_usdt=157311, funding_indicative=-0.000040, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.28%, turnover=6037479. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BIRB_USDT: quote_utc=2026-10-25T08:14:59+00:00, last15m_closed_end=2026-10-25T08:15+00:00, prior8high=0.085440, depth_time=2026-10-25T08:15:12+00:00, book20_bid_proxy_usdt=28835, book20_ask_proxy_usdt=29375, funding_indicative=-0.009836, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-19.51%, turnover=5129909. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-25T08:15:00+00:00, last15m_closed_end=2026-10-25T08:15+00:00, prior8high=1.915400, depth_time=2026-10-25T08:15:14+00:00, book20_bid_proxy_usdt=93377, book20_ask_proxy_usdt=12462, funding_indicative=-0.008767, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.27%, turnover=11644891. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T08:15:00+00:00, last15m_closed_end=2026-10-25T08:15+00:00, prior8high=1.036400, depth_time=2026-10-25T08:15:21+00:00, book20_bid_proxy_usdt=336564, book20_ask_proxy_usdt=346375, funding_indicative=-0.000025, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.15%, turnover=11782204. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T08:14:59+00:00, last15m_closed_end=2026-10-25T08:15+00:00, prior8high=0.044320, depth_time=2026-10-25T08:15:11+00:00, book20_bid_proxy_usdt=41340, book20_ask_proxy_usdt=40292, funding_indicative=-0.001745, next_funding_utc=2026-10-25T09:00:00+00:00, funding_cycle_h=1, 24h_change=-20.02%, turnover=33730946. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-25T08:15:00+00:00, last15m_closed_end=2026-10-25T08:15+00:00, prior8high=11.445000, depth_time=2026-10-25T08:15:35+00:00, book20_bid_proxy_usdt=533775, book20_ask_proxy_usdt=514284, funding_indicative=0.000044, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=0.01%, turnover=49070019. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T08:14:59+00:00, last15m_closed_end=2026-10-25T08:15+00:00, prior8high=0.057510, depth_time=2026-10-25T08:15:08+00:00, book20_bid_proxy_usdt=85807, book20_ask_proxy_usdt=73767, funding_indicative=-0.001063, next_funding_utc=2026-10-25T09:00:00+00:00, funding_cycle_h=1, 24h_change=-25.81%, turnover=13939114. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-25T08:15:00+00:00, last15m_closed_end=2026-10-25T08:15+00:00, prior8high=0.007503, depth_time=2026-10-25T08:15:32+00:00, book20_bid_proxy_usdt=189972, book20_ask_proxy_usdt=172579, funding_indicative=-0.000057, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.14%, turnover=5477210. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-25T08:15:00+00:00, last15m_closed_end=2026-10-25T08:15+00:00, prior8high=0.053280, depth_time=2026-10-25T08:15:27+00:00, book20_bid_proxy_usdt=333534, book20_ask_proxy_usdt=260666, funding_indicative=-0.000088, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.43%, turnover=9677640. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T08:15:00+00:00, last15m_closed_end=2026-10-25T08:15+00:00, prior8high=0.046630, depth_time=2026-10-25T08:15:18+00:00, book20_bid_proxy_usdt=924267, book20_ask_proxy_usdt=718515, funding_indicative=0.000030, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.69%, turnover=8637646. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T08:14:59+00:00, last15m_closed_end=2026-10-25T08:15+00:00, prior8high=0.921900, depth_time=2026-10-25T08:15:25+00:00, book20_bid_proxy_usdt=984653, book20_ask_proxy_usdt=974644, funding_indicative=0.000033, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.74%, turnover=65786775. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
