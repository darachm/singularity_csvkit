Bootstrap: docker
From: ubuntu:16.04

%labels
MAINTAINER darachm

%help

    This container is for providing `ssconvert` for a nextflow pipeline.
    
%post

    apt-get -y update
    apt-get -y install gnumeric

%test

    /usr/bin/ssconvert


