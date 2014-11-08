How to start
============
1. `git clone https://github.com/Kottans/bootstrap-starter-kit.git my-bp-project && cd $_ && rm -rf .git` - to get this source locally & delete .git folder, thus making it a simple folder
2. `npm run setup` - install bower dependencies, inital build
3. `npm run dev` - run gulp watcher, static server & open page in browser. In case you need to change port/hostname, be sure to edit [gulpfile](https://github.com/Kottans/bootstrap-starter-kit/blob/master/gulpfile.js#L12-L13)


Credits
=======
All the kudos should go to:  
  + [@ericlbarnes](https://twitter.com/ericlbarnes) and his [post](http://ericlbarnes.com/setting-gulp-bower-bootstrap-sass-fontawesome)
  + [@chrisltd](https://twitter.com/chrisltd) and his [post](http://chrisltd.com/blog/2014/07/gulp-server-livereload/)
  + [divshot/bootstrap-theme-white-plum](https://github.com/divshot/bootstrap-theme-white-plum)