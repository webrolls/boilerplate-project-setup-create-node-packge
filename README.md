# project-setup-for-creating-node-packges
Boilerplate project for creating node package using nodejs

This is node boilerplate project setup to kick start your node package development using nodejs.


Issues you might face

<pre>
c:\projects\boilerplate-project-setup-create-node-packge>npm run build
> modern-javascript-project-setup@1.0.0 build c:\projects\boilerplate-project-setup-create-node-packge
> webpack-dev-server --progress --watch

'webpack-dev-server' is not recognized as an internal or external command,
operable program or batch file.
npm ERR! code ELIFECYCLE
npm ERR! errno 1
npm ERR! modern-javascript-project-setup@1.0.0 build: `webpack-dev-server --progress --watch`
npm ERR! Exit status 1
npm ERR!
npm ERR! Failed at the modern-javascript-project-setup@1.0.0 build script.
npm ERR! This is probably not a problem with npm. There is likely additional logging output above.

npm ERR! A complete log of this run can be found in:
npm ERR!     C:\Users\kkhan\AppData\Roaming\npm-cache\_logs\2017-08-08T19_44_56_463Z-debug.log
</pre>

To resolve above issue while runnimg 'npm tun build' I just installed webpack and webpack-dev-server again and it fixed the problem for me.
<pre>
npm install -g webpack --save-dev
npm install -g webpack-dev-server --save-dev
</pre>

~webrolls
