# podman-in-container
Podman inside container


git clone https://github.com/mlucasdasilva/podman-in-container.git  pic
cd pic
docker-compose up -d
docker run -it pic_podman_1 bash
podman --cgroup-manager=cgroupfs --events-backend=file run docker.io/hello-world
podman --cgroup-manager=cgroupfs --events-backend=file ps
