# MMTrade Status Page

Status page for all MMTrade services.

## Getting started

It’s pretty easy to get started with Statusfy. Install it globally with npm:

***Make sure you have [npx][npx] installed (npx is shipped by default since [npm][npm] 5.2.0)***

``` bash
# change the working directory
cd existing_folder

# run the initialization command
npx statusfy init

# and install your local dependencies
npm install  # OR yarn install
```

Create a new incident with this command:

``` bash
npm run new-incident # OR yarn new-incident
```

and launch the development server with:

``` bash
npm run dev # OR yarn dev
```

You can also generate a Static Generated Website with:

``` bash
npm run generate # OR yarn generate
```

or generate a Server Rendered Website with:

``` bash
# generate static assets
npm run build # OR yarn build

# launch the server
npm run start # OR yarn start
```

[npx]: https://www.npmjs.com/package/npx
[npm]: https://www.npmjs.com/get-npm