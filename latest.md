# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T00:15:38Z**
- feed_generated_utc: 2026-11-07T00:15:39+00:00
- source_sha256: `ef3f0565e3c4251395b4b32aa3e7e691c832d6eca3fb9ca8faddcd0ff419cab3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T00:15+00:00, close=75924.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-07T00:00+00:00, close=75811.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-07T00:00+00:00, close=75811.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.136000|-28.42|-48.79|-28.54|34058432|7.36|
|CYBER_USDT|0.329200|-7.00|20.49|-7.12|6880467|3.04|
|ANTHROPIC_USDT|1345.260000|-6.00|-19.75|-6.12|7454753|3.64|
|TRUMPOFFICIAL_USDT|1.200000|-3.38|-23.66|-3.50|12640981|8.33|
|PUMPFUN_USDT|0.003923|-3.01|-4.48|-3.13|12671646|2.55|
|DOT_USDT|0.911000|-2.78|-6.00|-2.90|7322524|1.10|
|ENA_USDT|0.163650|-2.30|-13.81|-2.42|32906404|0.61|
|ADA_USDT|0.183900|-2.23|-4.51|-2.35|28192425|5.44|
|ONDO_USDT|0.370400|-1.62|-7.26|-1.74|11730848|2.70|
|LIT_USDT|3.344600|-1.40|18.42|-1.52|9377162|0.30|
|HBAR_USDT|0.067580|-1.19|-5.94|-1.31|5150756|1.48|
|XLM_USDT|0.153250|-1.17|-11.02|-1.29|23395805|0.65|
|UNI_USDT|6.891000|-0.89|-0.80|-1.01|30766048|1.45|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.183900|0.183800|0.183900|1.70|N|Y/Y|Y/Y|Y|N|
|ANTHROPIC_USDT|1345.260000|1322.000000|1345.260000|0.11|N|Y/Y|Y/Y|Y|N|
|CYBER_USDT|0.329200|0.333700|0.329200|1.53|Y|Y/Y|N/N|Y|N|
|DOT_USDT|0.911000|0.912400|0.911000|2.42|Y|Y/Y|Y/Y|Y|Y|
|ENA_USDT|0.163650|0.163440|0.163650|0.29|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.067580|0.067360|0.067580|2.30|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.344600|3.292600|3.344600|0.92|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.370400|0.370400|0.370400|3.48|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003923|0.003882|0.003923|0.19|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.200000|1.202000|1.201000|0.81|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.136000|0.134500|0.135100|0.38|N|Y/Y|N/N|Y|N|
|UNI_USDT|6.891000|6.871000|6.891000|0.81|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.153250|0.153110|0.153250|0.60|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-11-07T00:15:02+00:00, last15m_closed_end=2026-11-07T00:15+00:00, prior8high=0.186900, depth_time=2026-11-07T00:15:24+00:00, book20_bid_proxy_usdt=8491106, book20_ask_proxy_usdt=9145116, funding_indicative=0.000100, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.23%, turnover=28192425. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-07T00:15:02+00:00, last15m_closed_end=2026-11-07T00:15+00:00, prior8high=1364.960000, depth_time=2026-11-07T00:15:12+00:00, book20_bid_proxy_usdt=29374, book20_ask_proxy_usdt=30171, funding_indicative=0.000050, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.00%, turnover=7454753. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CYBER_USDT: quote_utc=2026-11-07T00:15:02+00:00, last15m_closed_end=2026-11-07T00:15+00:00, prior8high=0.356100, depth_time=2026-11-07T00:15:09+00:00, book20_bid_proxy_usdt=94499, book20_ask_proxy_usdt=147767, funding_indicative=-0.002201, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.00%, turnover=6880467. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-07T00:15:02+00:00, last15m_closed_end=2026-11-07T00:15+00:00, prior8high=0.925800, depth_time=2026-11-07T00:15:19+00:00, book20_bid_proxy_usdt=401732, book20_ask_proxy_usdt=503357, funding_indicative=0.000100, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.78%, turnover=7322524. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-07T00:15:02+00:00, last15m_closed_end=2026-11-07T00:15+00:00, prior8high=0.166110, depth_time=2026-11-07T00:15:20+00:00, book20_bid_proxy_usdt=194966, book20_ask_proxy_usdt=216958, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.30%, turnover=32906404. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-07T00:15:02+00:00, last15m_closed_end=2026-11-07T00:15+00:00, prior8high=0.068220, depth_time=2026-11-07T00:15:32+00:00, book20_bid_proxy_usdt=716427, book20_ask_proxy_usdt=763661, funding_indicative=0.000002, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.19%, turnover=5150756. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-07T00:15:02+00:00, last15m_closed_end=2026-11-07T00:15+00:00, prior8high=3.375500, depth_time=2026-11-07T00:15:28+00:00, book20_bid_proxy_usdt=27595, book20_ask_proxy_usdt=33241, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.40%, turnover=9377162. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-07T00:15:02+00:00, last15m_closed_end=2026-11-07T00:15+00:00, prior8high=0.375800, depth_time=2026-11-07T00:15:24+00:00, book20_bid_proxy_usdt=1555186, book20_ask_proxy_usdt=1706411, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.62%, turnover=11730848. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-07T00:15:02+00:00, last15m_closed_end=2026-11-07T00:15+00:00, prior8high=0.003993, depth_time=2026-11-07T00:15:17+00:00, book20_bid_proxy_usdt=2261005, book20_ask_proxy_usdt=2597738, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.01%, turnover=12671646. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-07T00:15:02+00:00, last15m_closed_end=2026-11-07T00:15+00:00, prior8high=1.229000, depth_time=2026-11-07T00:15:12+00:00, book20_bid_proxy_usdt=1427831, book20_ask_proxy_usdt=1432225, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.38%, turnover=12640981. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-07T00:15:02+00:00, last15m_closed_end=2026-11-07T00:15+00:00, prior8high=0.145700, depth_time=2026-11-07T00:15:07+00:00, book20_bid_proxy_usdt=250470, book20_ask_proxy_usdt=119864, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-28.42%, turnover=34058432. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-07T00:15:02+00:00, last15m_closed_end=2026-11-07T00:15+00:00, prior8high=6.980000, depth_time=2026-11-07T00:15:34+00:00, book20_bid_proxy_usdt=2288222, book20_ask_proxy_usdt=2293073, funding_indicative=0.000094, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.89%, turnover=30766048. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-07T00:15:02+00:00, last15m_closed_end=2026-11-07T00:15+00:00, prior8high=0.155630, depth_time=2026-11-07T00:15:34+00:00, book20_bid_proxy_usdt=226648, book20_ask_proxy_usdt=238201, funding_indicative=0.000000, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.17%, turnover=23395805. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
