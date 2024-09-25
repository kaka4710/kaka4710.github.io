# 1. 章节的增减

只需要将原先的章节复制了，然后在新的章节中重新编号，并编写整个内容即可。

# 导出文件

```js
library(bookdown)
render_book(input = ".", output_format = 'bookdown::gitbook', clean = TRUE,envir = parent.frame(),
            output_dir = NULL, new_session = NA, preview = FALSE,
            config_file = "_bookdown.yml")

```

这里最重要的修改是output_format,它有三种格式：

- bookdown::gitbook
- bookdown::pdf_book
- bookdown::epub_book

