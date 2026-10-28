# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T14:15:41Z**
- feed_generated_utc: 2026-10-28T14:15:45+00:00
- source_sha256: `fb5d0e1e6e93723dc3e89712554724e60ce636a0de1589a41b21680a7fe6c5c5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.08 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T14:15+00:00, close=80620.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-28T14:00+00:00, close=80713.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-28T12:00+00:00, close=81305.7, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BEAT_USDT|0.079580|-12.63|6.51|-12.74|12243940|1.26|
|Q_USDT|0.055740|-12.33|-54.59|-12.44|17814531|5.38|
|ENA_USDT|0.194590|-8.54|2.48|-8.65|81404274|0.51|
|AKE_USDT|0.019406|-8.13|-37.58|-8.24|6653299|2.58|
|INJ_USDT|7.787000|-4.94|-9.45|-5.05|24765834|1.28|
|ARB_USDT|0.163940|-2.70|-13.23|-2.81|16733374|0.61|
|UNI_USDT|6.993000|-2.31|-3.82|-2.42|14035015|1.43|
|DASH_USDT|52.920000|-2.30|5.96|-2.41|15701149|1.89|
|PUMPFUN_USDT|0.004191|-2.19|-7.09|-2.30|13421115|2.39|
|WLD_USDT|0.427400|-1.97|-24.05|-2.08|60929789|2.34|
|ADA_USDT|0.201800|-1.84|-8.85|-1.95|36128720|4.95|
|QNT_USDT|194.640000|-1.64|-0.26|-1.75|66333863|1.03|
|OP_USDT|0.109680|-1.47|-16.45|-1.58|6211223|0.91|
|APT_USDT|0.678300|-1.36|-14.96|-1.47|6315191|1.47|
|ASTER_USDT|0.703400|-1.34|-1.48|-1.45|5031498|1.42|
|SILVER_USDT|53.920000|-1.31|-6.95|-1.42|252275344|1.85|
|HBAR_USDT|0.075140|-1.28|-9.86|-1.39|10224075|1.33|
|AAVE_USDT|131.330000|-1.01|-13.63|-1.12|16499624|0.76|
|ZEC_USDT|1280.200000|-0.96|7.48|-1.07|1557816304|0.08|
|ONDO_USDT|0.413300|-0.93|-6.91|-1.04|16899375|2.42|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.201800|0.201500|0.201800|2.06|N|Y/Y|N/N|Y|N|
|AKE_USDT|0.019406|0.019399|0.019406|0.86|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.678300|0.677500|0.678300|2.07|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.163940|0.163710|0.163940|2.21|N|Y/Y|Y/Y|Y|N|
|ASTER_USDT|0.703400|0.701900|0.703400|1.82|N|Y/Y|N/N|Y|N|
|BEAT_USDT|0.079580|0.078520|0.079710|0.53|N|Y/Y|Y/N|Y|N|
|DASH_USDT|52.920000|52.880000|52.920000|2.35|N|Y/Y|N/N|Y|N|
|ENA_USDT|0.194590|0.195710|0.194590|1.40|Y|Y/Y|Y/N|Y|N|
|INJ_USDT|7.787000|7.789000|7.790000|3.65|N|Y/Y|N/N|Y|N|
|OP_USDT|0.109680|0.109570|0.109680|6.61|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004191|0.004183|0.004191|1.76|N|Y/Y|N/N|Y|N|
|QNT_USDT|194.640000|194.120000|194.640000|1.16|N|Y/Y|N/N|Y|N|
|Q_USDT|0.055740|0.052780|0.055840|1.68|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.993000|6.985000|6.993000|1.23|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.427400|0.425300|0.427300|1.93|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-10-28T14:15:01+00:00, last15m_closed_end=2026-10-28T14:15+00:00, prior8high=0.206400, depth_time=2026-10-28T14:15:31+00:00, book20_bid_proxy_usdt=6937556, book20_ask_proxy_usdt=7735404, funding_indicative=-0.000067, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.84%, turnover=36128720. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-28T14:15:01+00:00, last15m_closed_end=2026-10-28T14:15+00:00, prior8high=0.020149, depth_time=2026-10-28T14:15:11+00:00, book20_bid_proxy_usdt=5026, book20_ask_proxy_usdt=6276, funding_indicative=0.000050, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.13%, turnover=6653299. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-28T14:15:01+00:00, last15m_closed_end=2026-10-28T14:15+00:00, prior8high=0.696400, depth_time=2026-10-28T14:15:38+00:00, book20_bid_proxy_usdt=140244, book20_ask_proxy_usdt=208739, funding_indicative=-0.000077, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.36%, turnover=6315191. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-28T14:15:01+00:00, last15m_closed_end=2026-10-28T14:15+00:00, prior8high=0.168230, depth_time=2026-10-28T14:15:19+00:00, book20_bid_proxy_usdt=108211, book20_ask_proxy_usdt=88643, funding_indicative=-0.000101, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.70%, turnover=16733374. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ASTER_USDT: quote_utc=2026-10-28T14:15:01+00:00, last15m_closed_end=2026-10-28T14:15+00:00, prior8high=0.710400, depth_time=2026-10-28T14:15:38+00:00, book20_bid_proxy_usdt=1023642, book20_ask_proxy_usdt=783387, funding_indicative=0.000029, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.34%, turnover=5031498. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-28T14:15:01+00:00, last15m_closed_end=2026-10-28T14:15+00:00, prior8high=0.081130, depth_time=2026-10-28T14:15:07+00:00, book20_bid_proxy_usdt=8636, book20_ask_proxy_usdt=5464, funding_indicative=0.000050, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-12.63%, turnover=12243940. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-28T14:15:01+00:00, last15m_closed_end=2026-10-28T14:15+00:00, prior8high=53.670000, depth_time=2026-10-28T14:15:22+00:00, book20_bid_proxy_usdt=984111, book20_ask_proxy_usdt=779762, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.30%, turnover=15701149. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-28T14:15:01+00:00, last15m_closed_end=2026-10-28T14:15+00:00, prior8high=0.203790, depth_time=2026-10-28T14:15:12+00:00, book20_bid_proxy_usdt=226432, book20_ask_proxy_usdt=226215, funding_indicative=-0.000036, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.54%, turnover=81404274. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-28T14:15:01+00:00, last15m_closed_end=2026-10-28T14:15+00:00, prior8high=7.942000, depth_time=2026-10-28T14:15:17+00:00, book20_bid_proxy_usdt=257120, book20_ask_proxy_usdt=345199, funding_indicative=0.000127, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.94%, turnover=24765834. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-28T14:15:01+00:00, last15m_closed_end=2026-10-28T14:15+00:00, prior8high=0.112610, depth_time=2026-10-28T14:15:35+00:00, book20_bid_proxy_usdt=94686, book20_ask_proxy_usdt=119309, funding_indicative=-0.000062, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.47%, turnover=6211223. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-28T14:15:01+00:00, last15m_closed_end=2026-10-28T14:15+00:00, prior8high=0.004319, depth_time=2026-10-28T14:15:26+00:00, book20_bid_proxy_usdt=1965678, book20_ask_proxy_usdt=2416462, funding_indicative=-0.000003, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.19%, turnover=13421115. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-28T14:15:01+00:00, last15m_closed_end=2026-10-28T14:15+00:00, prior8high=200.250000, depth_time=2026-10-28T14:15:33+00:00, book20_bid_proxy_usdt=81909, book20_ask_proxy_usdt=97923, funding_indicative=-0.000326, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.64%, turnover=66333863. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T14:15:01+00:00, last15m_closed_end=2026-10-28T14:15+00:00, prior8high=0.055830, depth_time=2026-10-28T14:15:10+00:00, book20_bid_proxy_usdt=24053, book20_ask_proxy_usdt=19294, funding_indicative=-0.000826, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-12.33%, turnover=17814531. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-28T14:15:01+00:00, last15m_closed_end=2026-10-28T14:15+00:00, prior8high=7.141000, depth_time=2026-10-28T14:15:21+00:00, book20_bid_proxy_usdt=1879707, book20_ask_proxy_usdt=2272734, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.31%, turnover=14035015. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-28T14:15:01+00:00, last15m_closed_end=2026-10-28T14:15+00:00, prior8high=0.436200, depth_time=2026-10-28T14:15:28+00:00, book20_bid_proxy_usdt=2545191, book20_ask_proxy_usdt=3485492, funding_indicative=-0.000081, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.97%, turnover=60929789. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
