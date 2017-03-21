Inspired by https://github.com/jveldboom/docker-google-guetzli

# Docker Google's Guetzli 
Run Google's Guetzli within Docker. 

Visit https://github.com/google/guetzli for Guetzli's full documentation

# Run
- `docker run --rm -v $(PWD):/tmp jveldboom/google-guetzli input.jpg output.jpg`

# Run Examples
- `docker run --rm -v $(PWD):/tmp jveldboom/google-guetzli --quality 85 ./samples/bees.png ./samples/bees-out.png`
