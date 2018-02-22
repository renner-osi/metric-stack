# metric Stack

Run the complete metric stack using this [docker-compose](https://docs.docker.com/compose/) file.

## Usage

Start all the images as follows:

    # Start all images in the background
    docker-compose up -d

### Check that InfluxDB works:

Run this curl command, if no errors occur InfluxDB is running:

    curl http://localhost:8086/ping
