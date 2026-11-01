# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T02:45:31Z**
- feed_generated_utc: 2026-11-01T02:45:34+00:00
- source_sha256: `99b386278131db4ca123b3a767cf3b442c3c95e0a7d31b424f2cd54a1111959e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T02:45+00:00, close=77685, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-01T02:00+00:00, close=77680, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T00:00+00:00, close=77522.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.232080|-21.63|38.20|-21.79|29694630|0.43|
|BLESS_USDT|0.009254|-12.40|14.06|-12.56|7535774|5.40|
|ENA_USDT|0.186850|-3.69|0.03|-3.85|45699443|0.54|
|INJ_USDT|7.243000|-3.24|-3.60|-3.40|20248763|1.38|
|ZEC_USDT|1246.340000|-2.97|8.83|-3.13|995891609|0.08|
|WLD_USDT|0.397200|-1.78|-14.02|-1.94|32834701|2.52|
|XLM_USDT|0.168820|-1.70|0.24|-1.86|20516983|0.59|
|FARTCOIN_USDT|0.119910|-1.70|-1.69|-1.86|6335454|2.50|
|FET_USDT|0.160900|-1.46|-6.61|-1.62|5498812|6.22|
|TRX_USDT|0.309680|-0.84|-5.85|-1.00|11411129|1.29|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.009254|0.009262|0.009254|1.01|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.186850|0.186890|0.186850|1.28|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.119910|0.119930|0.119940|1.49|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.160900|0.159300|0.160900|6.37|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.243000|7.235000|7.243000|0.32|N|N/N|Y/Y|Y|N|
|LSK_USDT|0.232080|0.230520|0.232180|0.54|N|Y/Y|N/N|Y|N|
|TRX_USDT|0.309680|0.304130|0.309680|2.20|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.397200|0.397300|0.397200|1.25|N|Y/N|Y/Y|Y|N|
|XLM_USDT|0.168820|0.168450|0.168820|1.40|N|Y/Y|N/N|Y|N|
|ZEC_USDT|1246.340000|1247.230000|1246.680000|0.93|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-11-01T02:45:03+00:00, last15m_closed_end=2026-11-01T02:45+00:00, prior8high=0.009592, depth_time=2026-11-01T02:45:09+00:00, book20_bid_proxy_usdt=11308, book20_ask_proxy_usdt=16298, funding_indicative=0.000050, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-12.40%, turnover=7535774. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-01T02:45:02+00:00, last15m_closed_end=2026-11-01T02:45+00:00, prior8high=0.190060, depth_time=2026-11-01T02:45:13+00:00, book20_bid_proxy_usdt=172478, book20_ask_proxy_usdt=122206, funding_indicative=0.000050, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.69%, turnover=45699443. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-01T02:45:03+00:00, last15m_closed_end=2026-11-01T02:45+00:00, prior8high=0.120890, depth_time=2026-11-01T02:45:25+00:00, book20_bid_proxy_usdt=80580, book20_ask_proxy_usdt=87277, funding_indicative=0.000050, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.70%, turnover=6335454. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-11-01T02:45:03+00:00, last15m_closed_end=2026-11-01T02:45+00:00, prior8high=0.161600, depth_time=2026-11-01T02:45:27+00:00, book20_bid_proxy_usdt=1111271, book20_ask_proxy_usdt=803570, funding_indicative=-0.000314, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.46%, turnover=5498812. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-11-01T02:45:03+00:00, last15m_closed_end=2026-11-01T02:45+00:00, prior8high=7.348000, depth_time=2026-11-01T02:45:15+00:00, book20_bid_proxy_usdt=515298, book20_ask_proxy_usdt=347672, funding_indicative=0.000025, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.24%, turnover=20248763. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-11-01T02:45:02+00:00, last15m_closed_end=2026-11-01T02:45+00:00, prior8high=0.253830, depth_time=2026-11-01T02:45:08+00:00, book20_bid_proxy_usdt=5442, book20_ask_proxy_usdt=9118, funding_indicative=-0.001208, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-21.63%, turnover=29694630. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-11-01T02:45:03+00:00, last15m_closed_end=2026-11-01T02:45+00:00, prior8high=0.309890, depth_time=2026-11-01T02:45:27+00:00, book20_bid_proxy_usdt=171602, book20_ask_proxy_usdt=92040, funding_indicative=-0.001565, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.84%, turnover=11411129. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-01T02:45:03+00:00, last15m_closed_end=2026-11-01T02:45+00:00, prior8high=0.400800, depth_time=2026-11-01T02:45:19+00:00, book20_bid_proxy_usdt=3547390, book20_ask_proxy_usdt=3181375, funding_indicative=0.000047, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.78%, turnover=32834701. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-01T02:45:03+00:00, last15m_closed_end=2026-11-01T02:45+00:00, prior8high=0.169810, depth_time=2026-11-01T02:45:20+00:00, book20_bid_proxy_usdt=219355, book20_ask_proxy_usdt=236109, funding_indicative=-0.000025, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.70%, turnover=20516983. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-01T02:45:02+00:00, last15m_closed_end=2026-11-01T02:45+00:00, prior8high=1263.460000, depth_time=2026-11-01T02:45:17+00:00, book20_bid_proxy_usdt=337392, book20_ask_proxy_usdt=625263, funding_indicative=-0.000109, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.97%, turnover=995891609. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
