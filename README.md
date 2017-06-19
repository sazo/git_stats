# git_stats
docker image for https://github.com/tomgi/git_stats

## Usage

### Docker run

    docker run -it -v /some/dir/to/repos:/repos sazo/git_stats

### Generator

#### Print help

    $ git_stats
    Commands:
      git_stats generate        # Generates the statistics of a repository
      git_stats help [COMMAND]  # Describe available commands or one specific command