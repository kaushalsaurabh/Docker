# Use an existing image as base
FROM alpine

# Install dependencies
RUN apk  add --update redis

# Tell the image what to do when container starts as container
CMD ["redis-server"]