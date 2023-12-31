# (Custom) MacPorts Ports

an out-of-tree port repository for testing or upstreaming (or just resting) portfiles

## how to use

  - clone repo
  - run `portindex` at the root of repo
  - add the full path to the repository to `/opt/local/etc/macports/sources.conf` like below:

    ```
    file:///Users/linuxgemini/gitworkflow/macports-ports-custom [nosync]
    ```

    make sure that this link is _above_ the macports' default one.

  - use macports as you normally would