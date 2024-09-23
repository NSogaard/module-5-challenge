# Challenge #5 README
## Consulted Code Sources
The only code that I consulted this week (other than my notes and the pandas / matplotlib / scipy documentation) was from the following post on StackOverflow:

https://stackoverflow.com/questions/25075023/matplotlib-boxplot-outlier-color-change-if-keyword-sym-is-used

I used this article to find out how to change the color of outliers in a boxplot (the 'sym' parameter) - this code was used in the following code snippet (which generates the boxplot):

```python
plot_values.plot(
    kind="box",
    by="Drug Regimen",
    sym="r"
)
```

I marked off the relevant code segment with the "BorrowedCodeFlag1" flag added as a comment.