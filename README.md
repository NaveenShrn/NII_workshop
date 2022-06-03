# NII_workshop


```{R Basics}
hello <- function(){
  print('Hello World')
}
```

## Excercise_Week2
1. Why does this code not work?
```{R}
# The names of the fundamental functions- commonly used in R programming cannot be used as object names. The line of code can be run if we change the object name as follows-
my_fav_pathway <- c('IL6','LINC','OAS1')
my_fav_pathway
```
2.  Write an R code to create a character vector of your favorite pathway.
```{R}
nk_autophagy <- c('RAB1A', 'ATG13','PIK3C3', 'ATG14', 'ATG101', 'PIK3R4', 'WIPI1', 'WIPI2', 'ZFYVE1', 'ULK1', 'RB1CC1')
nk_autophagy

# source- https://www.genome.jp/entry/N00155
``` 
3. Write two vectors- numerical and character, and compile them in a dataframe.
```{R}
genes <- c('Nfkb2', 'Relb', 'Nfkbia', 'Map3k14', 'Rel')
genes
expr_values <- c(15, 21, 9, 17, 11)
expr_values

#create a dataframe from the two vectors
nk_genes <- data.frame(genes= c('Nfkb2', 'Relb', 'Nfkbia', 'Map3k14', 'Rel'),
+ expr_values= c(15, 21, 9, 17, 11))
print(nk_genes)
```
