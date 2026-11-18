# Research notebook

The prototype contains the company Research side panel and standalone company workspace. Open https://alexsherman91.github.io/tradingview-research-pilot/?surface=chart&symbol=AAPL&panel=research.

Six freely accessible sections cover Goal, optional Approach, Evidence, Reasoning, Challenges, and Conclusion. Research is stored in the browser, with separate company documents and JSON export.

## Evidence and reasoning

Observations retain their period, source and optional research question. Missing periods and missing or invalid HTTP/HTTPS sources are flagged beside the observation and in Conclusion. These checks concern metadata completeness. Users assess source reliability themselves.

In Reasoning, select multiple observations to view their periods, text and sources side by side. Missing or different period labels prompt a comparability check. Matching labels still require the user to check definitions and units. An argument created from the comparison starts with the selected evidence linked.

## Thesis review

Draft edits save automatically. Save thesis version creates a separate snapshot of the thesis, limitations, revision conditions, review date, goal, approach, questions, evidence and arguments.

Each subsequent version requires a review reason. Users may link the evidence that informed their review. The current draft is compared with the latest saved version, including added, updated and removed evidence. History retains the source records as they existed in each version, including records subsequently edited or removed. JSON export includes these snapshots and review links.

Existing browser documents remain readable. If the new workspace has no saved data, it reads research from the previous prototype storage. History begins with the first explicitly saved version.

## Scope

The interactive Research panel opens beside static TradingView reference screens. Product previews use AAPL. A standalone workspace supports AAPL, MSFT and NVDA. There is no live market-data import, automatic period matching, account sync or reminder delivery. The review date is stored in the research document.

The existing research rail icon retains its permanent red dot. All research actions remain within the side panel when opened from a product reference.
