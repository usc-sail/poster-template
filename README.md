# Poster template for SAIL

![snapshot](/images/Snapshot.png?raw=True "SAIL poster template")

## Brief Description
This is a template for posters for SAIL. It is an adaptation from [latex-beamerposter](https://www.github.com/latex-beamerposter), with custom coloring and logos. 

## Usage
Modify the content block to your heart's content. It can be set up as portrait (as example image) or landscape:

```
\usepackage[orientation=portrait,size=a0,scale=1.4,debug]{beamerposter}
```

You can add a new column as follows:
```
	\begin{column}{0.45\textwidth}
		%column content
	\end{column}
```

We recommend to use sections for clarity as provided in the example.

TODO:

* Manage author definition would be nice
* Many things more ...
