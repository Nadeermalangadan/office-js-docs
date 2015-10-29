# BreakType (JavaScript API for Word) 
The following are the supported break types on the API.

| Value         | Description     |
|:-----------------|:--------|
|column| Column break at the insertion point. |
|line| Line break. |
|lineClearLeft|  Line break. |
|lineClearRight|Line break. |
|next| Section break on next page. |
|page| Page break at the insertion point.|
|sectionContinuous| New section without a corresponding page break.|
|sectionEven| String | Section break with the next section beginning on the next even-numbered page. If the section break falls on an even-numbered page, Word leaves the next odd-numbered page blank.|
|sectionOdd| String | Section break with the next section beginning on the next odd-numbered page. If the section break falls on an odd-numbered page, Word leaves the next even-numbered page blank.|
|textWrapping| String | Ends the current line and forces the text to continue below a picture, table, or other item. The text continues on the next blank line that does not contain a table aligned with the left or right margin.|


## Support details

MD table without header

|**Available in requirement sets** | WordApi, 1.1|
|**Minimum permission level** | [ReadWriteDocument](https://msdn.microsoft.com/EN-US/library/office/jj220081.aspx)|
|**Add-in types** | Task pane|
|**Library** | Office.js|