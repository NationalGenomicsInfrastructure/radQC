From:nfcore/base
Bootstrap:docker

%labels
    MAINTAINER Remi-Andre Olsen <remi-andre.olsen@scilifelab.se>
    DESCRIPTION Singularity image containing all requirements for radseqQC pipeline
    VERSION 0.1.1dev

%files
    environment.yml /

%post
    /opt/conda/bin/conda env update -n root -f /environment.yml
    /opt/conda/bin/conda clean -a
