# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-29T19:15:43Z**
- feed_generated_utc: 2026-10-29T19:15:45+00:00
- source_sha256: `436d992d68bf8be45054d56448e866f5228c51bbbf200165008ce8d66ab6d970`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1195; contracts: 1187; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-29T19:15+00:00, close=80756.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-29T19:00+00:00, close=80824.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-29T16:00+00:00, close=81732.5, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.466900|-10.45|-18.05|-9.26|9730614|1.36|
|Q_USDT|0.035990|-6.30|-72.06|-5.11|25190617|2.77|
|NEAR_USDT|4.389000|-5.59|-11.22|-4.40|111843512|2.28|
|PENGU_USDT|0.007707|-5.21|-0.27|-4.02|6703739|1.30|
|APT_USDT|0.667700|-5.06|-13.53|-3.87|9527130|1.50|
|WLD_USDT|0.416200|-4.60|-21.78|-3.41|82911024|2.40|
|FARTCOIN_USDT|0.128560|-4.34|-9.99|-3.15|10664341|0.78|
|TRUMPOFFICIAL_USDT|1.658000|-4.05|-4.93|-2.86|6305797|6.03|
|QNT_USDT|190.970000|-3.90|0.13|-2.71|63059223|0.52|
|FET_USDT|0.177700|-3.84|-4.10|-2.65|9411471|5.63|
|DOT_USDT|0.978700|-3.80|-12.95|-2.61|10188700|1.02|
|ARB_USDT|0.167920|-3.74|-8.56|-2.55|26210809|0.59|
|OP_USDT|0.109710|-3.68|-8.46|-2.49|6747048|0.91|
|SEI_USDT|0.051540|-3.55|-11.24|-2.36|5350708|1.94|
|ONDO_USDT|0.414700|-3.51|-3.78|-2.32|23280535|2.41|
|HBAR_USDT|0.072880|-3.17|-9.02|-1.98|14999042|1.37|
|FILECOIN_USDT|0.889100|-3.14|-7.57|-1.95|9633644|1.12|
|ICP_USDT|2.546000|-3.08|-7.31|-1.89|5404984|3.93|
|TAO_USDT|251.880000|-2.66|-2.23|-1.47|62725166|1.19|
|SOL_USDT|100.270000|-2.30|-4.12|-1.11|633890395|1.00|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.667700|0.667500|0.667500|0.97|N|Y/N|N/Y|N|N|
|ARB_USDT|0.167920|0.167330|0.167920|0.30|N|Y/N|N/Y|N|N|
|BTW_USDT|1.466900|1.483000|1.466700|1.32|Y|Y/Y|Y/N|N|N|
|DOT_USDT|0.978700|0.977200|0.978700|0.50|N|Y/Y|N/Y|N|N|
|FARTCOIN_USDT|0.128560|0.128720|0.128560|0.73|N|Y/N|N/Y|N|N|
|FET_USDT|0.177700|0.176800|0.177700|0.43|N|Y/Y|N/N|N|N|
|NEAR_USDT|4.389000|4.395000|4.389000|0.50|N|Y/Y|N/Y|N|N|
|ONDO_USDT|0.414700|0.414800|0.414700|0.72|N|N/N|N/N|N|N|
|OP_USDT|0.109710|0.109470|0.109670|0.20|N|Y/N|N/Y|N|N|
|PENGU_USDT|0.007707|0.007711|0.007707|0.27|N|Y/N|N/N|N|N|
|QNT_USDT|190.970000|188.850000|190.880000|0.47|N|Y/Y|N/Y|N|N|
|Q_USDT|0.035990|0.035860|0.035990|2.12|N|Y/Y|Y/Y|N|N|
|SEI_USDT|0.051540|0.051390|0.051540|0.23|N|Y/Y|N/Y|N|N|
|TRUMPOFFICIAL_USDT|1.658000|1.656000|1.658000|0.40|N|Y/Y|N/Y|N|N|
|WLD_USDT|0.416200|0.416700|0.416000|0.90|N|Y/N|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-29T19:15:01+00:00, last15m_closed_end=2026-10-29T19:15+00:00, prior8high=0.694300, depth_time=2026-10-29T19:15:17+00:00, book20_bid_proxy_usdt=193855, book20_ask_proxy_usdt=157523, funding_indicative=0.000080, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.06%, turnover=9527130. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-29T19:15:01+00:00, last15m_closed_end=2026-10-29T19:15+00:00, prior8high=0.172700, depth_time=2026-10-29T19:15:34+00:00, book20_bid_proxy_usdt=53527, book20_ask_proxy_usdt=102117, funding_indicative=0.000100, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.74%, turnover=26210809. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-29T19:15:01+00:00, last15m_closed_end=2026-10-29T19:15+00:00, prior8high=1.561000, depth_time=2026-10-29T19:15:07+00:00, book20_bid_proxy_usdt=25633, book20_ask_proxy_usdt=23475, funding_indicative=0.000010, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-10.45%, turnover=9730614. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-29T19:15:01+00:00, last15m_closed_end=2026-10-29T19:15+00:00, prior8high=1.006300, depth_time=2026-10-29T19:15:31+00:00, book20_bid_proxy_usdt=497912, book20_ask_proxy_usdt=422019, funding_indicative=0.000097, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.80%, turnover=10188700. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-29T19:15:01+00:00, last15m_closed_end=2026-10-29T19:15+00:00, prior8high=0.133760, depth_time=2026-10-29T19:15:22+00:00, book20_bid_proxy_usdt=49276, book20_ask_proxy_usdt=65392, funding_indicative=0.000050, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.34%, turnover=10664341. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-29T19:15:01+00:00, last15m_closed_end=2026-10-29T19:15+00:00, prior8high=0.182600, depth_time=2026-10-29T19:15:30+00:00, book20_bid_proxy_usdt=1380236, book20_ask_proxy_usdt=922020, funding_indicative=0.000100, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.84%, turnover=9411471. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-29T19:15:01+00:00, last15m_closed_end=2026-10-29T19:15+00:00, prior8high=4.598000, depth_time=2026-10-29T19:15:12+00:00, book20_bid_proxy_usdt=2898589, book20_ask_proxy_usdt=4234750, funding_indicative=0.000100, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.59%, turnover=111843512. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-29T19:15:01+00:00, last15m_closed_end=2026-10-29T19:15+00:00, prior8high=0.426900, depth_time=2026-10-29T19:15:42+00:00, book20_bid_proxy_usdt=2153488, book20_ask_proxy_usdt=1528933, funding_indicative=0.000050, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.51%, turnover=23280535. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-29T19:15:01+00:00, last15m_closed_end=2026-10-29T19:15+00:00, prior8high=0.113160, depth_time=2026-10-29T19:15:37+00:00, book20_bid_proxy_usdt=100530, book20_ask_proxy_usdt=111771, funding_indicative=0.000006, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.68%, turnover=6747048. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-29T19:15:01+00:00, last15m_closed_end=2026-10-29T19:15+00:00, prior8high=0.007978, depth_time=2026-10-29T19:15:14+00:00, book20_bid_proxy_usdt=262539, book20_ask_proxy_usdt=315628, funding_indicative=0.000050, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.21%, turnover=6703739. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-29T19:15:01+00:00, last15m_closed_end=2026-10-29T19:15+00:00, prior8high=197.170000, depth_time=2026-10-29T19:15:27+00:00, book20_bid_proxy_usdt=63041, book20_ask_proxy_usdt=94191, funding_indicative=-0.000092, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.90%, turnover=63059223. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-29T19:15:01+00:00, last15m_closed_end=2026-10-29T19:15+00:00, prior8high=0.039050, depth_time=2026-10-29T19:15:10+00:00, book20_bid_proxy_usdt=66704, book20_ask_proxy_usdt=58422, funding_indicative=0.000026, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-6.30%, turnover=25190617. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-29T19:15:01+00:00, last15m_closed_end=2026-10-29T19:15+00:00, prior8high=0.053050, depth_time=2026-10-29T19:15:39+00:00, book20_bid_proxy_usdt=276129, book20_ask_proxy_usdt=265075, funding_indicative=0.000069, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.55%, turnover=5350708. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-10-29T19:15:02+00:00, last15m_closed_end=2026-10-29T19:15+00:00, prior8high=1.707000, depth_time=2026-10-29T19:15:22+00:00, book20_bid_proxy_usdt=2288780, book20_ask_proxy_usdt=1707072, funding_indicative=0.000041, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.05%, turnover=6305797. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-29T19:15:01+00:00, last15m_closed_end=2026-10-29T19:15+00:00, prior8high=0.434000, depth_time=2026-10-29T19:15:19+00:00, book20_bid_proxy_usdt=2898239, book20_ask_proxy_usdt=4621508, funding_indicative=0.000019, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.60%, turnover=82911024. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
