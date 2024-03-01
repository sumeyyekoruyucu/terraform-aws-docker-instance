provider "aws" {
  region = "us-east-1"
}

module "docker_instance" {
    source = "<sumeyyekoruyucu>/docker-instance/aws"
    key_name = "techproed"
}