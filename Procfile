web: docker run -d \
    -e RCH_ENABLE_BULK=1 \
    -e RCH_HEADER_SECRET=$RCH_HEADER_SECRET \
    -p 80:8080 \
    --name reacher_backend \
    reacherhq/backend:$RCH_VERSION
