# PackageID:

## 0x9b67152ee61589d72f1aa39570b41f8c5999e2f2b5c6fdf77225d2d3b2b8183f


This project was built on `Devnet` so there's a chance that at the time you are viewing this, it has already wiped.

To begin, create a new folder on your system titled react-e2e-counter to hold all your project files. You can name this directory differently, but the rest of the guide references this file structure. Inside that folder, create two more folders: move and src. Inside the move folder, create a counter directory (By running `sui move new counter`). Finally, open the counter.move file inside the sources folder and populate it with the code from [here](https://github.com/FavourEjiogu/react-e2e-counter/blob/main/move/counter/sources/counter.move) . Different projects have their own directory structure, but it's common to split code into functional groups to help with maintenance. See [Write a Move Package](https://docs.sui.io/guides/developer/first-app/write-package) to learn more about package structure and how to use the Sui CLI to scaffold a new project.

Now, you can run `sui move build` & `sui client publish`

Make sure you copy the packageID, because it'll be very important when building the front-end

For a full guide on how to build a simple  front-end for testing from scratch, visit this
[guide](http://docs.sui.io/guides/developer/app-examples/e2e-counter#frontend).