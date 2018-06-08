# should-treeshake-mui

Should TreeShake MUI with Next.js?

Yes! You should to save few kilobytes

The Example used here was gotten from https://github.com/mui-org/material-ui/blob/master/examples/nextjs/, and it shows how to properly remove unused code.

### What % difference?

Initial is the slightly almost the same when not importing multiple exports from the modules.

| Packages(s)  | Before | After | Percentage Gain |
| ------------ | ------ | ----- | --------------- |
| @material-ui | 679kb  | 421kb | 62% gain        |
| mui+icons    | 905kb  | 427kb | 47% gain        |

# License

CC0
