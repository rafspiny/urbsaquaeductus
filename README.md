# Docker images for Gentoo repository checkers

## History

Testing your ebuilds on the CI have always been, in the best case, clumsy.
You had to create a standard ubuntu docker image, spin it up and hack up tools like repoman.

For more details, take a look at [the way](https://github.com/rafspiny/enlightenment-live/blob/d0c09eec27f9fbd6f51fff2e1319ca3448685ec5/.travis.yml) it was done.

Being a bit tired of this, I looked for a gentoo docker image, so that one can just run it in his own _'natural'_ environment.

You can find the docker images here: https://hub.docker.com/urbsaquaeductus 

## Available images

**Notice**: repoman has been deprecated in the 2022. So here you can find a docker iamge with pkgcheck too.

| Version | repoman             | pkgcheck            |
| ------- | ------------------- | ------------------- |
| 1.0     | :white_check_mark:  | :x:                 |
| 2.0     | :white_check_mark:  | :x:                 |
| 3.0     | :x:                 | :white_check_mark:  |

