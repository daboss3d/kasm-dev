# kasm-dev
Testing Kasm for devops.

The aim of this is creating a DevOps Docker image for KASM Workspaces (KASM Tech).
Based on Ubuntu Jammy with Node.js installed.



# Build 
Change for your configs
sudo docker build -t daboss3d/kasm-ubuntu-jammy-devops:latest -f dockerfile-kasm-ubuntu-jammy-devops . 

# Push to registry
Change for your configs
docker push daboss3d/kasm-ubuntu-jammy-devops:latest
