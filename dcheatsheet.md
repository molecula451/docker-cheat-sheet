## Simple Docker Cheatsheet for daily use

### Show Containers
<code> docker ps </code>

### Show Images

<code> docker images </code>

### Pull image from repository

<code> docker pull <image name> </code>

### Remove Image

<code> docker rmf </code>

### Remove by force

<code> docker rmf -f </code>

### Save Image

<code> docker save <image-tag> --output [image name].tar </code>

### Load Saved Image

<code> docker load < [image-name].tar </code>
  
### Running container interactive mode

<code> docker run -it <image> </code>
