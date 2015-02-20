gulp-less-to-scss
=======
A gulp plugin convert less files to scss files

Usage
-------

```javascript
var scssToLess = require('gulp-scss-to-less');
gulp.task('scssToLess',function(){
    gulp.src('themes/system/scss/*.scss')
		.pipe(scssToLess())
		.pipe(gulp.dest('themes/system/less'));
});
```

Notice
-------
This plugin cannot handle with 'when' statement.

LICENSE
-------

(MIT License)
