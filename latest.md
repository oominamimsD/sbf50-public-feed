# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T12:30:38Z**
- feed_generated_utc: 2026-10-25T12:30:41+00:00
- source_sha256: `3b1dc63d34a7f21aca4fdb0e0948660a8c66e744700726ba721f7a6e1b48e6ec`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1180; contracts: 1172; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T12:30+00:00, close=80299.8, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T12:00+00:00, close=80542.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T12:00+00:00, close=80542.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.045810|-32.03|48.01|-32.70|8145564|4.36|
|IRYS_USDT|0.033750|-26.71|164.49|-27.38|27162452|2.96|
|WLD_USDT|0.445900|-3.48|-10.02|-4.15|97416239|2.24|
|BTW_USDT|1.688800|-3.01|-25.58|-3.68|12464075|2.96|
|STRK_USDT|0.045400|-2.84|-31.36|-3.51|10326452|2.20|
|DOT_USDT|1.021900|-1.65|-8.54|-2.32|12622024|0.98|
|APT_USDT|0.692900|-1.28|-13.11|-1.95|6177220|1.44|
|PENGU_USDT|0.007353|-1.20|-1.34|-1.87|5916871|1.36|
|SUI_USDT|0.914500|-1.13|-6.85|-1.80|70058118|1.09|
|SEI_USDT|0.052400|-0.90|-15.49|-1.57|7616705|1.91|
|ARB_USDT|0.164640|-0.66|-10.48|-1.33|16523362|1.21|
|LINK_USDT|11.326000|-0.49|-4.87|-1.16|48095508|0.88|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.692900|0.689400|0.692900|0.45|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.164640|0.163860|0.164640|1.00|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.688800|1.611000|1.688800|1.60|N|N/Y|Y/Y|Y|N|
|DOT_USDT|1.021900|1.013200|1.021900|1.49|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.033750|0.033550|0.033750|0.76|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.326000|11.284000|11.326000|1.15|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.045810|0.045930|0.045810|0.87|N|Y/Y|N/N|Y|N|
|PENGU_USDT|0.007353|0.007333|0.007348|0.81|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.052400|0.052220|0.052400|2.53|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.045400|0.044870|0.045390|0.50|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.914500|0.907500|0.914100|1.15|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.445900|0.441100|0.446000|1.16|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-25T12:30:01+00:00, last15m_closed_end=2026-10-25T12:30+00:00, prior8high=0.698900, depth_time=2026-10-25T12:30:24+00:00, book20_bid_proxy_usdt=90641, book20_ask_proxy_usdt=104753, funding_indicative=-0.000127, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.28%, turnover=6177220. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-25T12:30:00+00:00, last15m_closed_end=2026-10-25T12:30+00:00, prior8high=0.166330, depth_time=2026-10-25T12:30:34+00:00, book20_bid_proxy_usdt=77541, book20_ask_proxy_usdt=69613, funding_indicative=0.000063, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.66%, turnover=16523362. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-25T12:30:00+00:00, last15m_closed_end=2026-10-25T12:30+00:00, prior8high=1.699100, depth_time=2026-10-25T12:30:15+00:00, book20_bid_proxy_usdt=13329, book20_ask_proxy_usdt=9628, funding_indicative=-0.014163, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.01%, turnover=12464075. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T12:30:00+00:00, last15m_closed_end=2026-10-25T12:30+00:00, prior8high=1.028700, depth_time=2026-10-25T12:30:21+00:00, book20_bid_proxy_usdt=220102, book20_ask_proxy_usdt=284452, funding_indicative=-0.000049, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.65%, turnover=12622024. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T12:30:00+00:00, last15m_closed_end=2026-10-25T12:30+00:00, prior8high=0.036110, depth_time=2026-10-25T12:30:11+00:00, book20_bid_proxy_usdt=85909, book20_ask_proxy_usdt=79213, funding_indicative=0.000010, next_funding_utc=2026-10-25T13:00:00+00:00, funding_cycle_h=1, 24h_change=-26.71%, turnover=27162452. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-25T12:30:00+00:00, last15m_closed_end=2026-10-25T12:30+00:00, prior8high=11.416000, depth_time=2026-10-25T12:30:37+00:00, book20_bid_proxy_usdt=662226, book20_ask_proxy_usdt=425382, funding_indicative=-0.000046, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.49%, turnover=48095508. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T12:30:00+00:00, last15m_closed_end=2026-10-25T12:30+00:00, prior8high=0.051530, depth_time=2026-10-25T12:30:09+00:00, book20_bid_proxy_usdt=66911, book20_ask_proxy_usdt=63936, funding_indicative=-0.001264, next_funding_utc=2026-10-25T13:00:00+00:00, funding_cycle_h=1, 24h_change=-32.03%, turnover=8145564. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-25T12:30:01+00:00, last15m_closed_end=2026-10-25T12:30+00:00, prior8high=0.007422, depth_time=2026-10-25T12:30:26+00:00, book20_bid_proxy_usdt=119693, book20_ask_proxy_usdt=259117, funding_indicative=-0.000071, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.20%, turnover=5916871. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-25T12:30:01+00:00, last15m_closed_end=2026-10-25T12:30+00:00, prior8high=0.052880, depth_time=2026-10-25T12:30:31+00:00, book20_bid_proxy_usdt=248007, book20_ask_proxy_usdt=377250, funding_indicative=-0.000096, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.90%, turnover=7616705. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T12:30:01+00:00, last15m_closed_end=2026-10-25T12:30+00:00, prior8high=0.046180, depth_time=2026-10-25T12:30:16+00:00, book20_bid_proxy_usdt=1162102, book20_ask_proxy_usdt=675656, funding_indicative=0.000006, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.84%, turnover=10326452. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T12:30:00+00:00, last15m_closed_end=2026-10-25T12:30+00:00, prior8high=0.920400, depth_time=2026-10-25T12:30:29+00:00, book20_bid_proxy_usdt=1287233, book20_ask_proxy_usdt=1147050, funding_indicative=-0.000060, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.13%, turnover=70058118. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-25T12:30:00+00:00, last15m_closed_end=2026-10-25T12:30+00:00, prior8high=0.456100, depth_time=2026-10-25T12:30:14+00:00, book20_bid_proxy_usdt=2071739, book20_ask_proxy_usdt=1895954, funding_indicative=-0.000021, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.48%, turnover=97416239. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
