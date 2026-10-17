# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T06:45:42Z**
- feed_generated_utc: 2026-10-17T06:45:45+00:00
- source_sha256: `1f932798b424e42eb2622b666ad3738dbd57bd9212f772f3ed8c1c7bb60030b8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T06:45+00:00, close=81581.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-17T06:00+00:00, close=81542.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T04:00+00:00, close=81534.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.956400|-6.89|-3.94|-7.20|14072652|0.51|
|RIVER_USDT|1.074000|-4.61|-9.13|-4.92|5000941|9.31|
|STRK_USDT|0.070780|-4.28|-6.01|-4.59|21690060|1.41|
|ARB_USDT|0.189210|-2.93|4.65|-3.24|32401017|0.53|
|APT_USDT|0.834200|-2.55|4.20|-2.86|11963531|1.20|
|FET_USDT|0.194600|-2.50|-10.32|-2.81|12139073|5.14|
|OP_USDT|0.137090|-2.07|11.25|-2.38|14733114|2.19|
|ZEC_USDT|1163.710000|-2.04|-4.48|-2.35|1367766716|0.09|
|TAO_USDT|275.100000|-1.96|0.15|-2.27|70753207|1.09|
|SUI_USDT|1.007500|-1.27|-4.73|-1.58|93560776|0.99|
|FARTCOIN_USDT|0.153210|-0.97|-6.21|-1.28|7167288|0.65|
|AVAX_USDT|9.990000|-0.92|-1.98|-1.23|116854144|1.00|
|ICP_USDT|3.014000|-0.78|-0.16|-1.09|9031206|3.32|
|SEI_USDT|0.063800|-0.77|-2.56|-1.08|19412243|1.57|
|AAVE_USDT|156.100000|-0.75|-8.08|-1.06|27792966|0.64|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|156.100000|155.510000|156.110000|0.43|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.834200|0.836400|0.834200|1.23|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.189210|0.188840|0.189210|0.47|N|Y/Y|Y/N|Y|N|
|AVAX_USDT|9.990000|9.972000|9.990000|0.51|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.153210|0.152970|0.153210|9.79|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.194600|0.193700|0.194600|0.79|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|3.014000|3.013000|3.014000|0.96|N|N/N|Y/Y|Y|N|
|OP_USDT|0.137090|0.136620|0.137030|0.52|N|Y/N|Y/Y|Y|N|
|RIVER_USDT|1.074000|1.076000|1.074000|1.63|Y|Y/Y|Y/Y|Y|Y|
|SEI_USDT|0.063800|0.063800|0.063800|0.46|N|Y/Y|N/N|Y|N|
|STRK_USDT|0.070780|0.070440|0.070780|0.31|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|1.007500|1.008300|1.007500|1.11|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|275.100000|274.950000|275.120000|1.74|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1163.710000|1153.400000|1163.650000|0.65|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.956400|1.960500|1.956400|2.45|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-17T06:45:01+00:00, last15m_closed_end=2026-10-17T06:45+00:00, prior8high=156.680000, depth_time=2026-10-17T06:45:41+00:00, book20_bid_proxy_usdt=269736, book20_ask_proxy_usdt=349342, funding_indicative=0.000046, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.75%, turnover=27792966. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-17T06:45:01+00:00, last15m_closed_end=2026-10-17T06:45+00:00, prior8high=0.856200, depth_time=2026-10-17T06:45:15+00:00, book20_bid_proxy_usdt=117547, book20_ask_proxy_usdt=164289, funding_indicative=0.000073, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.55%, turnover=11963531. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-17T06:45:01+00:00, last15m_closed_end=2026-10-17T06:45+00:00, prior8high=0.192330, depth_time=2026-10-17T06:45:15+00:00, book20_bid_proxy_usdt=63404, book20_ask_proxy_usdt=70137, funding_indicative=-0.000032, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.93%, turnover=32401017. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-17T06:45:01+00:00, last15m_closed_end=2026-10-17T06:45+00:00, prior8high=10.037000, depth_time=2026-10-17T06:45:34+00:00, book20_bid_proxy_usdt=803570, book20_ask_proxy_usdt=706641, funding_indicative=0.000033, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.92%, turnover=116854144. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-17T06:45:01+00:00, last15m_closed_end=2026-10-17T06:45+00:00, prior8high=0.154340, depth_time=2026-10-17T06:45:32+00:00, book20_bid_proxy_usdt=59146, book20_ask_proxy_usdt=69789, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.97%, turnover=7167288. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-17T06:45:01+00:00, last15m_closed_end=2026-10-17T06:45+00:00, prior8high=0.196300, depth_time=2026-10-17T06:45:16+00:00, book20_bid_proxy_usdt=1924873, book20_ask_proxy_usdt=1064290, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.50%, turnover=12139073. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-17T06:45:01+00:00, last15m_closed_end=2026-10-17T06:45+00:00, prior8high=3.062000, depth_time=2026-10-17T06:45:36+00:00, book20_bid_proxy_usdt=950562, book20_ask_proxy_usdt=1151186, funding_indicative=0.000031, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.78%, turnover=9031206. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-17T06:45:01+00:00, last15m_closed_end=2026-10-17T06:45+00:00, prior8high=0.140730, depth_time=2026-10-17T06:45:21+00:00, book20_bid_proxy_usdt=27147, book20_ask_proxy_usdt=37821, funding_indicative=-0.000044, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.07%, turnover=14733114. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-17T06:45:01+00:00, last15m_closed_end=2026-10-17T06:45+00:00, prior8high=1.086000, depth_time=2026-10-17T06:45:10+00:00, book20_bid_proxy_usdt=484573, book20_ask_proxy_usdt=351111, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.61%, turnover=5000941. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-17T06:45:01+00:00, last15m_closed_end=2026-10-17T06:45+00:00, prior8high=0.064750, depth_time=2026-10-17T06:45:38+00:00, book20_bid_proxy_usdt=229358, book20_ask_proxy_usdt=397080, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.77%, turnover=19412243. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T06:45:01+00:00, last15m_closed_end=2026-10-17T06:45+00:00, prior8high=0.072130, depth_time=2026-10-17T06:45:13+00:00, book20_bid_proxy_usdt=267842, book20_ask_proxy_usdt=326108, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.28%, turnover=21690060. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-17T06:45:01+00:00, last15m_closed_end=2026-10-17T06:45+00:00, prior8high=1.019400, depth_time=2026-10-17T06:45:29+00:00, book20_bid_proxy_usdt=831357, book20_ask_proxy_usdt=1651166, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.27%, turnover=93560776. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-17T06:45:01+00:00, last15m_closed_end=2026-10-17T06:45+00:00, prior8high=277.150000, depth_time=2026-10-17T06:45:27+00:00, book20_bid_proxy_usdt=116721, book20_ask_proxy_usdt=125541, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.96%, turnover=70753207. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T06:45:01+00:00, last15m_closed_end=2026-10-17T06:45+00:00, prior8high=1168.180000, depth_time=2026-10-17T06:45:24+00:00, book20_bid_proxy_usdt=492254, book20_ask_proxy_usdt=122387, funding_indicative=0.000012, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.04%, turnover=1367766716. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T06:45:01+00:00, last15m_closed_end=2026-10-17T06:45+00:00, prior8high=1.992900, depth_time=2026-10-17T06:45:08+00:00, book20_bid_proxy_usdt=49913, book20_ask_proxy_usdt=53358, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.89%, turnover=14072652. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
