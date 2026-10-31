# lowlighter/metrics v3.34 with a fix for its repository pagination.
# Upstream is unmaintained, see base-pagination.patch for details.
FROM ghcr.io/lowlighter/metrics:v3.34
COPY base-pagination.patch /tmp/base-pagination.patch
RUN git apply /tmp/base-pagination.patch && rm /tmp/base-pagination.patch
