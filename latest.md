# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T01:15:31Z**
- feed_generated_utc: 2026-11-01T01:15:33+00:00
- source_sha256: `974f2bf0f561351870560390b1e9695e3dfca22b8ce110bba97c648d61882204`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T01:15+00:00, close=77653, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-01T01:00+00:00, close=77641.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T00:00+00:00, close=77522.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.242130|-18.24|44.19|-18.35|29409809|1.65|
|BLESS_USDT|0.009458|-10.46|16.57|-10.57|7683377|3.17|
|Q_USDT|0.030350|-5.39|-61.54|-5.50|9911325|3.29|
|BTW_USDT|1.072400|-4.41|-38.41|-4.52|5371518|0.93|
|ENA_USDT|0.189090|-2.53|1.23|-2.64|44047246|0.53|
|ZEC_USDT|1257.580000|-2.09|9.81|-2.20|1002573629|0.08|
|XLM_USDT|0.168930|-1.63|0.30|-1.74|20624253|0.59|
|FET_USDT|0.160800|-1.53|-6.67|-1.64|5445902|6.22|
|TRX_USDT|0.308170|-1.33|-6.31|-1.44|11025748|0.33|
|FARTCOIN_USDT|0.120510|-1.21|-1.20|-1.32|6366608|0.83|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.009458|0.009300|0.009458|0.84|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.072400|1.049300|1.072400|1.29|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.189090|0.187820|0.189090|0.75|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.120510|0.119900|0.120510|0.41|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.160800|0.159200|0.160800|0.83|N|Y/Y|Y/Y|Y|N|
|LSK_USDT|0.242130|0.235150|0.242010|1.27|N|Y/Y|N/N|Y|N|
|Q_USDT|0.030350|0.030800|0.030350|2.36|Y|Y/Y|Y/Y|Y|Y|
|TRX_USDT|0.308170|0.300770|0.308170|1.05|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.168930|0.168940|0.168950|1.04|N|Y/N|N/N|Y|N|
|ZEC_USDT|1257.580000|1243.100000|1257.580000|0.79|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-11-01T01:14:59+00:00, last15m_closed_end=2026-11-01T01:15+00:00, prior8high=0.009626, depth_time=2026-11-01T01:15:11+00:00, book20_bid_proxy_usdt=11867, book20_ask_proxy_usdt=14176, funding_indicative=0.000050, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.46%, turnover=7683377. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-01T01:14:59+00:00, last15m_closed_end=2026-11-01T01:15+00:00, prior8high=1.111500, depth_time=2026-11-01T01:15:15+00:00, book20_bid_proxy_usdt=32468, book20_ask_proxy_usdt=15400, funding_indicative=-0.000477, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.41%, turnover=5371518. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-01T01:14:59+00:00, last15m_closed_end=2026-11-01T01:15+00:00, prior8high=0.189790, depth_time=2026-11-01T01:15:18+00:00, book20_bid_proxy_usdt=138679, book20_ask_proxy_usdt=125235, funding_indicative=0.000033, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.53%, turnover=44047246. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-01T01:14:59+00:00, last15m_closed_end=2026-11-01T01:15+00:00, prior8high=0.120690, depth_time=2026-11-01T01:15:29+00:00, book20_bid_proxy_usdt=71413, book20_ask_proxy_usdt=88754, funding_indicative=0.000050, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.21%, turnover=6366608. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-11-01T01:14:59+00:00, last15m_closed_end=2026-11-01T01:15+00:00, prior8high=0.160200, depth_time=2026-11-01T01:15:24+00:00, book20_bid_proxy_usdt=1348196, book20_ask_proxy_usdt=904576, funding_indicative=-0.000152, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.53%, turnover=5445902. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-11-01T01:14:59+00:00, last15m_closed_end=2026-11-01T01:15+00:00, prior8high=0.253830, depth_time=2026-11-01T01:15:08+00:00, book20_bid_proxy_usdt=6331, book20_ask_proxy_usdt=5224, funding_indicative=-0.001705, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-18.24%, turnover=29409809. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-11-01T01:14:59+00:00, last15m_closed_end=2026-11-01T01:15+00:00, prior8high=0.031710, depth_time=2026-11-01T01:15:13+00:00, book20_bid_proxy_usdt=53872, book20_ask_proxy_usdt=57579, funding_indicative=-0.000983, next_funding_utc=2026-11-01T02:00:00+00:00, funding_cycle_h=1, 24h_change=-5.39%, turnover=9911325. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-11-01T01:14:59+00:00, last15m_closed_end=2026-11-01T01:15+00:00, prior8high=0.308350, depth_time=2026-11-01T01:15:27+00:00, book20_bid_proxy_usdt=32961, book20_ask_proxy_usdt=41219, funding_indicative=-0.001845, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.33%, turnover=11025748. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-01T01:14:59+00:00, last15m_closed_end=2026-11-01T01:15+00:00, prior8high=0.170190, depth_time=2026-11-01T01:15:21+00:00, book20_bid_proxy_usdt=265180, book20_ask_proxy_usdt=242780, funding_indicative=-0.000045, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.63%, turnover=20624253. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-01T01:14:59+00:00, last15m_closed_end=2026-11-01T01:15+00:00, prior8high=1258.380000, depth_time=2026-11-01T01:15:20+00:00, book20_bid_proxy_usdt=187596, book20_ask_proxy_usdt=258650, funding_indicative=-0.000083, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.09%, turnover=1002573629. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
