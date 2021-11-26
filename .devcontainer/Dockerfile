# See here for image contents: https://github.com/microsoft/vscode-dev-containers/tree/v0.205.2/containers/ubuntu/.devcontainer/base.Dockerfile

# [Choice] Ubuntu version (use hirsuite or bionic on local arm64/Apple Silicon): hirsute, focal, bionic
ARG VARIANT="hirsute"
FROM mcr.microsoft.com/vscode/devcontainers/base:0-${VARIANT}

# [Optional] Uncomment this section to install additional OS packages.
# RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
#     && apt-get -y install --no-install-recommends <your-package-list-here>

RUN apt-get update \
	&& apt-get install -y \
	latexmk \
	texlive-latex-recommended \
	texlive-latex-extra \
	texlive-fonts-recommended \
	texlive-extra-utils \
	# texlive-bibtex-extra \
	texlive-lang-german \
	texlive-plain-generic \
	chktex \
	texlive-luatex
	# texlive \
	# biber \


# Uses "Spaceship" theme with some customization. Uses some bundled plugins and installs some more from github
# RUN sh -c "$(wget -O- https://github.com/deluan/zsh-in-docker/releases/download/v1.1.2/zsh-in-docker.sh)" -- \
# 	-t https://github.com/denysdovhan/spaceship-prompt \
# 	-a 'SPACESHIP_PROMPT_ADD_NEWLINE="false"' \
# 	-a 'SPACESHIP_PROMPT_SEPARATE_LINE="false"' \
# 	-p git \
# 	-p ssh-agent \
# 	-p https://github.com/zsh-users/zsh-autosuggestions \
# 	-p https://github.com/zsh-users/zsh-completions