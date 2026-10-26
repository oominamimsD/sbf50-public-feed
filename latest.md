# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T07:30:43Z**
- feed_generated_utc: 2026-10-26T07:30:47+00:00
- source_sha256: `374be589321d211efe61797c8911ab88ec677160d6dda93d9451d9f8793ae564`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 16; crypto_deep: 15
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T07:30+00:00, close=79984, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T07:00+00:00, close=80093.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T04:00+00:00, close=79565.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.031480|-18.10|158.03|-17.34|13326593|3.18|
|APR_USDT|0.034580|-16.29|26.94|-15.53|9310190|2.89|
|CAP_USDT|0.092720|-13.73|39.42|-12.97|6489127|4.32|
|T_USDT|0.004796|-10.90|1.99|-10.14|5525971|2.09|
|WLD_USDT|0.437400|-4.20|-8.16|-3.44|68779935|2.29|
|XMR_USDT|586.340000|-3.44|0.65|-2.68|6271303|1.19|
|DOT_USDT|1.006600|-3.13|-5.87|-2.37|10602472|0.99|
|DASH_USDT|50.820000|-3.03|6.14|-2.27|11911281|1.97|
|LIT_USDT|3.086500|-2.89|5.32|-2.13|5958091|0.32|
|BTW_USDT|1.611500|-2.85|-30.09|-2.09|11035728|3.10|
|PUMPFUN_USDT|0.004171|-2.66|-0.57|-1.90|16612596|2.40|
|STRK_USDT|0.044550|-2.60|-27.63|-1.84|9734592|2.24|
|NEAR_USDT|4.447000|-2.13|-6.14|-1.37|130949798|2.25|
|TIA_USDT|0.526200|-2.02|-14.84|-1.26|17831433|1.90|
|APT_USDT|0.688200|-1.92|-10.46|-1.16|5969947|1.45|
|INJ_USDT|7.563000|-1.83|-6.87|-1.07|25707095|1.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.034580|0.032200|0.034580|1.27|N|Y/Y|N/N|Y|N|
|APT_USDT|0.688200|0.686800|0.688100|1.42|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.611500|1.578900|1.611500|0.76|N|Y/Y|Y/Y|Y|N|
|CAP_USDT|0.092720|0.097110|0.092720|2.37|Y|Y/N|N/N|Y|N|
|DASH_USDT|50.820000|50.820000|50.820000|0.12|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.006600|1.002800|1.006400|0.89|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.031480|0.030290|0.031480|1.28|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.086500|3.057100|3.086500|1.68|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.447000|4.442000|4.447000|0.46|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004171|0.004163|0.004171|3.92|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.044550|0.044490|0.044550|0.57|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.526200|0.519000|0.526200|0.33|N|Y/Y|Y/Y|Y|N|
|T_USDT|0.004796|0.004788|0.004796|1.05|N|Y/Y|Y/N|Y|N|
|WLD_USDT|0.437400|0.436400|0.437400|0.79|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|586.340000|584.290000|586.340000|2.21|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T07:30:01+00:00, last15m_closed_end=2026-10-26T07:30+00:00, prior8high=0.037240, depth_time=2026-10-26T07:30:10+00:00, book20_bid_proxy_usdt=59339, book20_ask_proxy_usdt=41121, funding_indicative=0.000050, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-16.29%, turnover=9310190. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-26T07:30:01+00:00, last15m_closed_end=2026-10-26T07:30+00:00, prior8high=0.704500, depth_time=2026-10-26T07:30:42+00:00, book20_bid_proxy_usdt=159833, book20_ask_proxy_usdt=116878, funding_indicative=-0.000008, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.92%, turnover=5969947. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T07:30:01+00:00, last15m_closed_end=2026-10-26T07:30+00:00, prior8high=1.667700, depth_time=2026-10-26T07:30:29+00:00, book20_bid_proxy_usdt=17238, book20_ask_proxy_usdt=14523, funding_indicative=-0.003997, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.85%, turnover=11035728. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CAP_USDT: quote_utc=2026-10-26T07:30:01+00:00, last15m_closed_end=2026-10-26T07:30+00:00, prior8high=0.114220, depth_time=2026-10-26T07:30:13+00:00, book20_bid_proxy_usdt=56655, book20_ask_proxy_usdt=61184, funding_indicative=0.000570, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-13.73%, turnover=6489127. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-26T07:30:01+00:00, last15m_closed_end=2026-10-26T07:30+00:00, prior8high=51.350000, depth_time=2026-10-26T07:30:26+00:00, book20_bid_proxy_usdt=1007200, book20_ask_proxy_usdt=470489, funding_indicative=0.000035, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.03%, turnover=11911281. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T07:30:01+00:00, last15m_closed_end=2026-10-26T07:30+00:00, prior8high=1.021300, depth_time=2026-10-26T07:30:23+00:00, book20_bid_proxy_usdt=260459, book20_ask_proxy_usdt=225660, funding_indicative=-0.000121, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.13%, turnover=10602472. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T07:30:01+00:00, last15m_closed_end=2026-10-26T07:30+00:00, prior8high=0.035230, depth_time=2026-10-26T07:30:07+00:00, book20_bid_proxy_usdt=89935, book20_ask_proxy_usdt=109276, funding_indicative=-0.000417, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=1, 24h_change=-18.10%, turnover=13326593. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T07:30:01+00:00, last15m_closed_end=2026-10-26T07:30+00:00, prior8high=3.131600, depth_time=2026-10-26T07:30:28+00:00, book20_bid_proxy_usdt=20495, book20_ask_proxy_usdt=10131, funding_indicative=0.000028, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.89%, turnover=5958091. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-26T07:30:01+00:00, last15m_closed_end=2026-10-26T07:30+00:00, prior8high=4.541000, depth_time=2026-10-26T07:30:38+00:00, book20_bid_proxy_usdt=3129673, book20_ask_proxy_usdt=2675278, funding_indicative=0.000045, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.13%, turnover=130949798. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-26T07:30:01+00:00, last15m_closed_end=2026-10-26T07:30+00:00, prior8high=0.004233, depth_time=2026-10-26T07:30:32+00:00, book20_bid_proxy_usdt=2455860, book20_ask_proxy_usdt=1737719, funding_indicative=-0.000023, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.66%, turnover=16612596. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-26T07:30:01+00:00, last15m_closed_end=2026-10-26T07:30+00:00, prior8high=0.045380, depth_time=2026-10-26T07:30:35+00:00, book20_bid_proxy_usdt=973848, book20_ask_proxy_usdt=589296, funding_indicative=0.000013, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.60%, turnover=9734592. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-26T07:30:01+00:00, last15m_closed_end=2026-10-26T07:30+00:00, prior8high=0.534000, depth_time=2026-10-26T07:30:40+00:00, book20_bid_proxy_usdt=259437, book20_ask_proxy_usdt=176432, funding_indicative=-0.000024, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.02%, turnover=17831433. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-26T07:30:01+00:00, last15m_closed_end=2026-10-26T07:30+00:00, prior8high=0.004895, depth_time=2026-10-26T07:30:15+00:00, book20_bid_proxy_usdt=126569, book20_ask_proxy_usdt=73288, funding_indicative=-0.000608, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=1, 24h_change=-10.90%, turnover=5525971. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T07:30:01+00:00, last15m_closed_end=2026-10-26T07:30+00:00, prior8high=0.446200, depth_time=2026-10-26T07:30:17+00:00, book20_bid_proxy_usdt=2501016, book20_ask_proxy_usdt=2597663, funding_indicative=-0.000073, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.20%, turnover=68779935. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T07:30:01+00:00, last15m_closed_end=2026-10-26T07:30+00:00, prior8high=591.790000, depth_time=2026-10-26T07:30:20+00:00, book20_bid_proxy_usdt=15415, book20_ask_proxy_usdt=32140, funding_indicative=0.000100, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.44%, turnover=6271303. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
