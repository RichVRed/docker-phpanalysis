## phpanalysis - The PHP library for PHP Analysis
[![Docker Pulls](https://img.shields.io/docker/pulls/rvannauker/phpanalysis.svg)](https://hub.docker.com/r/rvannauker/phpanalysis/) [![Docker Stars](https://img.shields.io/docker/stars/rvannauker/phpanalysis.svg)](https://hub.docker.com/r/rvannauker/phpanalysis/) [![](https://images.microbadger.com/badges/image/rvannauker/phpanalysis:latest.svg)](https://microbadger.com/images/rvannauker/phpanalysis:latest) [![GitHub issues](https://img.shields.io/github/issues/RichVRed/docker-phpanalysis.svg)](https://github.com/RichVRed/docker-phpanalysis) [![license](https://img.shields.io/github/license/RichVRed/docker-phpanalysis.svg)](https://tldrlegal.com/license/mit-license)

Docker container to install and run phpanalysis

### Installation / Usage
1. Install the rvannauker/phpanalysis container:
```bash
docker pull rvannauker/phpanalysis
```
2. Run phpanalysis through the phpanalysis container:
```bash
sudo docker run --rm --volume $(pwd):/workspace --name="phpanalysis" "rvannauker/phpanalysis" {destination}
```

### Download the source:
To run, test and develop the PHPANALYSIS Dockerfile itself, you must use the source directly:
1. Download the source:
```bash
git clone https://github.com/RichVRed/docker-phpanalysis.git
```
2. Build the container:
```bash
sudo docker build --force-rm --tag "rvannauker/phpanalysis" --file phpanalysis.dockerfile .
```
3. Test running the container:
```bash
 $ docker run rvannauker/phpanalysis --help
```