# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T10:30:47Z**
- feed_generated_utc: 2026-10-27T10:30:51+00:00
- source_sha256: `38738f82160a434190410c2f6693746732c97a17192b89502823a02e8986999b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 21; crypto_deep: 15
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T10:30+00:00, close=79611.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-27T10:00+00:00, close=79746.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T08:00+00:00, close=79774.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.025410|-7.86|106.92|-6.88|7532782|7.87|
|ENA_USDT|0.199530|-5.15|6.17|-4.17|85873105|0.50|
|AAVE_USDT|130.130000|-4.82|-11.60|-3.84|27217312|0.77|
|PUMPFUN_USDT|0.004128|-4.62|-7.36|-3.64|21429951|2.42|
|DOT_USDT|0.982800|-3.89|-14.30|-2.91|10884504|1.02|
|QNT_USDT|202.670000|-3.61|3.56|-2.63|127417887|0.49|
|FILECOIN_USDT|0.889100|-3.43|-12.14|-2.45|6128825|1.12|
|NEAR_USDT|4.421000|-3.32|-9.84|-2.34|91387228|2.26|
|ONDO_USDT|0.404900|-3.31|-6.40|-2.33|23354050|2.47|
|WLD_USDT|0.430500|-3.25|-14.97|-2.27|66874502|2.32|
|AVAX_USDT|8.735000|-2.91|-8.64|-1.93|23050555|1.15|
|ARB_USDT|0.165400|-2.70|-15.45|-1.72|18856709|0.60|
|TAO_USDT|246.700000|-2.68|-8.05|-1.70|47009322|1.22|
|INJ_USDT|7.745000|-2.38|-9.42|-1.40|22068485|1.29|
|CHIP_USDT|0.050250|-2.38|22.92|-1.40|6712337|1.99|
|LINK_USDT|11.264000|-2.29|-5.68|-1.31|126032426|0.89|
|TIA_USDT|0.523500|-2.27|-13.96|-1.29|17336302|1.91|
|SOL_USDT|99.560000|-2.23|-4.35|-1.25|658670143|1.00|
|HBAR_USDT|0.075730|-2.10|-7.49|-1.12|10670803|1.32|
|ADA_USDT|0.202100|-2.03|-6.86|-1.05|20261788|4.94|
|PEPE_USDT|0.000004|-2.01|4.02|-1.03|59735368|0.47|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.130000|129.720000|130.130000|2.58|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.165400|0.164480|0.165400|0.81|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.735000|8.687000|8.734000|1.52|N|Y/Y|Y/Y|Y|N|
|CHIP_USDT|0.050250|0.049770|0.050250|0.42|N|Y/N|N/N|Y|N|
|DOT_USDT|0.982800|0.979300|0.982800|1.71|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.199530|0.198350|0.199530|3.59|N|Y/Y|N/N|Y|N|
|FILECOIN_USDT|0.889100|0.884300|0.889100|2.68|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.745000|7.697000|7.743000|0.74|N|Y/Y|Y/N|Y|N|
|IRYS_USDT|0.025410|0.025100|0.025410|0.66|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.421000|4.389000|4.421000|1.16|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.404900|0.403000|0.404900|0.72|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004128|0.004093|0.004128|0.28|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|202.670000|201.420000|202.670000|1.39|N|N/N|N/N|Y|N|
|TAO_USDT|246.700000|245.490000|246.580000|0.74|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.430500|0.427500|0.430400|1.38|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T10:30:01+00:00, last15m_closed_end=2026-10-27T10:30+00:00, prior8high=131.600000, depth_time=2026-10-27T10:30:13+00:00, book20_bid_proxy_usdt=414070, book20_ask_proxy_usdt=436767, funding_indicative=0.000087, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.82%, turnover=27217312. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-27T10:30:01+00:00, last15m_closed_end=2026-10-27T10:30+00:00, prior8high=0.167870, depth_time=2026-10-27T10:30:38+00:00, book20_bid_proxy_usdt=58343, book20_ask_proxy_usdt=102222, funding_indicative=0.000012, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.70%, turnover=18856709. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T10:30:01+00:00, last15m_closed_end=2026-10-27T10:30+00:00, prior8high=8.804000, depth_time=2026-10-27T10:30:34+00:00, book20_bid_proxy_usdt=1084368, book20_ask_proxy_usdt=1751962, funding_indicative=0.000002, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.91%, turnover=23050555. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CHIP_USDT: quote_utc=2026-10-27T10:30:01+00:00, last15m_closed_end=2026-10-27T10:30+00:00, prior8high=0.052210, depth_time=2026-10-27T10:30:46+00:00, book20_bid_proxy_usdt=44171, book20_ask_proxy_usdt=49112, funding_indicative=0.000008, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.38%, turnover=6712337. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T10:30:01+00:00, last15m_closed_end=2026-10-27T10:30+00:00, prior8high=0.996200, depth_time=2026-10-27T10:30:18+00:00, book20_bid_proxy_usdt=296388, book20_ask_proxy_usdt=511025, funding_indicative=-0.000117, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.89%, turnover=10884504. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-27T10:30:00+00:00, last15m_closed_end=2026-10-27T10:30+00:00, prior8high=0.207160, depth_time=2026-10-27T10:30:11+00:00, book20_bid_proxy_usdt=118977, book20_ask_proxy_usdt=228795, funding_indicative=0.000027, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.15%, turnover=85873105. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T10:30:01+00:00, last15m_closed_end=2026-10-27T10:30+00:00, prior8high=0.899900, depth_time=2026-10-27T10:30:20+00:00, book20_bid_proxy_usdt=1101902, book20_ask_proxy_usdt=1580014, funding_indicative=0.000030, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.43%, turnover=6128825. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-27T10:30:01+00:00, last15m_closed_end=2026-10-27T10:30+00:00, prior8high=7.804000, depth_time=2026-10-27T10:30:44+00:00, book20_bid_proxy_usdt=177100, book20_ask_proxy_usdt=298635, funding_indicative=0.000226, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.38%, turnover=22068485. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T10:30:00+00:00, last15m_closed_end=2026-10-27T10:30+00:00, prior8high=0.026610, depth_time=2026-10-27T10:30:07+00:00, book20_bid_proxy_usdt=111274, book20_ask_proxy_usdt=103291, funding_indicative=-0.000452, next_funding_utc=2026-10-27T11:00:00+00:00, funding_cycle_h=1, 24h_change=-7.86%, turnover=7532782. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T10:30:00+00:00, last15m_closed_end=2026-10-27T10:30+00:00, prior8high=4.471000, depth_time=2026-10-27T10:30:24+00:00, book20_bid_proxy_usdt=4445445, book20_ask_proxy_usdt=4839454, funding_indicative=0.000086, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.32%, turnover=91387228. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-27T10:30:01+00:00, last15m_closed_end=2026-10-27T10:30+00:00, prior8high=0.409400, depth_time=2026-10-27T10:30:27+00:00, book20_bid_proxy_usdt=2023582, book20_ask_proxy_usdt=2816812, funding_indicative=0.000050, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.31%, turnover=23354050. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T10:30:01+00:00, last15m_closed_end=2026-10-27T10:30+00:00, prior8high=0.004196, depth_time=2026-10-27T10:30:15+00:00, book20_bid_proxy_usdt=2344265, book20_ask_proxy_usdt=2426620, funding_indicative=0.000050, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.62%, turnover=21429951. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T10:30:00+00:00, last15m_closed_end=2026-10-27T10:30+00:00, prior8high=209.800000, depth_time=2026-10-27T10:30:20+00:00, book20_bid_proxy_usdt=71914, book20_ask_proxy_usdt=102851, funding_indicative=-0.000204, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.61%, turnover=127417887. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T10:30:01+00:00, last15m_closed_end=2026-10-27T10:30+00:00, prior8high=249.200000, depth_time=2026-10-27T10:30:41+00:00, book20_bid_proxy_usdt=89966, book20_ask_proxy_usdt=93513, funding_indicative=0.000025, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.68%, turnover=47009322. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T10:30:00+00:00, last15m_closed_end=2026-10-27T10:30+00:00, prior8high=0.437200, depth_time=2026-10-27T10:30:31+00:00, book20_bid_proxy_usdt=3190398, book20_ask_proxy_usdt=4738300, funding_indicative=-0.000140, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.25%, turnover=66874502. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
