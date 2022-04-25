Docker
===

## For running the Dockefile of exercise 1 - nodejs-app-first-dockerfile
```
- CMD (for build): docker build . (docerfile and source is the same path)
```
- CMD (for run): docker run -it --name <namefile> (if neccessary) -v <hostPath:VirtualPath> dockerContainer

```
- Example:  docker run -it owner-docker (owner-docker is an dockerContainer)
            docker run -it --name myDocker -v ~/Documents/app:/mnt/app owner-docker
```

### Note:
- This example when running it would not run so we need to run this example with specific port: docker run -p 3000:80 owner-docker



