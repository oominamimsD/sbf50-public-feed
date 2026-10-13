# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T14:15:42Z**
- feed_generated_utc: 2026-10-13T14:15:46+00:00
- source_sha256: `01a6834cc05f45ca8de5e618d5cd6211220db7f9cef10172d5b8e6f0f4d120df`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 18; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T14:15+00:00, close=83649.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-13T14:00+00:00, close=83232.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T12:00+00:00, close=83325.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|W_USDT|0.018193|-24.38|28.63|-25.56|14662038|7.14|
|DOS_USDT|0.219200|-24.28|2.91|-25.46|9462110|9.12|
|ZRO_USDT|2.027400|-10.33|-0.88|-11.51|17130125|1.48|
|NEAR_USDT|5.099000|-8.10|1.53|-9.28|278278885|1.96|
|QNT_USDT|210.230000|-7.94|-18.12|-9.12|91067835|2.85|
|RLC_USDT|0.911800|-7.76|66.38|-8.94|6407439|1.10|
|PYTH_USDT|0.082110|-7.36|7.60|-8.54|9479581|1.22|
|LIT_USDT|3.382600|-6.69|-11.03|-7.87|8062960|0.29|
|USELESS_USDT|0.171240|-5.70|-24.48|-6.88|5990237|1.75|
|ONDO_USDT|0.471400|-5.36|-3.55|-6.54|66026157|2.12|
|GRASS_USDT|0.709100|-5.07|0.55|-6.25|5414551|1.41|
|SEI_USDT|0.063100|-4.92|-12.25|-6.10|10265132|1.58|
|PUMPFUN_USDT|0.005050|-4.87|-20.28|-6.05|34633826|1.98|
|JUP_USDT|0.328900|-4.08|-2.66|-5.26|8627698|3.04|
|STRK_USDT|0.087840|-3.12|68.56|-4.30|53886455|1.14|
|MAGIC_USDT|0.119330|-2.15|92.49|-3.33|7964514|0.84|
|SILVER_USDT|59.850000|-0.86|-2.23|-2.04|185635858|1.67|
|XAUT_USDT|4166.490000|0.07|0.71|-1.11|180282423|0.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOS_USDT|0.219200|0.216900|0.219200|1.45|N|Y/Y|Y/Y|N|N|
|GRASS_USDT|0.709100|0.697900|0.708800|1.05|N|Y/Y|Y/N|N|N|
|JUP_USDT|0.328900|0.321900|0.328900|0.99|N|Y/Y|Y/Y|N|N|
|LIT_USDT|3.382600|3.280300|3.382600|0.72|N|Y/Y|Y/Y|N|N|
|NEAR_USDT|5.099000|4.968000|5.100000|1.13|N|Y/Y|Y/Y|N|N|
|ONDO_USDT|0.471400|0.461100|0.471100|0.90|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.005050|0.004859|0.005051|0.72|N|Y/Y|Y/Y|N|N|
|PYTH_USDT|0.082110|0.081060|0.082110|0.34|N|Y/Y|N/N|N|N|
|QNT_USDT|210.230000|201.440000|209.810000|1.14|N|Y/Y|Y/Y|N|N|
|RLC_USDT|0.911800|0.896200|0.911800|1.33|N|Y/Y|Y/Y|N|N|
|SEI_USDT|0.063100|0.061440|0.063120|0.51|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.087840|0.086240|0.087840|1.02|N|Y/Y|Y/Y|N|N|
|USELESS_USDT|0.171240|0.164040|0.171240|0.54|N|Y/Y|Y/Y|N|N|
|W_USDT|0.018193|0.018040|0.018191|2.27|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|2.027400|2.003400|2.027400|0.31|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOS_USDT: quote_utc=2026-10-13T14:15:01+00:00, last15m_closed_end=2026-10-13T14:15+00:00, prior8high=0.222600, depth_time=2026-10-13T14:15:10+00:00, book20_bid_proxy_usdt=86751, book20_ask_proxy_usdt=97252, funding_indicative=0.000050, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-24.28%, turnover=9462110. target_RR/account_short_permission/settled_funding=UNKNOWN.
- GRASS_USDT: quote_utc=2026-10-13T14:15:01+00:00, last15m_closed_end=2026-10-13T14:15+00:00, prior8high=0.721000, depth_time=2026-10-13T14:15:32+00:00, book20_bid_proxy_usdt=69027, book20_ask_proxy_usdt=175088, funding_indicative=0.000050, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.07%, turnover=5414551. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-13T14:15:02+00:00, last15m_closed_end=2026-10-13T14:15+00:00, prior8high=0.330000, depth_time=2026-10-13T14:15:38+00:00, book20_bid_proxy_usdt=297323, book20_ask_proxy_usdt=391113, funding_indicative=-0.000044, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.08%, turnover=8627698. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-13T14:15:02+00:00, last15m_closed_end=2026-10-13T14:15+00:00, prior8high=3.395500, depth_time=2026-10-13T14:15:24+00:00, book20_bid_proxy_usdt=27311, book20_ask_proxy_usdt=20701, funding_indicative=0.000050, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.69%, turnover=8062960. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-13T14:15:01+00:00, last15m_closed_end=2026-10-13T14:15+00:00, prior8high=5.124000, depth_time=2026-10-13T14:15:14+00:00, book20_bid_proxy_usdt=348672, book20_ask_proxy_usdt=3267161, funding_indicative=0.000000, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.10%, turnover=278278885. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-13T14:15:01+00:00, last15m_closed_end=2026-10-13T14:15+00:00, prior8high=0.471600, depth_time=2026-10-13T14:15:29+00:00, book20_bid_proxy_usdt=1534696, book20_ask_proxy_usdt=1525055, funding_indicative=-0.000074, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.36%, turnover=66026157. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-13T14:15:01+00:00, last15m_closed_end=2026-10-13T14:15+00:00, prior8high=0.005056, depth_time=2026-10-13T14:15:36+00:00, book20_bid_proxy_usdt=703479, book20_ask_proxy_usdt=1236710, funding_indicative=0.000005, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.87%, turnover=34633826. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-13T14:15:02+00:00, last15m_closed_end=2026-10-13T14:15+00:00, prior8high=0.083930, depth_time=2026-10-13T14:15:22+00:00, book20_bid_proxy_usdt=98243, book20_ask_proxy_usdt=167936, funding_indicative=-0.000019, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.36%, turnover=9479581. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-13T14:15:01+00:00, last15m_closed_end=2026-10-13T14:15+00:00, prior8high=207.320000, depth_time=2026-10-13T14:15:17+00:00, book20_bid_proxy_usdt=56425, book20_ask_proxy_usdt=58174, funding_indicative=-0.000210, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-7.94%, turnover=91067835. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T14:15:01+00:00, last15m_closed_end=2026-10-13T14:15+00:00, prior8high=0.928800, depth_time=2026-10-13T14:15:19+00:00, book20_bid_proxy_usdt=58895, book20_ask_proxy_usdt=45587, funding_indicative=-0.000536, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.76%, turnover=6407439. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-13T14:15:02+00:00, last15m_closed_end=2026-10-13T14:15+00:00, prior8high=0.063190, depth_time=2026-10-13T14:15:34+00:00, book20_bid_proxy_usdt=78308, book20_ask_proxy_usdt=194244, funding_indicative=0.000061, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.92%, turnover=10265132. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T14:15:01+00:00, last15m_closed_end=2026-10-13T14:15+00:00, prior8high=0.090860, depth_time=2026-10-13T14:15:41+00:00, book20_bid_proxy_usdt=172584, book20_ask_proxy_usdt=221938, funding_indicative=0.000034, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.12%, turnover=53886455. target_RR/account_short_permission/settled_funding=UNKNOWN.
- USELESS_USDT: quote_utc=2026-10-13T14:15:02+00:00, last15m_closed_end=2026-10-13T14:15+00:00, prior8high=0.171590, depth_time=2026-10-13T14:15:27+00:00, book20_bid_proxy_usdt=13112, book20_ask_proxy_usdt=13694, funding_indicative=0.000059, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.70%, turnover=5990237. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-13T14:15:01+00:00, last15m_closed_end=2026-10-13T14:15+00:00, prior8high=0.018854, depth_time=2026-10-13T14:15:08+00:00, book20_bid_proxy_usdt=45420, book20_ask_proxy_usdt=41080, funding_indicative=-0.000398, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-24.38%, turnover=14662038. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-13T14:15:01+00:00, last15m_closed_end=2026-10-13T14:15+00:00, prior8high=2.072500, depth_time=2026-10-13T14:15:13+00:00, book20_bid_proxy_usdt=28422, book20_ask_proxy_usdt=29936, funding_indicative=-0.000004, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.33%, turnover=17130125. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
