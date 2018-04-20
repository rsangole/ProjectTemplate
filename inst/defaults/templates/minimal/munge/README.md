Here you can store any preprocessing or data munging code for your project. For example, if you need to add columns at runtime, merge normalized data sets or globally censor any data points, that code should be stored in the `munge` directory. The preprocessing scripts stored in `munge` will be executed sequentially when you call `load.project()`, so you should append numbers to the filenames to indicate their sequential order.