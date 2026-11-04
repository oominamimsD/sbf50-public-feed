# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T19:00:23Z**
- feed_generated_utc: 2026-11-04T19:00:25+00:00
- source_sha256: `1c33238ac6c50887360a3aff118d246cdbbb171b14abaf227a83d809a68bc66d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T19:00+00:00, close=80313.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T19:00+00:00, close=80313.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T16:00+00:00, close=80272.3, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TRUMPOFFICIAL_USDT|1.291000|-9.46|-24.45|-9.51|23916490|7.73|
|AGT_USDT|0.032060|-8.53|-28.89|-8.58|5248479|3.12|
|AKE_USDT|0.002614|-6.97|-86.99|-7.02|16910621|7.66|
|PUMPFUN_USDT|0.004161|-6.00|-1.09|-6.05|18490187|2.40|
|WLD_USDT|0.376900|-3.87|-12.91|-3.92|72300477|2.65|
|ZRO_USDT|1.794900|-3.74|4.84|-3.79|11032224|0.56|
|WLFI_USDT|0.047170|-1.31|-10.11|-1.36|5985943|2.12|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.032060|0.032370|0.032080|1.18|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.002614|0.002421|0.002614|0.26|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.004161|0.004181|0.004161|0.83|N|Y/Y|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.291000|1.215000|1.291000|0.29|N|Y/Y|Y/Y|N|N|
|WLD_USDT|0.376900|0.367100|0.377100|0.98|N|Y/N|N/N|N|N|
|WLFI_USDT|0.047170|0.046430|0.047150|0.59|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.794900|1.802500|1.793000|1.11|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T19:00:01+00:00, last15m_closed_end=2026-11-04T19:00+00:00, prior8high=0.035620, depth_time=2026-11-04T19:00:10+00:00, book20_bid_proxy_usdt=26599, book20_ask_proxy_usdt=31395, funding_indicative=0.000053, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-8.53%, turnover=5248479. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T19:00:01+00:00, last15m_closed_end=2026-11-04T19:00+00:00, prior8high=0.002842, depth_time=2026-11-04T19:00:12+00:00, book20_bid_proxy_usdt=127664, book20_ask_proxy_usdt=64604, funding_indicative=-0.000246, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-6.97%, turnover=16910621. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-04T19:00:01+00:00, last15m_closed_end=2026-11-04T19:00+00:00, prior8high=0.004476, depth_time=2026-11-04T19:00:14+00:00, book20_bid_proxy_usdt=1184562, book20_ask_proxy_usdt=1713976, funding_indicative=0.000050, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-6.00%, turnover=18490187. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T19:00:01+00:00, last15m_closed_end=2026-11-04T19:00+00:00, prior8high=1.406000, depth_time=2026-11-04T19:00:08+00:00, book20_bid_proxy_usdt=1178920, book20_ask_proxy_usdt=1117246, funding_indicative=-0.000407, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-9.46%, turnover=23916490. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-04T19:00:01+00:00, last15m_closed_end=2026-11-04T19:00+00:00, prior8high=0.393200, depth_time=2026-11-04T19:00:17+00:00, book20_bid_proxy_usdt=2236222, book20_ask_proxy_usdt=2192737, funding_indicative=-0.000346, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.87%, turnover=72300477. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLFI_USDT: quote_utc=2026-11-04T19:00:02+00:00, last15m_closed_end=2026-11-04T19:00+00:00, prior8high=0.048210, depth_time=2026-11-04T19:00:22+00:00, book20_bid_proxy_usdt=250286, book20_ask_proxy_usdt=216448, funding_indicative=0.000050, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.31%, turnover=5985943. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-04T19:00:02+00:00, last15m_closed_end=2026-11-04T19:00+00:00, prior8high=1.865200, depth_time=2026-11-04T19:00:19+00:00, book20_bid_proxy_usdt=26055, book20_ask_proxy_usdt=56838, funding_indicative=0.000050, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.74%, turnover=11032224. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
