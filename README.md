# Calendar API

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A user friendly SDK & API that returns a list of calendar dates for a given year in JSON format. Built with [day.js](https://day.js.org/) & typescript.

> Hey, we're just getting started & are actively seeking contributors & maintainers. If you'd like to get involed feel free to reach out in any open issue, or via email 6matbub@gmail.com. 🙂</br>
> \- TY, Mat


### On this page
- [Useage](#usage)
- [Contributing](#contributing)
- [This repo](#this-repo)

## Usage

### Via Nodejs

```shell
npm install @whilethiscompiles/calendar
```

```js
const {calendar} = require('@whilethiscompiles/calendar')
calendar(1999); // {january:{count:31,collection:{'1':'1999-1-01','2':'1999-1-02','3':'1999-1-03','4':'1999-1-04','5':'1999-1-05','6':'1999-1-06','7':'1999-1-07','8':'1999-1-08','9':'1999-1-09','10':'1999-1-10','11':'1999-1-11','12':'1999-1-12','13':'1999-1-13','14':'1999-1-14','15':'1999-1-15','16':'1999-1-16','17':'1999-1-17','18':'1999-1-18','19':'1999-1-19','20':'1999-1-20','21':'1999-1-21','22':'1999-1-22','23':'1999-1-23','24':'1999-1-24','25':'1999-1-25','26':'1999-1-26','27':'1999-1-27','28':'1999-1-28','29':'1999-1-29','30':'1999-1-30','31':'1999-1-31'}},february:{count:28,collection:{'1':'1999-2-01','2':'1999-2-02',....
```

### Via HTTP

A public endpoint is available via the GET method & accepts 1 query paramter `year=YYYY` returns a JSON response

```
https://calendar.whilethiscompiles.com/api/calendar?year=YYYY
```

## Contributing
- [Open Issues](https://github.com/yeahmat/calendar/issues?q=is%3Aissue+is%3Aopen)
- [Sprint Planning](https://github.com/yeahmat/calendar/projects/1)
- [Internal Docs](https://github.com/yeahmat/calendar/wiki)

This project was build entirely with GitHub's Codespaces & VSCode. 

## This repo
- `/lib/calendar` - NPM Package
- `/lib/calendar-tests` - Test suites for calendar as a package
- `/lib/developer` - Landing page, public API, documentation. Built with Next.js
