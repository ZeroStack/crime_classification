#San Francisco Crime Classification

## Global Settings

```r
# Set global options

# Print all commands
echo = TRUE

# Set working directory to parent
this.dir <- dirname(parent.frame(2)$ofile)
```

```
## Error in dirname(parent.frame(2)$ofile): a character vector argument expected
```

```r
setwd(this.dir)
```

```
## Error in setwd(this.dir): object 'this.dir' not found
```

```r
print(this.dir)
```

```
## Error in print(this.dir): object 'this.dir' not found
```

## Initial Data Exploration


