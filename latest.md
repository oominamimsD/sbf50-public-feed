# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T01:45:38Z**
- feed_generated_utc: 2026-11-07T01:45:40+00:00
- source_sha256: `1d931980db7825b6b5299ee76c47c3f1885809b7b07b2e486b3c789819b3d43d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T01:45+00:00, close=75973.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-07T01:00+00:00, close=75871, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-07T00:00+00:00, close=75811.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.143100|-24.68|-46.12|-24.86|34945970|7.00|
|CYBER_USDT|0.322000|-9.03|17.86|-9.21|6736964|3.10|
|ANTHROPIC_USDT|1342.570000|-6.19|-19.91|-6.37|7291392|0.07|
|TRUMPOFFICIAL_USDT|1.200000|-3.38|-23.66|-3.56|11693806|8.33|
|DOT_USDT|0.907000|-3.21|-6.41|-3.39|6849326|1.10|
|PUMPFUN_USDT|0.003931|-2.81|-4.28|-2.99|12480469|2.55|
|ARB_USDT|0.164210|-2.38|1.28|-2.56|26581774|0.61|
|APT_USDT|0.603800|-2.20|-3.80|-2.38|5075000|1.66|
|ENA_USDT|0.163930|-2.13|-13.66|-2.31|31649139|0.61|
|OP_USDT|0.105150|-2.02|-2.82|-2.20|5835492|0.95|
|ONDO_USDT|0.371500|-1.32|-6.98|-1.50|11232259|2.69|
|FARTCOIN_USDT|0.118580|-1.20|-1.42|-1.38|12739789|0.84|
|HBAR_USDT|0.067770|-0.92|-5.67|-1.10|5007204|1.48|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ANTHROPIC_USDT|1342.570000|1322.730000|1342.570000|0.03|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.603800|0.602100|0.603800|0.35|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.164210|0.164290|0.164210|1.02|N|Y/Y|N/N|Y|N|
|CYBER_USDT|0.322000|0.316100|0.322000|0.65|N|Y/Y|N/N|Y|N|
|DOT_USDT|0.907000|0.904500|0.907000|0.49|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.163930|0.163260|0.163930|0.71|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.118580|0.117630|0.118500|0.17|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.067770|0.067340|0.067770|1.74|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.371500|0.369900|0.371500|0.67|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.105150|0.104950|0.105150|1.29|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003931|0.003882|0.003931|0.15|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.200000|1.196000|1.200000|0.55|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.143100|0.130700|0.143100|1.15|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ANTHROPIC_USDT: quote_utc=2026-11-07T01:44:59+00:00, last15m_closed_end=2026-11-07T01:45+00:00, prior8high=1354.930000, depth_time=2026-11-07T01:45:11+00:00, book20_bid_proxy_usdt=21427, book20_ask_proxy_usdt=16033, funding_indicative=0.000050, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.19%, turnover=7291392. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-11-07T01:44:59+00:00, last15m_closed_end=2026-11-07T01:45+00:00, prior8high=0.605600, depth_time=2026-11-07T01:45:24+00:00, book20_bid_proxy_usdt=237396, book20_ask_proxy_usdt=161417, funding_indicative=0.000029, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.20%, turnover=5075000. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-07T01:44:59+00:00, last15m_closed_end=2026-11-07T01:45+00:00, prior8high=0.165540, depth_time=2026-11-07T01:45:22+00:00, book20_bid_proxy_usdt=122792, book20_ask_proxy_usdt=81366, funding_indicative=0.000006, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.38%, turnover=26581774. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CYBER_USDT: quote_utc=2026-11-07T01:44:59+00:00, last15m_closed_end=2026-11-07T01:45+00:00, prior8high=0.337100, depth_time=2026-11-07T01:45:08+00:00, book20_bid_proxy_usdt=91468, book20_ask_proxy_usdt=215869, funding_indicative=-0.002281, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.03%, turnover=6736964. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-07T01:44:59+00:00, last15m_closed_end=2026-11-07T01:45+00:00, prior8high=0.914000, depth_time=2026-11-07T01:45:16+00:00, book20_bid_proxy_usdt=480584, book20_ask_proxy_usdt=274726, funding_indicative=0.000100, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.21%, turnover=6849326. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-07T01:44:59+00:00, last15m_closed_end=2026-11-07T01:45+00:00, prior8high=0.164540, depth_time=2026-11-07T01:45:27+00:00, book20_bid_proxy_usdt=348101, book20_ask_proxy_usdt=144478, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.13%, turnover=31649139. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-07T01:44:59+00:00, last15m_closed_end=2026-11-07T01:45+00:00, prior8high=0.118900, depth_time=2026-11-07T01:45:34+00:00, book20_bid_proxy_usdt=94324, book20_ask_proxy_usdt=93201, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.20%, turnover=12739789. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-07T01:44:59+00:00, last15m_closed_end=2026-11-07T01:45+00:00, prior8high=0.067850, depth_time=2026-11-07T01:45:37+00:00, book20_bid_proxy_usdt=730382, book20_ask_proxy_usdt=684952, funding_indicative=-0.000040, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.92%, turnover=5007204. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-07T01:44:59+00:00, last15m_closed_end=2026-11-07T01:45+00:00, prior8high=0.372400, depth_time=2026-11-07T01:45:32+00:00, book20_bid_proxy_usdt=1678328, book20_ask_proxy_usdt=1214703, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.32%, turnover=11232259. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-07T01:44:59+00:00, last15m_closed_end=2026-11-07T01:45+00:00, prior8high=0.105740, depth_time=2026-11-07T01:45:28+00:00, book20_bid_proxy_usdt=151927, book20_ask_proxy_usdt=112300, funding_indicative=-0.000006, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.02%, turnover=5835492. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-07T01:44:59+00:00, last15m_closed_end=2026-11-07T01:45+00:00, prior8high=0.003941, depth_time=2026-11-07T01:45:19+00:00, book20_bid_proxy_usdt=2224988, book20_ask_proxy_usdt=2364674, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.81%, turnover=12480469. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-07T01:44:59+00:00, last15m_closed_end=2026-11-07T01:45+00:00, prior8high=1.209000, depth_time=2026-11-07T01:45:13+00:00, book20_bid_proxy_usdt=1509905, book20_ask_proxy_usdt=1257384, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.38%, turnover=11693806. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-07T01:44:59+00:00, last15m_closed_end=2026-11-07T01:45+00:00, prior8high=0.144300, depth_time=2026-11-07T01:45:07+00:00, book20_bid_proxy_usdt=165552, book20_ask_proxy_usdt=156685, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-24.68%, turnover=34945970. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
