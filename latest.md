# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T00:00:25Z**
- feed_generated_utc: 2026-10-31T00:00:27+00:00
- source_sha256: `a51e6ed8024bef94b923db89574addb412b2de36c36784f09b10dba95cf9e109`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T00:00+00:00, close=77313.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T00:00+00:00, close=77313.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T00:00+00:00, close=77313.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BLESS_USDT|0.009665|-28.43|18.42|-28.55|12519711|1.03|
|AKE_USDT|0.013926|-27.56|-60.20|-27.68|5694294|2.88|
|EVAA_USDT|1.140900|-11.55|117.35|-11.67|6657445|4.38|
|BTW_USDT|1.144900|-5.94|-32.74|-6.06|9637937|2.62|
|HYPE_USDT|90.000000|-2.96|14.79|-3.08|138579239|0.11|
|TRX_USDT|0.328810|-2.25|-0.16|-2.37|9502818|0.61|
|XMR_USDT|589.130000|-1.77|-2.94|-1.89|9936765|0.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.013926|0.013039|0.013926|0.66|N|Y/Y|Y/Y|Y|N|
|BLESS_USDT|0.009665|0.009414|0.009665|0.12|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.144900|1.135400|1.144900|0.32|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.140900|1.087700|1.140900|0.64|N|Y/Y|N/N|Y|N|
|HYPE_USDT|90.000000|89.002000|90.000000|0.85|N|Y/Y|N/N|Y|N|
|TRX_USDT|0.328810|0.328370|0.328810|0.99|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|589.130000|588.230000|589.130000|1.66|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T00:00:00+00:00, last15m_closed_end=2026-10-31T00:00+00:00, prior8high=0.014277, depth_time=2026-10-31T00:00:11+00:00, book20_bid_proxy_usdt=4174, book20_ask_proxy_usdt=10926, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-27.56%, turnover=5694294. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-10-31T00:00:00+00:00, last15m_closed_end=2026-10-31T00:00+00:00, prior8high=0.010060, depth_time=2026-10-31T00:00:07+00:00, book20_bid_proxy_usdt=11522, book20_ask_proxy_usdt=13762, funding_indicative=0.000138, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-28.43%, turnover=12519711. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T00:00:00+00:00, last15m_closed_end=2026-10-31T00:00+00:00, prior8high=1.171800, depth_time=2026-10-31T00:00:16+00:00, book20_bid_proxy_usdt=19882, book20_ask_proxy_usdt=11332, funding_indicative=-0.000232, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.94%, turnover=9637937. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-31T00:00:00+00:00, last15m_closed_end=2026-10-31T00:00+00:00, prior8high=1.149300, depth_time=2026-10-31T00:00:13+00:00, book20_bid_proxy_usdt=8129, book20_ask_proxy_usdt=8028, funding_indicative=0.000179, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-11.55%, turnover=6657445. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T00:00:00+00:00, last15m_closed_end=2026-10-31T00:00+00:00, prior8high=90.170000, depth_time=2026-10-31T00:00:18+00:00, book20_bid_proxy_usdt=217902, book20_ask_proxy_usdt=52160, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.96%, turnover=138579239. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T00:00:00+00:00, last15m_closed_end=2026-10-31T00:00+00:00, prior8high=0.331360, depth_time=2026-10-31T00:00:21+00:00, book20_bid_proxy_usdt=99065, book20_ask_proxy_usdt=82966, funding_indicative=-0.000473, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.25%, turnover=9502818. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-31T00:00:00+00:00, last15m_closed_end=2026-10-31T00:00+00:00, prior8high=594.550000, depth_time=2026-10-31T00:00:23+00:00, book20_bid_proxy_usdt=15892, book20_ask_proxy_usdt=5966, funding_indicative=0.000451, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.77%, turnover=9936765. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
