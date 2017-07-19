# Poster template for SAIL

![Poster snapshot]
(./images/Snapshot.png)

## Brief Description
This is a template for posters for SAIL. It is an adaptation from [a0poster](https://www.ctan.org/pkg/a0poster?lang=en), with custom coloring and logos. 

## Usage
Modify the content block to your heart's content.

You can add a new column as follows:
```
	\begin{minipage}[t]{col_width}
		%column content
	\end{minipage}
```
where `col_width` is the size of column.

Add a new section (i.e., colored box) using 
```
	\begin{Section}{TITLE}{
		%Section content
	}\end{Section}
```

TODO:
	- Transform it into a template
	- Manage author definition would be nice
	- Many things more ...