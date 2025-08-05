FROM mcr.microsoft.com/playwright:v1.54.0-noble
# Default ubuntu user is 1000, vscode doesn't override it via updateRemoteUserUID if it exists
# change it so that updateRemoteUserUID works. https://github.com/microsoft/vscode-remote-release/issues/10030
RUN usermod -u 2000 ubuntu && groupmod -g 2000 ubuntu