# How to push to DockerHub?

First build with tag:

```sh
# Clone it
git clone https://github.com/jcs-emacs/docker

# Navigate to the target version your want to build
cd docker/${VERSION}/

# Build the docker image
docker build -t jcs-emacs:${VERSION} .
```

Then push to DockerHub:

```sh
docker push jcs090218/jcs-emacs:[VERSION]
```

---

If missing the tag:

```sh
docker tag [IMAGE-NAME] jcs090218/jcs-emacs:[VERSION]
```
