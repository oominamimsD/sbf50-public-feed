# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T10:15:33Z**
- feed_generated_utc: 2026-10-31T10:15:36+00:00
- source_sha256: `06d4c0e8e4be4ee788af523cf39caecf8332aabbac64a7d5ec1ed57de3d4248c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T10:15+00:00, close=77441.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T10:00+00:00, close=77434.3, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T08:00+00:00, close=77316.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.010411|-44.97|-70.25|-44.80|10149654|4.80|
|Q_USDT|0.031600|-33.44|-73.29|-33.27|14270066|9.49|
|BTW_USDT|1.128000|-5.96|-33.74|-5.79|9016588|4.43|
|IDOL_USDT|0.019084|-5.72|140.95|-5.55|15856448|5.75|
|HYPE_USDT|87.072000|-5.70|11.05|-5.53|103465950|0.12|
|TRX_USDT|0.316520|-5.65|-3.89|-5.48|7166910|0.32|
|WLD_USDT|0.396000|-3.86|-25.61|-3.69|48122922|2.53|
|FET_USDT|0.161500|-3.06|-13.77|-2.89|5904873|6.19|
|DASH_USDT|47.810000|-2.50|-11.21|-2.33|13045763|2.09|
|PEPE_USDT|0.000005|-1.72|2.30|-1.55|127390572|0.20|
|LTC_USDT|54.830000|-1.59|-6.19|-1.42|6348257|3.65|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.010411|0.009146|0.010467|0.37|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.128000|1.124400|1.128000|0.72|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|47.810000|47.590000|47.810000|1.46|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.161500|0.161500|0.161400|9.29|Y|Y/Y|Y/Y|Y|Y|
|HYPE_USDT|87.072000|86.343000|87.072000|1.27|N|Y/Y|N/N|Y|N|
|IDOL_USDT|0.019084|0.018443|0.019149|1.03|N|Y/Y|N/N|Y|N|
|LTC_USDT|54.830000|54.520000|54.840000|4.55|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|1.41|N|N/N|N/N|Y|N|
|Q_USDT|0.031600|0.031080|0.031620|0.46|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.316520|0.316620|0.316510|3.03|Y|Y/Y|Y/Y|Y|Y|
|WLD_USDT|0.396000|0.394600|0.396100|3.67|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T10:15:03+00:00, last15m_closed_end=2026-10-31T10:15+00:00, prior8high=0.011333, depth_time=2026-10-31T10:15:08+00:00, book20_bid_proxy_usdt=7337, book20_ask_proxy_usdt=12801, funding_indicative=-0.000617, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-44.97%, turnover=10149654. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T10:15:03+00:00, last15m_closed_end=2026-10-31T10:15+00:00, prior8high=1.177100, depth_time=2026-10-31T10:15:09+00:00, book20_bid_proxy_usdt=20162, book20_ask_proxy_usdt=15239, funding_indicative=-0.000135, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.96%, turnover=9016588. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T10:15:03+00:00, last15m_closed_end=2026-10-31T10:15+00:00, prior8high=47.940000, depth_time=2026-10-31T10:15:23+00:00, book20_bid_proxy_usdt=877079, book20_ask_proxy_usdt=684788, funding_indicative=-0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.50%, turnover=13045763. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T10:15:03+00:00, last15m_closed_end=2026-10-31T10:15+00:00, prior8high=0.162400, depth_time=2026-10-31T10:15:22+00:00, book20_bid_proxy_usdt=1237923, book20_ask_proxy_usdt=825778, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.06%, turnover=5904873. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T10:15:03+00:00, last15m_closed_end=2026-10-31T10:15+00:00, prior8high=88.263000, depth_time=2026-10-31T10:15:18+00:00, book20_bid_proxy_usdt=45476, book20_ask_proxy_usdt=198156, funding_indicative=0.000050, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.70%, turnover=103465950. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-10-31T10:15:03+00:00, last15m_closed_end=2026-10-31T10:15+00:00, prior8high=0.023044, depth_time=2026-10-31T10:15:15+00:00, book20_bid_proxy_usdt=7017, book20_ask_proxy_usdt=4186, funding_indicative=0.000296, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.72%, turnover=15856448. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-31T10:15:03+00:00, last15m_closed_end=2026-10-31T10:15+00:00, prior8high=54.990000, depth_time=2026-10-31T10:15:31+00:00, book20_bid_proxy_usdt=1279840, book20_ask_proxy_usdt=1438803, funding_indicative=-0.000019, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.59%, turnover=6348257. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-31T10:15:03+00:00, last15m_closed_end=2026-10-31T10:15+00:00, prior8high=0.000005, depth_time=2026-10-31T10:15:30+00:00, book20_bid_proxy_usdt=20606, book20_ask_proxy_usdt=35708, funding_indicative=-0.000619, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.72%, turnover=127390572. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T10:15:03+00:00, last15m_closed_end=2026-10-31T10:15+00:00, prior8high=0.033810, depth_time=2026-10-31T10:15:10+00:00, book20_bid_proxy_usdt=51199, book20_ask_proxy_usdt=55018, funding_indicative=-0.000617, next_funding_utc=2026-10-31T11:00:00+00:00, funding_cycle_h=1, 24h_change=-33.44%, turnover=14270066. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T10:15:03+00:00, last15m_closed_end=2026-10-31T10:15+00:00, prior8high=0.321870, depth_time=2026-10-31T10:15:21+00:00, book20_bid_proxy_usdt=78563, book20_ask_proxy_usdt=87878, funding_indicative=-0.000798, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.65%, turnover=7166910. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T10:15:03+00:00, last15m_closed_end=2026-10-31T10:15+00:00, prior8high=0.399000, depth_time=2026-10-31T10:15:22+00:00, book20_bid_proxy_usdt=3702285, book20_ask_proxy_usdt=2810242, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.86%, turnover=48122922. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
