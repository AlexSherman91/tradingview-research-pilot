# Research notebook — working prototype

[Open the prototype](https://alexsherman91.github.io/tradingview-research-pilot/?v=4)

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

## Native page entry previews

The product pages retain their original layouts through reference screenshots with small HTML entry controls. Supercharts uses the user-provided screen; the other pages use captured TradingView screens. The added entry and the notebook are interactive. The underlying chart, quotes and product controls are static references, not live replicas.

- [Supercharts / Watchlist](https://alexsherman91.github.io/tradingview-research-pilot/?surface=chart&v=4): a small notebook icon in the right vertical toolbar, at the watchlist row level. Clicking it opens a compact 224 px research widget with notebook and observation links. Escape, the close button or an outside click dismisses it.
- [Financials](https://alexsherman91.github.io/tradingview-research-pilot/?surface=financials&v=4): small Research action beside the existing heading. Click the existing Statements control to reach the [metric-row preview](https://alexsherman91.github.io/tradingview-research-pilot/?surface=financials&v=4&detail=statement), where Add to research captures Total revenue and the comparison period.
- [Filings](https://alexsherman91.github.io/tradingview-research-pilot/?surface=filings&v=4): small notebook action in the annual report card’s existing action row.
- [Company overview](https://alexsherman91.github.io/tradingview-research-pilot/?surface=overview&v=4): small Research action beside the existing chart actions.
- [Screener](https://alexsherman91.github.io/tradingview-research-pilot/?surface=screener&v=4): a small Research action in the selected company’s existing details header; no replacement table or new research column.

These visual placements cover AAPL. For other research companies, the prototype links to the correct live product and offers the AAPL placement preview, rather than mislabelling AAPL screenshots. A source-return link stays available inside the notebook. Returning from metric capture restores the same statement preview.

The review footer sits outside the product screenshot and provides links between prototype scenes and an optional entry highlight.

## Scope and limits

This is a product case concept, not the current TradingView interface. It contains no live market-data connection, automatic import, account sync, calendar integration, notifications or AI. A review date is a field in the document. Browser storage is local; clearing it removes saved research. Export keeps a portable copy. Source URLs point to product pages; exact document passages or chart ranges are recorded manually.

Sample entries are explicitly labelled. They are not verified financial findings or investment recommendations. Saving or adding a record does not automatically validate a research question.

Legacy links `?step=1` through `?step=6` remain valid as section links.

[Overview of the workspace and entry concepts](https://alexsherman91.github.io/tradingview-research-pilot/overview.html)

The homepage background video and poster are loaded from TradingView’s public asset CDN. The Financials image is an original TradingView screenshot from the interface audit.
