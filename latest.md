# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T23:45:23Z**
- feed_generated_utc: 2026-11-04T23:45:24+00:00
- source_sha256: `17ee2b1503789ffbe0b2b795bc825e539274e1bc7e606ea3b1c8f2634e05dd85`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T23:45+00:00, close=80656.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T23:00+00:00, close=80682, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T20:00+00:00, close=79956.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002435|-13.34|-87.88|-13.81|16682073|4.10|
|TRUMPOFFICIAL_USDT|1.269000|-10.88|-25.74|-11.35|27138187|7.88|
|IDOL_USDT|0.021356|-8.99|146.69|-9.46|6260801|1.41|
|BTW_USDT|1.027600|-6.49|-40.87|-6.96|6209883|3.89|
|WLD_USDT|0.376500|-3.97|-13.00|-4.44|73886528|2.66|
|PUMPFUN_USDT|0.004273|-3.97|1.56|-4.44|18640439|2.34|
|ZRO_USDT|1.821600|-2.31|6.40|-2.78|11244227|0.55|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002435|0.002479|0.002435|2.67|Y|Y/Y|Y/Y|N|Y|
|BTW_USDT|1.027600|1.026000|1.027200|1.72|N|Y/Y|Y/N|N|N|
|IDOL_USDT|0.021356|0.020994|0.021356|0.23|N|Y/Y|N/N|N|N|
|PUMPFUN_USDT|0.004273|0.004191|0.004273|0.11|N|N/Y|Y/N|N|N|
|TRUMPOFFICIAL_USDT|1.269000|1.257000|1.269000|0.82|N|Y/Y|Y/Y|N|N|
|WLD_USDT|0.376500|0.374500|0.376500|0.49|N|N/Y|Y/N|N|N|
|ZRO_USDT|1.821600|1.794100|1.821600|0.24|N|N/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-04T23:45:00+00:00, last15m_closed_end=2026-11-04T23:45+00:00, prior8high=0.002595, depth_time=2026-11-04T23:45:07+00:00, book20_bid_proxy_usdt=142305, book20_ask_proxy_usdt=187558, funding_indicative=-0.000939, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-13.34%, turnover=16682073. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-04T23:45:00+00:00, last15m_closed_end=2026-11-04T23:45+00:00, prior8high=1.044500, depth_time=2026-11-04T23:45:15+00:00, book20_bid_proxy_usdt=34686, book20_ask_proxy_usdt=17788, funding_indicative=0.000050, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.49%, turnover=6209883. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-04T23:45:00+00:00, last15m_closed_end=2026-11-04T23:45+00:00, prior8high=0.021651, depth_time=2026-11-04T23:45:12+00:00, book20_bid_proxy_usdt=4282, book20_ask_proxy_usdt=5516, funding_indicative=0.000050, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-8.99%, turnover=6260801. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-04T23:45:00+00:00, last15m_closed_end=2026-11-04T23:45+00:00, prior8high=0.004318, depth_time=2026-11-04T23:45:20+00:00, book20_bid_proxy_usdt=2260803, book20_ask_proxy_usdt=2676804, funding_indicative=0.000023, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.97%, turnover=18640439. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T23:45:00+00:00, last15m_closed_end=2026-11-04T23:45+00:00, prior8high=1.286000, depth_time=2026-11-04T23:45:08+00:00, book20_bid_proxy_usdt=962853, book20_ask_proxy_usdt=1084424, funding_indicative=-0.000295, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.88%, turnover=27138187. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-04T23:45:00+00:00, last15m_closed_end=2026-11-04T23:45+00:00, prior8high=0.384000, depth_time=2026-11-04T23:45:17+00:00, book20_bid_proxy_usdt=2447008, book20_ask_proxy_usdt=2742626, funding_indicative=-0.000435, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.97%, turnover=73886528. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-04T23:45:00+00:00, last15m_closed_end=2026-11-04T23:45+00:00, prior8high=1.856300, depth_time=2026-11-04T23:45:21+00:00, book20_bid_proxy_usdt=84062, book20_ask_proxy_usdt=40860, funding_indicative=0.000050, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.31%, turnover=11244227. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
