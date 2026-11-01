# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T02:00:27Z**
- feed_generated_utc: 2026-11-01T02:00:29+00:00
- source_sha256: `d42e55ab07c798369db6be3bfba80c830f2f1b36e3efdc8b3c147a386bdda79d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T02:00+00:00, close=77680, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-01T02:00+00:00, close=77680, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T00:00+00:00, close=77522.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.235510|-21.31|40.25|-21.69|29375387|1.70|
|BLESS_USDT|0.009446|-11.40|16.43|-11.78|7413132|1.06|
|IDOL_USDT|0.017872|-10.38|126.22|-10.76|5104232|1.68|
|BTW_USDT|1.100700|-3.56|-36.78|-3.94|5399514|1.82|
|TRX_USDT|0.308750|-2.07|-6.13|-2.45|10920124|0.97|
|ZEC_USDT|1256.500000|-1.62|9.71|-2.00|970441234|0.08|
|ENA_USDT|0.188530|-1.62|0.93|-2.00|43822501|0.53|
|FET_USDT|0.160900|-0.74|-6.61|-1.12|5303739|6.21|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.009446|0.009355|0.009450|0.38|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.100700|1.049300|1.100700|2.30|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.188530|0.188460|0.188530|2.80|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.160900|0.159200|0.160900|1.13|N|Y/Y|Y/Y|Y|N|
|IDOL_USDT|0.017872|0.017098|0.017872|1.29|N|Y/Y|N/N|Y|N|
|LSK_USDT|0.235510|0.233000|0.235510|1.06|N|Y/Y|N/N|Y|N|
|TRX_USDT|0.308750|0.301240|0.308750|0.43|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1256.500000|1248.040000|1256.500000|1.06|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-11-01T02:00:00+00:00, last15m_closed_end=2026-11-01T02:00+00:00, prior8high=0.009626, depth_time=2026-11-01T02:00:10+00:00, book20_bid_proxy_usdt=11808, book20_ask_proxy_usdt=9085, funding_indicative=0.000050, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-11.40%, turnover=7413132. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-01T02:00:00+00:00, last15m_closed_end=2026-11-01T02:00+00:00, prior8high=1.104900, depth_time=2026-11-01T02:00:15+00:00, book20_bid_proxy_usdt=22794, book20_ask_proxy_usdt=20197, funding_indicative=-0.000420, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.56%, turnover=5399514. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-01T02:00:00+00:00, last15m_closed_end=2026-11-01T02:00+00:00, prior8high=0.190060, depth_time=2026-11-01T02:00:23+00:00, book20_bid_proxy_usdt=128660, book20_ask_proxy_usdt=125541, funding_indicative=0.000045, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.62%, turnover=43822501. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-11-01T02:00:00+00:00, last15m_closed_end=2026-11-01T02:00+00:00, prior8high=0.161600, depth_time=2026-11-01T02:00:26+00:00, book20_bid_proxy_usdt=1303661, book20_ask_proxy_usdt=725124, funding_indicative=-0.000223, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.74%, turnover=5303739. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-01T02:00:00+00:00, last15m_closed_end=2026-11-01T02:00+00:00, prior8high=0.018859, depth_time=2026-11-01T02:00:13+00:00, book20_bid_proxy_usdt=2924, book20_ask_proxy_usdt=4861, funding_indicative=0.000069, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.38%, turnover=5104232. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-11-01T02:00:00+00:00, last15m_closed_end=2026-11-01T02:00+00:00, prior8high=0.253830, depth_time=2026-11-01T02:00:08+00:00, book20_bid_proxy_usdt=6390, book20_ask_proxy_usdt=7736, funding_indicative=-0.001521, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-21.31%, turnover=29375387. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-11-01T02:00:00+00:00, last15m_closed_end=2026-11-01T02:00+00:00, prior8high=0.309890, depth_time=2026-11-01T02:00:18+00:00, book20_bid_proxy_usdt=601500, book20_ask_proxy_usdt=88317, funding_indicative=-0.001748, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.07%, turnover=10920124. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-01T02:00:00+00:00, last15m_closed_end=2026-11-01T02:00+00:00, prior8high=1263.460000, depth_time=2026-11-01T02:00:21+00:00, book20_bid_proxy_usdt=795593, book20_ask_proxy_usdt=396139, funding_indicative=-0.000099, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.62%, turnover=970441234. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
