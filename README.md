# OpenRefine 3.1 on Docker

This is a Docker file for running [OpenRefine](http://openrefine.org/) 3.1.

## Usage instructions

* Clone this repo, or download the `Dockerfile`
* Build the image:

```bash
~$ docker build -t {user_name}/open-refine -f Dockerfile .
```

Run the container: 

```bash
~$ docker run -p 8080:3333 -d {user_name}/open-refine
```

* Point your browser to http://127.0.0.1:8080

## Credits

This Dockerfile is based on work shared [here](https://github.com/opencultureconsulting/openrefine-docker).