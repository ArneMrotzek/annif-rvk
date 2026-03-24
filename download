{
  "name": "Annif RVK",
  "image": "mcr.microsoft.com/devcontainers/python:3.11",

  "features": {
    "ghcr.io/devcontainers/features/python:1": {
      "version": "3.11"
    }
  },

  "postCreateCommand": "pip install annif[fasttext,nn] && annif --version",

  "forwardPorts": [5000],
  "portsAttributes": {
    "5000": {
      "label": "Annif API",
      "onAutoForward": "notify",
      "visibility": "public"
    }
  },

  "customizations": {
    "vscode": {
      "extensions": [
        "ms-python.python"
      ],
      "settings": {
        "terminal.integrated.defaultProfile.linux": "bash"
      }
    }
  }
}
