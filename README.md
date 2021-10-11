
# quickopen

<!-- badges: start -->
<!-- badges: end -->

Sometimes you want to quickly view your data. For that there is an addin called `quickview`. But sometimes you need more control than the RStudio viewer and you want to open data in your favorite application. Then there is `quickopen`.

Currently only Linux is supported via xdg.

*Features*

 - Run complete line(s) or selection and open the result in your favorite application.
 - Works with pipes just like `quickview`.
 - Provide a quick command to open your working directory with your file manager.
 
Currently dataframes, matrices and vectors with more than one element will be open with your default CSV viewer.
Vector of length one will be open directly in your default text editor.


## Installation


You can install `quickopen` from GitHub with `remotes`:

``` r
remotes::install_github("fkeck/quickopen")
```
Then you will probably want to assign keyboard shortcuts to the `quickopen` commands. In RStudio use Tools > Addins > Browse Addins > Keyboard shortcuts.

I personally use Ctrl+F11 to open objects and F12 to open my working directory.
