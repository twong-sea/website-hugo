+++
title = "Table Test with mmark"
date = "2015-10-10T13:07:31+02:00"
tags = []
categories = ["Lorem"]
menu = ""
banner = "banners/placeholder.png"
+++

----------
markup = mmark

---

| | |
|-|-|
| Normal Key| Value1 |
|__BoldKey__| Value2 |

---

|-------------|--------|
|**Name:**    |John Doe|
|**Position:**|CEO     |

---

||     |
|-----|-----|
|Foo  |37   |
|Bar  |101  |

---

[]()  |[]() 
------|------
Row 1 | row 2

---

|Foo  |11   |
|-----|-----|
|Bar  |11   |

---

{table-plus:border=0|class=''}
| header1 | header 2 |
| cell11 | cell 12 | 
| cell 21 | cell 22 |
{table-plus}

- [ ] a task list item
- [ ] list syntax required
- [ ] incomplete
- [x] completed
---

copy paste 

|---
| Default aligned | Left aligned | Center aligned | Right aligned
|-|:-|:-:|-:
| First body part | Second cell | Third cell | fourth cell
| Second line |foo | **strong** | baz
| Third line |quux | baz | bar
|---
| Second body
| 2 line
|===
| Footer row

edited


| Default aligned | Left aligned | Center aligned | Right aligned|
|---|:---|:---:|---:|
| First body part | Second cell | Third cell | fourth cell|
| Second line |foo | **strong** | baz|
| Third line |quux | baz | bar|
|---|
| Second body
| 2 line
|===
| Footer row

---

#### Table

This is a table:

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

You can align cell contents with syntax like this:

| Left Aligned  | Center Aligned  | Right Aligned |
|:------------- |:---------------:| -------------:|
| col 3 is      | some wordy text |         $1600 |
| col 2 is      | centered        |           $12 |
| zebra stripes | are neat        |            $1 |

The left- and right-most pipes (`|`) are only aesthetic, and can be omitted. The spaces don’t matter, either. Alignment depends solely on `:` marks.

------
![GitHub Logo](/images/logo.png)

<style>
table { 
    display: table;
    border-collapse: separate;
    border-spacing: 1px;
    border-color: solid;
}
tbody {
				;}
</style>

<table>
  <tr><td>First column</td><td>Second column</td><td>Third column</td></tr>
  <tr><td>First column</td><td>Second column</td><td>Third column</td></tr>
  <tr><td>First column</td><td>Second column</td><td>Third column</td></tr>
</table>