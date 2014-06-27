Gitlab to Github : Migrate issues
================

### WARNING: this has no validation of existing issues and will create issues wich cannot be deleted in github!!!!

This script migrate issues from gitlab to github.

```
Usage: gitlab-to-github [options] [command]

  Commands:

    gitlab-projects        List gitlab projects
    import-issues <gitlab-project-id> <github-user> <github-repo> Impore gitlab issue to github

  Options:

    -h, --help                 output usage information
    -V, --version              output the version number
    --dry-run                  Dry-run
    -u, --lab-url <url>        Gitlab URL [REQUIRED]
    -t, --lab-token <token>    Gitlab token [REQUIRED]
    -n, --hub-user <username>  Github username
```

### WARNING: this has no validation of existing issues and will create issues wich cannot be deleted in github!!!!
