FROM gcr.io/distroless/static-debian13:nonroot@sha256:516757106de35205efb70b91ba03f6f1298424a0678c603255cf2852a7000087

COPY       mock-service /usr/bin/mock-service
ENTRYPOINT [ "/usr/bin/mock-service" ]

ARG revision
LABEL org.opencontainers.image.title="mock-service" \
      org.opencontainers.image.source="https://github.com/grafana/rollout-operator/integration/mock-service" \
      org.opencontainers.image.revision="${revision}"
