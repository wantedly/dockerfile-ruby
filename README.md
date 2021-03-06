# Ruby for Ubuntu [![](https://quay.io/repository/wantedly/ruby/status)](https://quay.io/repository/wantedly/ruby)
This Dockerfile is ported from debian's official ruby image to Ubuntu.
For more information about this, please see [official one's README](https://github.com/docker-library/ruby).

![](https://raw.githubusercontent.com/docker-library/docs/master/ruby/logo.png)

## SUPPORTED TAGS

* [`2.0.0-p598`](2.0/Dockerfile)
* [`2.1.5`](2.1/Dockerfile)
* [`2.2.0`](2.2/Dockerfile)

## HOW TO USE
Create a `Dockerfile` in your Ruby app project

```
FROM quay.io/wantedly/ruby:2.2.0
CMD ["./your-daemon-or-script.rb"]
```

## LICENSE
[![MIT License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat)](LICENSE)
