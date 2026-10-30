# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T07:30:45Z**
- feed_generated_utc: 2026-10-30T07:30:48+00:00
- source_sha256: `e0de4951946a74a576a4209c1c689e15361ec42db24880ee293d2748ce172d83`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1195; contracts: 1187; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T07:30+00:00, close=78468, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-30T07:00+00:00, close=78619.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T04:00+00:00, close=78198.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CRV_USDT|0.278100|-17.23|-24.28|-13.25|8742184|3.60|
|TIA_USDT|0.461900|-15.89|-18.73|-11.91|18435779|2.17|
|PYTH_USDT|0.061740|-15.64|-16.77|-11.66|5274721|3.24|
|LDO_USDT|0.328700|-13.13|-14.06|-9.15|6519745|3.04|
|FARTCOIN_USDT|0.118230|-12.03|-17.22|-8.05|15390037|0.85|
|PENGU_USDT|0.007201|-11.43|-6.81|-7.45|9960499|1.39|
|APT_USDT|0.623600|-11.33|-19.24|-7.35|12578192|3.21|
|FET_USDT|0.165400|-10.49|-10.73|-6.51|14159677|6.05|
|TRUMPOFFICIAL_USDT|1.557000|-9.89|-10.72|-5.91|11106963|6.42|
|ETHFI_USDT|0.612500|-9.86|-7.51|-5.88|5869565|8.17|
|INJ_USDT|7.349000|-9.62|-7.34|-5.64|31218699|1.36|
|PUMPFUN_USDT|0.004091|-9.59|-12.56|-5.61|31467683|2.44|
|SEI_USDT|0.048520|-9.20|-16.44|-5.22|7263933|2.06|
|BTW_USDT|1.491000|-8.97|-16.70|-4.99|10940373|4.03|
|UNI_USDT|6.746000|-8.75|-4.52|-4.77|62009004|1.48|
|ZEC_USDT|1264.740000|-6.82|2.47|-2.84|2167458230|0.08|
|SHIB_USDT|0.000005|-6.51|-5.69|-2.53|7709485|2.13|
|BEAT_USDT|0.097960|-6.09|45.70|-2.11|27823654|5.10|
|ETH_USDT|2247.490000|-5.08|-6.26|-1.10|2496842260|0.04|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.623600|0.617600|0.623600|2.24|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.491000|1.445000|1.488800|1.02|N|Y/Y|Y/Y|Y|N|
|CRV_USDT|0.278100|0.267900|0.278100|5.76|N|Y/Y|Y/Y|Y|N|
|ETHFI_USDT|0.612500|0.596800|0.612000|0.91|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.118230|0.117380|0.118230|0.66|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.165400|0.161100|0.165400|0.44|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.349000|7.311000|7.349000|0.66|N|Y/Y|Y/Y|Y|N|
|LDO_USDT|0.328700|0.323300|0.328700|0.36|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.007201|0.007138|0.007201|0.53|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004091|0.004083|0.004089|0.37|N|Y/Y|Y/Y|Y|N|
|PYTH_USDT|0.061740|0.060400|0.061740|0.11|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.048520|0.047950|0.048520|0.66|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.461900|0.453800|0.461900|0.66|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.557000|1.545000|1.558000|1.96|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.746000|6.732000|6.746000|0.52|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-30T07:30:01+00:00, last15m_closed_end=2026-10-30T07:30+00:00, prior8high=0.629600, depth_time=2026-10-30T07:30:24+00:00, book20_bid_proxy_usdt=112617, book20_ask_proxy_usdt=105427, funding_indicative=-0.000023, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-11.33%, turnover=12578192. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-30T07:30:01+00:00, last15m_closed_end=2026-10-30T07:30+00:00, prior8high=1.514000, depth_time=2026-10-30T07:30:41+00:00, book20_bid_proxy_usdt=11439, book20_ask_proxy_usdt=9377, funding_indicative=0.000050, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.97%, turnover=10940373. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CRV_USDT: quote_utc=2026-10-30T07:30:01+00:00, last15m_closed_end=2026-10-30T07:30+00:00, prior8high=0.277300, depth_time=2026-10-30T07:30:09+00:00, book20_bid_proxy_usdt=1371242, book20_ask_proxy_usdt=144078, funding_indicative=-0.000191, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-17.23%, turnover=8742184. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETHFI_USDT: quote_utc=2026-10-30T07:30:01+00:00, last15m_closed_end=2026-10-30T07:30+00:00, prior8high=0.613300, depth_time=2026-10-30T07:30:30+00:00, book20_bid_proxy_usdt=163864, book20_ask_proxy_usdt=174256, funding_indicative=0.000050, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.86%, turnover=5869565. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-30T07:30:01+00:00, last15m_closed_end=2026-10-30T07:30+00:00, prior8high=0.120530, depth_time=2026-10-30T07:30:18+00:00, book20_bid_proxy_usdt=31648, book20_ask_proxy_usdt=71221, funding_indicative=0.000050, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-12.03%, turnover=15390037. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-30T07:30:01+00:00, last15m_closed_end=2026-10-30T07:30+00:00, prior8high=0.166100, depth_time=2026-10-30T07:30:26+00:00, book20_bid_proxy_usdt=1113338, book20_ask_proxy_usdt=636600, funding_indicative=-0.000075, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-10.49%, turnover=14159677. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-30T07:30:01+00:00, last15m_closed_end=2026-10-30T07:30+00:00, prior8high=7.440000, depth_time=2026-10-30T07:30:33+00:00, book20_bid_proxy_usdt=188166, book20_ask_proxy_usdt=235269, funding_indicative=0.000006, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-9.62%, turnover=31218699. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-30T07:30:01+00:00, last15m_closed_end=2026-10-30T07:30+00:00, prior8high=0.332300, depth_time=2026-10-30T07:30:15+00:00, book20_bid_proxy_usdt=1360055, book20_ask_proxy_usdt=350462, funding_indicative=0.000100, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-13.13%, turnover=6519745. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-30T07:30:01+00:00, last15m_closed_end=2026-10-30T07:30+00:00, prior8high=0.007269, depth_time=2026-10-30T07:30:22+00:00, book20_bid_proxy_usdt=68939, book20_ask_proxy_usdt=255263, funding_indicative=-0.000021, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-11.43%, turnover=9960499. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-30T07:30:01+00:00, last15m_closed_end=2026-10-30T07:30+00:00, prior8high=0.004191, depth_time=2026-10-30T07:30:36+00:00, book20_bid_proxy_usdt=1120701, book20_ask_proxy_usdt=1488637, funding_indicative=0.000034, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.59%, turnover=31467683. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-30T07:30:01+00:00, last15m_closed_end=2026-10-30T07:30+00:00, prior8high=0.062440, depth_time=2026-10-30T07:30:14+00:00, book20_bid_proxy_usdt=97828, book20_ask_proxy_usdt=232448, funding_indicative=-0.000215, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-15.64%, turnover=5274721. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-30T07:30:01+00:00, last15m_closed_end=2026-10-30T07:30+00:00, prior8high=0.048860, depth_time=2026-10-30T07:30:38+00:00, book20_bid_proxy_usdt=132814, book20_ask_proxy_usdt=219738, funding_indicative=-0.000040, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-9.20%, turnover=7263933. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-30T07:30:01+00:00, last15m_closed_end=2026-10-30T07:30+00:00, prior8high=0.465200, depth_time=2026-10-30T07:30:10+00:00, book20_bid_proxy_usdt=282948, book20_ask_proxy_usdt=330591, funding_indicative=-0.000007, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-15.89%, turnover=18435779. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-10-30T07:30:01+00:00, last15m_closed_end=2026-10-30T07:30+00:00, prior8high=1.573000, depth_time=2026-10-30T07:30:29+00:00, book20_bid_proxy_usdt=1404655, book20_ask_proxy_usdt=1559975, funding_indicative=0.000050, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.89%, turnover=11106963. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-30T07:30:01+00:00, last15m_closed_end=2026-10-30T07:30+00:00, prior8high=6.880000, depth_time=2026-10-30T07:30:44+00:00, book20_bid_proxy_usdt=1291571, book20_ask_proxy_usdt=1884722, funding_indicative=0.000100, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-8.75%, turnover=62009004. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
