# CircleCI Docker Image

This auto-building repository is for combining these two images:
```
- image: circleci/golang:1.8
- image: google/cloud-sdk:latest
```

Since you cannot define them and be able to access things like `dev_appserver.py` in a single image as is likely required by Golang applications utilizing `aetest` on CircleCI.

In a world without computers, this probably wouldn't be needed.

## Sources

* https://github.com/CircleCI-Public/circleci-dockerfiles/blob/master/golang/images/1.8.7-jessie/Dockerfile
* https://github.com/GoogleCloudPlatform/cloud-sdk-docker/blob/master/Dockerfile

## Pull Requests

Sure, but please give me some time.  But seriously?

## License

Apache 2.0.
