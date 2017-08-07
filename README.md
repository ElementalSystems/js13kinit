# js13kinit
Simple set up for a js13k games entry with mobile boilerplate and  develop and release grunt tasks
Just shows a simple message

to install all the stuff use
npm install

To build a release use:
grunt release
which runs sass (with minify); uglify (with minify); copies extra files and zips the result into a single file (so you can see how you are dong with that 13k limit)

To develop use:
grunt develop
which runs sass (no Minify); uglify (no compress); copies files; launches and local http-server and opens chrome with the page in a tab - it then watches for changes and run tasks as needed to keep the server version up to date
