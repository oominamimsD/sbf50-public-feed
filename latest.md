# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T19:15:24Z**
- feed_generated_utc: 2026-11-04T19:15:26+00:00
- source_sha256: `92a224360a88e0548dd6c79f7817630395d704ae3797ff89e42e189cc3b25902`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T19:15+00:00, close=80234.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T19:00+00:00, close=80313.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T16:00+00:00, close=80272.3, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.032310|-10.00|-28.34|-9.96|5268107|3.09|
|TRUMPOFFICIAL_USDT|1.289000|-9.48|-24.57|-9.44|24172389|7.77|
|AKE_USDT|0.002599|-7.50|-87.06|-7.46|16993362|7.72|
|PUMPFUN_USDT|0.004188|-5.88|-0.45|-5.84|18729165|2.39|
|WLD_USDT|0.377700|-3.67|-12.73|-3.63|73537744|2.65|
|ZRO_USDT|1.800200|-3.45|5.15|-3.41|11201735|0.56|
|WLFI_USDT|0.047100|-1.46|-10.25|-1.42|5990052|2.12|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.032310|0.031770|0.032310|0.37|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.002599|0.002421|0.002600|0.28|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.004188|0.004150|0.004188|1.04|N|Y/Y|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.289000|1.215000|1.289000|0.49|N|Y/Y|Y/Y|N|N|
|WLD_USDT|0.377700|0.367100|0.377800|1.86|N|Y/N|N/N|N|N|
|WLFI_USDT|0.047100|0.046430|0.047090|0.14|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.800200|1.788900|1.800200|1.61|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T19:15:03+00:00, last15m_closed_end=2026-11-04T19:15+00:00, prior8high=0.035360, depth_time=2026-11-04T19:15:05+00:00, book20_bid_proxy_usdt=42093, book20_ask_proxy_usdt=20614, funding_indicative=0.000053, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-10.00%, turnover=5268107. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T19:15:03+00:00, last15m_closed_end=2026-11-04T19:15+00:00, prior8high=0.002842, depth_time=2026-11-04T19:15:13+00:00, book20_bid_proxy_usdt=63796, book20_ask_proxy_usdt=48513, funding_indicative=-0.000289, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-7.50%, turnover=16993362. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-04T19:15:03+00:00, last15m_closed_end=2026-11-04T19:15+00:00, prior8high=0.004454, depth_time=2026-11-04T19:15:15+00:00, book20_bid_proxy_usdt=1966412, book20_ask_proxy_usdt=1883217, funding_indicative=0.000050, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.88%, turnover=18729165. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T19:15:03+00:00, last15m_closed_end=2026-11-04T19:15+00:00, prior8high=1.396000, depth_time=2026-11-04T19:15:10+00:00, book20_bid_proxy_usdt=1378890, book20_ask_proxy_usdt=1215085, funding_indicative=-0.000389, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-9.48%, turnover=24172389. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-04T19:15:03+00:00, last15m_closed_end=2026-11-04T19:15+00:00, prior8high=0.393200, depth_time=2026-11-04T19:15:18+00:00, book20_bid_proxy_usdt=1307398, book20_ask_proxy_usdt=1451047, funding_indicative=-0.000360, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.67%, turnover=73537744. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLFI_USDT: quote_utc=2026-11-04T19:15:03+00:00, last15m_closed_end=2026-11-04T19:15+00:00, prior8high=0.048210, depth_time=2026-11-04T19:15:21+00:00, book20_bid_proxy_usdt=152736, book20_ask_proxy_usdt=336272, funding_indicative=0.000050, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.46%, turnover=5990052. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-04T19:15:03+00:00, last15m_closed_end=2026-11-04T19:15+00:00, prior8high=1.858900, depth_time=2026-11-04T19:15:21+00:00, book20_bid_proxy_usdt=40783, book20_ask_proxy_usdt=63600, funding_indicative=0.000050, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.45%, turnover=11201735. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
