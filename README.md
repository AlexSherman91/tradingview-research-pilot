# Research notebook — working prototype

[Open the prototype](https://alexsherman91.github.io/tradingview-research-pilot/?v=5)

A persistent company research document with six freely accessible sections: **Research brief, Open questions, Evidence, Assessment, Risks & alternatives, Thesis & review**. There is no required sequence, completion score or instructional walkthrough.

## Working interactions

- Small Research entry in the existing top navigation; Products also contains the notebook. The homepage hero is preserved.
- Editable title, research question and time horizon, including a custom horizon.
- Add, edit and remove research questions; manually set assessment status.
- Add, edit, filter and remove evidence with source URL, period and a linked question.
- Link evidence to supporting or challenging assessments, open issues, risks and alternative explanations.
- Edit a working thesis, limitations, invalidation conditions, review date and document status.
- Save locally across reloads; separate documents for AAPL, MSFT and NVDA.
- Undo a removal and export the research as JSON, preserving source links and sample labels.

## Unified research widget across products

All six product previews use the same notebook icon in the right vertical toolbar: Supercharts, Watchlist, Financials, Filings, Company overview and Stock screener. Financials also has a selected-metric state. The icon opens the same compact 224 px widget, with links to the notebook and to add an observation in the current product context.

A small red dot and the tooltip “Research notebook · New” identify the new feature. The dot is dismissed after the first widget or notebook opening and stays dismissed across products and reloads in the same browser. Discovery state is separate from saved research data. If browser storage is unavailable, discovery is remembered for the current page session.

The observation action retains source context: a selected Financials metric and comparison period, the Filings document period, or the current company/product source. A general Financials observation asks the user to enter the period rather than assuming a selected period.

- [Supercharts](https://alexsherman91.github.io/tradingview-research-pilot/?surface=chart&v=5)
- [Watchlist](https://alexsherman91.github.io/tradingview-research-pilot/?surface=watchlist&v=5)
- [Financials](https://alexsherman91.github.io/tradingview-research-pilot/?surface=financials&v=5) and [selected metric](https://alexsherman91.github.io/tradingview-research-pilot/?surface=financials&v=5&detail=statement)
- [Filings](https://alexsherman91.github.io/tradingview-research-pilot/?surface=filings&v=5)
- [Company overview](https://alexsherman91.github.io/tradingview-research-pilot/?surface=overview&v=5)
- [Stock screener](https://alexsherman91.github.io/tradingview-research-pilot/?surface=screener&v=5)

The landing page’s existing Research navigation entry uses the same new-feature indicator. No large promotional card is added.

The product pages retain their original layouts through reference screenshots. Supercharts uses the user-provided screen; the other pages use captured TradingView screens. The added widget and notebook are interactive; the underlying chart, quotes and other product controls are static references. Visual placements cover AAPL. Other company documents link to the correct live product and offer the AAPL placement preview. A source-return link stays available inside the notebook and restores the selected statement state when relevant.

The review footer sits outside the product screenshot and provides links between prototype scenes and an optional entry highlight.

## Scope and limits

This is a product case concept, not the current TradingView interface. It contains no live market-data connection, automatic import, account sync, calendar integration, notifications or AI. A review date is a field in the document. Browser storage is local; clearing it removes saved research. Export keeps a portable copy. Source URLs point to product pages; exact document passages or chart ranges are recorded manually.

Sample entries are explicitly labelled. They are not verified financial findings or investment recommendations. Saving or adding a record does not automatically validate a research question.

Legacy links `?step=1` through `?step=6` remain valid as section links.

[Overview of the workspace and entry concepts](https://alexsherman91.github.io/tradingview-research-pilot/overview.html)

The homepage background video and poster are loaded from TradingView’s public asset CDN. The Financials image is an original TradingView screenshot from the interface audit.
