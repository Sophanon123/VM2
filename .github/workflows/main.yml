name: Simple Workflow

on:
  push:
    branches: [ "master" ]



jobs:
  build:
    # The type of runner that the job will run on, self-hosted is label on runner
    runs-on: self-hosted
    steps:
      - uses: actions/checkout@v4

      - name: Run a one-line script
        run: echo Hello, Learning Github Actions!!
      - name: Run a multi-line script
        run: |
          echo Add other actions to build,
          echo test, and deploy your project.
