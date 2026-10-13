# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T15:00:46Z**
- feed_generated_utc: 2026-10-13T15:00:50+00:00
- source_sha256: `48a0c2b05b345fa80d6aa114ec8b30d01774a27ef0c3a9d542fba014d567239b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T15:00+00:00, close=83486.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-13T15:00+00:00, close=83486.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T12:00+00:00, close=83325.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOS_USDT|0.218300|-26.34|2.48|-27.31|9460522|4.58|
|W_USDT|0.017994|-25.21|27.22|-26.18|12652540|5.00|
|ZRO_USDT|2.006900|-14.47|-1.89|-15.44|15280370|0.50|
|RLC_USDT|0.908300|-11.52|65.74|-12.49|6051758|1.10|
|QNT_USDT|206.150000|-9.73|-19.71|-10.70|91103880|0.48|
|NEAR_USDT|5.012000|-9.67|-0.19|-10.64|273978992|2.00|
|LIT_USDT|3.330300|-8.13|-12.40|-9.10|7509135|0.30|
|PUMPFUN_USDT|0.005005|-7.75|-20.99|-8.72|33393821|2.00|
|USELESS_USDT|0.169220|-6.92|-25.37|-7.89|5592918|0.59|
|ONDO_USDT|0.468400|-5.96|-4.17|-6.93|62691642|4.27|
|CRV_USDT|0.339000|-5.85|-9.28|-6.82|13075895|8.85|
|SEI_USDT|0.062550|-5.75|-13.01|-6.72|9516301|1.60|
|STRK_USDT|0.085600|-5.59|64.26|-6.56|50964187|1.17|
|JUP_USDT|0.324800|-5.27|-3.87|-6.24|8104950|3.08|
|HYPE_USDT|81.223000|-3.75|-12.33|-4.72|76075679|0.12|
|SAND_USDT|0.059840|-2.65|-11.34|-3.62|5858498|1.67|
|MAGIC_USDT|0.118800|-2.59|91.64|-3.56|7689482|1.68|
|SILVER_USDT|59.620000|-1.24|-2.61|-2.21|167864270|1.68|
|RENDER_USDT|2.019000|-0.63|2.43|-1.60|21044578|9.91|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CRV_USDT|0.339000|0.336400|0.339000|0.06|N|Y/Y|Y/Y|N|N|
|DOS_USDT|0.218300|0.216700|0.218300|0.30|N|Y/Y|Y/Y|N|N|
|HYPE_USDT|81.223000|81.003000|81.223000|0.75|N|Y/Y|Y/Y|N|N|
|JUP_USDT|0.324800|0.324700|0.324600|0.59|N|Y/Y|Y/Y|N|N|
|LIT_USDT|3.330300|3.294700|3.330300|0.87|N|Y/Y|Y/Y|N|N|
|NEAR_USDT|5.012000|4.968000|5.012000|0.68|N|Y/Y|Y/Y|N|N|
|ONDO_USDT|0.468400|0.463500|0.468100|0.97|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.005005|0.004930|0.005005|0.23|N|Y/Y|Y/Y|N|N|
|QNT_USDT|206.150000|203.010000|206.120000|0.78|N|Y/Y|Y/Y|N|N|
|RLC_USDT|0.908300|0.896200|0.908300|0.79|N|Y/Y|Y/Y|N|N|
|SEI_USDT|0.062550|0.061790|0.062560|0.42|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.085600|0.086240|0.085420|1.66|Y|Y/Y|Y/Y|N|Y|
|USELESS_USDT|0.169220|0.165740|0.169220|0.80|N|Y/Y|Y/Y|N|N|
|W_USDT|0.017994|0.017894|0.017972|0.62|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|2.006900|2.003400|2.006800|1.72|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- CRV_USDT: quote_utc=2026-10-13T15:00:03+00:00, last15m_closed_end=2026-10-13T15:00+00:00, prior8high=0.344800, depth_time=2026-10-13T15:00:32+00:00, book20_bid_proxy_usdt=361358, book20_ask_proxy_usdt=372860, funding_indicative=0.000003, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.85%, turnover=13075895. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOS_USDT: quote_utc=2026-10-13T15:00:02+00:00, last15m_closed_end=2026-10-13T15:00+00:00, prior8high=0.222500, depth_time=2026-10-13T15:00:06+00:00, book20_bid_proxy_usdt=89518, book20_ask_proxy_usdt=122048, funding_indicative=0.000050, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-26.34%, turnover=9460522. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-13T15:00:02+00:00, last15m_closed_end=2026-10-13T15:00+00:00, prior8high=82.304000, depth_time=2026-10-13T15:00:45+00:00, book20_bid_proxy_usdt=226568, book20_ask_proxy_usdt=104522, funding_indicative=0.000039, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.75%, turnover=76075679. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-13T15:00:03+00:00, last15m_closed_end=2026-10-13T15:00+00:00, prior8high=0.330500, depth_time=2026-10-13T15:00:40+00:00, book20_bid_proxy_usdt=495962, book20_ask_proxy_usdt=561840, funding_indicative=-0.000063, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.27%, turnover=8104950. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-13T15:00:03+00:00, last15m_closed_end=2026-10-13T15:00+00:00, prior8high=3.404100, depth_time=2026-10-13T15:00:24+00:00, book20_bid_proxy_usdt=30043, book20_ask_proxy_usdt=28292, funding_indicative=0.000040, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.13%, turnover=7509135. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-13T15:00:02+00:00, last15m_closed_end=2026-10-13T15:00+00:00, prior8high=5.132000, depth_time=2026-10-13T15:00:22+00:00, book20_bid_proxy_usdt=1622812, book20_ask_proxy_usdt=3233460, funding_indicative=-0.000040, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-9.67%, turnover=273978992. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-13T15:00:02+00:00, last15m_closed_end=2026-10-13T15:00+00:00, prior8high=0.474700, depth_time=2026-10-13T15:00:32+00:00, book20_bid_proxy_usdt=1676458, book20_ask_proxy_usdt=1507998, funding_indicative=-0.000069, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.96%, turnover=62691642. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-13T15:00:02+00:00, last15m_closed_end=2026-10-13T15:00+00:00, prior8high=0.005077, depth_time=2026-10-13T15:00:27+00:00, book20_bid_proxy_usdt=1641142, book20_ask_proxy_usdt=1077631, funding_indicative=-0.000019, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.75%, turnover=33393821. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-13T15:00:02+00:00, last15m_closed_end=2026-10-13T15:00+00:00, prior8high=210.460000, depth_time=2026-10-13T15:00:19+00:00, book20_bid_proxy_usdt=62022, book20_ask_proxy_usdt=50360, funding_indicative=-0.000246, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-9.73%, turnover=91103880. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T15:00:02+00:00, last15m_closed_end=2026-10-13T15:00+00:00, prior8high=0.917300, depth_time=2026-10-13T15:00:16+00:00, book20_bid_proxy_usdt=81928, book20_ask_proxy_usdt=72112, funding_indicative=-0.000706, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-11.52%, turnover=6051758. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-13T15:00:03+00:00, last15m_closed_end=2026-10-13T15:00+00:00, prior8high=0.063460, depth_time=2026-10-13T15:00:37+00:00, book20_bid_proxy_usdt=277646, book20_ask_proxy_usdt=198094, funding_indicative=0.000029, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.75%, turnover=9516301. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T15:00:02+00:00, last15m_closed_end=2026-10-13T15:00+00:00, prior8high=0.090480, depth_time=2026-10-13T15:00:40+00:00, book20_bid_proxy_usdt=129585, book20_ask_proxy_usdt=309969, funding_indicative=0.000027, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.59%, turnover=50964187. target_RR/account_short_permission/settled_funding=UNKNOWN.
- USELESS_USDT: quote_utc=2026-10-13T15:00:02+00:00, last15m_closed_end=2026-10-13T15:00+00:00, prior8high=0.172750, depth_time=2026-10-13T15:00:30+00:00, book20_bid_proxy_usdt=9841, book20_ask_proxy_usdt=31547, funding_indicative=0.000050, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.92%, turnover=5592918. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-13T15:00:02+00:00, last15m_closed_end=2026-10-13T15:00+00:00, prior8high=0.018781, depth_time=2026-10-13T15:00:12+00:00, book20_bid_proxy_usdt=32218, book20_ask_proxy_usdt=13484, funding_indicative=-0.000357, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-25.21%, turnover=12652540. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-13T15:00:02+00:00, last15m_closed_end=2026-10-13T15:00+00:00, prior8high=2.059100, depth_time=2026-10-13T15:00:14+00:00, book20_bid_proxy_usdt=41239, book20_ask_proxy_usdt=24630, funding_indicative=-0.000020, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-14.47%, turnover=15280370. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
