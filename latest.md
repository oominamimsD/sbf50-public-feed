# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-29T14:15:30Z**
- feed_generated_utc: 2026-10-29T14:15:31+00:00
- source_sha256: `505fb4c82bb6aba5aa87524a59a991605fd5d903a45a00a6b708e2c4f829a999`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1194; contracts: 1186; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-29T14:15+00:00, close=80412.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-29T14:00+00:00, close=80275.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-29T12:00+00:00, close=80133.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.041860|-32.77|-63.96|-32.63|33776315|2.38|
|EVAA_USDT|1.183100|-20.32|109.91|-20.18|18759683|5.07|
|BLESS_USDT|0.009645|-11.97|19.84|-11.83|9314477|9.33|
|DASH_USDT|50.470000|-4.84|-5.25|-4.70|14739324|1.98|
|NEAR_USDT|4.438000|-4.12|-17.58|-3.98|103872060|2.25|
|BTW_USDT|1.690700|-2.72|15.02|-2.58|9517161|2.96|
|SILVER_USDT|52.290000|-2.57|-9.31|-2.43|544938024|1.91|
|WLD_USDT|0.421900|-2.51|-26.44|-2.37|77956239|2.37|
|HBAR_USDT|0.074130|-2.34|-13.74|-2.20|14631648|1.35|
|XRP_USDT|1.291600|-1.49|-6.42|-1.35|289794113|0.77|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.009645|0.009450|0.009645|0.58|N|Y/Y|Y/N|Y|N|
|BTW_USDT|1.690700|1.768900|1.690900|2.63|Y|N/N|N/N|Y|N|
|DASH_USDT|50.470000|49.890000|50.470000|1.21|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.183100|1.202700|1.180200|1.32|Y|Y/Y|N/N|Y|N|
|HBAR_USDT|0.074130|0.073220|0.074120|1.53|N|N/Y|Y/Y|Y|N|
|NEAR_USDT|4.438000|4.381000|4.438000|0.97|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.041860|0.039240|0.041860|0.54|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|52.290000|52.110000|52.290000|4.53|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.421900|0.416800|0.421800|0.67|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.291600|1.285100|1.291600|2.77|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-10-29T14:15:01+00:00, last15m_closed_end=2026-10-29T14:15+00:00, prior8high=0.009781, depth_time=2026-10-29T14:15:12+00:00, book20_bid_proxy_usdt=7151, book20_ask_proxy_usdt=8482, funding_indicative=0.000217, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-11.97%, turnover=9314477. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-29T14:15:01+00:00, last15m_closed_end=2026-10-29T14:15+00:00, prior8high=1.800000, depth_time=2026-10-29T14:15:19+00:00, book20_bid_proxy_usdt=29769, book20_ask_proxy_usdt=10946, funding_indicative=0.000050, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.72%, turnover=9517161. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-29T14:15:01+00:00, last15m_closed_end=2026-10-29T14:15+00:00, prior8high=50.560000, depth_time=2026-10-29T14:15:14+00:00, book20_bid_proxy_usdt=344204, book20_ask_proxy_usdt=631951, funding_indicative=0.000020, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.84%, turnover=14739324. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-29T14:15:01+00:00, last15m_closed_end=2026-10-29T14:15+00:00, prior8high=1.285900, depth_time=2026-10-29T14:15:10+00:00, book20_bid_proxy_usdt=11230, book20_ask_proxy_usdt=18353, funding_indicative=0.000165, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-20.32%, turnover=18759683. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-29T14:15:01+00:00, last15m_closed_end=2026-10-29T14:15+00:00, prior8high=0.074600, depth_time=2026-10-29T14:15:26+00:00, book20_bid_proxy_usdt=576486, book20_ask_proxy_usdt=621588, funding_indicative=0.000100, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.34%, turnover=14631648. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-29T14:15:01+00:00, last15m_closed_end=2026-10-29T14:15+00:00, prior8high=4.511000, depth_time=2026-10-29T14:15:17+00:00, book20_bid_proxy_usdt=556761, book20_ask_proxy_usdt=951797, funding_indicative=0.000078, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.12%, turnover=103872060. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-29T14:15:01+00:00, last15m_closed_end=2026-10-29T14:15+00:00, prior8high=0.042860, depth_time=2026-10-29T14:15:07+00:00, book20_bid_proxy_usdt=31684, book20_ask_proxy_usdt=45558, funding_indicative=0.000050, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-32.77%, turnover=33776315. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-29T14:15:01+00:00, last15m_closed_end=2026-10-29T14:15+00:00, prior8high=52.850000, depth_time=2026-10-29T14:15:21+00:00, book20_bid_proxy_usdt=50782993, book20_ask_proxy_usdt=41161054, funding_indicative=0.000079, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.57%, turnover=544938024. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-29T14:15:01+00:00, last15m_closed_end=2026-10-29T14:15+00:00, prior8high=0.424500, depth_time=2026-10-29T14:15:23+00:00, book20_bid_proxy_usdt=2890677, book20_ask_proxy_usdt=3989549, funding_indicative=0.000044, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.51%, turnover=77956239. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-10-29T14:15:01+00:00, last15m_closed_end=2026-10-29T14:15+00:00, prior8high=1.294800, depth_time=2026-10-29T14:15:29+00:00, book20_bid_proxy_usdt=2599042, book20_ask_proxy_usdt=3588635, funding_indicative=0.000098, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.49%, turnover=289794113. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
