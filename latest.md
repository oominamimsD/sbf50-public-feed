# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T08:30:22Z**
- feed_generated_utc: 2026-10-19T08:30:24+00:00
- source_sha256: `8796bba8b6045af332ff3b3fa3106dce2d5659c3ae528fcd641da004f35d190b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T08:30+00:00, close=82749, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T08:00+00:00, close=82695, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T08:00+00:00, close=82695, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.173200|-3.45|63.39|-5.43|6829957|5.78|
|STRK_USDT|0.059640|-3.11|-49.99|-5.09|17910274|1.68|
|BTW_USDT|2.258800|-2.02|34.27|-4.00|21566667|1.33|
|TIA_USDT|0.609600|-1.34|3.55|-3.32|57434067|1.64|
|HBAR_USDT|0.084710|-1.24|-9.67|-3.22|47943245|1.18|
|SAND_USDT|0.058720|-0.06|-11.61|-2.04|22111390|5.11|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|2.258800|2.206900|2.258900|0.44|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.084710|0.084010|0.084710|0.96|N|Y/Y|Y/Y|N|N|
|ICNT_USDT|0.173200|0.167000|0.173200|0.86|N|Y/Y|Y/N|N|N|
|SAND_USDT|0.058720|0.058430|0.058720|0.56|N|N/N|N/N|N|N|
|STRK_USDT|0.059640|0.059240|0.059650|0.61|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.609600|0.606000|0.609600|0.53|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-19T08:30:00+00:00, last15m_closed_end=2026-10-19T08:30+00:00, prior8high=2.321000, depth_time=2026-10-19T08:30:13+00:00, book20_bid_proxy_usdt=8354, book20_ask_proxy_usdt=29838, funding_indicative=-0.000339, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.02%, turnover=21566667. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T08:30:00+00:00, last15m_closed_end=2026-10-19T08:30+00:00, prior8high=0.085160, depth_time=2026-10-19T08:30:18+00:00, book20_bid_proxy_usdt=759605, book20_ask_proxy_usdt=973960, funding_indicative=-0.000057, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.24%, turnover=47943245. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-19T08:30:00+00:00, last15m_closed_end=2026-10-19T08:30+00:00, prior8high=0.175600, depth_time=2026-10-19T08:30:08+00:00, book20_bid_proxy_usdt=172262, book20_ask_proxy_usdt=155960, funding_indicative=-0.000180, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.45%, turnover=6829957. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-19T08:30:00+00:00, last15m_closed_end=2026-10-19T08:30+00:00, prior8high=0.061520, depth_time=2026-10-19T08:30:21+00:00, book20_bid_proxy_usdt=474932, book20_ask_proxy_usdt=503216, funding_indicative=-0.006344, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.06%, turnover=22111390. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T08:30:00+00:00, last15m_closed_end=2026-10-19T08:30+00:00, prior8high=0.060350, depth_time=2026-10-19T08:30:11+00:00, book20_bid_proxy_usdt=913394, book20_ask_proxy_usdt=658610, funding_indicative=0.000050, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.11%, turnover=17910274. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T08:30:00+00:00, last15m_closed_end=2026-10-19T08:30+00:00, prior8high=0.620500, depth_time=2026-10-19T08:30:16+00:00, book20_bid_proxy_usdt=252647, book20_ask_proxy_usdt=262414, funding_indicative=-0.000052, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.34%, turnover=57434067. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
