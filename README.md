# ISO 8601 TimeNow

Get the current Date and Time in ISO 8601 format. A timestamp!

## How to run

The first step in running this is to install all the dependencies. Without the dependencies, the code will not run. Run the following command to install all the dependencies:
```bash
npm install
```
The dependencies used are [node-jsonfile](https://github.com/jprichardson/node-jsonfile) which is used to direct the timestamp to the [`data.json` file](/data.json) and [moment](https://github.com/moment/moment) which is used to get the date and time (timestamp). So incase the dependencies don't get downloaded with `npm install`, you can induvidually install both dependencies.
```bash
npm i jsonfile
npm i moment
```

After you have installed the dependencies, all you need to do is run the [`index.js` file](/index.js).
```bash
node index.js
```
Once you have ran the [`index.js` file](/index.js), open the `data.json` file and you will see that you have the timestamp in that file. The timestamp will also be logged in your console.

## Acknowldgements

Thanks to the makers of the [dependencies](https://github.com/TheYoBots/ISO-8601-TimeNow/network/dependencies) used in this repository!