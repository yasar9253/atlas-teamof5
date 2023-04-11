FROM ubuntu
WORKDIR /tmp
COPY aravivo_base_file.txt /tmp
RUN mv /tmp/aravivo_base_file.txt /tmp/renamed_aravivo_base_file.txt