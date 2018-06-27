[How to build a library for Angular apps?](https://medium.com/@tomsu/how-to-build-a-library-for-angular-apps-4f9b38b0ed11)
<pre>
git clone https://github.com/panicoenlaxbox/tvmaze.git
cd app1
npm install
cd ..
cd lib-demo
npm install
ng build tvmaze --prod
npm start
do some change in the library...
update lib-demo\projects\tvmaze\package.json to a newer version
ng build tvmaze --prod
cd dist\tvmaze
npm whoami
npm login
npm publish --access public
cd ..
cd ..
cd ..
cd app1
npm i @panicoenlaxbox/tvmaze --save
npm start
</pre>
