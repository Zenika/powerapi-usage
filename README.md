docker run --init -it --rm --name chrome --shm-size=1024m --cap-add=SYS_ADMIN \
  --entrypoint=/usr/bin/google-chrome-unstable \
  yukinying/chrome-headless-browser \
  --headless --disable-gpu --dump-dom https://www.zenika.com
