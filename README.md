# Go Sample App using Mod

## Building

`pack build go-paketo-demo-app --buildpack gcr.io/paketo-buildpacks/go`

## Running

`docker run --interactive --tty --env PORT=8080 --publish 8080:8080 go-paketo-demo-app`

## Viewing

`curl http://localhost:8080`
