This is project to learn docker

1. Build image: `docker image build -t nguyetem/first-image .` (nguyetem is docker hub id, first-image is image name)
2. Run image: `docker container run --rm -p 80:80 nguyetem/first-image`
3. Push image to docker hub: `docker push nguyetem/first-image`, incase haven't login we need to login by `docker login`
4. Delete image on local: `docker image rm abdedf` (abdedf is image id), `docker image ls` to see image id to delete
