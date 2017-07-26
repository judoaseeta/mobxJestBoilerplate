# mobxJestBoilerplate

### why did i make this?

create-react-app-ts https://github.com/wmonk/create-react-app-typescript has provided us simple and easy way to initialize 
typescript-based react app. 

However, when you do unittest your app using bunches of mobx decorator function, it will make some errorr.
This is because react-scripts-ts has it own configuration and it collides with our app.

This boilerplate is shipped with following features.

* Jest configuration in package.json
  * transform TSX and other media files.
  * provides coverages
  * snapshot UI test.
  * modulename mapping for CSS.

