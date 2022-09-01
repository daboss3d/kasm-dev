# kasm-dev
Testing Kasm for devops

# Build 

sudo docker build -t daboss3d/kasm-ubuntu-jammy-devops:latest -f dockerfile-kasm-ubuntu-jammy-devops . 

# Push to registry
docker push daboss3d/kasm-ubuntu-jammy-devops:latest
