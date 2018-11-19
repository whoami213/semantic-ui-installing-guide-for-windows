Download nodejs for windows 
https://nodejs.org/dist/v11.2.0/node-v11.2.0-x64.msi

Download Semantic-UI (Clone or Download as zip)
https://github.com/Semantic-Org/Semantic-UI

Copy the Semantic-UI to your sites

After installing Node, Gulp can be installed globally using Node Package Manager (NPM)
shift + right-click to the Semantic-UI Folder, select >> ``` Open Command Windows here ```

```cmd
npm install -g gulp
````
after finished the installation of gulp

rename ``` semantic.json.example``` to ```semantic.json```
 ``` src/theme.config.example ``` to ``` src/theme.config```
 ``` src/_site``` to ``` src/site```
after renamed then type
```
gulp build
```
in cmd to build with the themes

```
gulp watch
```
## End

# Gulp commands
After setting up your project you have access to several commands for building your css and javascript.

``` gulp ``` # runs default task (watch)

``` gulp watch ``` # watches files for changes

``` gulp build ``` # builds all files from source

``` gulp install ``` # re-runs install
