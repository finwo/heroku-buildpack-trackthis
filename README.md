Heroku buildpack: trackthis
===========================

[![Codetree](https://codetree.com/images/managed-with-codetree.svg)](https://codetree.com/projects/gX1r)

This is a custom [Heroku buildpack](https://devcenter.heroku.com/articles/buildpacks) for our [trackthis](https://github.com/ratus/trackthis) project.

#### Heroku toolchain
```sh
heroku buildpacks:add "https://github.com/finwo/heroku-buildpack-trackthis.git"
```

#### `.buildpacks` file

```sh
echo "https://github.com/finwo/heroku-buildpack-trackthis.git" >> /path/to/app/.buildpacks
```

## Contributing

First, look at the [issues page](https://github.com/finwo/heroku-buildpack-extra/issues) to ensure your issue isn't already known. If it's not, you can create a new issue with a detailed description of what happened & how to reproduce the unexpected behavior.

If you decide to take on the challenge of fixing a known (or unknown) issue, you can do so by sending in a pull request from your own fork of the project. Once it has been tested and approved, it will be merged into the master branch of the repository.

## License

Copyright (c) 2018 Ratus B.V.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
