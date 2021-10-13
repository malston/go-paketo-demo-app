# Go Sample App using Mod

## Building

`pack build go-paketo-demo-app --buildpack gcr.io/paketo-buildpacks/go:0.10.0`

## Running

`docker run --interactive --tty --env PORT=8080 --publish 8080:8080 go-paketo-demo-app`

## Viewing

`curl http://localhost:8080`


`pack build go-paketo-demo-app --buildpack gcr.io/paketo-buildpacks/gopaketo-buildpacks/procfile@4.4.1 (Buildpack API 0.6) is incompatible with lifecycle 0.9.3 (Buildpack API(s) 0.2, 0.3, 0.4`
