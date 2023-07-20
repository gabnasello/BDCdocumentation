# Personalize a containers

### Mount an extra volume

You can personalize the `docker-compose.yaml` file in each container of the `~/BDcenter` directory.&#x20;

For example, if you want to mount a specify volume simply add:

```docker
  volumes:
    - $HOME_RESEARCHER:/config/researcher_home # already existing
    - /path/to/local/directory:/path/in/container # new volume mounted
```

Similarly, you can add the [`--bind option`](https://docs.sylabs.io/guides/3.0/user-guide/bind\_paths\_and\_mounts.html#specifying-bind-paths) in `start_singularity.sh` to mount volumes in Singularity containers. &#x20;

**IMPORTANT**: you will lose every change to the `docker-compose.yaml` or to the singularity file if you [update\_bd\_directory.md](../access-the-bdc/update\_bd\_directory.md "mention")

