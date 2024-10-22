# DeadlineAPI - Website


## Install Locally

Install [Lektor](https://pypi.org/project/Lektor/):
```
pip install Lektor
```

Then run  
```
lektor server -f scsscompile
```
to start the lektor build process.

## Run via Docker

The webpage runs in docker:
```bash
docker build .
```

## Contribute
In case you found any error or bug or if you just want to enhance the website, please make PullRequest and use the GitFlow approach. Small changes can be directly merged in `develop`. For bigger changes please use `feature/yourFeature` branches.


## Credits
Many credits got to [SpaceAPI](http://spaceapi.io) for the website template and most of the source. We simply adapted the content basically
