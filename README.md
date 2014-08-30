# add-brfs

[![stable](http://badges.github.io/stability-badges/dist/stable.svg)](http://github.com/badges/stability-badges)

Adds [brfs](https://github.com/substack/brfs) as a browserify transform to your package.json, if it isn't already listed.

```npm install add-brfs -g```

Then, in the directory of the module you want to use brfs:

`add-brfs`

This will prepend `brfs` to the list of transforms. You can use `--append` to append it instead. You can also use `--dir` to specify a different directory than the current working directory to look for package.json.

## Usage

[![NPM](https://nodei.co/npm/add-brfs.png)](https://nodei.co/npm/add-brfs/)

## License

MIT, see [LICENSE.md](http://github.com/mattdesl/add-brfs/blob/master/LICENSE.md) for details.
