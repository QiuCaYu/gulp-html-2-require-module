# gulp-html-2-require-module
基于package gulp-html-2-require-module的修改，给require所需要的html进行模块化打包

#### 先安装 cnpm install gulp-html-2-require-module

#### 下载index.js把原目录的index.js覆盖即可

#### 使用说明

> 参数:fileName 文件名称

```

var gulphtml2requiremodule = require('gulp-html-2-require-module');

gulp.src([
      './view/**/*.html',
])
.pipe(gulphtml2requiremodule('allHtml2.js'))
.pipe(gulp.dest('./dist/html'));

### result
  ./dist/html/allHtml.js
  
  
  
 ```
