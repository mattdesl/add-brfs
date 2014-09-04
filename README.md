# add-brfs

[![stable](http://badges.github.io/stability-badges/dist/stable.svg)](http://github.com/badges/stability-badges)

Adds [brfs](https://github.com/substack/brfs) as a browserify transform to your package.json, if it isn't already listed.

```npm install add-brfs -g```

Then, in the directory of the module you want to use brfs:

`add-brfs`

This will prepend `brfs` to the list of transforms for your current directory's package.json.


Alternatively:

`add-brfs --install`

The `--install` or `-i` flag will also install the `brfs` module and `--save` it as a dependency.

You can use `--append` to append it to the list of browserify transforms instead of prepend. You can also use `--dir` to specify a different directory than the current working directory to look for package.json (however, installing is still done in current directory).

## Usage

[![NPM](https://nodei.co/npm/add-brfs.png)](https://nodei.co/npm/add-brfs/)

```
Usage:
	add-brfs [opts]

Options:
  -h            show help message                     
  -d, --dir     the directory to look for package.json
  -a, --append  adds brfs at end of transform list    
  -i, --i       also install the latest brfs with --save flag
```

## License

MIT, see [LICENSE.md](http://github.com/mattdesl/add-brfs/blob/master/LICENSE.md) for details.
