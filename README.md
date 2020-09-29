
# Install individual release
helmfile -e local --selector name=$RELEASE_NAME sync
