 [![Build Status](https://secure.travis-ci.org/chrisfjones/coffin.png)](http://travis-ci.org/chrisfjones/coffin)

### Run coffin with Docker container
```
docker build -t coffin . 
docker run -ti --rm -v $(pwd)/examples:data coffin print demo.coffin
```
