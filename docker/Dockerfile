FROM ghcr.io/nikitacoeur/debug-gha-docker-backend/without-onbuild:main AS without-onbuild

RUN echo "This an echo inside final dockerfile without ONBUILD instructions."

FROM ghcr.io/nikitacoeur/debug-gha-docker-backend/with-onbuild:main AS with-onbuild

RUN echo "This an echo inside final dockerfile after ONBUILD instructions with only ONBUILD ARG MODE_PROD=${MODE_PROD}."
