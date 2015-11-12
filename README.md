# Gulp 發佈網頁到 GitHub

class [source](https://github.com/hdngr/treehouse-gulp-ghpages)

使用[gulp-gh-pages](https://www.npmjs.com/package/gulp-gh-pages)

```js

var pages = require('gulp-gh-pages');

gulp.task('deploy', function() {
  return gulp.src(options.dist + '**/*')
             .pipe(pages());
});
```

然後跑`gulp deploy`，再到github上面找branch，就可以看到網站了！

# 問題

* node server 呢？
* react呢？
















