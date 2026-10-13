# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T05:15:41Z**
- feed_generated_utc: 2026-10-13T05:15:44+00:00
- source_sha256: `c46f0a34dcf8d71eb255b7c8100ddbe456bc9e128547053ad01eb10cf9c9c27f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T05:15+00:00, close=83695.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-13T05:00+00:00, close=83419.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T04:00+00:00, close=83297.9, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|W_USDT|0.019335|-19.63|36.71|-20.85|35229113|8.27|
|DOS_USDT|0.236000|-18.48|10.79|-19.70|9260414|4.24|
|ZRO_USDT|2.129000|-5.83|4.07|-7.05|30307005|0.94|
|LIT_USDT|3.461800|-4.50|-8.95|-5.72|11217177|0.29|
|PUMPFUN_USDT|0.005096|-4.01|-19.55|-5.23|32632663|1.96|
|ENA_USDT|0.214000|-3.46|-12.85|-4.68|69592758|0.47|
|RLC_USDT|0.954700|-3.42|74.21|-4.64|7157222|1.05|
|SEI_USDT|0.064350|-3.04|-10.51|-4.26|9499597|1.55|
|ICP_USDT|3.199000|-2.91|-7.70|-4.13|16295369|3.13|
|STRK_USDT|0.088280|-2.63|69.41|-3.85|64944094|1.13|
|PONS_USDT|0.287200|-2.54|-25.11|-3.76|6306938|3.48|
|HBAR_USDT|0.088290|-2.44|-12.32|-3.66|22004592|1.13|
|HYPE_USDT|82.765000|-1.90|-10.66|-3.12|85348243|0.12|
|JUP_USDT|0.336800|-1.77|-0.32|-2.99|8914903|2.97|
|USELESS_USDT|0.178410|-1.75|-21.31|-2.97|6860061|0.56|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOS_USDT|0.236000|0.232600|0.236100|1.51|N|Y/Y|Y/N|N|N|
|ENA_USDT|0.214000|0.207990|0.214000|0.62|N|Y/Y|Y/Y|N|N|
|HBAR_USDT|0.088290|0.086850|0.088290|2.21|N|Y/Y|Y/Y|N|N|
|HYPE_USDT|82.765000|82.095000|82.765000|0.30|N|Y/Y|Y/Y|N|N|
|ICP_USDT|3.199000|3.097000|3.199000|1.18|N|Y/Y|Y/Y|N|N|
|JUP_USDT|0.336800|0.332200|0.336800|1.36|N|Y/Y|Y/Y|N|N|
|LIT_USDT|3.461800|3.395700|3.461800|0.58|N|Y/Y|Y/Y|N|N|
|PONS_USDT|0.287200|0.278200|0.287200|0.57|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.005096|0.004996|0.005096|0.99|N|Y/Y|Y/Y|N|N|
|RLC_USDT|0.954700|0.939400|0.954700|1.19|N|Y/Y|Y/Y|N|N|
|SEI_USDT|0.064350|0.062460|0.064350|1.40|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.088280|0.082550|0.088280|0.46|N|Y/Y|Y/Y|N|N|
|USELESS_USDT|0.178410|0.170990|0.178410|0.33|N|Y/Y|Y/Y|N|N|
|W_USDT|0.019335|0.018531|0.019335|0.41|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|2.129000|2.092200|2.127100|0.74|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOS_USDT: quote_utc=2026-10-13T05:15:01+00:00, last15m_closed_end=2026-10-13T05:15+00:00, prior8high=0.251000, depth_time=2026-10-13T05:15:11+00:00, book20_bid_proxy_usdt=102136, book20_ask_proxy_usdt=65967, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-18.48%, turnover=9260414. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-13T05:15:01+00:00, last15m_closed_end=2026-10-13T05:15+00:00, prior8high=0.213450, depth_time=2026-10-13T05:15:20+00:00, book20_bid_proxy_usdt=115541, book20_ask_proxy_usdt=85801, funding_indicative=-0.000033, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.46%, turnover=69592758. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-13T05:15:01+00:00, last15m_closed_end=2026-10-13T05:15+00:00, prior8high=0.088020, depth_time=2026-10-13T05:15:33+00:00, book20_bid_proxy_usdt=482243, book20_ask_proxy_usdt=566906, funding_indicative=0.000006, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.44%, turnover=22004592. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-13T05:15:01+00:00, last15m_closed_end=2026-10-13T05:15+00:00, prior8high=83.024000, depth_time=2026-10-13T05:15:36+00:00, book20_bid_proxy_usdt=168946, book20_ask_proxy_usdt=34428, funding_indicative=0.000006, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.90%, turnover=85348243. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-13T05:15:01+00:00, last15m_closed_end=2026-10-13T05:15+00:00, prior8high=3.192000, depth_time=2026-10-13T05:15:26+00:00, book20_bid_proxy_usdt=774503, book20_ask_proxy_usdt=691668, funding_indicative=-0.000053, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.91%, turnover=16295369. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-13T05:15:01+00:00, last15m_closed_end=2026-10-13T05:15+00:00, prior8high=0.337300, depth_time=2026-10-13T05:15:38+00:00, book20_bid_proxy_usdt=509992, book20_ask_proxy_usdt=555344, funding_indicative=-0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.77%, turnover=8914903. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-13T05:15:01+00:00, last15m_closed_end=2026-10-13T05:15+00:00, prior8high=3.472500, depth_time=2026-10-13T05:15:15+00:00, book20_bid_proxy_usdt=20565, book20_ask_proxy_usdt=24907, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.50%, turnover=11217177. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PONS_USDT: quote_utc=2026-10-13T05:15:01+00:00, last15m_closed_end=2026-10-13T05:15+00:00, prior8high=0.284600, depth_time=2026-10-13T05:15:31+00:00, book20_bid_proxy_usdt=224180, book20_ask_proxy_usdt=207196, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.54%, turnover=6306938. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-13T05:15:01+00:00, last15m_closed_end=2026-10-13T05:15+00:00, prior8high=0.005098, depth_time=2026-10-13T05:15:17+00:00, book20_bid_proxy_usdt=1629556, book20_ask_proxy_usdt=1655079, funding_indicative=0.000007, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.01%, turnover=32632663. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T05:15:01+00:00, last15m_closed_end=2026-10-13T05:15+00:00, prior8high=0.984900, depth_time=2026-10-13T05:15:22+00:00, book20_bid_proxy_usdt=48277, book20_ask_proxy_usdt=73083, funding_indicative=-0.000489, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.42%, turnover=7157222. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-13T05:15:01+00:00, last15m_closed_end=2026-10-13T05:15+00:00, prior8high=0.063950, depth_time=2026-10-13T05:15:24+00:00, book20_bid_proxy_usdt=103121, book20_ask_proxy_usdt=177818, funding_indicative=-0.000079, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.04%, turnover=9499597. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T05:15:01+00:00, last15m_closed_end=2026-10-13T05:15+00:00, prior8high=0.089670, depth_time=2026-10-13T05:15:29+00:00, book20_bid_proxy_usdt=150793, book20_ask_proxy_usdt=134946, funding_indicative=0.000022, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.63%, turnover=64944094. target_RR/account_short_permission/settled_funding=UNKNOWN.
- USELESS_USDT: quote_utc=2026-10-13T05:15:01+00:00, last15m_closed_end=2026-10-13T05:15+00:00, prior8high=0.177970, depth_time=2026-10-13T05:15:39+00:00, book20_bid_proxy_usdt=27081, book20_ask_proxy_usdt=21750, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.75%, turnover=6860061. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-13T05:15:01+00:00, last15m_closed_end=2026-10-13T05:15+00:00, prior8high=0.019413, depth_time=2026-10-13T05:15:08+00:00, book20_bid_proxy_usdt=32121, book20_ask_proxy_usdt=11795, funding_indicative=-0.000450, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-19.63%, turnover=35229113. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-13T05:15:01+00:00, last15m_closed_end=2026-10-13T05:15+00:00, prior8high=2.133900, depth_time=2026-10-13T05:15:13+00:00, book20_bid_proxy_usdt=38234, book20_ask_proxy_usdt=18925, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.83%, turnover=30307005. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
