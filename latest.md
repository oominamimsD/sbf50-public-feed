# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T00:30:36Z**
- feed_generated_utc: 2026-11-06T00:30:38+00:00
- source_sha256: `768dd3d1f8e66093f19337d5e387ca42f4a3c5942ee48b1bd93a98956ba4ee55`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T00:30+00:00, close=76154.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-06T00:00+00:00, close=76050.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T00:00+00:00, close=76050.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002119|-17.86|-89.93|-18.04|19547124|4.71|
|FLUID_USDT|2.450000|-3.23|18.70|-3.41|7526772|4.08|
|ATOM_USDT|1.383000|-2.60|-15.20|-2.78|5548108|7.23|
|XRP_USDT|1.214900|-2.38|-7.22|-2.56|434250170|0.82|
|HYPE_USDT|77.384000|-1.67|-17.61|-1.85|87938178|0.13|
|PUMPFUN_USDT|0.003873|-1.65|-14.40|-1.83|12335856|2.58|
|ZRO_USDT|1.598800|-1.44|-9.38|-1.62|7072085|0.63|
|FET_USDT|0.145100|-1.22|-21.48|-1.40|7519015|6.89|
|XPL_USDT|0.057910|-1.14|-26.63|-1.32|12550057|1.73|
|ONDO_USDT|0.369200|-0.88|-14.09|-1.06|31141273|2.71|
|QNT_USDT|190.160000|-0.86|-4.31|-1.04|43080512|0.53|
|WLD_USDT|0.338100|-0.82|-22.50|-1.00|80758865|2.96|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002119|0.002168|0.002119|1.63|Y|Y/Y|Y/Y|Y|Y|
|ATOM_USDT|1.383000|1.345000|1.384000|1.39|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.145100|0.141900|0.145100|0.38|N|Y/Y|Y/Y|Y|N|
|FLUID_USDT|2.450000|2.362000|2.454000|0.88|N|Y/Y|N/N|Y|N|
|HYPE_USDT|77.384000|76.284000|77.400000|0.43|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.369200|0.360600|0.369200|1.36|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003873|0.003823|0.003876|0.51|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|190.160000|185.570000|190.160000|0.61|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.338100|0.329300|0.338800|0.74|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.057910|0.056610|0.057900|0.25|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.214900|1.199300|1.214900|0.59|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.598800|1.568700|1.598800|0.39|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-06T00:30:02+00:00, last15m_closed_end=2026-11-06T00:30+00:00, prior8high=0.002275, depth_time=2026-11-06T00:30:07+00:00, book20_bid_proxy_usdt=25375, book20_ask_proxy_usdt=56538, funding_indicative=-0.000798, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-17.86%, turnover=19547124. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ATOM_USDT: quote_utc=2026-11-06T00:30:02+00:00, last15m_closed_end=2026-11-06T00:30+00:00, prior8high=1.395000, depth_time=2026-11-06T00:30:09+00:00, book20_bid_proxy_usdt=1970784, book20_ask_proxy_usdt=1963957, funding_indicative=-0.000113, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.60%, turnover=5548108. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-11-06T00:30:02+00:00, last15m_closed_end=2026-11-06T00:30+00:00, prior8high=0.147300, depth_time=2026-11-06T00:30:25+00:00, book20_bid_proxy_usdt=1179538, book20_ask_proxy_usdt=856712, funding_indicative=-0.000225, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.22%, turnover=7519015. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-06T00:30:02+00:00, last15m_closed_end=2026-11-06T00:30+00:00, prior8high=2.467000, depth_time=2026-11-06T00:30:06+00:00, book20_bid_proxy_usdt=262954, book20_ask_proxy_usdt=121974, funding_indicative=0.000696, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.23%, turnover=7526772. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-06T00:30:02+00:00, last15m_closed_end=2026-11-06T00:30+00:00, prior8high=77.727000, depth_time=2026-11-06T00:30:17+00:00, book20_bid_proxy_usdt=75800, book20_ask_proxy_usdt=301799, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.67%, turnover=87938178. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-06T00:30:02+00:00, last15m_closed_end=2026-11-06T00:30+00:00, prior8high=0.369600, depth_time=2026-11-06T00:30:30+00:00, book20_bid_proxy_usdt=1621566, book20_ask_proxy_usdt=1658394, funding_indicative=-0.000028, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.88%, turnover=31141273. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-06T00:30:02+00:00, last15m_closed_end=2026-11-06T00:30+00:00, prior8high=0.003970, depth_time=2026-11-06T00:30:19+00:00, book20_bid_proxy_usdt=1558387, book20_ask_proxy_usdt=1249227, funding_indicative=0.000003, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.65%, turnover=12335856. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-06T00:30:02+00:00, last15m_closed_end=2026-11-06T00:30+00:00, prior8high=191.370000, depth_time=2026-11-06T00:30:33+00:00, book20_bid_proxy_usdt=57734, book20_ask_proxy_usdt=48228, funding_indicative=0.000007, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.86%, turnover=43080512. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-06T00:30:02+00:00, last15m_closed_end=2026-11-06T00:30+00:00, prior8high=0.339500, depth_time=2026-11-06T00:30:35+00:00, book20_bid_proxy_usdt=2875693, book20_ask_proxy_usdt=2958257, funding_indicative=-0.000478, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.82%, turnover=80758865. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T00:30:02+00:00, last15m_closed_end=2026-11-06T00:30+00:00, prior8high=0.058970, depth_time=2026-11-06T00:30:27+00:00, book20_bid_proxy_usdt=418823, book20_ask_proxy_usdt=367482, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.14%, turnover=12550057. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T00:30:02+00:00, last15m_closed_end=2026-11-06T00:30+00:00, prior8high=1.226900, depth_time=2026-11-06T00:30:14+00:00, book20_bid_proxy_usdt=3216999, book20_ask_proxy_usdt=3649540, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.38%, turnover=434250170. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-06T00:30:02+00:00, last15m_closed_end=2026-11-06T00:30+00:00, prior8high=1.608300, depth_time=2026-11-06T00:30:22+00:00, book20_bid_proxy_usdt=67038, book20_ask_proxy_usdt=36955, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.44%, turnover=7072085. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
