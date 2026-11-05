# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T04:00:33Z**
- feed_generated_utc: 2026-11-05T04:00:35+00:00
- source_sha256: `f266972767231bca2e98bee4f436407ce927777c10ae11f9a22f164dba22cd16`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T04:00+00:00, close=80514.9, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-05T04:00+00:00, close=80514.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-05T04:00+00:00, close=80514.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002455|-12.63|-87.78|-12.93|16499381|8.15|
|TRUMPOFFICIAL_USDT|1.266000|-11.22|-25.92|-11.52|26658975|7.91|
|BTW_USDT|1.032400|-6.70|-40.59|-7.00|5717998|1.94|
|VVV_USDT|21.907000|-6.69|-8.01|-6.99|5092440|4.11|
|WLD_USDT|0.374700|-4.43|-13.42|-4.73|69526352|2.67|
|IDOL_USDT|0.021262|-3.98|145.60|-4.28|5557493|4.23|
|CLANKER_USDT|16.600000|-3.48|24.25|-3.78|20141886|6.01|
|ZRO_USDT|1.825500|-3.39|6.62|-3.69|9966494|0.55|
|HYPE_USDT|83.602000|-3.11|4.68|-3.41|83278103|0.12|
|OP_USDT|0.110490|-2.60|-0.53|-2.90|10316715|0.91|
|PEPE_USDT|0.000005|-1.24|3.04|-1.54|137715582|1.20|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002455|0.002197|0.002452|0.37|N|Y/Y|Y/Y|N|N|
|BTW_USDT|1.032400|1.020800|1.032400|0.76|N|Y/Y|Y/Y|N|N|
|CLANKER_USDT|16.600000|16.230000|16.600000|1.02|N|Y/Y|N/N|N|N|
|HYPE_USDT|83.602000|83.918000|83.602000|2.22|Y|Y/Y|Y/Y|N|Y|
|IDOL_USDT|0.021262|0.021092|0.021262|1.03|N|Y/Y|N/N|N|N|
|OP_USDT|0.110490|0.109860|0.110490|0.65|N|Y/Y|Y/Y|N|N|
|PEPE_USDT|0.000005|0.000005|0.000005|1.03|N|Y/N|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.266000|1.228000|1.266000|0.64|N|Y/Y|Y/Y|N|N|
|VVV_USDT|21.907000|21.148000|21.907000|2.88|N|Y/Y|Y/Y|N|N|
|WLD_USDT|0.374700|0.372900|0.374700|1.28|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.825500|1.811500|1.825500|1.27|N|Y/Y|N/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T04:00:01+00:00, last15m_closed_end=2026-11-05T04:00+00:00, prior8high=0.002642, depth_time=2026-11-05T04:00:07+00:00, book20_bid_proxy_usdt=32909, book20_ask_proxy_usdt=45056, funding_indicative=-0.000570, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-12.63%, turnover=16499381. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-05T04:00:01+00:00, last15m_closed_end=2026-11-05T04:00+00:00, prior8high=1.061500, depth_time=2026-11-05T04:00:12+00:00, book20_bid_proxy_usdt=21324, book20_ask_proxy_usdt=19812, funding_indicative=0.000050, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.70%, turnover=5717998. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CLANKER_USDT: quote_utc=2026-11-05T04:00:01+00:00, last15m_closed_end=2026-11-05T04:00+00:00, prior8high=17.830000, depth_time=2026-11-05T04:00:22+00:00, book20_bid_proxy_usdt=154114, book20_ask_proxy_usdt=127530, funding_indicative=0.000050, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.48%, turnover=20141886. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-05T04:00:01+00:00, last15m_closed_end=2026-11-05T04:00+00:00, prior8high=84.644000, depth_time=2026-11-05T04:00:27+00:00, book20_bid_proxy_usdt=90192, book20_ask_proxy_usdt=84122, funding_indicative=0.000050, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.11%, turnover=83278103. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-05T04:00:01+00:00, last15m_closed_end=2026-11-05T04:00+00:00, prior8high=0.021639, depth_time=2026-11-05T04:00:17+00:00, book20_bid_proxy_usdt=1868, book20_ask_proxy_usdt=8488, funding_indicative=0.000074, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.98%, turnover=5557493. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-05T04:00:01+00:00, last15m_closed_end=2026-11-05T04:00+00:00, prior8high=0.111820, depth_time=2026-11-05T04:00:30+00:00, book20_bid_proxy_usdt=107322, book20_ask_proxy_usdt=97369, funding_indicative=0.000040, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.60%, turnover=10316715. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-05T04:00:01+00:00, last15m_closed_end=2026-11-05T04:00+00:00, prior8high=0.000005, depth_time=2026-11-05T04:00:33+00:00, book20_bid_proxy_usdt=49871, book20_ask_proxy_usdt=30642, funding_indicative=0.000100, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.24%, turnover=137715582. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-05T04:00:01+00:00, last15m_closed_end=2026-11-05T04:00+00:00, prior8high=1.290000, depth_time=2026-11-05T04:00:09+00:00, book20_bid_proxy_usdt=1139429, book20_ask_proxy_usdt=1041533, funding_indicative=-0.000311, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-11.22%, turnover=26658975. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-05T04:00:01+00:00, last15m_closed_end=2026-11-05T04:00+00:00, prior8high=21.792000, depth_time=2026-11-05T04:00:15+00:00, book20_bid_proxy_usdt=34663, book20_ask_proxy_usdt=19094, funding_indicative=-0.000192, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.69%, turnover=5092440. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-05T04:00:01+00:00, last15m_closed_end=2026-11-05T04:00+00:00, prior8high=0.380500, depth_time=2026-11-05T04:00:17+00:00, book20_bid_proxy_usdt=3139542, book20_ask_proxy_usdt=2295066, funding_indicative=-0.000338, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.43%, turnover=69526352. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-05T04:00:01+00:00, last15m_closed_end=2026-11-05T04:00+00:00, prior8high=1.861000, depth_time=2026-11-05T04:00:25+00:00, book20_bid_proxy_usdt=100202, book20_ask_proxy_usdt=43527, funding_indicative=0.000050, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.39%, turnover=9966494. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
