# nodegulpbabelWindows

Study
Learning Javascript


es6 -> es5


프로젝트구조

#Git
.git
.gitignore

#npm
package.json
node_modules

#노드소스
es6
dist

#브라우저소스
public/
  es6
  dist
  
  

순서
1. node for windows install
2. git bash install
3. mkdir
4. npm init
5. npm install -g gulp (global)
6. npm install --save-dev gulp (project)
7. npm install --save-dev babel-preset-es2015
8. make .babelrc file {"presets":["es2015"]}
9. npm install --save-dev gulp-babel
10. make gulpfile.js (like code)
11. make test.js for es6 dir (like code)
12. gulp (transcomfile es6 -> es5)
