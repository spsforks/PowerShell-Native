FROM mcr.microsoft.com/powershell:ubuntu-22.04

LABEL maintainer="PowerShell Team <powershellteam@hotmail.com>"

RUN apt-get update \
	&& apt-get install -y --no-install-recommends \
	git \
	sudo \
	&& rm -rf /var/lib/apt/lists/*

ENTRYPOINT [ "pwsh" ]
