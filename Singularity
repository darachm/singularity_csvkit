Bootstrap: docker
From: ubuntu:16.04

%labels
MAINTAINER darachm

%help

    This container is for providing `csvkit` for a nextflow pipeline.
    
%post

    apt-get -y update
    apt-get -y install csvkit

%test

    /usr/bin/csvkit


