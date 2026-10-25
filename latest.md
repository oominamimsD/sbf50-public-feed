# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T07:30:34Z**
- feed_generated_utc: 2026-10-25T07:30:37+00:00
- source_sha256: `b1fe45d96c79dbabe6396de77113ae29f2e7181730e57a5acf2e424e944af1eb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1180; contracts: 1172; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T07:30+00:00, close=80562, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T07:00+00:00, close=80457.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T04:00+00:00, close=80826.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.054700|-18.84|76.73|-19.84|13827213|1.83|
|BIRB_USDT|0.081340|-16.71|67.64|-17.71|6451875|2.46|
|IRYS_USDT|0.039030|-15.24|205.87|-16.24|34033251|5.13|
|BTW_USDT|1.699600|-2.39|-25.10|-3.39|11530489|5.88|
|DOT_USDT|1.023800|-1.47|-8.37|-2.47|11976776|0.98|
|STRK_USDT|0.046200|-1.13|-30.15|-2.13|8671426|2.17|
|AKE_USDT|0.028928|-1.03|-0.11|-2.03|6563330|2.07|
|SUI_USDT|0.917200|-0.84|-6.57|-1.84|67218275|1.09|
|APT_USDT|0.699900|-0.28|-12.23|-1.28|6135619|1.43|
|SEI_USDT|0.052780|-0.18|-14.88|-1.18|9695345|1.90|
|LINK_USDT|11.370000|-0.10|-4.50|-1.10|49457881|0.88|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.028928|0.028767|0.028928|0.57|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.699900|0.697500|0.699900|5.17|N|Y/Y|Y/Y|Y|N|
|BIRB_USDT|0.081340|0.080220|0.081340|0.52|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.699600|1.590000|1.697500|2.36|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.023800|1.017100|1.023800|0.81|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.039030|0.038350|0.039040|0.52|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.370000|11.339000|11.370000|0.87|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.054700|0.054410|0.054700|0.50|N|Y/N|N/N|Y|N|
|SEI_USDT|0.052780|0.052650|0.052780|1.41|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.046200|0.045690|0.046200|3.36|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.917200|0.911400|0.917200|1.44|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-25T07:30:01+00:00, last15m_closed_end=2026-10-25T07:30+00:00, prior8high=0.030326, depth_time=2026-10-25T07:30:22+00:00, book20_bid_proxy_usdt=11429, book20_ask_proxy_usdt=9764, funding_indicative=0.000050, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.03%, turnover=6563330. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-25T07:30:01+00:00, last15m_closed_end=2026-10-25T07:30+00:00, prior8high=0.713600, depth_time=2026-10-25T07:30:28+00:00, book20_bid_proxy_usdt=152738, book20_ask_proxy_usdt=172145, funding_indicative=-0.000015, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.28%, turnover=6135619. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BIRB_USDT: quote_utc=2026-10-25T07:30:01+00:00, last15m_closed_end=2026-10-25T07:30+00:00, prior8high=0.085440, depth_time=2026-10-25T07:30:10+00:00, book20_bid_proxy_usdt=20777, book20_ask_proxy_usdt=21919, funding_indicative=-0.011775, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-16.71%, turnover=6451875. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-25T07:30:01+00:00, last15m_closed_end=2026-10-25T07:30+00:00, prior8high=1.915400, depth_time=2026-10-25T07:30:15+00:00, book20_bid_proxy_usdt=7474, book20_ask_proxy_usdt=10719, funding_indicative=-0.006867, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.39%, turnover=11530489. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T07:30:01+00:00, last15m_closed_end=2026-10-25T07:30+00:00, prior8high=1.042400, depth_time=2026-10-25T07:30:17+00:00, book20_bid_proxy_usdt=350951, book20_ask_proxy_usdt=321730, funding_indicative=-0.000065, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.47%, turnover=11976776. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T07:30:01+00:00, last15m_closed_end=2026-10-25T07:30+00:00, prior8high=0.044650, depth_time=2026-10-25T07:30:13+00:00, book20_bid_proxy_usdt=40582, book20_ask_proxy_usdt=39302, funding_indicative=-0.002643, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=1, 24h_change=-15.24%, turnover=34033251. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-25T07:30:01+00:00, last15m_closed_end=2026-10-25T07:30+00:00, prior8high=11.565000, depth_time=2026-10-25T07:30:33+00:00, book20_bid_proxy_usdt=944244, book20_ask_proxy_usdt=468666, funding_indicative=0.000063, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.10%, turnover=49457881. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T07:30:01+00:00, last15m_closed_end=2026-10-25T07:30+00:00, prior8high=0.059870, depth_time=2026-10-25T07:30:08+00:00, book20_bid_proxy_usdt=97163, book20_ask_proxy_usdt=74503, funding_indicative=-0.001168, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=1, 24h_change=-18.84%, turnover=13827213. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-25T07:30:01+00:00, last15m_closed_end=2026-10-25T07:30+00:00, prior8high=0.053660, depth_time=2026-10-25T07:30:30+00:00, book20_bid_proxy_usdt=216000, book20_ask_proxy_usdt=418233, funding_indicative=-0.000069, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.18%, turnover=9695345. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T07:30:01+00:00, last15m_closed_end=2026-10-25T07:30+00:00, prior8high=0.047110, depth_time=2026-10-25T07:30:20+00:00, book20_bid_proxy_usdt=800820, book20_ask_proxy_usdt=715390, funding_indicative=0.000033, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.13%, turnover=8671426. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T07:30:01+00:00, last15m_closed_end=2026-10-25T07:30+00:00, prior8high=0.930900, depth_time=2026-10-25T07:30:24+00:00, book20_bid_proxy_usdt=1643894, book20_ask_proxy_usdt=1241036, funding_indicative=0.000035, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.84%, turnover=67218275. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
