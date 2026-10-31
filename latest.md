# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T03:30:30Z**
- feed_generated_utc: 2026-10-31T03:30:32+00:00
- source_sha256: `b875a40ad3cdc580b38041aadda0bd175b1b37c88956dc9370ac6159034f6555`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T03:30+00:00, close=77318.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T03:00+00:00, close=77402.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T00:00+00:00, close=77313.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.011588|-38.75|-66.88|-38.42|6825716|0.86|
|Q_USDT|0.032440|-31.67|-72.58|-31.34|20341777|6.13|
|BEAT_USDT|0.100460|-4.46|38.39|-4.13|8847309|1.99|
|PEPE_USDT|0.000005|-3.13|0.84|-2.80|143357239|1.43|
|TRX_USDT|0.326220|-2.76|-0.94|-2.43|7722475|0.31|
|HYPE_USDT|89.841000|-2.71|14.58|-2.38|115677446|0.11|
|BTW_USDT|1.172900|-2.21|-31.10|-1.88|9730093|1.71|
|LIT_USDT|2.763400|-2.15|-16.86|-1.82|5958249|0.36|
|BLESS_USDT|0.009664|-1.89|18.41|-1.56|12662044|2.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.011588|0.011264|0.011629|0.43|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.100460|0.096210|0.100420|1.10|N|Y/Y|N/N|Y|N|
|BLESS_USDT|0.009664|0.009190|0.009659|1.17|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.172900|1.114700|1.174900|0.55|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|89.841000|89.156000|89.857000|0.57|N|Y/Y|N/N|Y|N|
|LIT_USDT|2.763400|2.751900|2.763400|0.16|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.40|N|Y/Y|N/N|Y|N|
|Q_USDT|0.032440|0.026260|0.032440|2.51|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.326220|0.322160|0.326220|0.14|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T03:30:04+00:00, last15m_closed_end=2026-10-31T03:30+00:00, prior8high=0.012965, depth_time=2026-10-31T03:30:08+00:00, book20_bid_proxy_usdt=7442, book20_ask_proxy_usdt=5509, funding_indicative=-0.000084, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-38.75%, turnover=6825716. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T03:30:04+00:00, last15m_closed_end=2026-10-31T03:30+00:00, prior8high=0.100800, depth_time=2026-10-31T03:30:12+00:00, book20_bid_proxy_usdt=5116, book20_ask_proxy_usdt=12888, funding_indicative=0.000141, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.46%, turnover=8847309. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-10-31T03:30:04+00:00, last15m_closed_end=2026-10-31T03:30+00:00, prior8high=0.009698, depth_time=2026-10-31T03:30:29+00:00, book20_bid_proxy_usdt=21062, book20_ask_proxy_usdt=16284, funding_indicative=0.000053, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.89%, turnover=12662044. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T03:30:04+00:00, last15m_closed_end=2026-10-31T03:30+00:00, prior8high=1.291900, depth_time=2026-10-31T03:30:23+00:00, book20_bid_proxy_usdt=11275, book20_ask_proxy_usdt=12470, funding_indicative=-0.000307, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.21%, turnover=9730093. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T03:30:04+00:00, last15m_closed_end=2026-10-31T03:30+00:00, prior8high=90.160000, depth_time=2026-10-31T03:30:21+00:00, book20_bid_proxy_usdt=100851, book20_ask_proxy_usdt=152733, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.71%, turnover=115677446. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-31T03:30:00+00:00, last15m_closed_end=2026-10-31T03:30+00:00, prior8high=2.792700, depth_time=2026-10-31T03:30:27+00:00, book20_bid_proxy_usdt=24516, book20_ask_proxy_usdt=21853, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.15%, turnover=5958249. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-31T03:30:04+00:00, last15m_closed_end=2026-10-31T03:30+00:00, prior8high=0.000005, depth_time=2026-10-31T03:30:16+00:00, book20_bid_proxy_usdt=48458, book20_ask_proxy_usdt=25161, funding_indicative=-0.000204, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.13%, turnover=143357239. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T03:30:04+00:00, last15m_closed_end=2026-10-31T03:30+00:00, prior8high=0.038580, depth_time=2026-10-31T03:30:11+00:00, book20_bid_proxy_usdt=25593, book20_ask_proxy_usdt=21049, funding_indicative=-0.020000, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-31.67%, turnover=20341777. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T03:30:04+00:00, last15m_closed_end=2026-10-31T03:30+00:00, prior8high=0.327100, depth_time=2026-10-31T03:30:19+00:00, book20_bid_proxy_usdt=30160, book20_ask_proxy_usdt=43908, funding_indicative=-0.001684, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.76%, turnover=7722475. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
